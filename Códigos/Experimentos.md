`
```python
import micropip
await micropip.install('rdflib')  
````

## Existência
```python
from rdflib import Graph, Namespace, RDF, URIRef

noo = Namespace("http://noosphera.org/ontology#")
grafo = Graph()
O1 = noo["O1"]
grafo.add((O1, RDF.type, noo.Object))

print("Número de triplas:", len(grafo))
for s, p, o in grafo:
	print(s, p, o)
````
# Estrutura

```python
from rdflib import Graph, Namespace, RDF


noo = Namespace("http://noosphera.org/ontology#")
grafo = Graph()

O1 = noo["O1"]
O2 = noo["O2"]

grafo.add((O1, RDF.type, noo.Object))
grafo.add((O2, RDF.type, noo.Object))

  

relacao = noo["relatesTo"]
grafo.add((O1, relacao, O2))
print("Número de triplas:", len(grafo))

for s, p, o in grafo:

	print(f"{s} -> {p} -> {o}")
````

##HIPÓTESES

```python

# Estrutura mínima: grafo de arestas rotuladas
grafo = {
    ("K", "manifesta", "R1"),
    ("K", "manifesta", "R2"),
    ("K", "manifesta", "R3"),
}
X = "X"  # existe como nó solto, sem aresta nenhuma

def is_representation(obj, grafo):
    """Hipótese B pura: Representation = alvo de alguma aresta 'manifesta'."""
    return any(p == "manifesta" and o == obj for _, p, o in grafo)

# --- Pergunta 1 ---
print("R1 é Representation?", is_representation("R1", grafo))  # True
print("X é Representation?", is_representation("X", grafo))    # False

# --- Pergunta 2: remover K->R1 ---
grafo_sem_r1 = {a for a in grafo if a != ("K", "manifesta", "R1")}
print("R1 após remover a aresta:", is_representation("R1", grafo_sem_r1))  # False
# R1 "perde a fase" — os bytes de R1 não mudaram, só a posição relacional

# --- Pergunta 3: materialização diferente, mesma posição relacional ---
# Note que is_representation nunca olha pra conteúdo/tamanho/formato de R1 ou R2 —
# só consulta a existência da aresta. Materialização é literalmente invisível aqui,
# o que já é a confirmação de que Doc01 §5 se sustenta.

# --- Pergunta 4: o custo da Hipótese B pura ---
grafo_forjado = grafo | {("K", "manifesta", "X")}
print("X após aresta forjada:", is_representation("X", grafo_forjado))  # True
# Nada no modelo impede isso. Esse print sendo True é o próprio problema
# que a Hipótese C resolveria: a função deveria consultar uma Policy antes
# de aceitar a aresta como válida, não só constatar que ela existe.
```
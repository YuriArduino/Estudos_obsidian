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

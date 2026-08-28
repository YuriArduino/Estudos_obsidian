


`∃` diz "existe pelo menos um S com essa propriedade"
`∀` "**toda** entidade possui identidade própria"
`struct` (estrutura) ==é um tipo de dado personalizado que agrupa várias variáveis de tipos diferentes sob um único nome==. Funciona como um contêiner para dados que pertencem a um mesmo contexto.

`Funtor` Preserva a **estrutura**. Se você tem uma regra na Ontologia, o Funtor proíbe que a Implementação a quebre. Se a Ontologia diz que o conhecimento é passivo, o Funtor impede que o código trate o conhecimento como um processo executável.

`Permutação`: A ordem IMPORTA

Na permutação, se você mudar a ordem dos mesmos elementos, você cria um **resultado totalmente novo**. É uma questão de **organização, fila ou sequência**.

- **Palavra-chave:** Senha, Anagrama, Pódio, Fila, Rota.
- **Exemplo Clínico:** Imagine uma corrida com 3 pessoas: **Ana (A), Bruno (B) e Carlos (C)**. Queremos premiar o 1º e o 2º lugar.
    - Se o pódio for **[A, B]** (Ana em 1º, Bruno em 2º), é **diferente** do pódio **[B, A]** (Bruno em 1º, Ana em 2º).
    - Mudar a ordem alterou o resultado. Isso é uma **Permutação**.

`Combinação`: A ordem NÃO IMPORTA

Na combinação, mudar a ordem dos elementos **não muda nada**. O resultado final é o mesmo grupo de coisas. É uma questão de **escolha, equipe, conjunto ou sorteio**.

- **Palavra-chave:** Dupla, Comissão, Salada de Frutas, Sorteio de Loteria.
- **Exemplo Clínico:** Usando as mesmas 3 pessoas (**A, B, C**), agora queremos apenas escolher 2 pessoas para formar uma dupla de estudos.
    - Se eu escolher a dupla **{Ana, Bruno}**, é **exatamente a mesma coisa** que a dupla **{Bruno, Ana}**. Eles vão estudar juntos do mesmo jeito.
    - Mudar a ordem não criou um resultado novo. Isso é uma **Combinação**.
```python
  
import itertools

letras = ['A', 'B', 'C']

# Permutação: se importa com a ordem
print(list(itertools.permutations(letras, 2)))
# Saída: [('A', 'B'), ('A', 'C'), ('B', 'A'), ('B', 'C'), ('C', 'A'), ('C', 'B')] -> 6 itens

# Combinação: ignora a ordem
print(list(itertools.combinations(letras, 2)))
# Saída: [('A', 'B'), ('A', 'C'), ('B', 'C')] -> 3 itens
````

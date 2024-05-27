<h1 align="center"> MER & DER - Cluble do Livro </h1> 
O projeto consistiu na elaboração de um DER (Diagrama Entidade Relacionamento) sobre um clube do livro virtual onde foram explicados e aplicados os conceitos de modelagem conecitual, lógica e física. Além disso foram explicados os conceitos de um Modelo Entidade Relacionamento (MER). Foram abordados conceitos como entidades(fortes e fracas), relacionamentos, atributos de uma entidade e suas chaves primárias e estrangeiras. 

<br><br>
 
![imagem_base_banco_de_dados_e_clube_do_livro](https://github.com/FelipeRFN/DER-Clube-do-Livro---Alura/assets/117915374/d0b05d31-f508-4058-83d2-b4831d5af45c)

<br><br>

<h2 align="center"> MER </h2>
<br>

Durante o curso nos foi apresentado os conceitos do Modelo Entidade Relacionamento (MER) onde foi introduzido o conceito de entidades, relacionamentos e atributos.
<br>
* __Entidades__: As entidades podem ser tanto físicas quanto lógicas a depender do objeto à ser observado. As entidades físicas são objetos observados na vida real e que em sua maioria são tangíveis, ou seja, podem ser tocados como por exemplo do projeto um cliente, um livro, etc... Já as entidades lógicas geralmente são definidos como conceitos ou idéias, são representações de um processo ou de um estado e que no mundo externo/real não são objetos físicos (não ocupam lugar no espaço). Também citando como exemplo do projeto os pedidos de compra ou até mesmo outros objetos como cargo, espécie e demais definições.

* __Relacionamentos__: Os relacionamentos definem como cada entidade se relaciona entre si. Como no exemplo do projeto um cliente que **faz** pedidos ou um estoque que **contém** livros. Estes relacionamentos contém um processo chamado _cardinalidade_. Em suma a cardinalidade define a obrigatoriedade de uma entidade estar contida em outra entidade por meio do relacionamento, podendo não ser obrigado, ter no mínimo uma entidade ou se pode conter várias entidades. Por exemplo a relação de **_cliente_ faz _pedido_**, analisando primeiramente a entidade cliente, obtem-se que para o modelo de negócios um cliente não necessáriamente fazer um pedido podendo então seu valor mínimo se torna zero (0), porém da mesma forma não conseguimos ter vários clientes realizando um único pedido, portanto seu valor máximo será de um (1) tornando assim a cardinalidade (0,1) e analisando a cardinalidade para os pedidos podemos definir como (0,n) onde novamente não precisamos que seja feito necessáriamente um pedido tornando o seu mínimo (0) e cada cliente pode fazer diversos pedidos diferentes tornado o seu máximo (n).

* 

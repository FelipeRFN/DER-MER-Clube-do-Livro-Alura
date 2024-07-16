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

* __Relacionamentos__: Os relacionamentos definem como cada entidade se relaciona entre si. Como no exemplo do projeto um cliente que **faz** pedidos ou um estoque que **contém** livros. Estes relacionamentos contém um processo chamado _cardinalidade_. Em suma a cardinalidade define a obrigatoriedade de uma entidade estar contida em outra entidade por meio do relacionamento, podendo não ser obrigado, ter no mínimo uma entidade ou podendo conter várias entidades. Por exemplo a relação de **cliente _faz_ pedido**, a cardinalidade entre os 2 pode ser definida como cliente(0,n) e pedido(1,n), pois em nosso modelo de negócio um cliente não precisa necesáriamente realizar um pedido para ser considerado cliente mas diversos clientes podem fazer pedidos tornando o mínimo 0 e o máximo n. De mesma forma para o pedido existir precisa haver um cliente realizando a operação tornando seu mínimo 1, mas diversos clientes podem fazer diversos pedidos tornando o seu máximo n.

* __Atributos__: Os atributos irão descrever as entidades, como por exemplo na entidade pessoa que possui os atributos nome, telefone de contato, email, endereço, um ID(que no caso é considerada uma chave primária). Tudo para descrever a entidade e explicar como ela se comporta e quais dados irá armazenar no banco de dados. Em geral as entidades carregam um atributo que é considerado uma chave primária ou chave estrangeira. As chaves primárias são únicas na tabela e não se repetem. Já as chaves estrangeiras são chaves primárias de uma entidade que foram herdadas de uma outra entidade para evitar redundância de dados e otimizar o processo de busca. Vale lembrar que em determinadas entidades se pode encontrar chaves primárias e chaves estrangeiras na mesa tabela (como no caso da entidade pedido que contém uma chave primária própria e uma chave estrangeira da tabela cliente) assim como podem ter chaves estrangeiras que agem como sua chave primária (como no caso do estoque que, por ser apenas 1, não necessita de uma chave única para identificar diferentes estoques e por conta disso utiliza as chaves estrangeiras de livro e editora como chaves primárias).

<br>

<div align="center"> 
  <img src = "https://dhg1h5j42swfq.cloudfront.net/2021/05/10191416/bd-mer.png") </>
</div>

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<br>

<h2 align="center"> DER </h2>
<br>
O Diagrama Entidade Relacionamento (DER) foi apresentado para a elaboração visual da Livraria Virtual onde foi montado um esquema conseitual representando cada entidade, atributo e relacionamento além de serem abordadas as suas características como por exemplo entidades fortes e fracas, chaves primárias e estrangeiras, atributos autorelacionáveis, dentre outros. Foi utilizado o aplicativo BrModelo para a criação do esquema e durante o curso foram utilizadas algumas das principais ferramentas para a criação e edição das Entidades e seus Relacionamentos tentando sempre manter as boas práticas nas nomeclaturas além de organizar o esquema de maneira que fique organizado e se mantenha legível para os demais "membros da equipe". 

<br><br><br><br>



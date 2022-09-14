# SQL x NoSQL DIO-BootCamp
Neste repositório falarei sobre o que é SQL e NoSQL, quais as suas diferenças, quando são utilizados e qual é o papel do Engenheiro de Dados e também Cientista de Dados.

# O que é SQL (Banco de dados Relacional):
É um tipo de banco onde armazenamos informações que tenham relacionamento entre si.
Relacionar informações se criar duplicidades e criar consistência. Principalmente quando possuímos um esquema de dados rígido, ou seja, sabemos o que vamos armazenar no banco.
É um tipo de banco que vai manter a integridade entre as informações.

# O que é NoSQL (Banco de dados Não Relacional):
É um banco que armazena informações não estruturadas, ou seja, não rígidas. Ex: Imagens, vídeos, fotos.
É um tipo de banco que não permite relações entre as informações, permite armazenar estruturas totalmente diferentes.

# O que NoSQL foi criado para substituir o SQL?
De forma alguma, o NoSQL foi criado justamente para atender problemas que não eram capazes de serem resolvidos através do banco SQL. Então não, ele não veio para substituir o banco SQL.
Devido ao alto volume de dados na internet, se fez necessário a criação do NoSQL para o armazenamento horizontal dessas informações, além dele ser mais flexível em relação aos dados.

# Como se faz a consulta no banco NoSQL?
Por mais que eu esteja armazenando um conjunto de informações, a consulta precisa ser pensada desde o início, definindo chaves, definindo as formas de consulta da informação, até mesmo para não armazenarmos de uma única forma. 
Armazenar de forma corre –> Pensar nas chaves –> Pensar na característica do banco = Performance


#### •	DataLake -> Repositório de informações que armazenamos grandes volumes de dados, estruturados ou não.

# Quais os maiores desafios na hora de realizar ETL?
O maior desafio realmente é a parte de manipulação de dados. Por isso, se faz necessário o uso de ferramentas que façam o scaddle de todas essas ETL’s.


# O tipo de Banco influencia na complexidade da ELT?
De fato, sim, influencia. Entretanto, se faz necessário conhecer bem o banco que irá trabalhar para solucionar o problema. Conhecer bem a arquitetura que você vai usar dentro do banco, quais as formas de consultas, quais as chaves, índices, entre outros. 

# Ciência de dados X Engenharia de dados: Quais as responsabilidades?
O papel do engenheiro de dados é preparar a informação, ou seja, a pessoa responsável precisa saber coletar a informação, preparar, armazenar e deixa-la disponível, tudo isso com o objetivo de deixar pronto para o Cientista de Dados utilizar. O Engenheiro de Dados acaba tendo uma maior aproximação com ferramentas de manipulação de dados e também tem um conhecimento técnico dessas ferramentas. 
Já o papel do Cientista de Dados fica responsável pela criação de modelos de ML, ou seja, ele vai utilizar uma informação disponibilizada por um Engenheiro de Dados e criar insights, sejam eles preditivos ou não. Resumindo, ele vai processar todos aqueles dados disponibilizados pelo Engenheiro. Através desse processamento de informação, o Cientista vai procurar gerar insights para negócios e também produção. 
É valido lembrar que são áreas complementares, trabalham juntas!


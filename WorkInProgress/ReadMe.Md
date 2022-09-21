[**](https://web.dio.me/track/database-experience)

##### Construindo seu Primeiro Projeto Lógico de Banco de Dados

**

[**](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/39e34429-4deb-4410-bdc1-99373fe3d2ce)[**](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/7d3689ff-046c-4413-b219-3e6c09eefb46)

<iframe id="ytc44" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" title="Apresentando o Desafio de Projeto Lógico para Banco de Dados" width="100%" height="100%" src="https://www.youtube.com/embed/UgXqweOJJSw?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-24="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



00:02

 

02:11







normal

auto

- CONTEÚDOS
- INFORMAÇÕES

[Apresentando o Desafio de Projeto Lógico para Banco de Dados](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/39e34429-4deb-4410-bdc1-99373fe3d2ce)[Considerações sobre a Variação Esquema ER](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/7d3689ff-046c-4413-b219-3e6c09eefb46)[Criando esquema Relacional a partir do Esquema Conceitual](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/8807b36f-4180-41fe-a91b-6ea0212cb9fd)[Criando o esquema de Banco de Dados – Script SQL - Parte 1](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/913d6227-7673-4623-b913-14242dad0545)[Criando o esquema de Banco de Dados – Script SQL - Parte 2](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/4c913de7-c01b-4c73-a0f9-4a1b71c60fa4)[Criando o esquema de Banco de Dados – Script SQL - Parte 3](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/41609cfe-aa93-4306-8dc5-228766d9c5ad)[Criando o esquema de Banco de Dados – Script SQL - Parte 4](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/0449642d-ffd9-45e2-9958-b87879680ad5)[Criando o esquema de Banco de Dados – Script SQL - Parte 5](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/f50768e2-9556-438e-b425-dda64c15fc26)[Criando o esquema de Banco de Dados – Script SQL - Parte 6](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/a3f58839-8431-4f20-ab52-3e546b70cb44)[Persistindo e Recuperando Dados a partir de Consultas SQL no Banco de Dados](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/ba6e01f5-e09e-4045-b681-79df04f192fd)[Entendendo o desafio – Criando e Implementando um Projeto Lógico de Banco de Dados](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/95807ea4-331e-446c-ac2d-dfc41738f206)[Instruções para entrega](https://web.dio.me/lab/construindo-seu-primeiro-projeto-logico-de-banco-de-dados/learning/30ffb3b9-3e87-4471-b256-71f733a32ae7)



# **Descrição do Desafio**

Replique a modelagem do projeto lógico de banco de dados para o cenário de e-commerce. Fique atento as definições de chave primária e estrangeira, assim como as constraints presentes no cenário modelado. Perceba que dentro desta modelagem haverá relacionamentos presentes no modelo EER. Sendo assim, consulte como proceder para estes casos. Além disso, aplique o mapeamento de modelos aos refinamentos propostos no módulo de modelagem conceitual.

Assim como demonstrado durante o desafio, realize a criação do Script SQL para criação do esquema do banco de dados. Posteriormente, realize a persistência de dados para realização de testes. Especifique ainda queries mais complexas dos que apresentadas durante a explicação do desafio. Sendo assim, crie queries SQL com as cláusulas abaixo:

- Recuperações simples com SELECT Statement
- Filtros com WHERE Statement
- Crie expressões para gerar atributos derivados
- Defina ordenações dos dados com ORDER BY
- Condições de filtros aos grupos – HAVING Statement
- Crie junções entre tabelas para fornecer uma perspectiva mais complexa dos dados

### **Diretrizes**

- Não há um mínimo de queries a serem realizadas;
- Os tópicos supracitados devem estar presentes nas queries;
- Elabore perguntas que podem ser respondidas pelas consultas;
- As cláusulas podem estar presentes em mais de uma query;

**O projeto deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto lógico para fornecer o contexto sobre seu esquema lógico apresentado.**

### **Objetivo:**

[Relembrando] Aplique o mapeamento para o cenário:

“Refine o modelo apresentado acrescentando os seguintes pontos”

- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;

**Algumas das perguntas que podes fazer para embasar as queries SQL:**

- Quantos pedidos foram feitos por cada cliente?
- Algum vendedor também é fornecedor?
- Relação de produtos fornecedores e estoques;
- Relação de nomes dos fornecedores e nomes dos produtos;

**Agora é a sua vez de ser o protagonista!** **Implemente o desafio sugerido pela expert e suba seu projeto para um repositório próprio, com isso, você aumentará ainda mais seu portfólio de projetos no GitHub!**



###### DESCRIÇÃO

Neste desafio, iremos replicar a modelagem do projeto lógico de banco de dados para um cenário de e-commerce.

**SQL**

------

###### Full-Stack

###### Avançado

------

###### ESPECIALISTA

![author](https://hermes.digitalinnovation.one/users/author/photos/a3d71bed-2938-4df8-95e1-3d4181cad1c3.png)

###### Juliana Mascarenhas

Data Scientist, DIO[**](https://www.linkedin.com/in/juliana-mascarenhas-00349426/)
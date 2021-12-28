# All For One Project

# Contexto
O objetivo do projeto é praticar todos os conceitos de SQL aprendidos sobre banco de dados relacionais, consulta e filtro de dados em um banco e também a manipular tabelas e suas informações. Para isso, será utilizado o banco de dados "Northwind".

Os requisitos podem ser encontrados [aqui](requirements.txt) e suas resoluções se encontram na pasta 'challenges'.

## Tecnologias usadas

Banco de dados:
> Desenvolvido usando: MySQL

## Habilidades treinadas

* Entender o que são bancos de dados
* Entender como a linguagem de consulta estruturada (SQL) é usada
* Compreender como as tabelas se encaixam no conceito de banco de dados
* Montar um ambiente de desenvolvimento local para praticar SQL
* Entender como usar o MySQL Workbench
* Compreender o que é uma query SQL e quais são seus tipos de comando
* Gerar valores com `SELECT`
* Selecionar colunas individualmente com `SELECT`
* Renomear e gerar colunas em uma consulta com `AS`
* Concatenar colunas e valores com `CONCAT`
* Remover dados duplicados em uma consulta com `DISTINCT`
* Contar a quantidade de resultados em uma consulta com `COUNT`
* Limitar a quantidade de resultados em uma consulta com `LIMIT`
* Pular resultados em uma consulta com `OFFSET`
* Ordernar os resultados de uma consulta com `ORDER BY`
* Filtrar resultados de consultas com o `WHERE`
* Utilizar operadores booleanos e relacionais em consultas
* Criar consultas mais dinâmicas e maleáveis com `LIKE`
* Fazer consultas que englobam uma faixa de resultados com `IN` e `BETWEEN`
* Encontrar e separar resultados que incluem datas.
* Inserir dados em tabelas com `INSERT`
* Atualizar dados em tabelas com `UPDATE`
* Apagar dados em tabelas com `DELETE`

## Clonando o repositório

1. Faça o clone
  * `git clone git@github.com:juan-formoso/all-for-one-project.git`.
  * Entre na pasta do repositório clonado:
    * `cd all-for-one-project`

2. Instale as dependências
  * `npm install`

3. Crie uma branch a partir da branch `main`
  * `git checkout -b my-new-branch`

4. Se divirta para fazer o que quiser :)

## Restaurando o banco de dados

1. Faça o download do arquivo [aqui](northwind.sql) e clique em "Raw", depois clique com botão direito e selecione a opção "Salvar como" e salve o arquivo em seu computador.

2. Abra o arquivo com algum editor de texto, e selecione todo o conteúdo usando `CTRL-A`.

3. Abra o MySQL Workbench (recomendado, porém pode utilizar a própria linha de comando se quiser).

4. Abra uma nova janela de query e cole dentro dela todo o conteúdo do banco.

5. Selecione todo o código com `CTRL-A` e depois clique no icone de raio para executar a query.

6. Aguarde um momento.

7. Clique na seta no canto superior esquerdo acima dos bancos para atualizar.

8. Verifique se o banco foi restaurado corretamente.

9. Clique com botão direito em cada tabela e selecione "Select Rows" e certifique-se que todas as tabelas possuem registros. Caso tenha alguma faltando, siga o passo 10.

10. Drope o banco de dados, clicando com o botão direito em cima do banco de dados northwind e selecionando "Drop Schema", e refaça os passos, porém aguardando um tempo maior para executar o script de restauração.

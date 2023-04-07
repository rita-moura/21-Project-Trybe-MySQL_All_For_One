# All For One

Este é um projeto desenvolvido com o objetivo de praticar todos os conceitos de SQL aprendidos até agora, utilizando o banco de dados Northwind com MySQL e Docker.

## Banco de dados Northwind
O Northwind é um banco de dados de exemplo que simula uma empresa que vende produtos. Ele é composto por diversas tabelas, incluindo informações sobre clientes, pedidos, produtos, funcionários e fornecedores.

## Como executar o projeto
Para executar o projeto All For One, siga as instruções abaixo:

1 - Abra o terminal.

2 - Clone o repositório do projeto:

```bash
git clone <URL DO REPOSITÓRIO>
```
3 - Acesse o diretório do projeto:

```bash
cd all-for-one-mysql-docker
```

4 - Execute o comando abaixo para baixar as configurações do projeto:

```bash
npm install
```

5 - Execute o seguinte comando para subir o docker compose:

```bash
docker-compose up -d
```

6 - Execute o seguinte comando para entrar no container `all_for_one`:

```bash
docker exec -it all_for_one bash
```

7 - Execute o comando abaixo para criar as tabelas do banco de dados:

```bash
mysql -u root -p Northwind < create_tables.sql
```
- Digite a senha que está definida no arquivo `docker-compose.yml` para acessar o MySQL.

8 - Copie e cole os comandos SQL do projeto para o terminal.

9 - Execute os comandos SQL para obter os resultados desejados.

## Conclusão
O projeto All For One é uma ótima maneira de praticar todos os conceitos de SQL aprendidos até agora utilizando o banco de dados Northwind com MySQL e Docker. Siga as instruções de instalação e execução do projeto para se familiarizar com o banco de dados e a linguagem SQL.
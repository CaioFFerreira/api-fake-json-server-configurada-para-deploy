# json-server configurado para deploy

Criado com <3 para desenvolvedores front-end que precisam de dados para codificação.

# Passo 1 
- Faça o Fork do Repositório
- Os arquivos já estão configurados, a única coisa que você precisa alterar é os dados do arquivo db.json

```sh
  git clone  https://github.com/CaioFFerreira/api-rest-json-server-deploy.git
```

- db.json
```
{
  "users": [
    {
      "id": 1,
      "name": "Super mario",
      "age": 98
    },
    {
      "id": 2,
      "name": "Caio Fábio Duarte Ferreira",
      "age": 26
    }
  ]
}

```
- `users` passa a ser um EndPoint quando o deploy for feito.

Você pode adicionar mais EndPoints dentro do mesmo arquivo.

- db.json
```
{
  "users": [
    {
      "id": 1,
      "name": "Super mario",
      "age": 98
    },
    {
      "id": 2,
      "name": "Caio Fábio Duarte Ferreira",
      "age": 26
    }
  ],

  "city": [
    {
      "id": 1,
      "name": "São Paulo",
      "population": 1198
    },
    {
      "id": 2,
      "name": "Rio de Janeiro",
      "population": 2226
    }
  ]
}

```
-  `city` passa a ser outro EndPoint.

# Passo 2 

Depois de criar seus EndPoints faça o commit de todos arquivos para o repositório, você pode criar um novo ou como preferir, desde que tenha essa mesma estrutura do oficial.

# Passo 3

Faça deploy do seu repositório. 

[Tutorial Heroku](https://devcenter.heroku.com/articles/github-integration)

# Passo 4

Após o deploy acesse o link gerado. 

[Exemplo repositório Link](https://jsonserverfake.herokuapp.com/)

- [Endpoint users](https://jsonserverfake.herokuapp.com/users)
- [EndPoint city](https://jsonserverfake.herokuapp.com/city)


Contato
----
- [Linkedin caio](https://www.linkedin.com/in/caio-fabio-duarte-ferreira/)

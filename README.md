
# Projeto Blog Pessoal ![image](https://github.com/Gercidio/blogpessoal/assets/51793269/e10056d0-74ea-4588-a76c-2332e1162835)

Projeto em desenvolvimento no bootcamp de Java fullstack da Generation Brasil. Nessa parte você verá o backend do blogpessoal, construído usando maven no Springboot, com estrutura básica de postagens divididas por temas e atribuídas a um usuário, autenticado por login. 
Além do CRUD, foi implementado a camada security e alguns testes unitários essenciais para esse tipo de aplicação. 
Em um mês esse projeto receberá o frontend, construído em HTML, CSS e React. Você pode acompanhar aqui pelo github e dar seu feedback e colaboração!
## Documentação da API

#### Retorna todos os itens

```http
  GET /api/items
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |

#### add(num1, num2)

Recebe dois números e retorna a sua soma.


## Deploy

Para fazer o deploy desse projeto rode

```bash
  npm run deploy
```


## Autores

- [@gercidio] (https://www.github.com/gercidio)
- [perfil linkedin] (https://www.linkedin.com/in/gercidiovaleriano/)

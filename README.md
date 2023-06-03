
# API simples com Laravel and Laravel Orion

Esta API consiste em um pequeno e rápido projeto Back-end para gestão de projetos. 


## Funcionalidades

- CRUD de Projetos
- CRUD de Usuários
- Autenticação da API com JWT


## Documentação da API

#### Retorna todos os itens

```http
  GET /api/projects
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `authentication` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um projeto específico

```http
  GET /api/projects/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do projeto que você quer |



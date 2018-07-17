# Teste de Front-end
Este teste é apresentado aos candidatos as vagas de desenvolvimento Front-end para avaliar os quesitos técnicos.

### O Desafio

Seu objetivo é criar um simples app que deve conter duas páginas, uma que exibe um formulário com os campos abaixo, e outra que liste os dados cadastrados.

* Nome completo
* CPF
* Telefone
* Email

### Pré-requisitos: 
 - Deve ser possível criar, listar e excluir os dados cadastrados pelo formulário;
 - Fazer a persistência dos dados no `localStorage`;

Para ter o estado inicial da lista de usuário utilizar este recurso abaixo:

> GET https://private-f91e8-optimusbrasil.apiary-mock.com/users

Response:

```json

[
  {
    "name": "My name 1",
    "cpf": "04080757247",
    "phone": "11987654321",
    "email": "myemail1@test.com.br"
  },
  {
    "name": "My name 2",
    "cpf": "77797584192",
    "phone": "11987654321",
    "email": "myemail2@test.com.br"
  },
  {
    "name": "My name 3",
    "cpf": "45486737688",
    "phone": "11987654321",
    "email": "myemail3@test.com.br"
  }
]
```

A partir deste ponto utilizar o `localStorage` para persistir localmente as informações.

Save:

```json
{
  "name": "My name 4",
  "cpf": "74668869066",
  "phone": "11987654321",
  "email": "myemail4@test.com.br"
}
```

Lista local:
```json
[
  {
    "name": "My name 1",
    "cpf": "04080757247",
    "phone": "11987654321",
    "email": "myemail1@test.com.br"
  },
  {
    "name": "My name 2",
    "cpf": "77797584192",
    "phone": "11987654321",
    "email": "myemail2@test.com.br"
  },
  {
    "name": "My name 3",
    "cpf": "45486737688",
    "phone": "11987654321",
    "email": "myemail3@test.com.br"
  },
  {
    "name": "My name 4",
    "cpf": "74668869066",
    "phone": "11987654321",
    "email": "myemail4@test.com.br"
  }
]
```

### Plus:
 - A página ser responsiva;
 - Permitir edição;
 - Uso de pré-processador css;
 - TDD

### O que esperamos:
 - Utilizar ECMAScript 6+;
 - Criar uma breve descrição da solução utilizada;
 - Angularjs;
 - TypeScript.

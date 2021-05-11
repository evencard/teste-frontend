 ![Evencard](https://avatars.githubusercontent.com/u/84023071?s=100&v=4)
 # Teste de dev frontend da Evencard
Este teste é aplicado aos candidatos as vagas de desenvolvimento frontend.

### O Desafio

O objetivo desse teste é desenvolver uma aplicação com 2 páginas, sendo uma que lista os estabelecimentos cadastrados e outra que permita mostrar os detalhes/edição do registro selecionado de acordo com a estrutura abaixo:

##### Campos

* Nome Fantasia
* CNPJ
* Valor de Faturamento Mensal
* Data de Início de Relacionamento


#### Requisitos
- A primeira página deve exibir uma lista de estabelecimentos, e pra cada registro ter a opção de detalhar / editar o mesmo;
- Ainda na página de listagem deve existir uma maneira de criar um novo estabelecimento.
- Na página de detalhe deve ser possível editar os dados;
- Fazer a persistência dos dados no `localStorage` ou `IndexedDB`;
- Deve utilizar algum dos frameworks:

	- Vue JS
	- AngularJS
	- React JS

Para ter o estado inicial da lista de estabelecimentos, pode usar o exemplo abaixo:

```json
[
  {
    "nomeFantasia": "Acme Software ME",
    "cnpj": "92.211.058/0001-00",
    "valorFaturamentoMensal": 300000.00,
    "dataInicio": "2020-03-01"
  },
 {
    "nomeFantasia": "Contoso Financeira SA",
    "cnpj": "98.024.704/0001-07",
    "valorFaturamentoMensal": 1500000.00,
    "dataInicio": "2018-09-01"
  },
 {
    "nomeFantasia": "Adventureworks  Veículos Ltda",
    "cnpj": "20.234.033/0001-03",
    "valorFaturamentoMensal": 2000000.00,
    "dataInicio": "2016-12-01"
  }
]
```

A partir deste ponto utilizar o `localStorage/IndexedDB` para persistir localmente as informações.

#### Plus:
 - A página ser responsiva;
 - Utilizar algum framework css
 - Permitir excluir um registro;
 - Uso de pré-processador css;
 - Testes unitários;

#### O que esperamos:
 - Que a aplicação funcione
 - Padrão de Projeto e boas práticas de Orientação a Objetos;
  - Criar um passo a passo de como rodar sua aplicação [(Sugestão)](https://github.com/wearehive/project-guidelines/blob/master/README.sample.md);
 - Criar uma breve descrição da solução utilizada.
 
 ### Forma de Entrega
 Pode utilizar alguma das formas abaixo:
  - Subir o código no seu github pessoal ou similar e nos enviar o link
  - Subir o zip do código no seu drive e compartilhar conosco (dropbox, google drive, one drive, etc)
  - Enviar o zip por email para provas@evencard.com.br

** Use sua criatividade  **

# FinAPI - Financeira
FINAPI - API financeira para transações bancarias, podendo criar uma conta, ver o extrato bancário,
realizar um saque etc.

## 💻 Sobre o Projeto
Esse é o Primeiro projeto do bootcamp do Ignite da Rocketseat, desenvolvida nas aulas do primeiro capitulo do curso Ignite, com o intuito de colocar em prática os fundamentos do NodeJs.

## 🧪 Tecnologias
- NodeJs(https://nodejs.org/)
- Express(https://expressjs.com/)
- Uuidv4(https://www.npmjs.com/package/uuidv4)


### Requisitos
- [x] Deve ser possível criar uma conta.
- [x] Deve ser possível buscar o extrato bancário do cliente.
- [x] Deve ser possível realizar um depósito.
- [ ] Deve ser possível realizar um saque.
- [ ] Deve ser possível buscar o extrato bancário do cliente por data.
- [ ] Deve ser possível atualizar dados da conta do cliente.
- [ ] Deve ser possível obter dados da conta do cliente.
- [ ] Deve ser possível deletar uma conta

### Regras de negócio
- [x] Não deve ser possível cadastrar uma conta com CPF já existente.
- [x] Não deve ser possível buscar estrato em uma conta não existente.
- [x] Não deve ser possível fazer depósito em uma conta não existente.
- [ ] Não deve ser possível fazer saque em uma conta não existente.
- [ ] Não deve ser possível excluir uma conta não existente.
- [ ] Não deve ser possível fazer saque quando o saldo for insuficiente.

### Como rodar o Projeto
```bash
    # Clonar o repositório
    $ git clone https://github.com/arkanael/FinAPI

    # Entrar no diretório
    $ cd FinApi

    # Instalar as dependências
    $ yarn install

    # Iniciar o projeto
    $ yarn start
```

<h4 align=center>Desenvolvido por <a href="https://www.linkedin.com/in/lbandeira/">Luiz Guilherme Bandeira</a></h4>

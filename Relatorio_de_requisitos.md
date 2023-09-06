# Relatório Especificação de Requisitos

## Engenharia de software 2023.2 | Universidade Federal do Tocantins - Palmas, 2023

## Introdução

O projeto desenvolvido na disciplina Engenharia de Software do semestre 2023.2 é dividido em etapas. Primeiramente, os integrantes descrevem os casos expandidos de uso e user stories dos requisitos funcionais do sistema. Foi combinado a utilização da plataforma GitHub para gerenciar e controlar as versões do projeto, além do método Kanban para gestão ágil, por meio da ferramenta Trello. Todo o trabalho será desenvolvido no formato markdown.

### Escopo:
Desenvolver uma plataforma de prestação de serviços que conecta prestadores de serviços a usuários, permitindo que os prestadores ofereçam seus serviços e os usuários solicitem os mesmos. A plataforma deve permitir que os prestadores de serviços criem perfis com informações pessoais, habilidades e preços, além de possibilitar a criação de perfis de usuários com informações de contato e preferências. Os usuários devem ser capazes de buscar e filtrar prestadores com base em critérios como localização e classificações, enviar solicitações de serviços e visualizar históricos de transações. Além disso, o sistema deve suportar a avaliação e revisão de prestadores e oferecer funcionalidades de pagamento seguro.

### Épico 1: Gerenciamento de Usuário -> RF01, RF15, R24
### Épico 2: Gerenciamento de Serviços -> RF08, RF10, RF14, RF22
### Épico 3: Gerenciamento de Solicitações de serviços -> RF09, RF11, RF23, RF27
### Épico 4: Avaliação de serviços -> RF02, RF03, RF06, RF07, RF16, RF17, RF20, RF21, RF25, RF28
### Épico 5: Gerenciamento de Despesas e Receitas -> RF04, RF05, RF12, RF13, RF18, RF19, RF26

## Iteração 1

- [X] RF01 -  Cadastrar prestador de serviço. [Benedito Jaime](https://github.com/beneX90) Revisado por [Jeová de Sousa Barbosa](https://github.com/jeovazin1v9)
- [X] RF02 - Cadastrar usuário. [Caio Henrique Pinho Santos](https://github.com/CaioHPS3) Revisado por [Diogo Eduardo da Silva](https://github.com/DioguBrabo)
- [X] RF03 -  Realizar Login. [Diogo Eduardo da Silva](https://github.com/DioguBrabo) Revisado por [Mateus Alves Araujo](https://github.com/MateusAlvez)
- [X] RF04 -  Buscar prestadores de serviço por critérios. [Érick Santos Marçal](https://github.com/erarich) Revisado por [Gabriel Tavares](https://github.com/GabrielUFT)
- [X] RF05 - Enviar solicitação de serviço. [Ícaro Mesquita Ponce](https://github.com/icarompo) Revisado por [Caio Henrique Pinho Santos](https://github.com/CaioHPS3)
- [X] RF06 - Visualizar histórico de transações. [Jeová de Sousa Barbosa](https://github.com/jeovazin1v9) Revisado por [João Pedro Noronha](https://github.com/jpnoronhaa)
- [X] RF07 - Aceitar ou recusar solicitação de serviço. [João Pedro Noronha](https://github.com/jpnoronhaa) Revisado por [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM)

<br/>

## Iteração 2


- [X] RF08 - Realizar o pagamento seguro pelo serviço prestado [Benedito Jaime](https://github.com/beneX90) Revisado por [Jeová de Sousa Barbosa](https://github.com/jeovazin1v9)
- [X] RF09 - Avaliar e revisar prestadores de serviço. [Caio Henrique Pinho Santos](https://github.com/CaioHPS3) Revisado por [Diogo Eduardo da Silva](https://github.com/DioguBrabo)
- [X] RF10 -  Manter perfis de prestadores de serviço atualizados (foto, descrição, etc.). [Diogo Eduardo da Silva](https://github.com/DioguBrabo) Revisado por [Mateus Alves Araujo](https://github.com/MateusAlvez)
- [X] RF11 - Notificar usuários sobre atualizações em solicitações de serviço (aceitação, recusa, conclusão).. [Érick Santos Marçal](https://github.com/erarich) Revisado por [Gabriel Tavares](https://github.com/GabrielUFT)
- [X] RF12 -  Permitir que os usuários editem seus perfis (informações de contato, preferências, etc.). [Ícaro Mesquita Ponce](https://github.com/icarompo) Revisado por [Caio Henrique Pinho Santos](https://github.com/CaioHPS3)
- [X] RF13 -   Implementar funcionalidade de pesquisa avançada de prestadores de serviço (por avaliação, preço, etc.). Revisado por [João Pedro Noronha](https://github.com/jpnoronhaa)
- [X] RF14 -Oferecer suporte a diferentes métodos de pagamento (cartão de crédito, PayPal, etc.).  [João Pedro Noronha](https://github.com/jpnoronhaa) Revisado por [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM)

<br/>

---
## **RF01 - Inserir nome de usuário**

<br/>

#### Autor: [Vinícius MAciel](https://github.com/viniciusDevelopment)

#### Revisor: [Vinícius Maciel Pires](link_do_perfil_do_revisor)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF01 - Inserir nome do usuário;                                                       |
| Resumo          | Adicionar o nome que será usado pelo usuário da conta bancária; |
| Ator principal  | Usuário - se cadastrará;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | O(s) ator(es) deve ter acessado o sistema do aplicativo;                          |
| Pós-condição    | O nome deverá ficar salvo na conta                                             |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de inserir o nome no menu principal.            |
| Passo 2 | O sistema exibe o nome do usuário. |

<br/>

### User story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **vizualizar meu saldo** para que **eu tenha um controle da minha situação financeira.** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**.

<br />

---

## **RF02 - Visualizar saldo**

<br/>

#### Autor: [@CaioHPS3](https://github.com/CaioHPS3) - Caio Henrique Pinho Santos

#### Revisor: [Diogo Eduardo da Silva](https://github.com/DioguBrabo)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF02 - Visualizar o saldo;                                                       |
| Resumo          | Visualiza o saldo para que possa saber sua situação bancaria; |
| Ator principal  | Usuário - Visualiza seu saldo;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | O(s) ator(es) deve ter acessado o sistema do aplicativo;                          |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar o saldo no menu principal.            |
| Passo 2 | O sistema exibe o saldo altual do usuário.

<br/>

 ### User story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **vizualizar meu saldo** para que **eu tenha um controle da minha situação financeira.**| Certificar que todos campos estao preenchidos |


<br/>

---

## **RF03 - Visualizar extrato**

<br/>

#### Autor: [@DioguBrabo](https://github.com/DioguBrabo) - Diogo Eduardo da Silva

#### Revisor: [Mateus Alves Araujo](https://github.com/MateusAlvez)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF03 - Visualizar o extrato;                                                       |
| Resumo          | Visualiza o extrato bancário de um determinado período; |
| Ator principal  | Usuário - Visualiza seu extrato;                                                    |
| Ator secundário | -                                                                             |
| Pré-condição    | O(s) ator(es) deve ter acessado o sistema do aplicativo;                          |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar o extrato no menu principal.            |
| Passo 2 | O sistema pede para o usuário informar um período relativo ao qual deseja visualizar o extrato. |
| Passo 3 | O sistema exibe o extrato do usuário no período informado. |

<br/>

### User story

**Persona um, usuário comum.**

|  User Story                                        | Critério de aceitação                                 |
| ------------------------------------------------- | ----------------------------------------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **visualizar o  meu extrato num período específico**, para que **eu tenha um controle melhor das minhas transações.** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. |

<br/>

---

## **RF04 - Inserir Despesas**

<br />

#### Autor: [Érick Santos Marçal](https://github.com/erarich)
#### Revisor: [Gabriel Tavares](https://github.com/GabrielUFT)

<br />

### Casos de Uso


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Inserir despesa                                                     |
| Resumo          | É esperado que o usuário tenha a possibilidade de inserir as despesas|
| Ator principal  | Usuário que faz uso da plataforma                                   |
| Ator secundário | Não possui                                                          | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma            |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login   |

<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | Entrar no aplicativo e fazer login                                          |
| Passo 2 | Entrar na seção de Despesas                                                 |
| Passo 3 | Clicar no botão "Inserir"                                                   |
| Passo 4 | Inserir campos do formulário                                                |
| Passo 5 | Salvar                                                                      |
<br />

#### Campos do formulário

| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome             | Sim          | Sim       | Texto        |
| Data             | Sim          | Sim       | Data         |
| Conta            | Sim          | Sim       | Texto        |
| Tipo             | Sim          | Sim       | Texto        |
| Valor            | Sim          | Sim       | Numérico     |

<br />

#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Inserir despesa | Confirmar dados inseridos |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Despesa inserida com sucesso | Isso confirma e garante todo êxito na operação de inserção de despesa   | Texto   |
<br />

                                   
### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas despesas salvas na plataforma a fim de ter um controle sobre os meus gastos | Certificar que todos campos estao preenchidos

<br/>

---

## **RF05 - Inserir Receita**

<br />

#### Autor: Icaro Mesquita Ponce[@icarompo](https://github.com/icarompo)
#### Revisor: Caio Henrique Pinho Santos[@CaioHPS3](https://github.com/CaioHPS3)  
<br />

### Casos de Uso
<br />

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Inserir receita                                                   |
| Resumo          | É esperado que o usuário tenha a possibilidade de inserir as receitas|
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma          |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login |
<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login        |
| Passo 2 | Entrar na seção de Receitas               |
| Passo 3 | Clicar no botão "Inserir"                 |
| Passo 4 | Inserir campos do formulário              |
| Passo 5 | Salvar                                    |
<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome             | Sim          | Sim       | Texto        |
| Data             | Sim          | Sim       | Data         |
| Conta            | Sim          | Sim       | Texto        |
| Tipo             | Sim          | Sim       | Texto        |
| Valor            | Sim          | Sim       | Numérico     |
<br />

#### Opções do usuário
| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Inserir receita | Confirmar dados inseridos |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Receita inserido com sucesso | Isso confirma e garante todo êxito na operação de inserção de receita   | Texto   |
<br />

#### Fluxo alternativo

| Não Possui                                 |
<br /><br />

### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas dados de receitas salvos na plataforma para ter um controle dos meus gastos| Certificar que todos campos estão preenchidos

<br/>

---

## **RF06 - Visualizar receitas (valor) no mês.**

<br/>

#### Autor: [@jeovazin1v9](https://github.com/jeovazin1v9) - Jeová de Sousa Barbosa

#### Revisor: [@jpnoronhaa](https://github.com/jpnoronhaa) - João Pedro Noronha

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | RF06 - Visualizar o valor das receitas  do mês                                              |
| Resumo          | É esperado que o usuário tenha a possibilidade de visualizar o valor das receitas do mês                                                                     |
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma e ter inserido alguma receita         |
| Pós-condição    | Não possui |

<br/>

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login        |
| Passo 2 | Estar no aplicativo e clicar no botão 'Visualizar receitas'|

<br/>

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Receitas         | Não          | Não       | Texto        |

<br/>

#### Opções do usuário
| Opção             | Descrição                 | Atalho |
| -------------     | ------------------------- | ------ |
| Ocultar receitas | Trocar o texto que mostra o valor das receitas por um alternativo |        |

<br/>

#### Relatório de usuário

| Campo      | Descrição   | Formato |
| ---------- | ----------- |---------|
| Não possui |             |         |

<br/>

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | --------------------------------------------------------------------------------------------- |
| Passo 1.1 | O usuário não cadastrou nenhuma receita                                                         |
| Passo 1.2 | O sistema informa que não há receitas cadastradas                                             |

<br/>

### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **usuário do aplicativo** preciso ser capaz de **visualizar o valor das minhas receitas ou ocultá-las** para que **eu tenha um controle maior da minha situação financeira** | O usário poderá ver o valor das receitas do mês ou ocultá-las, se preferir, utilizando um botão ao lado.

<br/>

---

## **RF07 - Visualizar despesas (valor) no mês**

<br/>

#### Autor: [João Pedro Noronha](https://github.com/jpnoronhaa)

#### Revisor: [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM)

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Visualizar despesas (valor) no mês                                |
| Resumo          | Visualiza o somatório das despesas que o usário teve no mês       |
| Ator principal  | Usuário que faz uso da plataforma                                 |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma e adicionado alguma despesa                                                                               |
| Pós-condição    | Não possui                                                        | 

<br/>

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login        |
| Passo 2 | Visualizar o valor das despesas           |

<br/>

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Despesas         | Não          | Não       | Texto        |

<br/>

#### Opções do usuário
| Opção             | Descrição                                                         | Atalho |
| ----------------- | ----------------------------------------------------------------- | ------ |
| Esconder despesas | Trocar o texto que mostra o valor das despesas por um alternativo |        |

<br/>

#### Relatório de usuário

| Campo      | Descrição  | Formato |
| ---------- | ---------- | ------- |
| Não possui |            |         |

<br/>

#### Fluxo alternativo
| Passos    | Descrição                                               |
| --------  | ------------------------------------------------------- |
| Passo 1.1 | O ator não cadastrou nenhuma despesa                    |
| Passo 1.2 | O sistema informa que não existem despesas cadastradas  |
<br />


### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto um **usuário do aplicativo** eu preciso ser capaz de **visualizar o valor das minhas despesas ou ocultá-las** para que **eu tenha um controle da minha situação financeira**. | O usário poderá ver o valor das despesas do mês ou ocultá-las, se preferir, utilizando um botão ao lado. 

<br/>

---

## RF08 - Inserir Conta Bancaria

<br/>

#### Autor: [@98loann](https://github.com/98loann)

#### Revisor: [Sophia Menezes Pontes](https://github.com/SophiaMenezes)

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Inserir conta Bancária                                            |
| Resumo          | É esperado que o usuário tenha a possibilidade de inserir a conta bancária na qual ele quer ter controle                                                                              |
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma          |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login |
<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login        |
| Passo 2 | Estar no aplicativo e clicar no botão +   |
| Passo 3 | Digitar o nome do banco e o tipo de conta |
| Passo 4 | Inserir o saldo total da conta            |
| Passo 5 | Salvar                                    |
<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome             | Sim          | Sim       | Texto        |
| Banco            | Sim          | Sim       | Texto        |
| Tipo de Conta    | Sim          | Sim       | Texto        |
| Saldo            | Sim          | Sim       | Numérico     |
<br />

#### Opções do usuário
| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Inserir banco | Confirmar dados inseridos |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Banco inserido com sucesso | Isso confirma e garante todo êxito na operação de cadastro de banco   | Texto   |
<br />

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | --------------------------------------------------------------------------------------------- |
| Passo 1.1 | O ator tenta adicionar um conta de banco que já foi cadastrada                                |
| Passo 1.2 | O sistema acusa que a conta em questão já existe                                              |
| Passo 2.1 | O ator tenta adicionar um novo banco                                                          |
| Passo 2.2 | O sistema exibe que não foi possível concluir a operação                                      |
<br />

### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas informações salvas na plataforma através de uma conta a fim de ter mais praticidade | Certificar que todos campos estão preenchidos

<br/>

---

## RF09 - Inserir Cartão de crédito

<br/>

#### Autor: [@luisfilipebandeira](https://github.com/luisfilipebandeira)

#### Revisor: [Erick Marçal](https://github.com/erarich)

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Inserir cartão de crédito                                         |
| Resumo          | É esperado que o usuário tenha a possibilidade de inserir o cartão de crédito que ele quer ter controle|
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma          |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login |
<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login        |
| Passo 2 | Estar no aplicativo e clicar no botão adicionar cartão   |
| Passo 3 | Digitar o número do cartão |
| Passo 4 | Digitar o nome que está impresso no cartão |
| Passo 5 | Digitar a data de vencimento do cartão |
| Passo 6 | Digitar o CVV do cartão |
| Passo 7 | Salvar                                    |
<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome             | Sim          | Sim       | Texto        |
| Numero do cartão            | Sim          | Sim       | Texto        |
| Data de validade    | Sim          | Sim       | Texto        |
| CVV            | Sim          | Sim       | Texto     |
<br />

#### Opções do usuário
| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Inserir Cartão | Confirmar dados inseridos |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cartão inserido com sucesso | Isso confirma e garante todo êxito na operação de cadastro dp cartão   | Texto   |
<br />

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | --------------------------------------------------------------------------------------------- |
| Passo 1.1 | O ator tenta adicionar um cartão que já foi cadastrado                                |
| Passo 1.2 | O sistema acusa que o cartão em questão já existe                                              |
| Passo 2.1 | O ator tenta adicionar um novo cartão                                                          |
| Passo 2.2 | O sistema exibe que não foi possível concluir a operação                                      |
<br />

### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas informações salvas na plataforma através de uma conta a fim de ter mais praticidade | Certificar que todos campos estão preenchidos

<br/>

---

## **RF10 - Visualizar Contas Bancárias.**

<br/>

### Autor: [Marcos Vinicius Barbosa e Silva](https://github.com/eziors)

### Revisor: [Benedito Jaime](https://github.com/orgs/Turma-2023-1-Engenharia-de-Software/people/beneX90)

<br/>

###  Caso de uso

| Item            |Descrição                                                |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF10 - Visualizar Contas Bancárias;                                       |
| Resumo          | Responsável pela visualização de contas bancárias do usuário; |
| Ator principal  | Usuário - Vizualizador da conta;                               |
| Ator secundário | -                                                                                   |
| Pré-condição    | Ter acesso ao aplicativo, e ter pelo menos uma conta adicionada;                          |
| Pós-condição    | -                                                                                   |

#### Fluxo principal


| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar suas contas bancárias         |  
| Passo 2 | O usuário seleciona a opção de visualizar uma conta especifica


### User story

**Persona um, usuário comum.**

| User Story                                                                                                                                                              | Critério de aceitação                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **Verificar minhas contas bancárias ** para que **eu tenha uma controle da minha atual situação financeira.** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. |

<br/>

---

## **RF11 - Visualizar contas de Crédito**

<br/>

#### Autor: [@SophiaMenezes](https://github.com/SophiaMenezes) - Sophia Menezes Pontes

#### Revisor: [Luan Porto](https://github.com/98loann)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF11 - Visualizar contas de crédito;                                                |
| Resumo          | O usuário pode ver o saldo atual da sua conta de crédito e monitorar seus gastos;   |
| Ator principal  | Usuário do aplicativo de controle financeiro;                                       |
| Ator secundário | -                                                                                   |
| Pré-condição    | Usuário já deve ter uma conta de crédito cadastrada no aplicativo;                  |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar "contas de crédito" no menu principal.            |
| Passo 2 | O aplicativo exibe uma lista de todas as contas de crédito associadas à conta do usuário.   |
| Passo 3 | O usuário seleciona a conta de crédito específica para ver mais detalhes, como saldo atual, limite de crédito e data de vencimento da próxima fatura;   |
<br />


### User story

*Persona um, usuário comum.*

| User Story                                                                                                                                                              | Critério de aceitação                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| "Enquanto um *usuário do aplicativo de controle financeiro*, eu preciso visualizar minhas contas de crédito e seus respectivos saldos para poder monitorar meus gastos e manter meu orçamento sob controle." | O usuário poderá selecionar uma conta de crédito específica para ver mais detalhes. |

<br/>

---

## **RF12 - Editar despesas**

<br/>

#### Autor: [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM) 

#### Revisor: [Marcos Vinicius Barbosa e Silva](https://github.com/eziors)

<br/>

### Caso de uso

Item	          |Descrição
:----------------:|:--------------------------------:
Caso de uso	Editar| despesas do usuário.
Resumo	O usuário | deseja editar as suas despesas.
Ator principal	  |Usuário
Pré-condição	  |Existam despesas constando para o usuário em seu histórico.
Pós-condição	  |O usuário consegue editar suas despesas da forma desejada.

<br/>

#### Fluxo principal

Passos	  |Descrição
:--------:|:-----------------------------------------------:
Passo 01  |O usuário acessa o app.
Passo 02  |O usuário abre as suas despesas
Passo 03  |O usuário seleciona a opção de editar a despesa.
Passo 04  |O usuário abre a edição de sua despesa.

<br/>

#### Opções de usuário


Opção          |Descrição
---------------|----------------
Editar despesas|Edita a despesa.
<br />

### User Story

User story|	Critério de aceitação
-------------|--------------------
Enquanto ator quando visualizo minhas despesas gostaria de poder edita-las.|	Ator necessita ter despesas para editar.

<br/>

---

## **RF13 - Editar receitas.**

<br/>

#### Autor: [Mateus Alves Araujo](https://github.com/MateusAlvez) 

#### Revisor: [Ícaro Mesquita Ponce](https://github.com/icarompo)

<br/>

###  Caso de uso

| Item            |Descrição                                                |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF13 - Editar receita;                                       |
| Resumo          | Responsável pela mudança de receita do usuário; |
| Ator principal  | Usuário- Editar receita;                               |
| Ator secundário | -                                                                                   |
| Pré-condição    | Ter acesso ao aplicativo, e ter saldo adicionado.;                          |
| Pós-condição    | -                                                                                   |
<br />

#### Fluxo principal


| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar o saldo no menu principal.        |  
| Passo 2 | O usuário seleciona a opção de modificar o saldo
<br />


### User story

**Persona um, usuário comum.**

| User Story                                                                                                                                                              | Critério de aceitação                                         |
 |----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
 Enquanto **um usuário do aplicativo** eu preciso ser capaz de **Modificar meu saldo** para que **eu tenha um controle da minha situação financeira.** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. |

<br/>

---

## **RF14 - Editar conta bancária**

<br/>

#### Autor: [Raphael Sales de Souza](https://github.com/raphaelsales)

#### Revisor: [Vinicius Maciel](https://github.com/) 

<br/>

### Caso de uso

| Item            |Descrição                                                |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF13 - Editar conta bancária;                                       |
| Resumo          | Responsável pela alteração de dados da conta bancária; |
| Ator principal  | Usuário- Editar conta bancária;                               |
| Ator secundário | -                                                                                   |
| Pré-condição    | Ter acesso ao aplicativo, e ter uma conta adicionada.;                          |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário faz login no aplicativo             |
| Passo 2 | O usuário seleciona a opção de visualizar conta bancária no menu principal.|
| Passo 3 | O usuário clica em editar conta bancária            |
| Passo 4 | O usuário preenche o formulário com as informações que deseja alterar|
| Passo 5 | O usuário clica em salvar conta bancária|

<br/>

#### Campos do Formulário

| Campo  | Obrigatório | Formato |
| ------- | ---------------------------|----------------------- |
| Nome   | Sim          | Texto    |
| Banco   | Sim          | Texto    |
| Tipo de Conta   | Sim          | Texto    |
| Saldo   | Sim          | Numérico    |
<br />

### User story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto um **usuário do aplicativo** eu preciso ser capaz de **editar os dados das minhas contas bancárias** para que **eu possa garantir a veracidade dos dados**. | Certifique-se de que o usuário preencheu corretamente os campos do formulário. 


---

## **RF15 - Editar nome de usuário**

<br/>

#### Autor: [Raphael Sales de Souza](https://github.com/raphaelsales)

#### Revisor: [Vinicius Maciel](https://github.com/)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | R151 - Editar nome do usuário;                                                       |
| Resumo          | Alterar e salvar o nome que será usado pelo usuário da conta bancária; |
| Ator principal  | Usuário - Mudará o nome;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | O(s) ator(es) deve ter acessado o sistema do aplicativo;                          |
| Pós-condição    | O nome deve ser alterado após a ação.                                            |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de editar o nome no menu principal.            |
| Passo 2 | O sistema exibe o ícone para alterar o nome do usuário. |
| Passo 3 | O usuário digita o novo nome. |
| Passo 4 | O sistema salva o novo nome na conta bancária. |

<br/>

#### Campos do Formulário

| Campo  | Obrigatório | Formato |
| ------- | ---------------------------|----------------------- |
| Nome   | Sim          | Texto    |
| Banco   | Sim          | Texto    |
| Tipo de Conta   | Sim          | Texto    |
| Saldo   | Sim          | Numérico    |

<br />

### User story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **alterar o meu nome** para que **eu possa consertar o meu nome, caso eu o tenha errado** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. 

<br />

## **RF16 - Esconder saldo**

<br/>

#### Autor: [Raphael Sales de Souza](https://github.com/raphaelsales) 

#### Revisor: [Raphael Sales de Souza](https://github.com/raphaelsales)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF02 - Esconder o saldo;                                                       |
| Resumo          | Esconder o saldo para que possa ter uma privacidade sobre sua situação bancaria; |
| Ator principal  | Usuário - Esconder seu saldo;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | O(s) ator(es) deve ter acessado o sistema do aplicativo;                          |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de esconder o saldo no menu principal.            |
| Passo 2 | O sistema oculta o saldo do usuario

<br/>

 ### User story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **Esconder meu saldo** para que **eu tenha um controle da minha situação financeira.**| Certificar que todos campos estao preenchidos |

<br/>

---


## **RF17 - Esconder extrato**

<br/>

#### Autor: [Raphael Sales de Souza](https://github.com/raphaelsales) 

#### Revisor: [Raphael Sales de Souza](https://github.com/raphaelsales) 


<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF17 - Esconder o extrato do menu principal;                                                       |
| Resumo          | Alterna o estado de visualização do extrato na home da aplicação; |
| Ator principal  | Usuário;                                                    |
| Ator secundário | -                                                                             |
| Pré-condição    | O(s) ator(es) deve ter acessado o sistema do aplicativo;                          |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de esconder a view do extrato do menu principal.            |
| Passo 2 | O sistema esconde a view do extrato habilitado que apareceria no menu principal. |

<br/>

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | --------------------------------------------------------------------------------------------- |
| Passo 1 | O sistema pede para o usuário escolher um período ao qual será mostrato um novo extrato correspondente na home da aplicação.                                                |
| Passo 2 | O sistema habilita a visualização do extrato referente ao período informado na tela inicial.                                                 |

<br/>

### User story

**Persona um, usuário comum.**

| User Story                                        | Critério de aceitação                                 |
| ------------------------------------------------- | ----------------------------------------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **visualizar o  meu extrato na home da aplicação**, para que **eu tenha um acesso rápido aos meus gastos num determinado período.** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. |

<br/>



## **RF18 - Buscar despesas**

<br/>

#### Autor: [Raphael Sales de Souza](https://github.com/raphaelsales) 
#### Revisor: [Raphael Sales de Souza](https://github.com/raphaelsales) 


<br />

### Casos de Uso


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Buscar despesas                                                    |
| Resumo          | É esperado que o usuário tenha a possibilidade de buscar as despesas|
| Ator principal  | Usuário que faz uso da plataforma                                   |
| Ator secundário | Não possui                                                          | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma            |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login   |

<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | Entrar no aplicativo e fazer login                                          |
| Passo 2 | Entrar na seção de Despesas                                                 |
| Passo 3 | Clicar no barra de pesquisa                                                 |
| Passo 4 | Digitar texto que deseja buscar                                             |
| Passo 5 | Clicar no ícone de pesquisar (uma lupa)                                     |
<br />


#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Buscar despesa | Clicar no ícone de pesquisar  |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Despesas encontradas com sucesso | Isso confirma e garante todo êxito na operação de busca de despesas   | Texto   |

<br />

                                   
### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter acesso às minhas despesas registradas na plataforma a fim de visualizar e monitorar meu histórico de gastos | Certificar que a busca retorna as despesas corretas de acordo com os filtros selecionados, como data, categoria ou valor.

<br/>

## **RF19 - Buscar receitas**

<br/>

#### Autor: [Raphael Sales de Souza](https://github.com/raphaelsales) 
#### Revisor: [Raphael Sales de Souza](https://github.com/raphaelsales) 

<br />

### Casos de Uso


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Buscar receitas                                                     |
| Resumo          | É esperado que o usuário tenha a possibilidade de buscar as receitas|
| Ator principal  | Usuário que faz uso da plataforma                                   |
| Ator secundário | Não possui                                                          | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma            |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login   |


<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | Entrar no aplicativo e fazer login                                          |
| Passo 2 | Entrar na seção de Receitas                                                 |
| Passo 3 | Clicar no barra de pesquisa                                                 |
| Passo 4 | Digitar texto que deseja buscar                                             |
| Passo 5 | Clicar no ícone de pesquisar (uma lupa)                                     |
<br />


#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Buscar receita | Clicar no ícone de pesquisar  |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Receitas encontradas com sucesso | Isso confirma e garante todo êxito na operação de busca de receitas   | Texto   |
<br />

                                   
### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter acesso às minhas receitas registradas na plataforma a fim de visualizar e monitorar meu histórico de entradas | Certificar que a busca retorna as receitas corretas de acordo com os filtros selecionados, como data, categoria ou valor.

<br/>

## **RF20 - Visualizar extrato no mês.**

<br/>

#### Autor:[Raphael Sales de Souza](https://github.com/raphaelsales) 


#### Revisor: [Raphael Sales de Souza](https://github.com/raphaelsales) 


<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | RF20 - Visualizar extrato no mês                                              |
| Resumo          | É esperado que o usuário tenha a possibilidade de visualizar o extrato no mês que desejar     |
| Ator principal  | Usuário que faz uso da plataforma                                                             |
| Ator secundário | Não possui                                                                                    | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma e ter inserido receitas e/ou despesas|
| Pós-condição    | Não possui |

<br/>

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login        |
| Passo 2 | Estar no aplicativo e clicar no botão 'Visualizar extrato'|
| Passo 3 | Selecionar a opção de filtragem e escolher o mês|

<br/>

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Extrato          | Não          | Não       | Texto        |

<br/>

#### Opções do usuário
| Opção             | Descrição                 | Atalho |
| -------------     | ------------------------- | ------ |
| Alterar o mês | Alterar o mês que deseja visualizar o extrato   |        |

<br/>

#### Relatório de usuário

| Campo      | Descrição   | Formato |
| ---------- | ----------- |---------|
| Não possui |             |         |

<br/>

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | --------------------------------------------------------------------------------------------- |
| Passo 1.1 | O usuário não possui nenhuma receita e nenhuma despesa no mês selecionado                                                       |
| Passo 1.2 | O sistema informa que não há extrato naquele mês                                            |

<br/>

### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **usuário do aplicativo** preciso ser capaz de **visualizar o extrato do mês que eu necessitar ver** para que **eu tenha um controle maior da minha situação financeira** | O extrato financeiro exibido deve incluir todas as transações que ocorreram durante o mês selecionado, incluindo a data da transação, o valor e uma breve descrição.

<br/>

## **RF21 - Deletar Conta (valor) no mês.**

<br/>

#### Autor: [Raphael Sales de Souza](https://github.com/raphaelsales) 
#### Revisor: [Raphael Sales de Souza](https://github.com/raphaelsales) 

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Deletar Conta (valor) no mês                                            |
| Resumo          | O usuário deve poder remover o valor da conta em um determinado mês             |
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha inserido uma conta no mês em que está          |
| Pós-condição    | É necessário que para remover uma conta, ela já deva estar previamente cadastrada |

<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo                      |
| Passo 2 | Abrir a conta e o mês que ele quer excluir    |
| Passo 3 | Clicar nas opções e selecionar excluir    |
| Passo 4 | Confirmar a exclusão                      |

<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Conta            | Sim          | Sim       | Texto        |
| Mês            | Sim          | Sim       | Data        |
| Confirmar exclusão          | Sim          | Sim       | Texto     |

<br />

#### Opções do usuário

| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Deletar conta | Confirmar a exclusão      |        |

<br />

#### Relatório de usuário
| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Conta excluída com sucesso | Isso confirma e garante todo êxito na operação de exclusão de conta   | Texto   |

<br />

#### Fluxo alternativo
| Não possui |

<br />

### User Story

**Persona um, usuário comum.**
| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas informações deletadas com garantia de que nada ficou | Certificar de confirmar a exclusão

<br/>

## **RF22 - Deletar Conta Bancaria**

<br/>

#### Autor: [Raphael Sales de Souza](https://github.com/raphaelsales) 
#### Revisor: [Raphael Sales de Souza](https://github.com/raphaelsales) 


<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Deletar conta Bancária                                            |
| Resumo          | É esperado que o usuário tenha a possibilidade de remover as conta bancárias que ele já inseriu                                                                              |
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha uma conta bancaria ja inserida          |
| Pós-condição    | É necessário que para remover uma conta, ela já deva estar previamente cadastrada |

<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo                      |
| Passo 2 | Abrir a conta na qual ele quer excluir    |
| Passo 3 | Clicar nas opções e selecionar excluir    |
| Passo 4 | Confirmar a exclusão                      |

<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Banco            | Sim          | Sim       | Texto        |
| Confirmar exclusão          | Sim          | Sim       | Texto     |

<br />

#### Opções do usuário

| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Deletar banco | Confirmar a exclusão      |        |

<br />

#### Relatório de usuário
| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Banco deletado com sucesso | Isso confirma e garante todo êxito na operação de exclusão do banco   | Texto   |

<br />

#### Fluxo alternativo
| Não possui |

<br />

### User Story

**Persona um, usuário comum.**
| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas informações deletadas com garantia de que nada ficou | Certificar de confirmar a exclusão

<br/>

## **RF23 - Deletar cartão de crédito**

<br/>

#### Autor: [Raphael Sales de Souza](https://github.com/raphaelsales) 
#### Revisor: [Raphael Sales de Souza](https://github.com/raphaelsales) 

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Deletar cartão de crédito                                           |
| Resumo          | O usuário deve poder remover o cartão de crédito do app             |
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha inserido um cartão de crédito          |
| Pós-condição    | É necessário que para remover um cartão de crédito, ele já deva estar previamente cadastrado |

<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo                      |
| Passo 2 | Editar cartões    |
| Passo 3 | Clicar nas opções e selecionar excluir    |
| Passo 4 | Confirmar a exclusão                      |

<br />

#### Opções do usuário

| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Deletar cartão | Confirmar a exclusão      |        |

<br />

#### Relatório de usuário
| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cartão excluído com sucesso | Isso confirma e garante todo êxito na operação de exclusão do cartão  | Texto   |

<br />

#### Fluxo alternativo
| Não possui |

<br />

### User Story

**Persona um, usuário comum.**
| User Story | Critério de aceitação |
| --------- | --------------------- |
| Eu enquanto "usuário comum" quero "ter o poder de entrar no aplicativo e excluir os cartões de crédito que já cadastrei" | Certificar de confirmar a exclusão

<br/>

## **RF24 - Sair do Aplicativo**

<br/>

#### Autor: [Marcos Vinicius Barbosa e Silva](https://github.com/eziors)
#### Revisor: [Benedito Jaime](https://github.com/orgs/Turma-2023-1-Engenharia-de-Software/people/beneX90)

<br />

### Casos de Uso


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Sair do aplicativo                                                    |
| Resumo          | Usuário deve ter a possibilidade de sair do aplicativo|
| Ator principal  | Usuário que utiliza a plataforma                                   |
| Ator secundário | Não possui                                                          | 
| Pré-condição    | É necessário que o usuário esteja no aplicativo            |
| Pós-condição    | É necessário que para sair da conta o usuário tenha aberto o aplicativo  |

<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | Entrar no aplicativo (Login não é obrigatório)                                     |
| Passo 2 | Sair do aplicativo atráves da opção de saída(Ícone seguido por nome)                                    |
<br />


#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Sair do aplicativo | Clicar no nome/ícone de saída   |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Saindo do aplicativo... | Isso confirma e garante todo êxito na operação de saída do aplicativo, encerramento o mesmo.   | Texto   |

<br />

                                   
### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter acesso a alguma opção de saída do aplicativo. | Certificar de que usuário conseguiu sair do aplicativo.

<br/>

## **RF25 - Filtrar contas de Crédito**

#### Autor: [@SophiaMenezes](https://github.com/SophiaMenezes) - Sophia Menezes Pontes


#### Revisor: [Luan Porto](https://github.com/98loann)

<br/>

## Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF25 - Filtragem das contas de Crédito;                                             |
| Resumo          | O usuário pode filtrar suas contas de crédito por saldo, limite de crédito e data de vencimento da próxima fatura;   |
| Ator principal  | Usuário do aplicativo de controle financeiro;                                       |
| Ator secundário | -                                                                                   |
| Pré-condição    | Usuário já deve ter uma conta de crédito cadastrada no aplicativo;                  |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar "contas de crédito" no menu principal;            |
| Passo 2 | O aplicativo exibe uma lista de todas as contas de crédito associadas à conta do usuário;   |
| Passo 3 | O usuário seleciona a opção de filtragem desejada: por saldo, por limite de crédito ou por data de vencimento da próxima fatura; |
| Passo 4 | O usuário insere o critério de filtro desejado, como um valor mínimo ou máximo de saldo ou limite de crédito, ou uma data de vencimento específica; |
| Passo 5 | O aplicativo filtra as contas de crédito com base nos critérios inseridos pelo usuário e exibe apenas as contas que atendem aos critérios de filtro; |


## User story

*Persona um, usuário comum.*

| User Story                                                                                                                                                              | Critério de aceitação                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| "Como usuário do aplicativo de controle financeiro, eu gostaria de filtrar minhas contas de crédito por saldo, limite de crédito e data de vencimento da próxima fatura, para que eu possa visualizar apenas as contas que atendem aos meus critérios de filtro e ter uma melhor compreensão da minha situação financeira em relação a cada conta de crédito." | O aplicativo deve permitir a seleção de uma ou mais opções de filtro para as contas de crédito: saldo, limite de crédito e data de vencimento da próxima fatura. |

<br/>


## **RF26-Deletar despesas**
<br/>

#### Autor: [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM) 

#### Revisor: [Marcos Vinicius Barbosa e Silva](https://github.com/eziors)

<br/>

### Caso de uso

Item	          |Descrição
:----------------:|:--------------------------------:
Caso de uso	      | Deletar despesas do usuário.
Resumo            | O usuário deseja deletar as suas despesas.
Ator principal	  | Usuário
Pré-condição	  | Existam despesas constando para o usuário em seu histórico.
Pós-condição	  | O usuário consegue deletar suas despesas da forma desejada.

<br/>

#### Fluxo principal

Passos	  |Descrição
:--------:|:-----------------------------------------------:
Passo 01  |O usuário acessa o app.
Passo 02  |O usuário abre as suas despesas
Passo 03  |O usuário seleciona a opção de deletar a despesa.
Passo 04  |O usuário comfirma a opção.

<br/>

#### Opções de usuário


Opção          |Descrição
---------------|----------------
Deletar despesas|Deleta a despesa.
<br />

### User Story

User story|	Critério de aceitação
-------------|--------------------
Enquanto ator quando visualizo minhas despesas gostaria de poder deleta-las.|	Ator necessita ter despesas para deletar.

<br/>

## **RF27-Editar cartão de crédito**

<br/>

#### Autor: [Mateus Alves Araújo](https://github.com/MateusAlvez)
#### Revisor: [Ícaro Mesquita Ponce](https://github.com/icarompo)

<br />

### Casos de Uso


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Editar cartão de crédito                                                   |
| Resumo          | Edição dos dados de cartão de crédito 
| Ator principal  | Usuário que faz uso da plataforma  -Editar cartão                                 |
| Ator secundário | Não possui                                                          | 
| Pré-condição    | Ter acesso ao aplicativo, e ter pelo menos um cartão adicionado.|
| Pós-condição    | - |

<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | O usuário acessa o sistema de gerenciamento de cartões de crédito                                         |
| Passo 2 | O usuário seleciona a opção "Meus cartões de crédito" na página inicial do sistema                                                 |
| Passo 3 | O usuário localiza o cartão de crédito que deseja editar na lista de cartões e clica no botão "Editar"                                                 |
| Passo 4 | O sistema exibe uma página de edição para o cartão de crédito selecionado, com todos os campos disponíveis para edição                                             |
<br />


#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Buscar cartão | Clicar no ícone de editar cartão  |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cartão editado com sucesso | Isso confirma e garante todo êxito na operação de edição de cartão   | Texto   |
<br />

                                   
### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
|<br> Como usuário, eu quero ser capaz de acessar minha lista de cartões de crédito existentes dentro do sistema e selecionar o cartão que desejo editar. Eu quero ter a opção de editar todas as informações do cartão de crédito, incluindo o número do cartão, nome do titular do cartão, data de vencimento, endereço de cobrança, informações de segurança, limite de crédito e outros detalhes importantes.| Certifique-se de que o usuário é capaz de acessar o aplicativo, ter um cartão já cadastrado


<br/>

## **RF28 - Exportar conteúdo**

#### Autor: [Gabriel Tavares dos Santos](https://github.com/GabrielUFT)

#### Revisor: [Luis FilipeBandeira](https://github.com/luisfilipebandeira) 

<br/>
## Caso de uso

| Item            |Descrição                                                |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF28 - Exportar conteúdo;                                       |
| Resumo          | Responsável por salvar os dados do aplicativo em um arquivo externo; |
| Ator principal  | Usuário- Exportar conteúdo;                               |
| Ator secundário | -                                                                                   |
| Pré-condição    | Ter acesso ao aplicativo, ter uma conta adicionada, ter dados para serem salvos.;                          |
| Pós-condição    | -                                                                                   |
<br/>
#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário faz login no aplicativo             |
| Passo 2 | O usuário seleciona a opção de configurações no menu principal.|
| Passo 3 | O usuário clica em exportar conteúdo |
| Passo 4 | O usuário seleciona o endereço onde o arquivo deve ser salvo|
| Passo 5 | O usuário clica em confirmar exportação de conteúdo|


## User story

**Persona um, usuário comum.**

| User Story                                                                                                                                                              | Critério de aceitação                                         |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **Exportar conteúdo** para que **eu possa fazer backup dos meus dados por meio do arquivo gerado da exportação.** | Certifique-se de que o usuário selecionou um **endereço válido** para o salvamento do arquivo. |

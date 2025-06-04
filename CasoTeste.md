## 🧪 ID: 001

###  Nome do Teste:
Adiconar Usuário 

###  Descrição:
 Verificar se o sistema permite cadastrar um novo usuário com dados válidos.

###  Pré-requisitos:
 Usuário deve estar na tela de cadastro
 Banco de dados deve estar acessível

### Procedimentos (Passos para execução do teste):
1.  Acessar a tela de cadastro
2.  Preencher os campos obrigatórios com dados válidos
3.  Clicar no botão "Cadastrar"

###  Dados de Entrada:
| Campo            | Valor de Teste        |
|------------------|------------------------|
| Nome             | Luis Guilherme         |
| Email            | luisguilherme@email.com|
| Senha            | Senha123               |
| Confirmar Senha  | Senha123               |

###  Resultado Esperado:
Usuário deve ser cadastrado e redirecionado para a página inicial com a mensagem "Cadastro realizado com sucesso"

###  Resultado Obtido:
 

###  Status do Teste:


---
## 🧪 ID: 002

###  Nome do Teste:
Adicionar agendamento 

###  Descrição:
 Verificar se o sistema permite o usuario fazer agendamentos.

###  Pré-requisitos:
 Usuário deve estar na tela de agendamento
 Banco de dados deve estar acessível

### Procedimentos (Passos para execução do teste):
1.  Acessar a tela agendamento
2.  Preencher os campos obrigatórios com dados válidos
3.  Clicar no botão "Agendar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste  |
|------------------|-----------------|
| Dia             |    31/02         |
| Hora            |    12:00|        |
| Tipo            |    Completa      |

###  Resultado Esperado:
Usuário deve fazer o agendamento e redirecionado para a página inicial com a mensagem "Agendamento realizado com sucess"

###  Resultado Obtido:
 

###  Status do Teste:

---

## 🧪 ID: 003

###  Nome do Teste:
Editar Agendamentos

###  Descrição:
 Verificar se o sistema permite o usuario editar os seus agendamentos.

###  Pré-requisitos:
 Usuário deve estar na tela de meus Agendamentos
 Banco de dados deve estar acessível

### Procedimentos (Passos para execução do teste):
1.  Acessar a tela meus agendamentos
2.  Preencher os campos obrigatórios com dados válidos
3.  Clicar no botão "Agendar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste  |
|------------------|-----------------|
| Dia             |    01/31         |
| Hora            |    21:00|        |
| Tipo            |    expressa      |

###  Resultado Esperado:
Usuário deve editar o agendamento e ser redirecionado para a página inicial com a mensagem "Agendamento editado com sucesso"

###  Resultado Obtido:
 

###  Status do Teste:

---
## 🧪 ID: 004

###  Nome do Teste:
Excluir agendamento 

###  Descrição:
 Verificar se o sistema permite o usuario Excluir os seus agendamentos.

###  Pré-requisitos:
 Usuário deve estar na tela de meus Agendamentos
 Banco de dados deve estar acessível

### Procedimentos (Passos para execução do teste):
1.  Acessar a tela meus agendamento
3.  Clicar no botão "Excluir"

###  Resultado Esperado:
O agendamento não deve mas aparecer em meus Agendamentos

###  Resultado Obtido:
 

###  Status do Teste:

---

## 🧪 ID: 005

###  Nome do Teste:
Intereface do Usuario

###  Descrição:
 Verificar se a interface esta intuitiva e agradável 

###  Pré-requisitos:
 Usuário deve estar na tela de meus Agendamentos
 Banco de dados deve estar acessível

### Procedimentos (Passos para execução do teste):
1.  Acessar as tela  aplicativo

###  Resultado Esperado:
ser intuitivel e agradável

###  Resultado Obtido:
 

###  Status do Teste:

---

## 🧪 ID: 006

###  Nome do Teste:
Adicionar usuario campos  invalidos

###  Descrição:
 Verefica como o sistema responde com um email invalido

###  Pré-requisitos:
 Usuário deve estar na tela de cadastro


### Procedimentos (Passos para execução do teste):
1.  Acessar a tela de cadastro
2.  Preencher os campos obrigatórios com dados inválidos
3.  Clicar no botão "Cadastrar"

###  Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Nome             | 22141443312132         |
| Email            | eueueueututututu       |
| Senha            | ************           |
| Confirmar Senha  | ++++++++               |

###  Resultado Esperado:
deve returnar uma mensagem: "Campos invalidos"

###  Resultado Obtido:
 

###  Status do Teste:

---

## 🧪 ID: 007

###  Nome do Teste:
Adicionar Agendamentos com campos inválidos

###  Descrição:
 Verificar como o sistema responde o usuario quando tenta adicionar um agendamento com campos invalidos.

###  Pré-requisitos:
 Usuário deve estar na tela de Adicionar Agendamentos


### Procedimentos (Passos para execução do teste):
1.  Acessar a tela agendamento
2.  Preencher os campos obrigatórios com dados inválidos
3.  Clicar no botão "Agendar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste  |
|------------------|-----------------|
| Dia             |    66666         |
| Hora            |    27:99        |
| Tipo            |    sua mãe      |

###  Resultado Esperado:

deve returnar uma mensagem: "Campos invalidos"

###  Resultado Obtido:
 

###  Status do Teste:

---

## 🧪 ID: 008

###  Nome do Teste:
Editar Agendamentos com campos invalidos

###  Descrição:
verificar como o sistema responde o usuario quando tenta editar um agendamento com campos invalidos.

###  Pré-requisitos:
 Usuário deve estar na tela de meus Agendamentos


### Procedimentos (Passos para execução do teste):
1.  Acessar a tela meus agendamentos
2.  Preencher os campos obrigatórios com dados inválidos
3.  Clicar no botão "Editar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste  |
|------------------|-----------------|
| Dia             |    977777        |
| Hora            |    99:000        |
| Tipo            |    one punch man      |

###  Resultado Esperado:

deve returnar uma mensagem: "Campos invalidos"

###  Resultado Obtido:
 

###  Status do Teste:

---

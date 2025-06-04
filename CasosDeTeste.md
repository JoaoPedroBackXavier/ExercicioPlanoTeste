## 🧪 ID: 001

### ✅ Cadastro de usuario com dados válidos:

### 🎯 Descrição:
Testar se o programa pode registrar usuarios com dados válidos

### 🧰 Pré-requisitos:
- Usuário deve estar na tela de cadastro
- Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de cadastro
2. Preencher os campos obrigatórios com dados válidos
3. Clicar no botão "Cadastrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Nome             | João da Silva          |
| Email            | joao@email.com         |
| Senha            | Senha123               |
| Confirmar Senha  | Senha123               |

### 💡 Resultado Esperado:
Usuario deve ser redirecionado para a tela inicial e deve ser notificado de que sua conta foi criada com sucesso e as informaçoes devem ser adicionadas ao banco de dados.

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 002

### ✅ Cadastro de usuario com email já registrado:

### 🎯 Descrição:
Testar como o programa responde ao tentar registrar um email ja registrado

### 🧰 Pré-requisitos:
- Usuário deve estar na tela de cadastro
- Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de cadastro
2. Preencher os campos obrigatórios com dados válidos, mas o email dever ser preechido com um email ja existente
3. Clicar no botão "Cadastrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste                         |
|------------------|----------------------------------------|
| Nome             | João da Silva                          |
| Email            | joaopedro.backxavier@gmail.com         |
| Senha            | Senha123                               |
| Confirmar Senha  | Senha123                               |

### 💡 Resultado Esperado:
Usuario deve ser notificado que o email ja existe e todos os campos devem ser apagados e o banco de dados nao deve ser alterado

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado

---
## 🧪 ID: 003

### ✅ Cadastro de usuario com email inesistente:

### 🎯 Descrição:
Testar como o programa reaje ao tentar cadastrar um email que nao existe

### 🧰 Pré-requisitos:
- Usuário deve estar na tela de cadastro
- Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de cadastro
2. Preencher os campos obrigatórios com dados validos, mas o campo de email deve ser preenchido com um email que nao existe
3. Clicar no botão "Cadastrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Nome             | João da Silva          |
| Email            | fantasma@gmail.com     |
| Senha            | Senha123               |
| Confirmar Senha  | Senha123               |

### 💡 Resultado Esperado:
Usuario deve ser rnotificado de que o email nao foi encontrado e todas as lacunas deve ser limpas.

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 004

### ✅ logar com sucesso:

### 🎯 Descrição:
verificar se o sistema permite que o usuário ingresse a sua conta com seu 
 e-mail e senha

### 🧰 Pré-requisitos:
- O usuário deve estar na tela de logar
- O banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de Login
2. Preencher os campos obrigatórios com dados válidos
3. Clicar no botão "Entrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Email            | joao@email.com         |
| Senha            | Senha123               |

### 💡 Resultado Esperado:
O usuário deve ser redirecionado para a tela inicial do aplicativo.

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado


## 🧪 ID: 005

### ✅ Tentativa de logar com senha invalida:

### 🎯 Descrição:
verificar como o sistema responde ao tentar logar com senha invalida com email valido

### 🧰 Pré-requisitos:
- O usuário deve estar na tela de loga
- O banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de Login
2. Preencher os campos obrigatórios com email correto e senha correta
3. Clicar no botão "Entrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Email            | joao@email.com         |
| Senha            | SenhaErrada123         |

### 💡 Resultado Esperado:
O usuário deve ser notificado de que a senha esta errada e apenas o campo de senha deve ser esvaziado.

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 006

### ✅ Logar Com E-mail Invalido:

### 🎯 Descrição:
Verificar Como o sistema responde ás tentativas de login com um email invalido

### 🧰 Pré-requisitos:
-  O usuário deve estar na tela de logar  
-  Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de Login
2. Preencher os campos obrigatórios com email incorreto
3. Clicar no botão "Entrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Email            | fantasma@email.com     |
| Senha            | SenhaErrada123         |

### 💡 Resultado Esperado:
O usuário deve ser notificado de que o email nao foi encontrado e os espaços devem ser apagados.

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 007

### ✅ Cadastrar produto ja existente:

### 🎯 Descrição:
Verificar Como o sistema responde á tentativa de inserir um produto que ja existe com o mesmo nome

### 🧰 Pré-requisitos:
-  O usuário deve estar na tela de cadastrar produtos
-  Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. Acessar a tela de cadastrar produto
2. Preencher o campo de nome com um produto ja cadastrado
3. Clicar no botão "Cadastrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Nome             | repolho                |

### 💡 Resultado Esperado:
O usuário deve ser notificado de que o produto ja existe e o campo de nome deve ser limpo.

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 008

### ✅ Cadastrar produto com sucesso:

### 🎯 Descrição:
Verificar que o sistema permite adicionar um produto em a lista de compras e o produto aparece corretamente na lista após salvar

### 🧰 Pré-requisitos:
-  O usuário deve estar na tela de cadastrar produtos
-  Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. O usuário tem que estar na tela de adicionar produto
2. O usuário tem que adicionar um produto na lista
3. Clicar no botão "Cadastrar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Nome             | banana                 |

### 💡 Resultado Esperado:
tem que estar adicionado na lista e o usuario deve ser notificado de que o produto foi registrado.

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado

---
      
## 🧪 ID: 009

### ✅ Remover produto com sucesso:

### 🎯 Descrição:
Remover um produto usando o seu nome que ja foi registrado

### 🧰 Pré-requisitos:
-  O usuário deve estar na tela de remover produtos
-  Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. O usuário tem que estar na tela de remover produto
2. O usuário tem que tentar remover um produto
3. Clicar no botão "Remover"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Nome             | banana                 |

### 💡 Resultado Esperado:
O produto deve ser removido do banco de dados e o usuario deve ser notificado de que o produto foi removido

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado

---

## 🧪 ID: 010

### ✅ Editar o nome de um produto ja registrado:

### 🎯 Descrição:
Editar o nome de um produto ja registrado

### 🧰 Pré-requisitos:
-  O usuário deve estar na tela de editar produtos
-  Banco de dados deve estar acessível

### 📝 Procedimentos (Passos para execução do teste):
1. O usuário tem que estar na tela de editar produto
2. O usuário tem que tentar editar um produto com nome valido
3. O usuario tem que tentar botar um novo nome valido
4. Clicar no botão "Editar"

### 🧾 Dados de Entrada:
| Campo            | Valor de Teste         |
|------------------|------------------------|
| Nome             | banana                 |
| NovoNome         | maçãn                  |

### 💡 Resultado Esperado:
O produto deve ser editado, o usuario deve ser notificado de que o produto foi editado e o usuario deve ser redicionado para a tela inicial

### 📌 Resultado Obtido:
!

### ✅ Status do Teste:
!
- [ ] Aprovado
- [ ] Reprovado

---
      



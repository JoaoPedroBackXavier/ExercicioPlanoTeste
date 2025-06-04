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

### ✅ Cadastro de usuario com email já existente:

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

### ✅ Cadastro de usuario com email invalido:

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




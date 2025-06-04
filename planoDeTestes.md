# 📋 PLANO DE TESTE - Lista de Compras

---

## 1. 🎯 Objetivo dos Testes

O objetivo deste plano de teste é garantir que o aplicativo Lista de Compras funcione corretamente nas funcionalidades de criar, editar, visualizar e excluir compras.
Os testes visam validar a precisão dessas funcionalidades e a integridade da interação do usuário com o aplicativo.


---

## 2. 📦 Escopo dos Testes

### ✔️ O que será testado


| Funcionalidade           | Descrição                                              |
|--------------------------|--------------------------------------------------------|
|  adicionar um produto    | O usuario deve ser capaz de adicionar compras á lista  |
|  excluir um produto      | O usuario deve ser capaz de remover compras da lista   |
|  editar um produto       | O usuario deve ser capaz de editar um produto da lista |
|  visualizar lista        | O usuario deve ser capaz de ver as compras da lista    |

### ❌ O que **não** será testado


| Funcionalidade fora do escopo  | Justificativa                             |
|--------------------------------|-------------------------------------------|
| Segurança                      | Será avaliada em uma fase futura          |
| Tempo de resposta              | Não será avaliado o tempo de resposta     |

---

## 3. ✅ Critérios de Sucesso

Especifique os critérios para considerar o teste como **bem-sucedido**:

| Funcionalidade           | Critério de sucesso                                 |
|--------------------------|-----------------------------------------------------|
| Adicionar produto        | produto aparece corretamente na lista após salvar   |
| Editar produto           | Alterações refletem imediatamente na lista          |
| Excluir produto          | produto deve ser removido sem erros                 |
| Visualizar lista         | O usuário deve ver uma lista atualizada de compras  |

---

## 4. 🧪 Estratégia de Teste

### Tipos de Testes Utilizados:

- [x] Testes Funcionais
- [ ] Testes de Interface (UI)
- [ ] Testes de Usabilidade

### Método de Execução:

- [x] Manual
- [x] Automatizado
- [ ] Híbrido

---

## 5. 🧰 Recursos Necessários

### Equipamentos:

| Equipamento        | Especificações mínimas                     |
|--------------------|--------------------------------------------|
|  Computador        | Navegador Chrome/Firefox atualizado        |

### Ferramentas:

| Ferramenta             | Finalidade                             |
|------------------------|----------------------------------------|
|        JUnit           | Testes automatizados                   |
|      TestRail          | Planejamento e execução dos testes     |
|   Apache Netbeans      | Testes automatizados                   |

### Equipe Envolvida:

| Função                 | Quantidade | Nome(s) (opcional)       |
|------------------------|------------|--------------------------|
| Testador               |            |                          |
| Desenvolvedor          |            |                          |


---

## 6. 🛠️ Plano de Execução

  1. execução automatizada: Os testes serao programados e rodados automaticamente

### Etapas de Execução:

1. Preparação dos ambientes de teste.
2. Instalação da versão de teste do sistema.
3. Execução dos casos de teste atumatizados.
4. Registro de defeitos encontrados.
5. Análise de resultados.

### Ambiente de Teste:

| Ambiente               | Descrição                                     |
|------------------------|-----------------------------------------------|
| Ex: Desenvolvimento    | Versão com novas funcionalidades              |
| Ex: Homologação        | Ambiente próximo ao ambiente de produção      |

---

## 7. 📆 Cronograma

Organize o tempo das etapas do teste.

| Atividade                  | Data de Início | Data de Término |
|---------------------------|----------------|-----------------|
| Planejamento do Teste     |                |                 |
| Preparação do Ambiente    |                |                 |
| Execução dos Testes       |                |                 |
| Documentação dos Resultados|               |                 |

---

## 8. ⚠️ Riscos e Mitigações

Liste possíveis problemas que podem afetar os testes, com planos de ação.

| Risco Identificado                      | Possível Impacto                   | Estratégia de Mitigação                   |
|----------------------------------------|-----------------------------------|---------------------------------------------|
| Ex: Incompatibilidade com iOS antigo   | Aplicativo não abre em alguns aparelhos | Testar em diferentes versões do iOS   |
| Ex: Falta de dispositivos de teste     | Atraso nos testes manuais         | Uso de emuladores                           |

---

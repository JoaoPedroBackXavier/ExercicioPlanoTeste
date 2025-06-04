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
- [x] Testes de Interface (UI)
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
|  IOS               | Versão 12 ou superior                      |
|  celular android   | Versão 10 ou superior                      |
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
| Testador               |       1    |          Seu zé          |
| Desenvolvedor          |       1    |          fulano          |


---

## 6. 🛠️ Plano de Execução

  1. execução automatizada: Os testes serao programados e rodados automaticamente
  2. Execução Manual: Os testes serão executados manualmente nos dispositivos móveis, verificando a interação do usuário com a interface e o comportamento das funcionalidades.

### Etapas de Execução:

1. Preparação dos ambientes de teste.
2. Instalação da versão de teste do sistema.
3. Execução dos casos de teste atumatizados.
4. Execução dos casos de teste manuais.
5. Registro de defeitos encontrados.
6. Análise de resultados.

### Ambiente de Teste:

| Ambiente               | Descrição                                     |
|------------------------|-----------------------------------------------|
|  Desenvolvimento    | Versão com novas funcionalidades              |

---

## 7. 📆 Cronograma


| Atividade                  | Data de Início | Data de Término |
|----------------------------|----------------|-----------------|
| Planejamento do Teste      |    4/6/2027    |    5/6/2027     |
| Preparação do Ambiente     |    5/6/2027    |    6/6/2027     |
| Execução dos Testes        |    6/6/2027    |    9/6/2027     |
| Documentação dos Resultados|   9/6/2027     |    10/6/2027    |

---

## 8. ⚠️ Riscos e Mitigações


| Risco Identificado                                            | Possível Impacto                        | Estratégia de Mitigação                                                |
|---------------------------------------------------------------|-----------------------------------------|------------------------------------------------------------------------|
| Ex: Incompatibilidade com iOS de versao 12 ou inferior        | Aplicativo não abre em alguns aparelhos | Testar em diferentes versões do iOS                                    |
| Ex: A interface pode não ser responsiva em certos dispositivos| Dificuldade de navegação pela aplicação | Incluir testes em diferentes tipos de dispositivos                     |

---

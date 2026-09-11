# 📝 UC1 — Projeto de Software
## 🚀 Aula 2 — Projeto de Software e Levantamento de Requisitos

### Link da aula: https://canva.link/qgs05wourg6hjzq
### Documento de Requisitos:  https://drive.google.com/file/d/1jTMY3tbU5wedZglhkg943vMD-ZgBLv7B/view?usp=drive_link

Nesta aula, começamos a entender uma etapa fundamental no desenvolvimento de sistemas:

> 💡 **Antes de começar a programar, precisamos entender o problema e planejar a solução.**

Um bom software não começa pelo código. Ele começa pela compreensão das **necessidades do usuário**, pela definição dos **requisitos** e pelo planejamento de como o sistema será construído.

---

# 🧩 1. O que é um Projeto de Software?

O **projeto de software** é o processo de definir como um sistema será estruturado antes e durante seu desenvolvimento.

Ele envolve decisões relacionadas a:

- 🏗️ arquitetura;
- 🧩 componentes;
- 📦 módulos;
- 🔗 interfaces;
- 🛠️ tecnologias;
- 📊 organização do sistema.

Seu objetivo é transformar os requisitos levantados em uma **solução estruturada e organizada**.

Um bom projeto ajuda a garantir **escalabilidade, desempenho e manutenibilidade**.

---

# 🏗️ 2. Design de Alto Nível e Baixo Nível

O design de software ocorre em diferentes níveis de abstração.

## 🏢 Design de Alto Nível — Arquitetura

Define a **estrutura global do sistema**, incluindo:

- padrões arquiteturais;
- camadas;
- tecnologias utilizadas;
- organização geral do software.

### 💡 Exemplo

Em um aplicativo de e-commerce, pode-se definir um **back-end em microserviços** e um **front-end separado**.

---

## 🔍 Design de Baixo Nível — Componentes

Foca nos detalhes da implementação de:

- classes;
- módulos;
- interfaces;
- algoritmos;
- estruturas de dados;
- interações internas.

Ele está mais próximo da codificação, pois define como cada parte do sistema será implementada.

---

# 🔄 3. Etapas de um Projeto de Software

```text
📋 Levantamento de Requisitos
        ↓
📊 Análise e Planejamento
        ↓
🏗️ Design de Alto Nível
        ↓
🧩 Design de Baixo Nível
        ↓
💻 Implementação
        ↓
🧪 Testes
        ↓
🚀 Implantação
        ↓
🔧 Manutenção e Evolução
```

### 📋 Levantamento de Requisitos
Entender as necessidades do usuário e definir as funcionalidades esperadas.

### 📊 Análise e Planejamento
Definir escopo, recursos, cronograma e riscos.

### 🏗️ Design de Alto Nível
Definir a estrutura do software, padrões arquiteturais e tecnologias.

### 🧩 Design de Baixo Nível
Especificar classes, módulos e lógica interna.

### 💻 Implementação
Desenvolver o software conforme os designs definidos.

### 🧪 Testes
Verificar se o software atende aos requisitos e corrigir erros.

### 🚀 Implantação
Disponibilizar o software para os usuários finais.

### 🔧 Manutenção e Evolução
Corrigir bugs, atualizar funcionalidades e otimizar o desempenho.

---

# 🎯 4. Traduzindo Requisitos em Soluções Estruturadas

O sucesso de um software depende da correta interpretação dos requisitos.

Traduzir requisitos significa:

> **Transformar necessidades do usuário em uma estrutura organizada de software.**

Isso envolve:

- modelagem;
- definição da arquitetura;
- escolha das tecnologias apropriadas.

Uma interpretação incorreta pode fazer com que o resultado final seja diferente daquilo que o usuário realmente precisava.

---

# ⚠️ 5. A importância da comunicação

Durante o desenvolvimento, a interpretação da necessidade pode mudar entre cliente, analista, arquiteto, desenvolvedor e equipe de manutenção.

Isso pode provocar:

- ❌ falhas de comunicação;
- ❌ falta de alinhamento;
- ❌ requisitos pouco claros;
- ❌ funcionalidades ausentes;
- ❌ resultado diferente do esperado pelo usuário.

> 💡 **Entender corretamente o problema é tão importante quanto programar a solução.**

---

# 📋 6. O que são Requisitos?

Os requisitos descrevem necessidades, funcionalidades, características e regras que devem orientar o desenvolvimento do sistema.

Nesta aula foram abordados:

### ⚙️ Requisitos Funcionais
Definem **o que o sistema deve fazer**.

### 🛡️ Requisitos Não Funcionais
Definem características de qualidade e **como o sistema deve se comportar**.

### 🏢 Requisitos de Negócio
Representam regras e diretrizes que orientam o desenvolvimento.

### 🔗 Requisitos de Interface
Descrevem como o sistema interage com usuários ou outros sistemas.

---

# ⚙️ 7. Requisitos Funcionais — RF

Os **Requisitos Funcionais** descrevem as funcionalidades que o sistema deve executar.

### Exemplos

```text
RF01 — O sistema deve permitir que o usuário cadastre novos produtos.

RF02 — O sistema deve emitir relatórios financeiros.

RF03 — O sistema deve permitir pesquisar informações.
```

### 🧠 Pergunta-chave

> **O que o sistema deve fazer?**

---

# 🛡️ 8. Requisitos Não Funcionais — RNF

Os **Requisitos Não Funcionais** descrevem características de qualidade do sistema.

Podem envolver:

- ⚡ desempenho;
- 🔐 segurança;
- 👨‍💻 usabilidade;
- 📈 escalabilidade.

### Exemplos

```text
RNF01 — O sistema deve processar 500 transações por segundo.

RNF02 — O sistema deve possuir uma interface intuitiva.
```

### 🧠 Pergunta-chave

> **Como o sistema deve funcionar ou se comportar?**

---

# 🆚 9. RF x RNF

| Tipo | Pergunta | Exemplo |
|---|---|---|
| ⚙️ **RF** | O que o sistema faz? | Cadastrar produto |
| 🛡️ **RNF** | Como o sistema deve funcionar? | Possuir interface intuitiva |

### 🧠 Macete

> **RF = FUNÇÃO**

> **RNF = QUALIDADE / COMPORTAMENTO / RESTRIÇÃO**

---

# 🔗 10. Requisitos de Interface

Descrevem como o sistema interage com outros sistemas ou com seus usuários.

### Exemplo

```text
RI01 — O sistema deve enviar uma notificação por e-mail sempre que um novo usuário se cadastrar.
```

---

# 🔎 11. Processo de Levantamento de Requisitos

O levantamento de requisitos pode ser realizado utilizando diferentes técnicas:

### 🗣️ Entrevistas
Conversas com stakeholders, como clientes, usuários e gerentes.

### 👀 Observação
Observar o processo que o sistema pretende automatizar.

### 📝 Questionários
Utilizar formulários para coletar informações específicas.

### 🧠 Brainstorming
Gerar e discutir ideias iniciais.

---

# 📚 12. Exemplo — Sistema de Gerenciamento de Biblioteca

O sistema deve permitir que estudantes e bibliotecários realizem operações como:

- empréstimo de livros;
- devolução;
- cadastro de livros;
- pesquisa;
- visualização do histórico de empréstimos.

---

# ⚙️ Requisitos Funcionais do Sistema de Biblioteca

```text
RF1 — O sistema deve permitir que o bibliotecário cadastre novos livros.

RF2 — O sistema deve permitir registrar empréstimos de livros.

RF3 — O sistema deve permitir pesquisar livros por título, autor ou categoria.

RF4 — O sistema deve permitir registrar a devolução dos livros.

RF5 — O sistema deve permitir visualizar o histórico de empréstimos.

RF6 — O sistema deve permitir gerar relatórios de livros mais emprestados e livros atrasados.

RF7 — O sistema deve enviar notificações quando o prazo de devolução estiver se aproximando.
```

---

# 🛡️ Requisitos Não Funcionais do Sistema de Biblioteca

```text
RNF1 — O sistema deve processar até 200 requisições simultâneas de empréstimos.

RNF2 — O sistema deve ser acessível via web.

RNF3 — O sistema deve possuir uma interface amigável e intuitiva.

RNF4 — As informações devem ser protegidas contra acessos não autorizados.

RNF5 — O sistema deve responder às ações do usuário em até 2 segundos.

RNF6 — O sistema deve ser escalável.
```

---

# 📜 13. Regras de Negócio — Sistema de Biblioteca

## 👤 Cadastro de Usuários

- Os usuários podem ser alunos, professores ou visitantes.
- Cada usuário deve possuir nome, CPF, endereço, e-mail e telefone.
- O sistema deve verificar se o usuário já está cadastrado antes de permitir um novo cadastro.

## 🔐 Acesso ao Sistema

- Usuários devem acessar utilizando login e senha.
- Bibliotecários possuem permissões administrativas para gerenciar livros e usuários.
- O sistema deve permitir recuperação de senha via e-mail.

## 📖 Empréstimo de Livros

- Cada usuário pode pegar até **3 livros por vez**.
- O prazo para alunos é de **7 dias**.
- O prazo para professores é de **14 dias**.
- Usuários com livros atrasados não podem realizar novos empréstimos até regularizar a situação.

## 🔄 Renovação

- O usuário pode renovar um livro apenas **uma vez**.
- A renovação só é permitida se o livro não estiver reservado por outro usuário.
- Pode ser realizada online ou presencialmente.

## 📥 Devolução

- O sistema deve registrar data e hora da devolução.
- Em caso de atraso, será gerada multa de **R$ 2,00 por dia**.
- A multa poderá ser paga online ou diretamente na biblioteca.

## 📌 Reserva

- Um usuário pode reservar um livro que esteja emprestado.
- Após a devolução, o usuário terá até **24 horas** para retirar o livro.
- Se não retirar dentro do prazo, o livro volta a ficar disponível.

## 🔔 Notificações

- O sistema deve enviar lembretes sobre prazos de devolução.
- Deve informar quando uma reserva estiver disponível.
- Em caso de atraso, o usuário receberá notificações diárias até regularizar a situação.

---

# 🧠 14. Resumindo

```text
NECESSIDADE DO USUÁRIO
        ↓
LEVANTAMENTO DE REQUISITOS
        ↓
┌─────────────────────────────┐
│ ⚙️ Requisitos Funcionais    │
│ 🛡️ Requisitos Não Funcionais│
│ 📜 Regras de Negócio        │
└─────────────────────────────┘
        ↓
🏗️ PROJETO DO SOFTWARE
        ↓
💻 IMPLEMENTAÇÃO
        ↓
🧪 TESTES
        ↓
🚀 SISTEMA
```

---

# 📝 Atividade da Aula

Os grupos deverão realizar a **análise de requisitos de diferentes tipos de sistemas**.

Cada grupo será responsável por um sistema e deverá identificar:

- ⚙️ **Requisitos Funcionais (RF)**
- 🛡️ **Requisitos Não Funcionais (RNF)**
- 📜 **Regras de Negócio**

O objetivo é exercitar a análise das necessidades do sistema antes de iniciar sua implementação.

---

# 🚀 Conclusão

Desenvolver software não significa apenas escrever código.

Antes da implementação, é necessário compreender as necessidades do usuário, definir requisitos, estabelecer regras e planejar a estrutura da solução.

> 💡 **Um bom software começa com um problema bem compreendido e requisitos bem definidos.**

---

## 💻 UC1 — Projeto de Software

**Planejamento • Requisitos • Arquitetura • Desenvolvimento 🚀**

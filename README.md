## 📌 Sobre o Projeto

Este projeto é uma aplicação interativa de gerenciamento de tarefas (**ToDo List**) desenvolvida em **React** com **TypeScript** e estruturada sobre o **Vite**. O objetivo principal é aplicar conceitos sólidos do ecossistema do React, abordando desde a composição de componentes até o tratamento refinado de fluxos assíncronos e comportamento de interface.

A aplicação simula cenários reais do desenvolvimento frontend, resolvendo desafios como:
- **Gerenciamento de Estado Consistente:** Fluxo completo e reativo de criação, conclusão e deleção de tarefas dentro do estado local (`array`).
- **Estados de Transição e Simulação de Latência:** Controle visual e lógico de estados intermediários (como tarefas em modo `creating`), simulando atrasos de rede (*delays*) para validar estados de *loading*.
- **Otimização de Interação (UI/UX):** Implementação de travas físicas e visuais via CSS (`pointer-events-none`) para evitar requisições ou cliques duplicados acidentais, além de estratégias seguras para exclusão de itens.

## 🚀 Funcionalidades

- [x] **Criação Reativa:** Adição de tarefas com validação de campos e controle de estados transicionais.
- [x] **Controle de Status:** Alternância dinâmica entre tarefas pendentes e concluídas.
- [x] **Deleção Inteligente:** Remoção direta e segura de itens do estado local, mesmo se ainda estiverem em processo de criação.
- [x] **Garantia de UX:** Feedback visual instantâneo e bloqueio de ações repetidas em botões durante o processamento.
- [x] **Tipagem Estrita:** Código 100% estruturado em TypeScript, minimizando erros em tempo de execução.

## 🛠️ Tecnologias Utilizadas

- **[React](https://react.dev/)** — Biblioteca base para construção da interface baseada em componentes.
- **[TypeScript](https://www.typescriptlang.org/)** — Superset que adiciona tipagem estática e segurança ao código.
- **[Vite](https://vitejs.dev/)** — Ferramenta de build ultra-rápida para o ambiente de desenvolvimento.
- **ESLint** — Linter configurado com regras estritas para garantir a padronização e qualidade do código.

## 🔧 Como Executar o Projeto

### Pré-requisitos
Antes de começar, certifique-se de ter o **Node.js** instalado em sua máquina.

### Passo a Passo

```bash
# 1. Clone este repositório
git clone [https://github.com/leandromarqueti/seu-repositorio-todo.git](https://github.com/leandromarqueti/seu-repositorio-todo.git)

# 2. Acesse o diretório do projeto
cd seu-repositorio-todo

# 3. Instale as dependências
npm install
# ou se preferir utilizar o yarn: yarn

# 4. Execute o servidor de desenvolvimento local
npm run dev
# ou se preferir utilizar o yarn: yarn dev

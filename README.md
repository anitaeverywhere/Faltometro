# 🎓 Faltômetro

> Um Web App minimalista e intuitivo para estudantes universitários gerenciarem suas presenças e evitarem reprovações por falta. 

![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)

---

## 📖 Sobre o Projeto

O **Faltômetro** nasceu para resolver uma dor comum na vida acadêmica: perder o controle de quantas aulas você já faltou e quão perto está do limite de reprovação (geralmente exigência de 75% de presença). 

Ao invés de planilhas complexas, o sistema oferece um dashboard visual que calcula automaticamente o limite de cada cadeira (com base nos créditos/períodos semanais) e indica, através de cores e barras de progresso, o status atual do aluno. Tudo rodando direto no navegador, sem necessidade de banco de dados externo.

## ✨ Funcionalidades

* **Autenticação Local (`localStorage`):** Sistema de login simples (baseado no nome do usuário) que cria instâncias separadas no navegador. Perfeito para uso pessoal rápido.
* **Cálculo Inteligente:** O app calcula o limite exato de faltas permitidas (25%) com base no número de semanas do semestre e nos períodos semanais de cada disciplina.
* **Dashboard Reativo:** Os cards das disciplinas mudam de cor dinamicamente conforme o consumo das faltas:
  * 🟢 **Verde:** Seguro (0% a 50% das faltas usadas).
  * 🟡 **Amarelo:** Atenção (51% a 80% das faltas usadas).
  * 🔴 **Vermelho:** Crítico (Mais de 80% das faltas usadas).
* **Prevenção de Erros:** Opção fácil e rápida para desfazer a adição de uma falta acidental.

## 🧠 Foco em Interação Humano-Computador (IHC)

Este projeto foi desenvolvido aplicando conceitos sólidos de usabilidade e design centrado no usuário:
* **Visibilidade do Status do Sistema:** Uso não apenas de cores, mas de textos claros (ex: `Faltas: 12/20`) garantindo acessibilidade para daltônicos.
* **Controle e Liberdade do Usuário:** Ações rápidas de "+1 Falta" e reversão imediata de erros.
* **Carga Cognitiva Reduzida:** Interface limpa e direta ao ponto, evitando menus desnecessários.

---

## 🚀 Como Executar o Projeto Localmente

### Pré-requisitos
* [Node.js](https://nodejs.org/) instalado em sua máquina.
* 1. Faça o clone deste repositório:
  ```bash
   git clone [https://github.com/SEU_USUARIO/faltometro.git](https://github.com/SEU_USUARIO/faltometro.git)
   Acesse a pasta do projeto:
* 2. Acesse a pasta do projeto:
  ```bash
  cd faltometro 
* 3. Instale as Dependências:
  ```bash
  npm install
* 4. Inicie o servidor localmente
```bash
 npm run dev

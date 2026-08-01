# 🛡️ NZOChain Security Scan

> Validação instantânea e inteligente de carteiras Web3. Uma ferramenta de alta performance desenvolvida para análise de risco em smart contracts e detecção de atividades maliciosas em múltiplas redes blockchain.

![Status do Projeto](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)
![Deploy](https://img.shields.io/badge/Deploy-Vercel-black?logo=vercel)
![React](https://img.shields.io/badge/Frontend-React%20%2B%20TypeScript-blue?logo=react)

---

## 🚀 Sobre o Projeto

O **NZOChain Security Scan** foi construído para oferecer aos desenvolvedores e entusiastas de Web3 uma verificação de segurança rápida, precisa e com uma interface intuitiva. A plataforma avalia o histórico e a reputação de endereços de carteiras em diferentes redes, sinalizando proativamente riscos críticos ou atestando a confiabilidade das operações.

---

## ✨ Principais Funcionalidades

- **🔍 Validação Multi-Chain:** Suporte para verificação em redes como *Ethereum, Polygon, Arbitrum e Binance Smart Chain*.
- **⚡ Análise Instantânea & Integração Real:** Conexão direta via POST com a API oficial de risk scan da NZOChain usando autenticação por cabeçalho (`X-API-Key`).
- **🚨 Sistema Inteligente de Alertas:**
  - 🟢 **Card Verde:** Carteiras com histórico limpo e operações seguras.
  - 🔴 **Card Vermelho:** Alerta crítico para contratos vulneráveis ou atividades suspeitas.
- **🎨 UI/UX Moderna:** Interface limpa, responsiva e com foco total na experiência do usuário (modo escuro nativo voltado para o ecossistema cripto).

---

## 🧠 Decisões Técnicas e Desafios Enfrentados

Durante o desenvolvimento do **NZOChain Security Scan**, algumas escolhas arquiteturais e desafios importantes foram superados:

1. **Escolha da Stack (React, TypeScript e Vite):** A decisão de utilizar React com TypeScript e Vite garantiu não apenas um build ultrarrápido, mas também uma tipagem estática rigorosa, prevenindo erros em tempo de execução e assegurando a integridade dos dados enviados para a API.
2. **Integração Assíncrona e Segurança:** O principal desafio técnico foi estruturar o fluxo de requisições HTTP seguras passando a chave de API via headers customizados, mantendo o tratamento de erros robusto.
3. **Resiliência e Fallback Inteligente:** Para garantir que a aplicação nunca quebre caso ocorra instabilidade temporária na rede externa ou restrições de CORS durante demonstrações ao vivo, implementei uma camada de fallback inteligente que mantém a fidelidade visual e a validação de risco ativa.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as melhores práticas do ecossistema moderno de desenvolvimento frontend:

- **React 18** + **TypeScript** (Base da aplicação e tipagem estática)
- **Vite** (Build ultrarrápido e otimizado)
- **CSS / Inline Styling Modular** (Design responsivo e isolado)
- **Vercel** (Infraestrutura de deploy e entrega contínua)

---

## 📦 Como Executar o Projeto Localmente

Se você quiser clonar e rodar o projeto na sua máquina:

```bash
# Clone o repositório
git clone [https://github.com/dinizdaniel284/nzochain-test.git](https://github.com/dinizdaniel284/nzochain-test.git)

# Entre na pasta do projeto
cd nzochain-test

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev

🌐 Acesso Online (Deploy)
A aplicação está hospedada e ativa na nuvem da Vercel:

👉 Acesse o NZOChain Security Scan na Vercel

👨‍💻 Desenvolvido por Daniel Diniz
Full-Stack & Web3 Engineer
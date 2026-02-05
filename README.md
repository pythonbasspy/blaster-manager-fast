# 🧨 BlasterManager

> Sistema de gestão operacional e financeira para pirotecnia e eventos (PWA / Single-File Application).

![Status](https://img.shields.io/badge/Status-Concluído-success) ![Plataforma](https://img.shields.io/badge/Plataforma-Web%20%7C%20Mobile-blue)

## 📋 Sobre o Projeto

O **BlasterManager** é uma solução ERP compacta desenvolvida para resolver a complexidade logística e financeira de shows pirotécnicos. 

A aplicação foi projetada para funcionar **offline-first** e sem dependência de servidores complexos (Backendless), permitindo que técnicos em campo (Blasters) criem orçamentos, gerenciem estoque e emitam documentos PDF diretamente de seus dispositivos móveis, mesmo em locais remotos sem internet.

## 🚀 Funcionalidades Principais

* **Gestão de Estoque:** Controle de entrada e saída de materiais com cálculo de custo médio.
* **Orçamentos Inteligentes:** Criação rápida de orçamentos com cálculo automático de margem de lucro (Spread) e custos extras.
* **Gerador de PDF:** Exportação de orçamentos profissionais em PDF com logo da empresa e assinatura, prontos para envio via WhatsApp.
* **Área Operacional:** Checklist interativo para montagem e integração direta com **Google Calendar**.
* **Backup & Restore:** Sistema de persistência de dados via JSON, garantindo segurança das informações sem necessidade de banco de dados na nuvem.
* **Responsividade:** Interface 100% adaptada para uso em smartphones (Mobile First).

## 🛠 Tecnologias Utilizadas

O projeto foi construído utilizando o conceito de **Single File Component** para máxima portabilidade, utilizando as seguintes tecnologias:

* **Vue.js 3 (CDN):** Para reatividade, gerenciamento de estado e lógica da interface.
* **Tailwind CSS:** Para estilização rápida, moderna e responsiva.
* **LocalStorage API:** Para persistência de dados no navegador (NoSQL local).
* **jsPDF & AutoTable:** Bibliotecas para geração dinâmica de documentos PDF no client-side.
* **HTML5 / FontAwesome:** Estrutura semântica e iconografia.

## 📱 Como Utilizar

1.  Acesse o link da aplicação.
2.  **Configuração:** Vá na engrenagem e cadastre os dados da sua empresa (Logo, Nome, Responsável).
3.  **Estoque:** Cadastre seus itens disponíveis na aba "Estoque".
4.  **Novo Show:** Crie um orçamento, adicione itens e custos extras.
5.  **Aprovação:** Ao aprovar a venda, o sistema baixa o estoque automaticamente e libera o Checklist Operacional.

## 📄 Licença

Este projeto foi desenvolvido para fins de portfólio e utilidade pública para atender uma demanda específica da comunidade de eventos, focada em blasters.

---
## **Desenvolvido por **[pythonbasspy]
[https://www.linkedin.com/in/elias-rodrigues-de-oliveira-filho-43503123/]

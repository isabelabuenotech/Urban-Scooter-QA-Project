# 🎓 Projeto Urban Scooter QA: Central de Testes, Validação Web & API

Uma solução completa de **Garantia de Qualidade (QA)** e **Validação de Software** desenvolvida para o aplicativo **Urban Scooter** (plataforma de aluguel de patinetes elétricos). O projeto contempla a modelagem de processos de teste, regras de negócio de pedidos, especificação BDD, testes de limite (BVA), classes de equivalência, execução cross-browser, gestão de defeitos vinculados ao Jira e testes de integração de API no Postman.

---

## 📌 O que é o projeto?

Em aplicações Web e Mobile de mobilidade urbana, a falta de padronização na entrada de dados de formulários gera falhas críticas no processamento de pedidos e corrompimento de bases operacionais.

Este projeto consolida a estratégia de qualidade aplicada à interface e regras de negócio do fluxo **"Fazer Pedido"** do aplicativo **Urban Scooter**, estruturada a partir da análise dos requisitos e mapeamento de cenários. A arquitetura de testes cobre duas camadas estratégicas:

### Validação Web & Interface (Fluxo "Fazer Pedido"):

- Formulário "Para quem é a Scooter": Checagem de obrigatoriedade, tipos de caracteres aceitos e comportamento do foco em campos críticos (Nome, Sobrenome, Endereço, Estação de Metrô, Telefone).

- Particionamento por Classes de Equivalência e Análise de Valor Limite (BVA): Mapeamento de entradas limítrofes (ex: strings de 1, 2, 7, 14, 15 e 16 caracteres no campo "Nome").

- Matriz Cross-Browser: Teste e validação de layout/funcionalidade executados em resoluções 1280x720 no Google Chrome 1280x720 e Opera 1280x720.

### Garantia de Qualidade em API e Regras de Negócio:

- Validação de Payloads e Contratos: Teste de integridade dos dados enviados no fluxo de criação de pedidos via API.

- Tratamento de Exceções & Sanitização: Verificação de rejeição para caracteres especiais, alfabetos não latinos e entradas com múltiplos espaços.

---
## 🚀 Diferenciais: Funcionalidades e Impacto de Negócio

- Matriz de Cobertura de Limites (BVA): Automação que testa dinamicamente os valores de borda dos campos do formulário para evitar falhas de validação no frontend e estouro de banco de dados no backend.

- Cenários BDD em Gherkin: Tradução dos casos de teste manuais para linguagem natural focada em comportamento de negócio, facilitando a comunicação entre QA, produto e desenvolvimento.

- Rastreabilidade Integrada com Jira: Mapeamento completo entre casos de teste, evidencias aprovadas/reprovadas e reportes de inconsistências apontando para o Jira.

---

## 🛠️ Arquitetura e Tecnologias utilizadas

- **Linguagem de Especificação BDD**: Gherkin (100% da documentação de cenários).
- **Gestão de Defeitos e Suporte**: Jira e Postman.
- **Navegadores & Ambientes de Teste**: Google Chrome e Opera (Resolução base: 1280x720).

---

## 👩‍💻 Autora e Contato

**Isabela Bueno** — Psicóloga Escolar | Analista Educacional Sênior | Data & Tech Enabler (QA & Python)

📧 **E-mail**: [isabelabueno.tech@gmail.com](mailto:isabelabueno.tech@gmail.com)  
💼 **LinkedIn**: [isabela-bueno-silva](https://www.linkedin.com/in/isabela-bueno-silva)  
🐱 **GitHub**: [@isabelabuenotech](https://github.com/isabelabuenotech)

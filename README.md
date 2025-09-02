# 🧪 Guia Profissional de Testes — QA Engineer (Selenium)  

---

## 🎯 Visão Geral  

Sou **Artur Felipe Albuquerque Portela**, candidato à vaga de **QA Engineer (Selenium)** pela Match Profiler.  
Este guia resume como aplico meu processo de QA ao setor **Bancário e Trade Finance**, combinando **método, automação, uso de IA e validação de contratos de API** para garantir qualidade e previsibilidade em cada entrega.  

---

## 🎯 Objetivo  

Assegurar que fluxos críticos como **login e autenticação**, **pagamentos e transferências**, **verificação de identidade/documentos** e **operações de comércio internacional (cartas de crédito, garantias)** sejam validados ponta a ponta, com foco em:  

- ✅ **Segurança e conformidade** (evitar falhas financeiras ou regulatórias).  
- ✅ **Previsibilidade nas entregas** (cada release com confiança).  
- ✅ **Produtividade** (automatização e uso de IA para reduzir tempo em tarefas repetitivas).  
- ✅ **Estabilidade de integrações externas** (uso do Contract Analyzer para prevenir falhas em APIs).  

---

## 🔑 Estrutura de Trabalho  

### 1. Planejamento  
- Levantamento de requisitos com base no **SDLC (Software Development Life Cycle)**.  
- Identificação dos **fluxos mais críticos** (login, pagamentos, verificação de documentos, Trade Finance).  
- Escrita de cenários em **BDD/Gherkin** (fácil adaptação a Cucumber).  
- Priorização por **risco e impacto financeiro**.  

📊 **Tempo médio desta etapa:** 3–5 dias úteis.  

---

### 2. Automação  
- Desenvolvimento de testes de fluxos ponta a ponta em **Selenium (Java)**.  
- Validação de consistência de dados com **SQL**.  
- Execução de **ações em massa** quando necessário (ex.: múltiplas autorizações ou transferências), aplicando o conceito de **RPA (UiPath) para reduzir esforço humano e garantir consistência**.  
- Criação de **scripts simples (PowerShell)** para acelerar execuções e ligar ao pipeline.  

📊 **Resultados esperados:**  
- Redução de até **40% no tempo gasto em testes regressivos**.  
- Eliminação de **falhas repetidas** nos fluxos já cobertos.  

---

### 3. Execução  
- Testes locais e em **pipelines CI/CD** (Jenkins, GitHub Actions).  
- **Smoke tests pós-deploy** para validar login e pagamentos imediatamente.  
- **Contract Analyzer** integrado ao pipeline para APIs críticas:  
  - Compara versões de especificação de APIs (ex.: pagamentos, histórico de transações).  
  - Gera relatórios automáticos de risco.  
  - **Falha o pipeline** se houver mudança de alto impacto sem mitigação.  
- Integração de **agentes de IA** para:  
  - gerar casos de teste repetitivos,  
  - revisar relatórios,  
  - manter documentação padronizada.  

📊 **Impacto comprovado:**  
- IA reduziu em **30–40% o tempo de escrita de documentação**.  
- Contract Analyzer eliminou **riscos de quebras silenciosas em APIs**.  
- Permitiu **entregar mais projetos freelance em paralelo**, mantendo qualidade.  

---

### 4. Evidências e Relatórios  
- **Screenshots e logs automáticos**.  
- **Relatórios visuais** em Allure/ExtentReports.  
- Documentação organizada em **Confluence**, acessível a toda a equipa.  
- Feedback claro e rastreável, com indicadores de produtividade.  
- **Classificação e priorização de bugs**: avalio impacto e urgência de acordo com o contexto, priorizando sempre falhas em **fluxos críticos (ex.: pagamentos, autenticação)** ou em **edge cases** que possam comprometer a confiabilidade do sistema.  

📊 **Indicadores de qualidade:**  
- **Cobertura mínima de 80%** nos fluxos críticos.  
- **MTTD (Mean Time to Detect):** falhas críticas são detetadas em minutos após execução.  
- **MTTR (Mean Time to Repair):** correção média em até 1 dia para defeitos críticos.  

---

## 📊 Pirâmide de Testes  

- **Base** → verificações rápidas de regras e dados essenciais.  
- **Integração** → APIs e base de dados em conjunto.  
- **Contratos** → uso do **Contract Analyzer** para garantir que alterações em APIs não quebram sistemas externos.  
- **Fluxos completos (End-to-End)** → Selenium cobre login, pagamentos, KYC e operações financeiras.  
- **Robustez** → amostras de desempenho (tempo de resposta) e segurança (falhas comuns).  
- **Monitorização** → healthchecks e alertas automáticos após cada deploy.  

👉 Esta ordem segue as **melhores práticas**: evita desperdício, reduz retrabalho e mantém foco no que gera valor.  

---

## 🧰 Ferramentas  

| Categoria             | Ferramentas principais                  |
|-----------------------|-----------------------------------------|
| Automação UI          | **Selenium WebDriver (Java)**           |
| Validação de dados    | **SQL**                                |
| Integração contínua   | Jenkins, GitHub Actions                 |
| Relatórios            | Allure, ExtentReports, Confluence       |
| Gestão                | Git, GitHub, Jira, Trello               |
| Validação de APIs     | **Contract Analyzer (.NET)**            |

---

## 🔚 Encerramento  

A minha abordagem funciona como um **esqueleto flexível**: pode ser aplicada **desde o início de um projeto** ou adaptada em produtos já em andamento.  
É **reciclável e ajustável** às necessidades de cada equipa de desenvolvimento e às prioridades de cada produto.  
Assim, consigo entregar valor rápido no arranque e, ao mesmo tempo, evoluir a estratégia de testes conforme as demandas do cliente e do setor bancário.  

---

📌 **Artur Felipe Albuquerque Portela**  
📍 Póvoa de Lanhoso, Braga – Portugal  
📧 arturengqa@gmail.com | 📱 +351 932 508 100  
🔗 GitHub: [github.com/ArturMoco](https://github.com/ArturMoco)  

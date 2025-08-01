# 3. Stack Tecnológica e Arquitetura

> Descreva as decisões técnicas, padrões e ferramentas que serão utilizados.

### 3.1. Diagrama e Justificativa da Arquitetura
* **Arquitetura Escolhida:** (Ex: Microsserviços com comunicação via API Gateway)
* **Justificativa:** *(Ex: Escolhemos Microsserviços para permitir escalabilidade independente dos módulos e facilitar o trabalho de equipes paralelas.)*
* **Link para Diagrama (se houver):** ### 3.2. Stack Tecnológica Detalhada
| Camada      | Tecnologia          | Versão | Justificativa Breve                       |
| :---------- | :------------------ | :----- | :---------------------------------------- |
| Frontend    | React               | 18+    | Ecossistema robusto e familiaridade da equipe. |
| Backend     | Node.js (Express)   | 20+    | Alto desempenho para I/O e unificação de linguagem (JS). |
| Banco de Dados| PostgreSQL          | 15+    | Confiabilidade, suporte a JSON e funcionalidades relacionais. |
| Cache       | Redis               | 7+     | Cache de sessão e dados frequentemente acessados. |
| Infra/Cloud | AWS (ECS, RDS, S3)  | N/A    | Escalabilidade e serviços gerenciados.    |
| CI/CD       | GitHub Actions      | N/A    | Integração nativa com o repositório.      |

### 3.3. Padrões de Código e Qualidade
* **Linter / Formatter:** ESLint, Prettier
* **Estratégia de Branching:** GitFlow (main, develop, feature/x, bugfix/x, hotfix/x)
* **Estratégia de Testes:**
    * **Unitários:** Jest, Vitest (>80% de cobertura)
    * **Integração:** Supertest
    * **End-to-End (E2E):** Cypress, Playwright

### 3.4. APIs e Integrações de Terceiros
* **Pagamentos:** Stripe
* **Envio de E-mails:** AWS SES, SendGrid
* **Autenticação Social:** Google OAuth2
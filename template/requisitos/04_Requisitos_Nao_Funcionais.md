# 4. Requisitos Não-Funcionais (RFNs)

> Defina os critérios de qualidade do sistema. Eles são tão importantes quanto as funcionalidades.

| Categoria       | Requisito                                                              | Métrica / Critério de Aceite                                      | Prioridade |
| :-------------- | :--------------------------------------------------------------------- | :---------------------------------------------------------------- | :--------- |
| **Desempenho** | Tempo de carregamento da página principal (LCP)                        | < 2.5 segundos                                                    | Alta       |
| **Desempenho** | Tempo de resposta da API (p95)                                         | < 300ms para 95% das requisições                                  | Alta       |
| **Escalabilidade**| Suporte a usuários simultâneos                                         | Suportar 1.000 usuários simultâneos com tempo de resposta estável | Média      |
| **Disponibilidade**| Uptime do serviço                                                      | 99.9% (máx. 43 min de downtime/mês)                               | Alta       |
| **Segurança** | Proteção de dados do usuário                                           | Criptografia de senhas (bcrypt) e conformidade com a LGPD          | Crítica    |
| **Usabilidade** | Acessibilidade                                                         | Conformidade com o padrão WCAG 2.1 Nível AA                       | Média      |
| **Manutenibilidade**| Complexidade Ciclomática                                               | Média dos métodos/funções deve ser < 10                           | Baixa      |
| **Localização (i18n)** | Suporte a múltiplos idiomas                                          | O sistema deve ser projetado para suportar Inglês e Português-BR. | Média      |
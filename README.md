<div align="center">
  <h1>🤖 Gerador de PRD com IA Agêntica</h1>
  
  [![GitHub license](https://img.shields.io/github/license/alexandre-henrique-rp/Gerador-de-PRP?style=for-the-badge)](https://github.com/alexandre-henrique-rp/Gerador-de-PRP/blob/main/LICENSE)
  [![GitHub stars](https://img.shields.io/github/stars/alexandre-henrique-rp/Gerador-de-PRP?style=for-the-badge)](https://github.com/alexandre-henrique-rp/Gerador-de-PRP/stargazers)
  [![GitHub forks](https://img.shields.io/github/forks/alexandre-henrique-rp/Gerador-de-PRP?style=for-the-badge)](https://github.com/alexandre-henrique-rp/Gerador-de-PRP/network/members)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)
  
  <p><strong>Sistema de prompts sequenciais para gerar Documentos de Requisitos de Produto (PRD) completos e detalhados usando IA</strong></p>
  
  <p>
    <a href="#-por-que-usar">Por que usar?</a> •
    <a href="#-como-usar">Como usar</a> •
    <a href="#-exemplos">Exemplos</a> •
    <a href="#-estrutura">Estrutura</a> •
    <a href="#-contribuição">Contribuição</a>
  </p>
</div>

## ✨ Recursos

- **🧠 Simulação de Equipe Especializada**: Trabalhe com três especialistas virtuais:
  - Analista de Mercado
  - Gerente de Produto (PM)
  - Líder Técnico (Tech Lead)
- **🚀 Fluxo Guiado**: Atue como Diretor do Projeto e guie a IA através de etapas estruturadas
- **📄 Saída Formatada**: Gere documentos PRD bem estruturados em Markdown
- **🔄 Processo Iterativo**: Desenvolva requisitos de forma incremental e controlada

## 🤔 Por Que Usar Este Método? {#-por-que-usar}

Em vez de usar um único prompt gigante, este método **"agêntico"** divide o problema em partes menores e especializadas:

### ✅ Vantagens

| Benefício | Descrição |
|-----------|-----------|
| **🎯 Maior Qualidade** | A IA foca em uma área de cada vez, gerando conteúdo mais rico e detalhado |
| **🎮 Melhor Controle** | Você revisa e aprova cada seção antes de prosseguir |
| **👥 Simulação Realista** | Imita como uma equipe de produto real colabora |
| **🔄 Processo Iterativo** | Permite ajustes e melhorias em cada etapa |

### 🆚 Comparação

| Método Tradicional | Método Agêntico |
|-------------------|-----------------|
| 1 prompt gigante | 4 prompts especializados |
| Resultado genérico | Resultado detalhado |
| Sem controle | Controle total do processo |
| Saída única | Revisão em cada etapa |

## 🚀 Como Usar {#-como-usar}

### 📋 Pré-requisitos

- ✅ Acesso a uma ferramenta de IA (ChatGPT, Gemini, Claude, etc.)
- ✅ Sua ideia de produto bem definida
- ✅ Tempo para revisar cada etapa (~30-60 min total)

### 🎯 Passo a Passo

> **⚠️ Importante:** Mantenha toda a interação na **mesma conversa/chat** para preservar o contexto.

| Etapa | Ação | Tempo Estimado |
|-------|------|----------------|
| **1️⃣** | Cole o [Prompt 1](#-prompt-1-analista-de-mercado) + sua ideia | 5 min |
| **2️⃣** | Revise a análise e cole o [Prompt 2](#-prompt-2-gerente-de-produto) | 10 min |
| **3️⃣** | Revise os requisitos e cole o [Prompt 3](#-prompt-3-líder-técnico) | 10 min |
| **4️⃣** | Cole o [Prompt 4](#-prompt-4-compilação-final) para o PRD final | 5 min |

### 💡 Dicas de Uso

```markdown
💡 **Para melhores resultados:**
• Seja específico ao descrever sua ideia
• Revise cada seção antes de continuar
• Peça ajustes quando necessário
• Mantenha o contexto na mesma conversa
```

## 🎬 Exemplo Prático {#-exemplos}

### 📱 Caso: App "PetRide" - Uber para Pets

**Ideia inicial:**
> "Aplicativo de transporte para pets. Donos sem carro podem solicitar motoristas verificados com veículos adaptados para levar seus animais ao veterinário, pet shop ou creche."

**Resultado após os 4 prompts:**
- ✅ Análise de mercado detalhada
- ✅ 2 personas bem definidas (Dona Maria, João)  
- ✅ 15+ user stories organizadas
- ✅ Stack tecnológica sugerida
- ✅ PRD completo de 10 páginas

<details>
<summary><strong>📄 Ver exemplo de saída</strong></summary>

```markdown
# PRD: PetRide - Transporte Seguro para Pets

## 1. Resumo do Problema
Pet owners sem veículo próprio enfrentam dificuldades para transportar 
seus animais com segurança...

## 2. Análise de Mercado  
- TAM: R$ 2,3 bilhões (mercado pet brasileiro)
- Principais concorrentes: Uber Pet (limitado), 99Pets...

## 3. User Personas
**Persona 1: Maria Silva (45 anos)**
- Profissão: Professora
- Pet: Gato persa idoso
- Frustração: Transporte público não aceita pets...
```
</details>

---

## 📋 Os Prompts

Aqui estão os 4 prompts que formam o núcleo deste sistema.

### 🚀 Prompt 1: Analista de Mercado {#-prompt-1-analista-de-mercado}

**🎯 Objetivo:** Inicializar o processo e criar a base estratégica do produto  
**👤 Persona IA:** Analista de Mercado e Negócios  
**📊 Saída:** Análise de mercado, concorrentes e personas

<details>
<summary><strong>Clique para ver o Prompt 1</strong></summary>

```markdown
# PERSONA
Você é um Coordenador de Projetos de Software especialista e atuará como meu assistente para criar um Documento de Requisitos de Produto (PRD) completo.

# PROCESSO
Nosso trabalho será dividido em 4 etapas, simulando uma equipe de especialistas. A cada etapa, você assumirá uma nova persona e usará as informações geradas anteriormente para construir a próxima seção do documento. As personas são:
1.  **Analista de Mercado e Negócios:** Foco em mercado, público-alvo e concorrentes.
2.  **Gerente de Produto (Product Manager):** Foco na visão, estratégia e funcionalidades do produto.
3.  **Líder Técnico (Tech Lead):** Foco nos requisitos técnicos e arquitetura.
4.  **Compilador Final:** Organização de todo o conteúdo em um único documento coeso.

Não avance para a próxima etapa sem minha confirmação explícita.

# ETAPA 1: ANALISTA DE MERCADO E NEGÓCIOS

**PERSONA ATUAL:** Assuma a persona de um **Analista de Mercado e Negócios**.

**TAREFA:** Com base na minha ideia de produto abaixo, gere a primeira seção do nosso PRD.

**INPUT (MINHA IDEIA DE PRODUTO):**
[ !!! AQUI VOCÊ DEVE INSERIR SUA IDEIA DE PRODUTO. SEJA O MAIS DETALHADO POSSÍVEL !!! ]

**OUTPUT ESPERADO (Seção 1):**
Crie um documento em Markdown contendo:

1.  **Resumo do Problema:**
    * Qual problema principal estamos resolvendo?
    * Quem enfrenta esse problema?
    * Por que é importante resolvê-lo agora?

2.  **Análise de Mercado:**
    * Qual o tamanho estimado do mercado (TAM, SAM, SOM)?
    * Quais são as principais tendências e oportunidades neste setor?

3.  **Análise de Concorrentes:**
    * Liste 2-3 concorrentes diretos ou indiretos.
    * Para cada um, descreva seus pontos fortes e fracos.
    * Identifique uma brecha ou diferencial que nosso produto pode explorar.

4.  **Definição de User Personas:**
    * Crie 2 personas detalhadas que representam nosso público-alvo principal.
    * Inclua: Nome, Idade, Profissão, Objetivos, Frustrações (relacionadas ao problema) e Comportamentos.

Ao final, escreva: "**Análise de Mercado e Personas concluída. Aguardando sua revisão e confirmação para prosseguir para a Etapa 2 (Gerente de Produto).**"
```

</details>

### 🎯 Prompt 2: Gerente de Produto {#-prompt-2-gerente-de-produto}

**🎯 Objetivo:** Definir visão, estratégia e funcionalidades do produto  
**👤 Persona IA:** Product Manager experiente  
**📋 Saída:** Visão, requisitos funcionais e métricas de sucesso

<details>
<summary><strong>📋 Ver Prompt 2 completo</strong></summary>

```markdown
# ETAPA 2: GERENTE DE PRODUTO (PRODUCT MANAGER)

**CONTEXTO:** Excelente trabalho na análise anterior. Aprovado. 

**PERSONA ATUAL:** Gerente de Produto (Product Manager) experiente.

**TAREFA:** Utilize as informações da "Análise de Mercado e Personas" para definir visão, estratégia e requisitos funcionais.

**OUTPUT ESPERADO:**
5. **Visão e Estratégia do Produto**
6. **Requisitos Funcionais (User Stories)**  
7. **Métricas de Sucesso (KPIs)**
```
</details>

### 🛠️ Prompt 3: Líder Técnico {#-prompt-3-líder-técnico}

**🎯 Objetivo:** Definir aspectos técnicos e arquitetura do sistema  
**👤 Persona IA:** Tech Lead pragmático e experiente  
**🔧 Saída:** Requisitos não-funcionais, stack e considerações técnicas

<details>
<summary><strong>🔧 Ver Prompt 3 completo</strong></summary>

```markdown
# ETAPA 3: LÍDER TÉCNICO (TECH LEAD)

**CONTEXTO:** Visão e funcionalidades aprovadas.

**PERSONA ATUAL:** Líder Técnico (Tech Lead) pragmático.

**TAREFA:** Detalhar requisitos técnicos e arquitetura.

**OUTPUT ESPERADO:**
8. **Requisitos Não-Funcionais**
9. **Arquitetura e Stack Tecnológica**
10. **Considerações de Implementação**
```
</details>

### 📄 Prompt 4: Compilação Final {#-prompt-4-compilação-final}

**🎯 Objetivo:** Consolidar todas as seções em um PRD unificado  
**👤 Persona IA:** Coordenador de Projetos  
**📋 Saída:** Documento PRD completo e formatado

<details>
<summary><strong>📄 Ver Prompt 4 completo</strong></summary>

```markdown
# ETAPA 4: COMPILAÇÃO FINAL

**PERSONA ATUAL:** Coordenador de Projetos de Software

**TAREFA:** Reunir TODAS as seções em um único PRD

**ESTRUTURA FINAL:**
1. Resumo do Problema
2. Análise de Mercado  
3. Análise de Concorrentes
4. User Personas
5. Visão e Estratégia
6. Requisitos Funcionais
7. Métricas de Sucesso
8. Requisitos Não-Funcionais
9. Arquitetura e Stack
10. Considerações de Implementação
```
</details>

---

## 🏗️ Estrutura do Projeto {#-estrutura}

```
Gerador-de-PRP/
├── 01-orquestrador/           # 🔍 Análise de mercado inicial
│   └── O_Mestre_Orquestrador_e_o_Analista_de_Mercado.md
├── 02-produto/               # 🎯 Definição do produto  
│   └── O_Gerente_de_Produto.md
├── 04-tec/                   # 🔧 Especificações técnicas
│   └── O_Líder_Técnico.md
├── 04-final/                 # 📋 Documento final consolidado
│   └── A_Compilação_Final.md
└── README.md                 # 📖 Este arquivo
```

## 🤝 Contribuição {#-contribuição}

Contribuições são bem-vindas! Para contribuir:

1. **Fork** o projeto
2. **Crie** uma branch (`git checkout -b feature/NovaFuncionalidade`)
3. **Commit** suas mudanças (`git commit -m 'Add: Nova funcionalidade'`)
4. **Push** para a branch (`git push origin feature/NovaFuncionalidade`) 
5. **Abra** um Pull Request

### 💡 Como Ajudar

- 🐛 Reportar bugs ou problemas
- 💡 Sugerir melhorias nos prompts
- 📝 Melhorar a documentação
- ⭐ Dar uma estrela no projeto

## 📄 Licença

Distribuído sob a licença MIT. Veja [`LICENSE`](LICENSE) para mais informações.

---

<div align="center">
  <p><strong>📧 Contato</strong></p>
  
  Feito com ❤️ por <a href="https://github.com/alexandre-henrique-rp">Alexandre Henrique</a>
  
  <p>
    <a href="https://github.com/alexandre-henrique-rp/Gerador-de-PRP">🔗 Repositório</a> •
    <a href="https://github.com/alexandre-henrique-rp/Gerador-de-PRP/issues">🐛 Issues</a> •
    <a href="https://github.com/alexandre-henrique-rp/Gerador-de-PRP/discussions">💬 Discussões</a>
  </p>
  
  <p><em>Se este projeto te ajudou, considere dar uma ⭐️!</em></p>
</div>


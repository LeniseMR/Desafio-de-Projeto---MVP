# Desafio-de-Projeto---MVP
Desafio de Projeto - Construindo seu Primeiro APP
# Passo 1 - Escolha a Dor

1. **EAD WarGame Studio**

Foco:Formação Militar Superior / Gestão do C-Sup

Unifica a criação, distribuição e acompanhamento de jogos de crise e simulações de tomada de decisão jurídica/estratégica para alunos Oficiais Superiores.

- **O problema que resolve:** Simulações e jogos de crise em EAD costumam ser pulverizados em PDFs e fóruns, dificultando a mediação e a avaliação em tempo real.
- **Telas / Fluxos principais do MVP:**
    1. **Dashboard do Instrutor:** Visão geral da turma, inclusão de "Injetes" (eventos/notícias inesperadas no cenário) e envio de dilemas éticos/estratégicos.
    2. **Central da Operação (Visão do Aluno):** Linha do tempo da crise, mapa de cenários, área para upload de pareceres e decisões sob pressão de tempo.
    3. **Matriz de Avaliação:** Rubrica interativa de desempenho por competências estratégicas.
- **Por que no Lovable:** Permite criar layouts complexos em estilo "Center of Operations" ou *Command Center* com cartões, painéis com estado de crise (alerta amarelo/vermelho) e cronômetros dinâmicos.

# Passo 2 - Valide com IA

Abaixo está o dimensionamento de mercado, o Business Model Canvas completo e a matriz de validação das hipóteses para o **EAD WarGame Studio**.

## 1. Estimativa de Mercado (TAM, SAM e SOM)

Para estimar o mercado de uma plataforma SaaS B2B/B2G voltada para **Simulações, Wargaming e Jogos de Crise no Ensino Superior e Corporativo**, utilizou-se a abordagem *Top-Down* combinada com dados de mercado para Tecnologia Educacional (EdTech) e Simulação em Defesa/Corporativa no Brasil e na América Latina.

### **TAM (Total Addressable Market) — Mercado Total Endereçável**

- **Conceito:** Mercado global de softwares de simulação corporativa, jogos de guerra (*wargaming*) e plataformas de aprendizagem baseada em cenários (*scenario-based learning*) para Defesa, Governo e Corporações.
- **Tamanho Estimado:** **~US$ 3,8 bilhões/ano** (baseado no mercado global de *Corporate Simulation & Defense Training Software*).

### **SAM (Serviceable Addressable Market) — Mercado Endereçável Atendível**

- **Conceito:** Instituições de Ensino Militar, Academias de Segurança Pública, Escolas de Governo e Instituições de Ensino Superior (pós-graduação/MBA) no Brasil e na América Latina que utilizam metodologias ativas e estudos de caso complexos.
    - ~30 Academias / Escolas de Guerra e Defesa na América Latina.
    - ~200 Escolas de Governo, Academias de Polícia e Defesa Civil na região.
    - ~1.200 Programas de Pós-Graduação e MBAs em Estratégia, Relações Internacionais, Gestão de Crises e Direito no Brasil/América Latina.
- **Tamanho Estimado:** **~R$ 180 milhões/ano** (considerando um ticket médio anual de R$ 50 mil a R$ 150 mil por instituição).

### **SOM (Serviceable Obtainable Market) — Mercado Inicial Objetivável (Foco do MVP)**

- **Conceito:** As primeiras instituições atendíveis no Brasil nos primeiros 18 a 24 meses (Escolas de Pós-Graduação Militar, Cursos de Gestão de Crise em Escolas de Governo e MBAs de Nicho em Estratégia/Defesa).
    - Metas iniciais: **10 a 15 instituições/programas educacionais**.
    - Ticket Médio Anual (SaaS): **R$ 36.000 a R$ 60.000/ano** por licença institucional/curso.
- **Tamanho Estimado:** **~R$ 600 mil a R$ 900 mil/ano** no ciclo inicial de validação.

## 2. Business Model Canvas (BMC)

| **Bloco do Canvas** | **Descrição Estratégica** |
| --- | --- |
| **Parcerias-Chave** | • Centros de Estudos Estratégicos e Institutos de Pesquisa em Defesa/Direito.

• Especialistas em Wargaming e game designers de cenários de crise.

• Provedores de infraestrutura cloud e IA (OpenAI, Google Cloud, AWS).

• Comunidades de Design Instrucional e EAD. |
| **Atividades-Chave** | • Desenvolvimento e manutenção da plataforma SaaS (React/Tailwind no Lovable).

• Curadoria e criação de templates de cenários/jogos de crise (Jurídico, Marítimo, Cibernético).

• Suporte técnico e capacitação pedagógica dos mediadores/instrutores. |
| **Recursos-Chave** | • Motor de simulação e controle de "Injetes" (eventos assíncronos e síncronos).

• Biblioteca de rubricas de avaliação e matrizes de competência.

• Algoritmos/Modelos de IA para geração rápida de cenários fictícios e *briefings*. |
| **Proposta de Valor** | • **Para Coordenadores:** Centralização e controle completo de jogos de crise em ambiente EAD sem necessidade de múltiplas ferramentas soltas.

• **Para Instrutores/Mediadores:** Facilidade para lançar desdobramentos ("injetes") em tempo real e avaliar tomadas de decisão sob pressão.

• **Para Alunos (Oficiais/Executivos):** Experiência imersiva e visual de tomada de decisão com feedback estruturado por competências. |
| **Relacionamento com Clientes** | • Atendimento consultivo (*High-Touch*) na fase de implantação/onboarding de cursos.

• Suporte técnico especializado durante as rodadas ativas do jogo.

• Comunidade de prática entre mediadores de jogos de simulação. |
| **Canais** | • Venda direta (B2B/B2G) para coordenações pedagógicas e direções de ensino.

• Apresentação em congressos de Educação Militar, Simulação e Metodologias Ativas.

• Demonstrações práticas do MVP (degustação em workshops/webinares). |
| **Segmentos de Clientes** | • **Principal (B2G/B2B):** Coordenações de Cursos Superiores de Guerra, Defesa, Segurança Pública e Escolas de Governo.

• **Secundário (B2B):** MBAs de Gestão Estratégica, Gestão de Crises, Direito Marítimo/Internacional e Governança Corporativa. |
| **Estrutura de Custos** | • Custos de infraestrutura em nuvem e APIs de IA.

• Desenvolvimento de software e UX/UI Design.

• Produção de conteúdo e validação de cenários por especialistas.

• Esforço comercial e jurídico (licitações/contratos corporativos). |
| **Fontes de Receita** | • **Assinatura SaaS Institucional:** Licença anual por curso/departamento.

• **Licenciamento por Aluno Ativo (Per-Seat):** Para turmas sazonais.

• **Serviços Adicionais:** Customização de cenários exclusivos e workshops de capacitação de instrutores. |

## 3. Hipóteses Fiscais e Críticas a Testar com o MVP

Para garantir que o MVP no Lovable cumpra seu papel de validação sem desperdício de recursos, é necessário testar quatro categorias de hipóteses:

### 1. Hipóteses de Problema (Os clientes sentem essa dor?)

- **H1.1:** Coordenadores e instrutores consideram trabalhoso e fragmentado gerir simulações e jogos de crise usando apenas AVA tradicional (Moodle/Canvas), fóruns e PDFs.
- **H1.2:** Alunos adultos/seniores sentem falta de uma interface engajadora e imersiva para visualizar o desdobramento das crises e o impacto de suas decisões em tempo real.

### 2. Hipóteses de Solução (O MVP resolve o problema?)

- **H2.1:** Um painel estilo *Command Center* com controle de "Injetes" aumenta o engajamento dos alunos e reduz o tempo de resposta em exercícios assíncronos/síncronos.
- **H2.2:** A inclusão de uma matriz de avaliação por rubricas integrada ao fluxo do jogo facilita o trabalho de mediação do professor e entrega feedbacks mais consistentes.

### 3. Hipóteses de Usabilidade (O software construído no Lovable é funcional?)

- **H3.1:** Professores conseguem criar e disparar um "Injete" de crise em menos de 2 minutos durante o jogo sem necessidade de suporte técnico.
- **H3.2:** Alunos conseguem submeter pareceres e visualizar a linha do tempo da crise de forma clara em dispositivos móveis e desktop.

### 4. Hipóteses de Negócio e Disposição a Pagar (O mercado paga por isso?)

- **H4.1:** Instituições de ensino superior/militar possuem orçamento e viabilidade regulatória para contratar licenças SaaS de softwares de simulação complementar.
- **H4.2:** O valor percebido na centralização do processo justifica um investimento anual recorrente por turma/curso.

  # **Passo 3 - Escreva o mega prompt.**

Peça ao ChatGPT um prompt em Markdown com o fluxo do cliente, o painel de administração e as cores. No Lovable, use o back-end do **Lovable Cloud**, sem banco de dados seu;

Este prompt está pronto para ser copiado e colado diretamente no **Lovable**.

Ele foi estruturado com todos os componentes visuais, o fluxo da **Central da Operação (Aluno)**, o **Dashboard do Instrutor (Admin)**, o esquema de cores e a integração nativa com o **Lovable Cloud Database (Supabase embutido)**.

Markdown

```
# PROMPT DE CRIAÇÃO: EAD WarGame Studio (MVP)

Crie um aplicativo Web em React com Tailwind CSS chamado **EAD WarGame Studio**, focado na gestão e execução de simulações, jogos de guerra (*wargaming*) e cenários de crise para ensino superior/militar em EAD.

---

## 🛠️ ARQUITETURA DE BACK-END & BANCO DE DADOS
- Use **exclusivamente** a infraestrutura nativa do **Lovable Cloud** (Supabase integrado) para autenticação e banco de dados.
- Não utilize APIs externas ou bancos de dados de terceiros.
- Crie o esquema de dados no Lovable Cloud com as seguintes tabelas principais:
  1. `profiles`: `id`, `user_id`, `full_name`, `role` ('instructor' | 'student'), `avatar_url`.
  2. `simulations`: `id`, `title`, `description`, `status` ('draft' | 'active' | 'completed'), `created_at`.
  3. `injecao_events` (Injetes/Crises): `id`, `simulation_id`, `title`, `content`, `urgency_level` ('low' | 'medium' | 'high' | 'critical'), `published_at`.
  4. `student_decisions`: `id`, `simulation_id`, `injecao_id`, `student_id`, `decision_text`, `submitted_at`, `status` ('pending' | 'evaluated').
  5. `evaluations`: `id`, `decision_id`, `instructor_id`, `score`, `feedback_text`, `rubric_scores` (jsonb).

---

## 🎨 PALETA DE CORES E IDENTIDADE VISUAL
Crie uma interface moderna, profissional e imersiva com estilo **Command Center / Defense Dashboard**:

- **Fundo Principal (Dark Mode por padrão):** `#0F172A` (Slate 900)
- **Painéis e Cards:** `#1E293B` (Slate 800) com bordas em `#334155` (Slate 700)
- **Cor Primária (Ação / Estratégico):** `#0284C7` (Navy Blue / Sky 600)
- **Cor Secundária (Alerta / Destaque):** `#F59E0B` (Amber 500)
- **Alerta de Crise Crítica (Injete Urgente):** `#EF4444` (Red 500)
- **Status / Sucesso:** `#10B981` (Emerald 500)
- **Texto Principal:** `#F8FAFC` (Slate 50)
- **Texto Secundário:** `#94A3B8` (Slate 400)
- **Tipografia:** Fonte Sans-serif limpa e técnica (Inter / Roboto) com rótulos e marcadores em fonte Monospaced (`font-mono`) para códigos e horários.

---

## 👤 FLUXO DO CLIENTE (VISÃO DO ALUNO / OFICIAL)

### 1. Tela de Login e Seleção de Simulação
- Tela de entrada minimalista com login por e-mail/senha via Lovable Cloud Auth.
- Dashboard inicial listando as **Simulações Ativas** e **Simulações Concluídas**.

### 2. Central de Operações (Tela Principal do Aluno)
- **Cabeçalho:** Título da Simulação, Badge de Status em Tempo Real ("EM ANDAMENTO") e Cronômetro em Contagem Regressiva para a próxima rodada/entrega.
- **Feed da Linha do Tempo (Timeline de Crises):**
  - Lista em ordem cronológica reversa dos "Injetes" (situações/eventos de crise) disparados pelo instrutor.
  - Cartões marcados visualmente pelo nível de urgência (Cores: Verde para Normal, Amarelo para Atenção, Vermelho para Crise Crítica).
- **Painel de Ação e Envio de Decisão:**
  - Área para o aluno redigir seu parecer técnico / tomada de decisão.
  - Botão de ação em destaque: `[ Enviar Decisão Estratégica ]`.
  - Indicador de estado de envio (Pendente / Enviado no Horário / Atrasado).
- **Histórico de Feedbacks / Avaliação:**
  - Área onde o aluno visualiza o feedback do instrutor e as notas obtidas por competência na matriz de rubrica.

---

## 🛡️ PAINEL DE ADMINISTRAÇÃO (VISÃO DO INSTRUTOR / MEDIADOR)

### 1. Dashboard do Instrutor (Command Center)
- Visão geral da turma com indicadores rápidos:
  - Total de Alunos Ativos.
  - Injetes Disparados.
  - Decisões Pendentes de Avaliação.

### 2. Gerenciador e Lançador de "Injetes" (Eventos de Crise)
- Botão proeminente: `[ + Disparar Novo Injete ]`.
- **Modal de Lançamento Rápido (Disparo em < 2 min):**
  - Campo de Título da Crise.
  - Seletor de Nível de Urgência (Baixa, Média, Alta, Crítica).
  - Editor de Texto para descrição do evento fictício.
  - Checkbox para definir tempo limite de resposta (ex: 15 min, 30 min, 1 hora).
  - Botão `[ Disparar Injete para a Turma ]` que atualiza instantaneamente o feed dos alunos.

### 3. Matriz de Avaliação e Correção por Rubricas
- Tabela com todas as decisões submetidas pelos alunos.
- Modal de Correção Rápida com escala de rubricas de 1 a 5 para as competências:
  - *Análise de Cenário*
  - *Fundamentação Jurídica/Estratégica*
  - *Tempo de Resposta sob Pressão*
- Campo de Texto para Feedback Qualitativo do Instrutor.
- Botão `[ Salvar e Enviar Feedback ao Aluno ]`.

---

## 🚀 REQUISITOS DE INTERATIVIDADE E UX
- Feedback visual imediato usando Notificações Toast (`Sonner` ou `Radix UI`) para ações como envio de decisões, disparo de injetes e salvamento de avaliações.
- Layout totalmente responsivo (otimizado para Desktop e usável em Mobile).
- Transições suaves nos cards e animações de entrada de novos Injetes na timeline.
```

### Dica de Execução no Lovable

1. Abra o **Lovable.dev** e crie um novo projeto.
2. Cole todo o bloco Markdown acima na caixa de prompt.
3. Certifique-se de ativar o **Lovable Cloud** (Database & Auth) quando a plataforma solicitar para a criação automática das tabelas.

Link para o App: https://command-center-sims.lovable.app

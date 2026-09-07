# Guia de Gestão Financeira e Modelos de Negócio na Educação Física e Artes Marciais 🥋💼

Este repositório foi desenvolvido como o projeto prático para o Desafio de Projeto da **DIO (Digital Innovation One)**: *"IA Generativa: Organização do Conhecimento com NotebookLM"*.

O objetivo deste material é atuar como um **caderno temático inteligente**, integrando a trajetória profissional em Educação Física e Taekwondo à área de **Gestão Financeira, Modelos de Negócio e Captação de Recursos no Terceiro Setor**.

---

## 1. Contexto e Objetivos

### Contexto
O mercado de Educação Física e Artes Marciais exige do profissional uma visão que vai além do planejamento técnico de treinos e aulas. Seja atuando como Personal Trainer em estúdios privados [4, 5], coordenando aulas de Taekwondo infantil [3], oferecendo atividades aquáticas estruturadas [4], ou gerenciando projetos socioesportivos por meio de **Organizações da Sociedade Civil (OSCs)** financiadas por repasses municipais (ONGs), a sustentabilidade orçamentária é o pilar que viabiliza a continuidade do serviço.

### Objetivos de Estudo
* **Dominar a Precificação de Serviços:** Compreender como calcular o preço justo da hora-aula para treinos funcionais rápidos (método Tabata de 30 minutos) [5] e sessões individualizadas presenciais em estúdios [4, 5].
* **Compreender a Gestão Financeira no Terceiro Setor:** Estudar os mecanismos de captação de recursos, termos de colaboração via **MROSC (Lei nº 13.019/2014)** e processos de prestação de contas de verbas públicas em escolas municipais.
* **Garantir a Viabilidade Operacional:** Avaliar custos de infraestrutura e materiais pedagógicos/esportivos (como tatames e protetores) para a manutenção segura de turmas de Taekwondo infantil [3].

---

## 2. Curadoria de Fontes

Para alimentar o **NotebookLM** e extrair as análises financeiras e pedagógicas deste projeto, foram utilizadas as seguintes fontes:

1. **Portfólio Profissional de Pedro Henrique de Maynart Ramos (`Portfolio_Taekwondo_Educacao_Fisica_Eca.pdf`):** Documento base que reúne a trajetória prática iniciada em 2011 [2], detalhando a atuação em estúdios de personal trainer [4], aulas infantis lúdicas [3], reabilitação/treinos em piscina [4] e circuitos funcionais de alta intensidade (Tabata) [5].
2. **Guia SEBRAE de Precificação para Prestadores de Serviços (Fonte Aberta):** Utilizado para fundamentar conceitos de custos fixos, variáveis, margem de contribuição e ponto de equilíbrio aplicados a profissionais autônomos de Educação Física.
3. **Lei Federal nº 13.019/2014 - Marco Regulatório das Organizações da Sociedade Civil (MROSC) (Fonte Aberta):** Base legal utilizada para compreender o fluxo financeiro de repasses públicos da prefeitura para projetos sociais esportivos realizados em escolas.

---

## 3. Engenharia de Prompts & "Cicatrizes" (Troubleshooting)

Nesta seção, registramos as tentativas, os erros ("cicatrizes") e as evoluções nos prompts para obter análises financeiras precisas do NotebookLM com base em nosso portfólio.

### Prompt de Teste 1 (Abordagem Genérica)
> *"Como eu posso cobrar por uma aula de personal trainer e de Taekwondo?"*

* **Resposta da IA:** Trouxe uma média nacional genérica de preços (R$ 50 a R$ 150 a hora), sem diferenciar os custos de estúdio privado, taxas de deslocamento ou a estrutura pedagógica de grupos.
* **Cicatriz (Dificuldade):** O modelo ignorou as particularidades do portfólio, como os treinos de alta intensidade (Tabata) que duram apenas 30 minutos [5], exigindo uma precificação baseada em eficiência e ganho de escala, e não apenas em "hora cheia".

### Prompt de Teste 2 (Abordagem Otimizada - Com Engenharia de Prompt)
> *"Agindo como um Gestor de Finanças especializado em Academias e Projetos Sociais Esportivos, analise as experiências do meu portfólio (desde 2011 no Taekwondo [2], aulas lúdicas infantis [3], circuitos funcionais Tabata de 30 minutos [5] e aulas em piscina [4]). Como estruturar a precificação da hora-aula de cada uma dessas frentes de forma financeiramente sustentável?"*

* **Resposta Obtida:** O modelo segmentou com sucesso as frentes de atuação:
  1. **Tabata (30 min) [5]:** Recomendou cobrança em formato de *micro-class* (mensalidade recorrente em grupo), otimizando o faturamento por metro quadrado de estúdio [4, 5].
  2. **Taekwondo Infantil [3]:** Sugeriu a inserção do custo de depreciação de materiais (tatames lúdicos, cones) no valor mensal cobrado dos pais.
  3. **Projetos em Escolas via OSC (Público):** Destacou que o foco financeiro não é o lucro, mas o cumprimento exato do plano de trabalho e prestação de contas junto à prefeitura nos termos da Lei 13.019/14.

---

## 4. Miniguia de Estudo (Entrega Final)

### A. Resumos Estruturados do Assunto

#### 1. Precificação de Serviços Privados de Educação Física e Personal
Para garantir a sustentabilidade de atuações individuais em estúdio [4] ou em grupo (funcional/Tabata) [5], a fórmula de cálculo da **Hora-Aula Mínima Viável (HAMV)** deve considerar:
$$\text{HAMV} = \frac{\text{Custos Fixos} + \text{Custos Variáveis} + \text{Pró-Labore Desejado}}{\text{Horas Ativas de Trabalho por Mês}}$$
* **Custos Fixos:** Taxas de estúdio, assinatura de aplicativos de treino, seguro profissional.
* **Custos Variáveis:** Combustível/deslocamento, materiais esportivos descartáveis ou de reposição.
* **Ganho de Escala (Tabata de 30 min) [5]:** Treinos curtos e de alta intensidade permitem um giro rápido de alunos por hora. O profissional pode cobrar um ticket menor individualmente, mas aumentar consideravelmente sua receita horária atendendo grupos em circuitos.

#### 2. Gestão Orçamentária no Terceiro Setor (Projetos em Escolas via OSC)
O financiamento de atividades esportivas pedagógicas [3] em escolas municipais por meio de parcerias com OSCs funciona sob regras financeiras rígidas:
* **Termo de Colaboração/Fomento:** Instrumento jurídico que formaliza o repasse de verba da prefeitura para a ONG/OSC executar as aulas de Taekwondo.
* **Plano de Trabalho:** Documento que discrimina previamente onde cada centavo será aplicado (ex: recursos humanos, equipamentos pedagógicos de Taekwondo [3], materiais de natação [4]).
* **Prestação de Contas (Não-Lucratividade):** Toda a verba recebida deve ser executada estritamente conforme o planejado. Eventuais saldos financeiros não utilizados devem ser devolvidos aos cofres públicos ou reprogramados com autorização da prefeitura.

---

### B. Glossário de Conceitos Aprendidos

* **Tabata (Método) [5]:** Protocolo de treino intervalado de alta intensidade (HIIT) que intercala 20 segundos de atividade máxima com 10 segundos de descanso, repetidos por 8 ciclos (4 minutos no total). Permite treinos dinâmicos, rápidos e de alta eficiência financeira para estúdios [4, 5].
* **MROSC (Lei nº 13.019/2014):** Marco Regulatório das Organizações da Sociedade Civil. Define as regras de parceria e repasses de recursos públicos para ONGs realizarem atividades de interesse social (como esportes na escola).
* **Adaptação ao Meio Líquido [4]:** Processo pedagógico de familiarização e segurança na piscina. Sob a ótica financeira, exige atenção à taxa de uso de piscina (aluguel de raia) e controle do número de alunos por turma para garantir a segurança [4].
* **Prestação de Contas (Accountability):** Dever de comprovar o uso regular de recursos financeiros públicos, apresentando notas fiscais, holerites, extratos bancários e relatórios de execução do projeto de Taekwondo.

---

### C. Prompts Reutilizáveis para Revisões Futuras

Salve os prompts abaixo para realizar novas consultas estruturadas no seu NotebookLM:

```markdown
# PROMPT 1: Planejador de Custos para Turmas de Artes Marciais
Aja como consultor de negócios para artes marciais. Com base no meu portfólio de Taekwondo [2, 3], ajude-me a calcular os custos necessários para abrir uma nova turma infantil de 15 alunos. Liste os equipamentos pedagógicos indispensáveis [3], a taxa de depreciação anual de tatames e sugira o valor da mensalidade ideal considerando uma margem de segurança de 20%.

# PROMPT 2: Guia Rápido de Prestação de Contas (OSC / MROSC)
Aja como contador especializado no Terceiro Setor. Explique quais são os 3 erros mais comuns na prestação de contas de projetos socioesportivos financiados por prefeituras (via Lei 13.019/14) e sugira uma planilha-modelo simples de conciliação bancária para controle de folha de pagamento de instrutores.
```

---

## Como Entregar na Plataforma da DIO
1. Crie um repositório no seu GitHub (ex: `miniguia-estudos-notebooklm`).
2. Copie este conteúdo, cole em um arquivo chamado `README.md` na raiz do seu repositório e salve.
3. Adicione o seu arquivo de portfólio em PDF na pasta do repositório (opcional).
4. Submeta o link do seu repositório do GitHub na plataforma da DIO para garantir o seu **Nota 10**! 🚀

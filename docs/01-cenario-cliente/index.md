# 1. Cenário Atual do Cliente e do Negócio

## 1.1 Identificação do Cliente/Parceiro

| Campo | Informação |
|-------|-----------|
| **Nome** | Anderson Brito de Figueiredo |
| **Tipo** | Pessoa Física — Instrutor de projeto com jovens aprendizes |
| **Representante** | Ana das Graças Ferreira Rodrigues (Líder de equipe) |
| **Forma de contato** | Reuniões periódicas e canal de mensagem instantânea |
| **Vínculo com o projeto** | Cliente real e parte interessada principal |

---

## 1.2 Introdução ao Negócio e Contexto

O **Observatório de Talentos do Transporte** é um ecossistema integrado de gestão da jornada do aprendiz, idealizado em 2026 por estudantes do SEST SENAT B093, em Luzânia. O projeto é voltado para empresas do setor de transporte e jovens em formação profissional, com o objetivo de oferecer uma **plataforma tecnológica com modelo de negócio sustentável** capaz de mitigar a evasão escolar e fomentar o engajamento por meio de reconhecimento.

A solução opera conectando o ambiente educacional presencial com os sistemas das empresas parceiras, realizando integração via API e por meio de um aplicativo próprio — o **"Jornada Transporte +"** — que centraliza dados de frequência, desempenho e engajamento dos aprendizes.

A missão central do projeto é transformar as primeiras semanas profissionais dos jovens aprendizes, promovendo um acolhimento humanizado capaz de erradicar a invisibilidade que esses jovens frequentemente enfrentam, aumentando suas chances de efetivação na carreira e reduzindo a taxa de evasão atual de 30%, com meta de atingir um ROI de 94% para as transportadoras parceiras.

O público-alvo da solução abrange jovens de 14 a 24 anos em sua primeira experiência no mercado formal de trabalho, além de gestores de RH das empresas parceiras. O principal gargalo identificado é a desconexão entre os sistemas institucionais e os controles manuais ainda utilizados pelas organizações, o que impede o acompanhamento eficaz da jornada dos aprendizes.

---

## 1.3 Rich Picture

O diagrama a seguir representa o cenário atual da evasão, intitulado **"O Cenário da Evasão: A Jornada Desconectada do Aprendiz"**. Ele ilustra os principais atores, fluxos de informação e pontos de ruptura que motivam a proposta do projeto.

![Rich Picture - Cenário da Evasão](../assets/images/rich-picture.png)

*Figura 1: O Cenário da Evasão — A Jornada Desconectada do Aprendiz.*

O diagrama evidencia quatro dimensões do problema: o **Fator Humano** (sensação de invisibilidade dos aprendizes), os **Cargos Operacionais** (desconexão entre funções e expectativas), o **Impacto Financeiro e Social** (custos ocultos com rotatividade) e as **Falhas de Integração** (ausência de APIs e dados rastreáveis entre sistemas).

---

## 1.4 Identificação da Oportunidade ou Problema

A necessidade de mitigar a alta evasão de jovens aprendizes no setor de transporte constitui um problema complexo, motivado por empecilhos de natureza organizacional e tecnológica. Três categorias principais de causas foram identificadas:

**Falhas de processo** — Carência de um acolhimento estruturado nas primeiras semanas e invisibilidade do desempenho dos aprendizes perante as empresas parceiras e a própria instituição de ensino.

**Limitações tecnológicas** — Ausência de canais de comunicação humanizados entre aprendizes, instrutores e gestores, combinada com a falta de integração entre os sistemas das instituições de ensino e das empresas parceiras.

**Lacunas de indicadores** — Inexistência de dados rastreáveis sobre o ROI da formação de aprendizes e desmotivação gerada pela falta de feedbacks estruturados ao longo da jornada.

A proposta visa substituir modelos de gestão puramente funcionais e frios por um **ecossistema gamificado** que atue diretamente sobre esses gargalos operacionais. Economicamente, a solução justifica-se pela otimização de recursos e pela redução de custos ocultos com rotatividade e retreinamento, transformando a jornada do aprendiz em um processo mensurável, engajador e sustentável.

O diagrama de Ishikawa a seguir organiza as causas raiz do problema segundo os 6Ms:

![Diagrama de Ishikawa](../assets/images/ishikawa-diagram.png)

*Figura 2: Diagrama de Ishikawa — Causas da Evasão de Jovens Aprendizes.*

!!! warning "Reflexão importante"
    Nem todas as causas identificadas no diagrama de Ishikawa se resolvem com software. A solução tecnológica proposta atua sobre os fatores de **Tecnologia**, **Método** e **Medida**, enquanto fatores de **Pessoas** e **Meio Ambiente** demandam ações complementares de gestão e cultura organizacional.

---

## 1.5 Desafios do Projeto

### Desafios do Negócio (lado do cliente)

Os principais obstáculos operacionais identificados junto ao cliente são:

| Desafio | Impacto Atual |
|---------|--------------|
| **Baixa retenção dos jovens** | Taxa de evasão de 25% nas primeiras semanas de aprendizagem |
| **Processos manuais** | Equipe administrativa demora em média 15 minutos por aula em chamadas manuais (~5h/mês) |
| **Baixo engajamento dos aprendizes** | Sensação de invisibilidade e ausência de canal para tirar dúvidas |
| **Falta de dados rastreáveis** | 0% de dados sobre efetivação pós-curso, inviabilizando demonstração de ROI para empresas |

### Desafios de Desenvolvimento (lado da equipe)

Do ponto de vista da construção da solução, os principais desafios técnicos e de gestão são:

**Prazo de desenvolvimento do MVP** — O semestre letivo impõe um horizonte temporal restrito para a entrega de um produto funcional e validado.

**Calibragem da gamificação** — Definir um sistema de pontuação e recompensas que seja motivador sem se tornar superficial ou desconectado da realidade dos aprendizes exige testes e iterações.

**Adesão e engajamento dos gestores** — A adoção da plataforma pelos instrutores e gestores de RH depende de uma curva de aprendizado e de demonstração de valor prático.

**Integração de múltiplos atores** — Coordenar as necessidades de jovens aprendizes, instrutores, gestores institucionais e empresas parceiras em um único produto é um desafio de escopo e priorização.

**Viabilidade de infraestrutura** — Garantir que a solução seja acessível em contextos com conectividade limitada, comuns entre o público jovem aprendiz.

---

## 1.6 Mapa de Stakeholders

| Stakeholder | Relação com a Solução | Interesses e Expectativas | Nível de Influência | Participação no Projeto |
|---|---|---|---|---|
| **Instrutores e orientadores** | Usuários principais | Otimização do tempo em tarefas manuais, melhoria no acompanhamento, ferramentas para atuar no engajamento | Alto — adoção do sistema | Uso diário, validação de funcionalidades |
| **Jovens aprendizes** | Usuários secundários e beneficiários | Reconhecimento, acolhimento, visibilidade e reconhecimento do esforço | Médio | Participação em funcionalidades de gamificação |
| **Gestores de instituições de ensino** | Parceiros estratégicos | Dados de efetivação, fortalecimento da instituição, reconhecimento de impacto social | Alto — aprovação institucional para uso | Decisões estratégicas e alinhamento dos objetivos |
| **Empresas parceiras** | Beneficiários de resultados financeiros e relatórios | Redução de custos com rotatividade, formação completa e de maior qualidade | Baixo — dentro do contexto de aprendizado | Recepção dos aprendizes formados, relatórios de desempenho |

---

## 1.7 Segmentação de Clientes

### Segmento 1: O Cliente — Gestores, Profissionais de RH e Instrutores Pedagógicos

Este segmento é composto pelos profissionais responsáveis pelo acolhimento, treinamento e liderança dos jovens aprendizes dentro das instituições de ensino e das empresas parceiras.

**Perfil Profissional:** Atuam na interface entre a instituição de ensino e as empresas, gerenciando processos de frequência, desempenho e comunicação com os aprendizes. Em geral, lidam com múltiplos sistemas desconectados e controles manuais que consomem tempo e geram inconsistências.

**Desafios Operacionais:** Enfrentam a ausência de ferramentas integradas para acompanhar a jornada dos aprendizes de forma contínua, o que dificulta a identificação precoce de riscos de evasão e a demonstração de resultados para as empresas parceiras.

**Necessidades e Objetivos:** Buscam ferramentas eficientes que substituam controles burocráticos por dashboards intuitivos, alertas preditivos e relatórios automatizados, liberando tempo para atividades de maior valor pedagógico e relacional.

---

### Segmento 2: O Usuário Final — Jovens Aprendizes

Este segmento é composto pelos jovens de 14 a 24 anos que vivenciam sua primeira experiência no mercado formal de trabalho, frequentemente em situação de vulnerabilidade socioeconômica.

**Perfil Sociodemográfico:** Jovens em processo de formação profissional, muitas vezes com baixa familiaridade com ambientes corporativos e com necessidades de suporte emocional e orientação prática.

**Desafios de Adaptação:** Enfrentam barreiras multifatoriais de ordem socioeconômica, emocional e profissional. A sensação de invisibilidade — não saber se seu esforço está sendo reconhecido — é um dos principais gatilhos de desmotivação e evasão.

**Perfil de Engajamento:** Tendem a se desmotivar rapidamente diante de ambientes impessoais, mas são altamente responsivos a mecânicas de gamificação, reconhecimento de conquistas e comunicação direta e humanizada.

---

*Próxima seção: [2. Solução Proposta](../02-solucao-proposta/index.md)*

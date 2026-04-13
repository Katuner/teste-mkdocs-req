# 2. Solução Proposta

## 2.1 Objetivo Geral do Produto

O produto proposto tem como objetivo geral **mitigar as causas da evasão de jovens aprendizes** no setor de transporte, aumentando a retenção e o engajamento por meio de um sistema de pontuação e reconhecimento. A solução busca reduzir a evasão, otimizar o trabalho docente e aumentar o interesse dos estudantes ao longo de toda a jornada de aprendizagem.

---

## 2.2 Objetivos Específicos (OE) do Produto

Os objetivos específicos orientam o escopo funcional da solução e foram definidos a partir dos problemas e desafios identificados na Seção 1:

| ID | Objetivo Específico |
|----|---------------------|
| **OE1** | Reduzir a evasão por meio de comunicação, acolhimento e suporte contínuo ao longo da jornada do aprendiz |
| **OE2** | Demonstrar o valor da retenção para as empresas parceiras por meio de métricas de ROI rastreáveis |
| **OE3** | Monitorar continuamente o desempenho, a assiduidade e a evolução dos aprendizes |
| **OE4** | Aumentar o engajamento dos jovens por meio de mecânicas de gamificação |
| **OE5** | Otimizar o tempo de trabalho dos instrutores e orientadores, reduzindo tarefas manuais repetitivas |
| **OE6** | Viabilizar a tomada de decisão estratégica baseada em dados para gestores institucionais e empresas parceiras |

---

## 2.3 Características de Produto

As características a seguir foram mapeadas preliminarmente e relacionadas aos objetivos específicos que cada uma atende:

| OE Principal | Contribuição Secundária | ID | Característica | Descrição Resumida | Valor de Negócio Principal |
|:---:|:---:|:---:|---|---|---|
| OE4 | OE1 | C1 | **Sistema de Gamificação** | Mecânicas de pontuação, conquistas e ranking que reconhecem frequência, desempenho e participação dos aprendizes | Aumento do engajamento e redução da sensação de invisibilidade |
| OE3 | OE6 | C2 | **Dashboard Educacional** | Painel de acompanhamento em tempo real com indicadores de frequência, desempenho e evolução individual e coletiva | Visibilidade do progresso para instrutores e gestores |
| OE1 | OE3 | C3 | **Sistema de Alertas Preditivos de Evasão** | Identificação automática de padrões de risco (faltas, baixo engajamento) com notificações para instrutores | Intervenção precoce antes que o aprendiz abandone o programa |
| OE1 | OE4 | C4 | **Canal de Acolhimento e Suporte Contínuo** | Espaço de comunicação humanizada entre aprendizes, instrutores e orientadores, com FAQ e suporte a dúvidas | Redução da sensação de abandono nas primeiras semanas |
| OE5 | OE3 | C5 | **Automatização de Controle de Frequência** | Registro automatizado de presença integrado ao sistema da instituição, eliminando chamadas manuais | Economia de ~5h/mês por instrutor em tarefas administrativas |
| OE2 | OE6 | C6 | **Gerador de Relatórios Institucionais** | Relatórios automáticos de desempenho, retenção e ROI para empresas parceiras e gestores institucionais | Demonstração de valor da formação e embasamento para decisões estratégicas |

---

## 2.4 Tecnologias a Serem Utilizadas

A escolha das tecnologias foi orientada pela familiaridade da equipe e pela adequação ao escopo do MVP a ser entregue ao final do semestre:

| Camada | Tecnologia | Justificativa |
|--------|-----------|---------------|
| **Front-end** | React | Biblioteca amplamente utilizada, com ecossistema maduro e componentes reutilizáveis |
| **Back-end** | Flask (Python) | Framework leve e flexível, adequado para APIs REST e integração com bibliotecas de análise de dados |
| **Banco de Dados** | PostgreSQL | Banco relacional robusto, com suporte a consultas complexas e escalabilidade |
| **Testes** | pytest | Framework de testes unitários e de integração para Python |
| **Infraestrutura/Deploy** | Docker | Containerização que garante portabilidade e consistência entre ambientes de desenvolvimento e produção |

---

## 2.5 Pesquisa de Mercado e Análise Competitiva

O mercado de soluções para engajamento e gestão de aprendizagem corporativa é relativamente consolidado, mas apresenta lacunas específicas para o contexto de jovens aprendizes no setor de transporte. A tabela a seguir compara as principais soluções existentes com a proposta do Observatório de Talentos:

| Solução | Foco Principal | Gamificação | Alerta Preditivo | Foco em Aprendizes | Integração com Transportadoras |
|---------|---------------|:-----------:|:----------------:|:------------------:|:------------------------------:|
| **Ludos Pro** | Gamificação corporativa | ✅ | ❌ | ❌ | ❌ |
| **Feedz (TOTVS)** | Engajamento e RH | ✅ | ❌ | ❌ | ❌ |
| **Niduu (Gupy)** | Educação corporativa | Parcial | ❌ | ❌ | ❌ |
| **Taqe** | Recrutamento jovem | ❌ | ❌ | ✅ | ❌ |
| **Gamefic** | Gamificação educacional | ✅ | ❌ | Parcial | ❌ |
| **Observatório de Talentos** | Retenção de aprendizes | ✅ | ✅ | ✅ | ✅ |

O diferencial competitivo da solução proposta reside na **combinação única** de gamificação, alertas preditivos de evasão, foco específico no perfil do jovem aprendiz e integração com o ecossistema das empresas do setor de transporte — uma lacuna não atendida por nenhuma das soluções concorrentes analisadas.

---

## 2.6 Viabilidade da Proposta

A viabilidade técnica da proposta é considerada **alta**, uma vez que a equipe possui experiência prévia com as tecnologias selecionadas (React, Flask, PostgreSQL e Docker). O escopo do MVP foi deliberadamente delimitado para ser entregável dentro do prazo do semestre letivo, priorizando as características de maior impacto sobre o problema central (C1, C3 e C5).

Do ponto de vista de acesso ao cliente, a equipe conta com canal direto de comunicação com Anderson Brito de Figueiredo e com a representante Ana das Graças Ferreira Rodrigues, o que viabiliza ciclos de validação regulares ao longo do desenvolvimento.

A principal restrição de viabilidade identificada é a **calibragem da gamificação**: definir um sistema de recompensas que seja percebido como justo e motivador pelos aprendizes exigirá testes com usuários reais, o que demanda planejamento cuidadoso das iterações de validação.

---

## 2.7 Benefícios Esperados

### Para o Cliente (Gestores, Instrutores e Empresas Parceiras)

A adoção da plataforma permitirá que instrutores e orientadores reduzam significativamente o tempo gasto em tarefas administrativas manuais, liberando energia para atividades pedagógicas de maior valor. Gestores institucionais terão acesso a dados consolidados sobre o desempenho e a retenção dos aprendizes, fortalecendo a posição da instituição perante as empresas parceiras. Para as transportadoras, a solução entregará relatórios de ROI que demonstram objetivamente o retorno do investimento em formação de jovens aprendizes, subsidiando decisões estratégicas de contratação e desenvolvimento.

### Para os Usuários Finais (Jovens Aprendizes)

Os jovens aprendizes se beneficiarão de um ambiente de aprendizagem mais acolhedor e transparente, no qual seu esforço e progresso são reconhecidos de forma contínua. A gamificação criará um senso de pertencimento e competição saudável, enquanto o canal de suporte contínuo reduzirá a sensação de abandono que frequentemente precede a evasão. Em última instância, a solução aumenta as chances de efetivação dos aprendizes ao final do programa, impactando positivamente sua trajetória profissional.

---

*Próxima seção: [3. Estratégias de Engenharia de Software](../03-estrategias-esw/index.md)*

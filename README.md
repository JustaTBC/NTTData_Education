# 🚀 Solução Analítica Educacional: Infraestrutura e Desempenho (NTT DATA - Grupo 8)
## 🌟 Visão Geral do Projeto

Este projeto, desenvolvido pelo Grupo 8 da Residência NTT DATA + Porto Digital + Cesar School (2º Semestre 2025), apresenta um Data Lakehouse completo focado no setor educacional brasileiro.

Nosso objetivo foi unificar dados públicos do INEP, ENEM e ENADE para correlacionar a infraestrutura escolar com o desempenho acadêmico, fornecendo uma base sólida para a tomada de decisões estratégicas e políticas públicas.

## 💡 Justificativa do Projeto: O Cenário Atual da Educação
A educação no país passa por uma grande transformação, impulsionada por exames e indicadores nacionais que avaliam tanto o final da educação básica quanto o ensino superior. Esses indicadores orientam o acesso à faculdade, a oferta de vagas, bolsas e financiamentos, além de ajudarem a medir a qualidade dos cursos.

O impacto da pandemia acelerou drasticamente a adoção da tecnologia, forçando a migração para o ensino on-line e abrindo espaço para modelos híbridos. No entanto, essa mudança também escancarou desigualdades de acesso a equipamentos, internet e condições adequadas de estudo em casa.

Desafios do Cenário Misto:

* Ensino Presencial: Persistência de problemas de infraestrutura e grandes diferenças de qualidade entre regiões.

* Ensino a Distância (EAD): Questões de engajamento, alta evasão e a necessidade de garantir a qualidade dos cursos, somadas à limitação tecnológica de muitos estudantes.

Essa combinação de mudanças, oportunidades e desafios é o ponto central do nosso projeto, justificando a necessidade de uma análise de dados robusta e integrada.

---

## 🏗️ Arquitetura da Solução (Medalhão)

Adotamos a Arquitetura Medalhão (Bronze, Silver, Gold) para garantir a qualidade, confiabilidade e estruturação progressiva dos dados:

Bronze (Bruto)
* Função: Recebimento dos dados brutos e Armazenamento inicial.
* Processo: Padronização de schemas.

Silver (Limpo/Enriquecido)
* Função: Limpeza e consolidação.
* Processo: Tratamento de inconsistências, Joins e reorganização das bases.

Gold (Curado/Negócio)
* Função: Modelagem e agregação final.
* Processo: Criação de tabelas analíticas e dados prontos para visualização e dashboards.

![Arquitetura Medalhão](https://encrypted-tbn1.gstatic.com/licensed-image?q=tbn:ANd9GcQysgVi_7ri5r2fzjja-AJmPcdvXZ4MCRM8BbPQVbLkXYmJTA6_VYnECcn2WgFh0f-qA0I0p0woB8ArR853lGoLPbizElzs_qJ-17-kn61jEaZYwqo)

## Bases de Dados Integradas

* UM: **RESULTADOS_2024** , **ITENS_PROVA_2024**

* Censo Escolar (INEP): **HAD_ESCOLAS_2024**

* ENADE: **conceito_enade_2023**

---

## 🛠️ Conjunto de Tecnologias

Engenharia de Dados:

* Python
* PySpark
* Pandas

Ambiente:

* Databricks

Controle de Versões:

* Git e GitHub

## 📊 Dashboards

Os dashboards desenvolvidos incluem:

* Ranking Top 10 de escolas

* Comparação entre infraestrutura × desempenho

* Histogramas e distribuições ENADE

* Análises de notas ENEM

* Correlações por modalidade de ensino

## 📈 Resultados e Entregáveis

O projeto entrega uma base analítica sólida e dashboards focados em insights:

* Data Lakehouse completo preparado para expansão.

* Dashboards de Ranking: Top 10 escolas e análises de notas ENEM.

* Análise de Correlação: Comparação entre infraestrutura × desempenho.

* Base Analítica: Sólida para o desenvolvimento de políticas públicas educacionais.

---
## 🧑‍💻 Equipe
- **Heitor Didier** — [Eito2511](https://github.com/Eito2511)  
- **Luiz Felipe** — [LuizMXavier](https://github.com/LuizMXavier)  
- **Marcus Vinicius** — [Marcus-Vini-Tavares](https://github.com/Marcus-Vini-Tavares)  
- **Nicolly Rodrigues** — [nicky89ck](https://github.com/nicky89ck)  
- **Pedro Armando** — [pedrosol-dev](https://github.com/pedrosol-dev)  
- **Thomaz Barros** — [JustaTBC](https://github.com/JustaTBC)  

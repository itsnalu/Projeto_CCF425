# Projeto SPSafe - Dados de Criminalidade de SP

Este repositório contém o projeto desenvolvido para a análise dos dados de criminalidade de São Paulo (SPSafe). O objetivo é explorar e responder a questões relevantes sobre a criminalidade, identificando padrões, correlações e tendências que possam contribuir para a compreensão dos dados e aplicação prática dos aprendizados adquiridos na matéria CCF425. As entregas ocorrerão na branch **main**.

---

## Sumário

- [Objetivo](#objetivo)
- [Introdução](#introdução)
- [Perguntas](#perguntas)
- [Integrantes do Grupo](#integrantes-do-grupo)
- [Participação nas Tarefas](#participação-nas-tarefas-a-partir-da-entrega-2)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Observações](#observações) 
- [Referências](#referências)

---

## Objetivo

O objetivo deste projeto é aplicar técnicas de ciência de dados para analisar e explorar o conjunto de dados de criminalidade de São Paulo (SPSafe). A análise busca responder a diversas perguntas de criadas pelos alunos.

---

## Introdução

Nos últimos anos, a segurança pública no Brasil tem enfrentado desafios crescentes, especialmente com o aumento de crimes como roubos, furtos e homicídios. Em São Paulo, os dados da Secretaria de Segurança Pública (SSP/SP) mostram uma elevação nos índices criminais em comparação ao período pré-pandemia. A disponibilização de dados sobre criminalidade é essencial para auxiliar gestores, pesquisadores e a população na identificação de padrões e na formulação de políticas públicas mais eficazes.

No entanto, a estrutura desses dados frequentemente apresenta inconsistências, como falta de padronização e fragmentação, dificultando sua análise e interpretação. Diante desse cenário, este trabalho propõe o SPSafe, um conjunto de dados construído a partir dos boletins de ocorrência registrados entre 2003 e 2022 no estado de São Paulo.

---

## Perguntas

1. **Quais foram os anos nos quais mais houveram ocorrências registradas em 2022?** (PERGUNTA FRAGMENTADA EM 14, 15, 16)
2. ~~Como se distribuem os perfis de pessoas envolvidas (vítimas/autores) em termos de idade, sexo e cor de pele (fatores demográficos)?~~ (PERGUNTA REMOVIDA)
3. **Qual a natureza e espécie de crimes mais comuns?**
4. **Qual é o tempo médio entre a ocorrência, a elaboração do boletim e a comunicação dos fatos?**
5. **Quais são 3 tipos de relacionamentos possíveis entre veículos (marca, modelo, ano de fabricação e cidade) e crimes patrimoniais?**
6. **Quais são os tipos de locais mais comuns para a ocorrência de homicídios e latrocínios?** (PERGUNTA ATUALIZADA)
7. **Qual a distribuição dos períodos do dia (manhã, tarde, noite, madrugada) nas ocorrências?**
8. **Há alguma tendência de aumento ou diminuição nas ocorrências fatais ao longo dos meses?** (PERGUNTA ATUALIZADA)
9. ~~Quais perfis demográficos (sexo, profissão, cor de pele) estão mais presentes em ocorrências fatais?~~ (PERGUNTA REMOVIDA)
10. **Existe uma faixa etária que apresenta maior probabilidade de fatalidades em determinados tipo de ocorrência?** 
11. **Qual é o município com mais ocorrências registradas em 2022 em valores absolutos e relativos a população do município?** (PERGUNTA ATUALIZADA)
12. **Qual é o bairro e logradouro com mais ocorrências registradas em 2022 em valores absolutos?** (PERGUNTA ADICIONADA)
13. **Quais foram os 15 anos em que ocorreram mais crimes que só foram registrados em 2022, desconsiderando os crimes efetivamente cometidos em 2022** (PERGUNTA ADICIONADA)
14. **Quais foram os meses nos quais mais houveram ocorrências registradas em 2022?** (PERGUNTA ADICIONADA)
15. **Quais foram os dias da semana nos quais mais houveram ocorrências registradas em 2022?** (PERGUNTA ADICIONADA)
16. **Quais foram os horários nos quais mais houveram ocorrências registradas em 2022?** (PERGUNTA ADICIONADA)
17. **Quais são os dias da semana e horários específicos com maior número de ocorrências?** (PERGUNTA ADICIONADA)

---

## Integrantes do Grupo

| Nome                             | Matrícula |
| -------------------------------- | --------- |
| Ana Luísa Moreira Rodrigues      | 5389      |
| Lucas da Costa Moreira           | 5377      |
| Aléxia Karoline Augusta Germano  | 5373      |
| Daniel Martins de Abreu          | 5798      |

---

## Participação nas Tarefas (a partir da Entrega 2)

A partir da **Entrega 2** do projeto, adotaremos uma abordagem mais estruturada para a documentação das tarefas realizadas por cada integrante do grupo, utilizando o **Github Projects** e utilizando um modelo simplificado do Kanban.

---

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **/data**: Contém todos os arquivos de dados utilizados durante o trabalho prático. Isso inclui o datasets com os dados dos alunos, que é o foco do trabalho, bem como outros datasets auxiliares que poderão ser utilizados para responder certas perguntas no trabalho.
- **/src**:  É a pasta que contém os arquivos .py e .ipynb criados durante o trabalho.
- **README.md**: Arquivo de documentação.

---

## Observações

É importante ressaltar é que ao fim do tratamento, correção e enriquecimento do dataset, terminamos com algumas colunas que não existiam no dataset original, que são:

FAIXA_ETARIA;
DIA_OCORRENCIA;

---

## Referências

- [IBGE](https://www.ibge.gov.br/explica/codigos-dos-municipios.php)
- [Data Types and Missing Values](https://www.kaggle.com/code/residentmario/data-types-and-missing-values)
- [Indexing, Selecting & Assigning](https://www.kaggle.com/learn/pandas)
- [Principais técnicas para lidar com valores ausentes](https://www.datacamp.com/pt/tutorial/techniques-to-handle-missing-data-values)
- [6 truques do Pandas para impulsionar sua análise de dados](https://www.insightlab.ufc.br/6-truques-do-pandas-para-impulsionar-sua-analise-de-dados/)

---

*Projeto SPSafe - Dados de Criminalidade de SP*  
*2025 - Universidade Federal de Viçosa – Campus Florestal*

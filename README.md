# Projeto SPSafe - Dados de Criminalidade de SP

Este repositório contém o projeto desenvolvido para a análise dos dados de criminalidade de São Paulo (SPSafe). O objetivo é explorar e responder a questões relevantes sobre a criminalidade, identificando padrões, correlações e tendências que possam contribuir para a compreensão dos dados e aplicação prática dos aprendizados adquiridos na matéria CCF425.

---

## Sumário

- [Objetivo](#objetivo)
- [Introdução](#introdução)
- [Perguntas](#perguntas)
- [Integrantes do Grupo](#integrantes-do-grupo)
- [Estrutura do Projeto](#estrutura-do-projeto)

---

## Objetivo

O objetivo deste projeto é aplicar técnicas de ciência de dados para analisar e explorar o conjunto de dados de criminalidade de São Paulo (SPSafe). A análise busca responder a diversas perguntas de criadas pelos alunos.

---

## Introdução

Nos últimos anos, a segurança pública no Brasil tem enfrentado desafios crescentes, especialmente com o aumento de crimes como roubos, furtos e homicídios. Em São Paulo, os dados da Secretaria de Segurança Pública (SSP/SP) mostram uma elevação nos índices criminais em comparação ao período pré-pandemia. A disponibilização de dados sobre criminalidade é essencial para auxiliar gestores, pesquisadores e a população na identificação de padrões e na formulação de políticas públicas mais eficazes.

No entanto, a estrutura desses dados frequentemente apresenta inconsistências, como falta de padronização e fragmentação, dificultando sua análise e interpretação. Diante desse cenário, este trabalho propõe o SPSafe, um conjunto de dados construído a partir dos boletins de ocorrência registrados entre 2003 e 2022 no estado de São Paulo.

---

## Perguntas

1. ⭐⭐⭐(bom pra ver se a violencia diminuiu com os anos passados ou nao)**Qual é a distribuição temporal das ocorrências (por ano, mês, dia da semana e horário)?**
2. ⭐**Quais são as regiões (cidades, bairros, coordenadas geográficas) com maior incidência de ocorrências?** **Pergunta 2 e pergunta 12 sao basicamente a mesma ideia**
3. **Como a natureza das ocorrências se distribui e quais são as categorias mais comuns?**
4. ⭐⭐⭐⭐(maravilhoso)**Existe correlação entre a idade, o sexo e o tipo de ocorrência?**
5. ⭐⭐(dificil, mas é bom)**Qual é o tempo médio entre a ocorrência, a emissão do boletim e a comunicação dos fatos?**
6. ⭐⭐(interessante, mas pode ser dificil ver qual carro, nao sei como estao os dados em relacao a isso)**Como os atributos relacionados a veículos (marca, modelo, ano de fabricação e cidade) se relacionam com os tipos de ocorrências?**
7. (meio paia)**Quais delegacias, departamentos ou seccionais concentram maior número de ocorrências?**
8. ⭐⭐⭐⭐(maravilhoso)**Qual a distribuição dos períodos do dia (manhã, tarde, noite, madrugada) nas ocorrências?**
9. ⭐⭐(se for a ideia de quanto maior a idade menor crime é interessante pq ele passou na sala hoje isso)**Há alguma tendência de aumento ou diminuição nas ocorrências fatais ao longo dos anos?**
10. ⭐(meio meh)**Como os diferentes tipos de locais (residencial, comercial, público, etc.) influenciam na ocorrência dos incidentes?**
11. ⭐⭐(pode ser dificil de ser feito)**Existe uma faixa etária que apresenta maior probabilidade de fatalidades em determinados tipos de ocorrências?**
12. ⭐⭐(se for ver quais sao os top 50 piores bairros, por exemplo, acho interessante)**Como as características geográficas (cidade, bairro, UF) se relacionam com a incidência de mortes fatais?** **Pergunta 2 e pergunta 12 sao basicamente a mesma ideia**
13. ⭐⭐(pode ser criadas ideias de "quanto mais tarde da noite mais chance de morte)"**Qual a relação entre o horário/período das ocorrências e a gravidade dos incidentes fatais?**
14. ⭐⭐⭐⭐(maravilhoso)**Quais perfis demográficos (sexo, profissão, cor de pele) estão mais presentes em ocorrências fatais?**

---

## Integrantes do Grupo

| Nome                             | Matrícula |
| -------------------------------- | --------- |
| Ana Luísa Moreira Rodrigues      | 5389      |
| Lucas da Costa Moreira           | 5377      |
| Aléxia Karoline Augusta Germano  | 5373      |
| Daniel Martins de Abreu          | 5798      |

---

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **/data**: Contém todos os arquivos de dados utilizados durante o trabalho prático. Isso inclui o datasets com os dados dos alunos, que é o foco do trabalho, bem como outros datasets auxiliares que poderão ser utilizados para responder certas perguntas no trabalho.
- **/src**:  É a pasta que contém os arquivos .py e .ipynb criados durante o trabalho.
- **README.md**: Arquivo de documentação.

---

*Projeto SPSafe - Dados de Criminalidade de SP*  
*2025 - Universidade Federal de Viçosa – Campus Florestal*

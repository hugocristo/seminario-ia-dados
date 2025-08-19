# Seminário de Pesquisa em Metodologia X (PPGP-0114) - 2025/2

Boas-vindas ao repositório do seminário **Análise Computacional de Dados Textuais (2025/2)**, ofertado pelo Programa de Pós-Graduação em Psicologia da Universidade Federal do Espírito Santo.

Nesta página você encontrará todo o material citado e apresentado ao longo dos encontros, bem como indicações de links para a instalação dos ambientes e códigos-fonte das demonstrações.

**Temas**
* Introdução à linguagem R
* Medidas quantitativas de dados textuais
* Limpeza, processamento e análise de dados textuais
* Modelos de linguagem de larga escala (LLMs)
* Visualização de dados e comunicação de resultados

**Requisitos**
* Notebook (processador i5, 8GB de memória RAM ou superior)
* Aplicações: [RStudio](https://posit.co/downloads/), [linguagem R](https://cran.r-project.org/) e [Ollama](https://ollama.com)
* **Não é necessário saber programar**, mas não ter medo ajuda 😊!

**Metodologia**
* Carga horária: 15h
* Quartas-feiras, das 9 às 12h (05 de novembro a 03 de dezembro)
* Aulas expositivas com laboratórios de código em R
* Avaliação: participação e presença (0,5 cada aula) e trabalho final (7,5) - processamento de dados textuais

**Responsável**
* Prof. Dr. Hugo Cristo Sant'Anna - hugo.santanna@ufes.br
* Atendimento fora de aula (mediante agendamento): Cemuni IV, sala 15

## Conjuntos de dados

*Em breve*

## 05/11: Aula 1 -  Introdução ao R
* Instalação e execução do ambiente RStudio e da linguagem R
* Princípios básicos de programação em R: funções, laços, variáveis e operadores
* Instalação e carregamento de pacotes
* Importação de arquivos e o pacote `openxlsx`

## 12/11: Aula 2 -  Medidas quantitativas de dados textuais
* Caractere, palavra, termo, token, n-grams
* Frequências: termo, documento, inversa
* Vocabulários 

## 19/11: Aula 3 -  Tratamento para representações numéricas
* Pacotes `stringr`, `stringi`, `tokenizers` e `stopwords`
* Limpeza de dados: palavras de parada, acentuação, pontuação, caracteres especiais
* Lematização: gênero, número, radicais
* Representações distribuídas de dados textuais e o pacote `word2vec`
* Redução da dimensionalidade e pacote `Rdimtools`
* Métricas de similaridade e agrupamento: `dist` e `hclust`
* Operações com matrizes: `cosine` do pacote `lsa`

## 26/11: Aula 4 -  Modelos de linguagem de larga escala
* Modelo PARTE para *prompts*
* Pacote `ollamar`: *prompts*, respostas e *embeddings*
* Mais operações com matrizes

## 03/12: Aula 5 -  Visualização de dados
* Dendrogramas, nuvens de palavras, gráficos bi e tridimensionais
* Pacotes `ggplot2`, `plotly`, `ggdendro`, `wordcloud2`

## Referências
* Benoit, K., Muhr, D., & Watanabe, K. (2021). stopwords: Multilingual Stopword Lists. https://doi.org/10.32614/CRAN.package.stopwords
* Google. (2024). Prompting Guide 101—October 2024 Edition. Google Workspace. https://workspace.google.com/learning/content/gemini-prompt-guide?hl=pt-BR
* Lang, D., & Chien, G. (2018). wordcloud2: Create Word Cloud by “htmlwidget”. https://CRAN.R-project.org/package=wordcloud2
* Lin, H., & Safi, T. (2024). ollamar: An R package for running large language models. PsyArXiv. https://doi.org/10.31234/osf.io/zsrg5
* Mikolov, T., Sutskever, I., Chen, K., Corrado, G. S., & Dean, J. (2013). Distributed Representations of Words and Phrases and their Compositionality. Advances in Neural Information Processing Systems, 26. https://proceedings.neurips.cc/paper/2013/hash/9aa42b31882ec039965f3c4923ce901b-Abstract.html
* Mullen, L. A., Benoit, K., Keyes, O., Selivanov, D., & Arnold, J. (2018). Fast, Consistent Tokenization of Natural Language Text. Journal of Open Source Software, 3(23), 655. https://doi.org/10.21105/joss.00655
* Schauberger, P., & Walker, A. (2025). openxlsx: Read, Write and Edit xlsx Files. https://doi.org/10.32614/CRAN.package.openxlsx
* Sievert, C. (2020). Interactive Web-Based Data Visualization with R, plotly, and shiny. Chapman and Hall/CRC. https://plotly-r.com
* Silge, J., & Robinson, D. (2025, julho 24). Term Frequency and Inverse Document Frequency (tf-idf) Using Tidy Data Principles. CRAN. https://cran.r-project.org/web/packages/tidytext/vignettes/tf_idf.html
* Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., Kaiser, Ł. ukasz, & Polosukhin, I. (2017). Attention is All you Need. Advances in Neural Information Processing Systems, 30. https://proceedings.neurips.cc/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html
* Vries, A. de, & Ripley, B. D. (2024). ggdendro: Create Dendrograms and Tree Diagrams Using “ggplot2”. https://doi.org/10.32614/CRAN.package.ggdendro
* Wickham, H. (2016). ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York. https://ggplot2.tidyverse.org
* Wickham, H. (2023). stringr: Simple, Consistent Wrappers for Common String Operations. https://doi.org/10.32614/CRAN.package.stringr
* Wild, F. (2022). lsa: Latent Semantic Analysis. https://doi.org/10.32614/CRAN.package.lsa
* Wijffels, J., & Watanabe, K. (2023). word2vec: Distributed Representations of Words. https://doi.org/10.32614/CRAN.package.word2vec
* You, K., & Shung, D. (2022). Rdimtools: An R Package for Dimension Reduction and Intrinsic Dimension Estimation. Software Impacts, 14, 100414. https://doi.org/10.1016/j.simpa.2022.100414



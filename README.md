# Análise de Emissões de Gases de Efeito Estufa no Brasil

Este projeto faz parte de um curso da **Alura** sobre análise de dados utilizando a biblioteca **pandas** em Python. Nele, aplicamos técnicas de manipulação e visualização de dados para explorar as emissões de gases de efeito estufa no Brasil.

## Conteúdo do Projeto
Este projeto tem como objetivo analisar dados de emissões de gases de efeito estufa no Brasil, com base em dados extraídos do SEEG (Sistema de Estimativas de Emissões de Gases de Efeito Estufa). A análise busca identificar padrões de emissão, setores mais poluentes, variações ao longo dos anos e emissões per capita, proporcionando insights sobre as principais fontes de emissões e suas tendências.

## Tecnologias Utilizadas
- **Linguagem de Programação**: Python
- **Bibliotecas**:
  - `pandas`: Para manipulação e análise de dados.
  - `matplotlib` e `plotly`: Para criação de visualizações gráficas.
  - `numpy`: Para operações matemáticas auxiliares.
- **Ferramentas de Colaboração**: Jupyter Notebook

## Resultados e Insights
1. **Distribuição por Tipo de Gás**:
   - A análise revelou que o **CO2** é o maior contribuidor para as emissões totais de gases de efeito estufa, representando mais de 90% das emissões no período de 1970 a 2021.
   - Outros gases significativos incluem CH4 (metano) e N2O (óxido nitroso).

2. **Setores Mais Poluentes**:
   - O setor de **Mudança de Uso da Terra e Floresta** é o maior responsável pelas emissões de CO2.
   - O setor **Agropecuário** também apresenta emissões significativas, especialmente de CH4 e N2O.

3. **Variações ao Longo do Tempo**:
   - As emissões de gases de efeito estufa apresentaram flutuações ao longo das décadas, com picos associados a mudanças em setores econômicos e ambientais.

4. **Emissão Per Capita**:
   - Estados com baixa densidade populacional, mas com atividades intensivas em emissões, apresentam as maiores taxas de emissão per capita.
   - Visualizações gráficas destacaram estados como **Mato Grosso** e **Pará**.

## Como Executar

1. Link para download da base de dados https://cdn3.gnarususercontent.com.br/2927-pandas-selecao-agrupamento-dados/1-SEEG10_GERAL-BR_UF_2022.10.27-FINAL-SITE.xlsx
2. Link para download contendo os dados do censo de 2022 https://cdn3.gnarususercontent.com.br/2927-pandas-selecao-agrupamento-dados/POP2022_Municipios.xls
3. Clone este repositório.
4. Certifique-se de ter o Python e as bibliotecas instaladas.
5. Execute o notebook Jupyter para explorar e visualizar os dados.

    ```bash
    git clone https://github.com/seu_usuario/projeto_gases_estufa.git
    cd projeto_gases_estufa
    jupyter notebook projeto_gases_estufa.ipynb
    ```

## Sobre o Curso

Este projeto é uma parte do curso da Alura sobre **"Pandas: selecionando e agrupando dados"**. Aprenda a explorar e manipular dados com a biblioteca pandas, extraindo informações relevantes e criando tabelas e agrupamentos úteis. Desenvolva gráficos que destacam padrões e tendências, além de aplicar filtros avançados para análises detalhadas. Para mais informações sobre o curso, visite [Alura](https://www.alura.com.br).

# dados_python_alura
Análise de Salários em Tecnologia com Python

📈 Projeto de Análise de Dados: Salários em Tecnologia

Este projeto foi desenvolvido como parte da Imersão Dados com Python, oferecida pela Alura. O objetivo principal foi aplicar técnicas de análise e visualização para explorar um conjunto de dados sobre salários em diversas áreas da tecnologia com foco em dados.

Todo o projeto foi construído e documentado em um Jupyter Notebook, primeiramente no Google Colab, culminando na criação (no VS Code) de um dashboard interativo com Streamlit.

🔧 Ferramentas e Bibliotecas

Utilizei as seguintes bibliotecas Python:

Pandas: Para manipulação e análise dos dados.

Matplotlib e Seaborn: Para a criação de gráficos estáticos.

Plotly e Pycountry: Para a criação de visualizações interativas.

Streamlit: Para a construção do dashboard interativo.

📁 Estrutura do Projeto

1. Análise Exploratória de Dados (EDA)

Nesta etapa, o conjunto de dados foi carregado e explorado com os métodos do Pandas (.head(), .info(), .describe(), .shape, .value_counts()). As colunas foram renomeadas e alguns valores foram traduzidos para facilitar a análise.

2. Limpeza e Pré-processamento

A base de dados foi tratada para lidar com valores ausentes, utilizando df.dropna(). O tipo de dado da coluna 'ano' foi convertido de float64 para int64 para garantir a integridade dos dados.

3. Visualização e Insights

Vários gráficos foram criados de modo a extrair insights sobre os dados.

Gráficos Estáticos (Seaborn/Matplotlib): Análise da distribuição de salários por senioridade (barplot) e da distribuição geral dos salários (histograma e boxplot).

Gráficos Interativos (Plotly): Exploração da média salarial por senioridade (gráfico de barras interativo) e da proporção dos regimes de trabalho (gráfico de setores tradicional e 'rosca').

4. Dashboard Interativo com Streamlit

A fase final do projeto consistiu na criação de um dashboard completo e funcional.

Funcionalidades: Permite filtrar os dados por ano, senioridade, tipo de contrato e tamanho da empresa.

Métricas Principais: Exibe o salário médio, salário máximo, total de registros e o cargo mais frequente.

Visualizações Dinâmicas: Apresenta gráficos de barras (Top 10 Cargos), histograma de salários, gráfico de rosca (Tipos de Trabalho) e um mapa coroplético (Salário por País), todos atualizados com base nos filtros selecionados.

⚙️ Como Rodar o Dashboard

Clone este repositório.

Instale as bibliotecas necessárias: pip install streamlit pandas plotly pycountry.

Navegue até o diretório do projeto no terminal e execute o comando:
streamlit run app.py

⚠️ Nota de Instalação e Configuração

Como este é o meu primeiro projeto de ponta-a-ponta, durante o desenvolvimento, enfrentei desafios de permissão do terminal do VS Code (PowerShell) para a execução de scripts das bibliotecas. Se você também for iniciante e se deparar com um problema similar, o caminho é manter a calma. Para fazer funcionar, ajustei as autorizações do PowerShell pela interface de comando dele mesmo e não a interface de comando geral do Windows seguindo este tutorial:
https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.security/set-executionpolicy?view=powershell-7.5. 

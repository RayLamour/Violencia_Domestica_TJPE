# Violência Doméstica em Pernambuco (2020–2024)
Análise de dados dos processos judiciais relacionados à violência doméstica contra mulheres em Pernambuco, entre os anos de 2020 e 2024, com base nas informações públicas do TJPE (Tribunal de Justiça de Pernambuco) disponibilizadas pelo DataJud/CNJ.
________________________________________
## Objetivo
O projeto busca compreender a evolução dos casos de violência doméstica ao longo dos anos — especialmente durante e após o período da pandemia — e identificar padrões geográficos e temporais que possam contribuir para o debate sobre políticas públicas e acesso à justiça.
________________________________________
 ## Tecnologias Utilizadas
•	Python → Coleta, limpeza e normalização dos dados via API DataJud
•	Power BI → Visualizações interativas e painéis analíticos
•	Gama (Gamma App) → Criação de infográficos e visualizações finais para comunicação dos resultados
________________________________________
## Coleta de Dados
Os dados foram obtidos via API pública do CNJ (DataJud):
https://api-publica.datajud.cnj.jus.br
O filtro aplicado considerou:
•	Tribunal: TJPE
•	Grau: 1º grau
•	Assunto: Violência Doméstica Contra Mulher
•	Período: 2020 a 2024
Cada ano foi coletado separadamente, com os dados consolidados em um único DataFrame (df_final) e exportados para CSV.
________________________________________
## Análises Realizadas
•	Evolução temporal (2020–2024) dos casos
•	Distribuição geográfica por município
•	Top 3 municípios com mais registros (Recife, Olinda e Jaboatão dos Guararapes)
•	Indicadores gerais:
  	Total de processos
  	Quantidade de municípios com registros
    Linha do tempo dos casos
________________________________________
## Principais Insights
•	Mais de 46 mil processos em cinco anos
•	130 municípios com registros de casos
•	Região Metropolitana concentra mais de 60% das ações judiciais
•	Após o pico em 2022, houve queda nos registros — possivelmente refletindo ações de prevenção e políticas públicas
________________________________________
## Visualizações
•	Power BI: Dashboard interativo com indicadores e mapa de calor
•	Gama (Gamma App): Infográficos narrativos para redes sociais
________________________________________
## Autoria
Rayanna Monteiro
📍 Recife – PE
💻 Projeto de Análise de Dados | 2025

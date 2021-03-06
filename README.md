# Documentation "Unemployment in Germany during COVID-19"

The present documentation explains the concept for the problem-driven data visualization project “Unemployment in Germany during COVID-19”.

## Domain problem characterization
With the beginning of the corona pandemic in Germany, there was the strongest increase in unemployment between two quarters since reunification (IamExpat, 2020). This project investigates the effects of the corona pandemic on unemployment in Germany from a national, federal and industrial view. Thus, the visualizations are addressed to people that are interested in the economic effects of COVID-19 on unemployment. More specifically, this could be employees of a specific industry or region. The visualisations answer questions regarding labor market effects, government measures, industry effects and regional differences:

- At which point of the pandemic can be seen effects on the labour market?
- How did government measures regarding COVID-19 influence unemployment?
- Which industry is affected most by COVID-19 regarding unemployment?
- Is there a regional difference regarding the development of unemployment during COVID-19?

For this purpose, a secondary research approach was chosen. Various data sources from the Agentur für Arbeit were used which describe the absolute and relative (compared to the same month of the previous year) increase in unemployment and the sizes of the different industries in Germany.  These data may be used for non-commercial purposes [Source].

## Data / task abstraction

|             | Job market industries [1]   | Unemployment Germany [2]    | Unemployment region [3]     | COVID-19 Cases RKI [4]                     |
| ----------- | --------------------------- | --------------------------- | --------------------------- | ------------------------------------------ |
| Topic       | Industry size               | Unemployment                | Unemployment                | COVID-19                                   |
| Location    | Germany                     | Germany                     |  Germany - Federal          | Germany - Federal                          |
| Time frame <br> Interval | 01/2020 - 07/2020 <br> (monthly) | 01/2019 - 09/2020 <br> (monthly) | 03/2020 - 09/2020 <br> (monthly) | 01/2020 - 10/2020 <br> (daily) |
| Editing     | Industry clustering         | Industry clustering         | Estimation of missing values <br> Industry clustering| Summarized monthly|

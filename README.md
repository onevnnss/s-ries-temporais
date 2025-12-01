📊 Análise de Séries Temporais: Investimento, Inflação e Desemprego (EUA)

Este projeto investiga como choques em inflação e desemprego afetam a dinâmica do investimento agregado nos Estados Unidos, utilizando técnicas clássicas de séries temporais e modelos VAR.

O estudo segue uma abordagem econométrica completa, incluindo:

🔎 Etapas do projeto

- Coleta e preparação dos dados (FRED/St. Louis Fed)

- Análise exploratória com visualização das séries

- Testes de estacionariedade (ADF e KPSS)

- Modelagem VAR e seleção ótima de defasagens

- Causalidade de Granger

- Funções Impulso–Resposta (IRF)

- Decomposição da variância do erro de previsão (FEVD)

🧠 Principais achados

- O desemprego possui forte poder preditivo sobre a variação do investimento.

- A inflação, por outro lado, tem efeito marginal nas variações de curto prazo.

- As IRFs mostram que choques negativos no mercado de trabalho geram quedas imediatas e significativas no investimento.

- A FEVD indica que, embora o investimento seja amplamente autoexplicativo, choques no desemprego ganham importância conforme aumenta o horizonte de previsão.

📘 Tecnologias e bibliotecas

- Python (Pandas, NumPy, Statsmodels, Matplotlib)

- Jupyter / VSCode

- Modelos VAR, testes de raiz unitária, IRF, FEVD

🎯 Objetivo final

Fornecer um arcabouço empírico para entender a interação entre mercado de trabalho, inflação e investimento — contribuindo para discussões sobre política macroeconômica.
# penscomp

Objetivo
Criar um programa simples que raspa os dados das séries históricas de análise de conjuntura do Instituto de Pesquisa Econômica Aplicada (Ipea), armazena as informações como banco de dados histórico, e possibilita posterior cruzamento das informações.

Metodologia
O programa identifica a página html do Ipea que contém as bases de dados sobre Atividade Econômica, Emprego e Renda, Inflação, Setor Externo, Política Monetária, Finanças Públicas, Economia Mundial e Séries Históricas; localiza nos metadados as informações em formato xlsx (utilizando a variável split), limpa o que não é necessário e devolve os links para download já organizados. 

Resultado
O notebook pode ser acessado em: https://colab.research.google.com/drive/1O19KhTnRhheNs99u7EmBHS96tr3beqWz#scrollTo=EXHv8ooiZ9Uc

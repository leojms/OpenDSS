## OpenDSS

##### Descrição do projeto

Integração do software de estudo de sistemas elétricos de potência OpenDSS, com o Python, atráves da bilbioteca py-dss-interface e utilizando-se de Jupyter Notebooks.
A partir da simulação de dois alimentadores padrão IEEE presentes na base de dados do software (IEEE 13 bars e IEEE 34 bars), pôde ser implementado diversos cenários,
com sistemas fotovoltaicos em geração distribuída, em um dos nós de cada alimentador, sendo aumentados gradualmente.
A partir das simulações em regime diário, foram exportados os gráficos das variáveis do sistema fotovoltaico e gráficos de potência na subestação e perdas no circuito. 
Para o tratamento dos dados, além de recursos nativos do Python, foram utilizadas bibliotecas de análise de dados, como NumPy e Pandas e bibliotecas de visualização
de dados, como Bokeh, que exporta os gráficos, presentes nesse repositório em um arquivo HTML, que pode ser visto aqui também.

# DICIONÁRIO DE DADOS - AMES HOUSING DATASET

# VARIÁVEL ALVO
SalePrice: Preço de venda do imóvel em dólares.

# VARIÁVEIS PRINCIPAIS (QUALIDADE E ÁREA)
Overall Qual: Avaliação geral do material e acabamento (10 = Muito Excelente, 1 = Muito Pobre).
Overall Cond: Avaliação geral da condição (10 = Muito Excelente, 1 = Muito Pobre).
Gr Liv Area: Área habitável acima do nível do solo.
Total Bsmt SF: Área total do porão.
1st Flr SF: Área do primeiro andar.
Full Bath: Número de banheiros completos.
Garage Cars: Capacidade da garagem em número de carros.
Garage Area: Tamanho da garagem.

# VARIÁVEIS DE LOCALIZAÇÃO E IDADE
Neighborhood: Localização física dentro dos limites da cidade de Ames.
House Style: Estilo da habitação (Ex: 1Story, 2Story, 1.5Fin).
Year Built: Ano de construção original.
Year Remod/Add: Ano da remodelação (o mesmo que o ano de construção se não houve remodelação ou adição).
Yr Sold: Ano da venda.

# VARIÁVEIS DE ACABAMENTO E CONDIÇÃO
Exter Qual: Qualidade do material externo (Ex: Ex=Excelente, Gd=Bom, TA=Média).
Kitchen Qual: Qualidade da cozinha (Ex: Ex=Excelente, Gd=Bom, TA=Média).
Heating QC: Qualidade e condição do aquecimento (Ex: Ex=Excelente, Gd=Bom, TA=Média).
Fireplaces: Número de lareiras.
Fireplace Qu: Qualidade da lareira (Ex: Ex=Excelente, Gd=Bom, TA=Média).

# VARIÁVEIS DIVERSAS (USADAS NO TRATAMENTO DE NULOS)
Pool QC: Qualidade da piscina (NaN significa 'Sem piscina').
Fence: Qualidade da cerca (NaN significa 'Sem cerca').
Alley: Acesso ao beco (NaN significa 'Sem acesso ao beco').
Misc Feature: Outras características não cobertas em outras categorias (NaN significa 'Nenhuma').
Lot Frontage: Pés de rua conectados à propriedade. (Variável numérica com nulos).

# VARIÁVEIS DE PORÃO
Bsmt Qual: Altura do porão (Ex: Ex=Excelente, Gd=Bom, TA=Típico). (NaN significa 'Sem porão').
Bsmt Cond: Condição geral do porão. (NaN significa 'Sem porão').
# PREDICAO-VALORES-DE-IMOVEIS

O projeto foi desenvolvido utilizando linguagem Python no Jupyter Notebook. O python possui um série de bibliotecas que nos auxiliam na construção das análises e modelagem dos dados. Neste projeto, foram utilizadas as seguintes:

Pandas
Numpy
Seaborn
Matplotlib
Scikit-learn
LightGBM


O objetivo deste projeto é a predição de valores dos imóveis da cidade de São Paulo a partir de dados como metragem do imóvel, quantidade de quartos, banheiros e vagas de garagem.

Dados

A base de dados possui informações sobre:

Rua
Bairro
Cidade
Metragem
Quartos
Banheiros
Vagas de garagem
Valor do imóvel

Conclusões

Após o pré-processamento dos dados, foram criados modelos de Regressão Linear, Random Forest Regressor e LightGBM. O modelo Random Forest Regressor com validação cruzada e Grid Search se adequou melhor por ter a métrica r2 mais próxima de 1.

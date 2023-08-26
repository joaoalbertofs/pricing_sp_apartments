# São Paulo Apartment Pricing

## Predicting Apartment Prices in São Paulo

### Project Motivation:
This project is aimed at creating a predictive model for apartment prices in São Paulo. We seek to understand the key factors that influence apartment prices in different neighborhoods across the city. Our goal is to provide valuable insights for individuals, real estate professionals, and investors looking to buy or sell apartments in São Paulo.

### Data Description:
The dataset used for this project contains information about apartments in São Paulo. Here are the main columns in the dataset:

id: Unique identifier for each apartment. <br>
valor_total: Total price of the apartment.<br>
unit: Price per unit area.<br>
area_util: Usable area of the apartment.<br>
quartos: Number of bedrooms.<br>
vagas: Number of parking spaces.<br>
condominio: Condominium fee.<br>
suites: Number of suites.<br>
banheiros: Number of bathrooms.<br>
piscina: Indicates whether the apartment has a pool (1 for yes, 0 for no).<br>
academia: Indicates whether the apartment has a gym (1 for yes, 0 for no).<br>
quadra: Indicates whether the apartment has a sports court (1 for yes, 0 for no).<br>
endereco: Address of the apartment.<br>
link: Link to the apartment listing.<br>
bairro: Neighborhood of the apartment.<br>
media_bairro: Average apartment price in the neighborhood.<br>
qtd_dados_bairro: Number of data points in the neighborhood.<br>
media_idh: Average Human Development Index (IDH) in the neighborhood.<br>
media_gini: Average Gini Index in the neighborhood.<br>
expectativa_vida: Life expectancy in the neighborhood.<br>
renda_percapita: Per capita income in the neighborhood.<br>
estacao_prox: Nearest subway station.<br>
linha_prox: Subway line of the nearest station.<br>
dist: Distance to the nearest subway station (in meters).<br>
lat: Latitude of the apartment.<br>
lon: Longitude of the apartment.<br>


### Analysis / Modeling:

For modeling, we will use a Random Forest regression model. This choice is based on its ability to handle complex relationships between features and target variables, making it well-suited for predicting apartment prices in São Paulo using latitude and longitude coordinates, as well as other relevant features.

### Implementation:
To use the predictive model, input the following apartment details:
<br>
area: Usable area of the apartment (integer value).<br>
bedrooms: Number of bedrooms (integer value).<br>
parking_spaces: Number of parking spaces (integer value).<br>
condominium: Condominium fee (floating-point number).<br>
suites: Number of suites (integer value).<br>
bathrooms: Number of bathrooms (integer value).<br>
pool: Does it have a pool? (1 for yes, 0 for no, integer value).<br>
gym: Does it have a gym? (1 for yes, 0 for no, integer value).<br>
sports_court: Does it have a sports court? (1 for yes, 0 for no, integer value).<br>
cep: Enter the CEP (use separator, string value).<br>
The model will then predict the total value of the apartment based on these inputs.<br>

### Libraries Used:
pandas: A powerful data manipulation library for data analysis.
scikit-learn: A machine learning library for modeling and prediction.
geopy: A library for geocoding and working with location data.
folium: A library for creating interactive maps.
matplotlib: A plotting library for creating visualizations in Python.
seaborn: A data visualization library built on top of matplotlib, providing additional aesthetic and statistical features.
<br>
To install the required libraries, you can use the following command:

```
pip install pandas scikit-learn geopy folium matplotlib seaborn
```

### File Description:
Analysis.ipynb: Jupyter Notebook containing the code and analysis for the project.<br>
dados_wgs.xlsx: Excel spreadsheet containing raw data for apartment listings in São Paulo.


### Usage:
To replicate this analysis or make predictions using the provided model, please refer to the code and dataset available in this repository. The code provides a comprehensive understanding of the analysis process and how to use the model for predicting apartment prices.

Feel free to explore the code and dataset, and don't hesitate to reach out if you have any questions or need further assistance.

## Resolution

You can fin the study in this link: https://medium.com/@joaoalberto.sequeira/predicting-apartment-prices-in-s%C3%A3o-paulo-ac28aee14daf

Data source: https://www.kaggle.com/datasets/jlgrego/apartamentos-venda-na-cidade-de-sao-paulo-sp
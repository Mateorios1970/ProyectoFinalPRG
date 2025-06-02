# ProyectoFinalPRG

- Proyecto cuyo objetivo es realizar un análisis numérico del Dataset público de la NASA, 'PlanetaryInfo.csv', con la información general de mas de 6000 planetas conocidos. También se encuentra la implementación de 2 modelos de predicción numérica para buscar un analisis más profundo de los datos, además de una comparación con un diagrama de Bland-Altman y el coeficiente de Cohen-Kappa buscando determinar cual de los modelos es más efectivo para la predicción. 
- La carpeta se divide de la siguiente forma:
    - README.md: Explicación breve del proyecto
    - 01_exploracion.ipynb: Analisis general de los datos 
    - 02_preprocesado.ipynb: Prepara el Dataset para su analisis predictivo 
    - 03_modelo_1.ipynb: Aplicación de RandomForestRegressor
    - 04_modelo_2.ipynb: Aplicación de RandomizedSearchCV
    - 05_comparacion.ipynb: Se comparan ambos modelos predictivos
    - 06_dataset.csv: El Dataset siendo utilizado
    - Informe.pdf: Analisis y conclusiones obtenidas de este proceso.
 
- NOTA: El Archivo 06_dataset.csv, al ser tan grande y pesado tuvo que ser comprimido, por ende para el buen funcionamiento del codigo este archivo tiene que ser descomprimido 

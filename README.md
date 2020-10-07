Prueba técnica de mercado libre 
================

Notebooks de exploración de datos y modelamiento del campo de sold_quantities de mercado libre. Cada uno de los notebooks tiene comentarios sobre los procedimientos que se usaron y las mejoras que tienen cabida en cada uno. 

Una anotación importante es que es un primer approach a modelas el campo de sold_quantities, los modelos tienen mucho trabajo por delante, desde modificar y/o tener nuevos datos para modelarlo, hasta hacer una búsqueda de parámetros optimizados para los modelos que lo requieran.

Archivos del repositorio
-------------------
- ``Exploratory analysis.ipynb``
  Este análisis exploratorio revisa un poco las distribuciones de los descuentos que hay actualmente en mercado libre con los 100 productos más relevantes, se puede configurar la variable de offset para hacer el análisis con más productos, solo que conllevara un poco más de tiempo del script de obtener los items. 

- ``Model.ipynb``
  Este archivo contiene 3 modelos especificos para tratar de predecir las cantidades vendidas para cada item. Tiene un modelamiento básico que explora diferentes features y transformación de datos. 

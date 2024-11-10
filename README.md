Enunciado SPARK
Completa las celdas del notebook:

https://drive.google.com/file/d/1-boyqRGdLmqDKW_jK9sYFz0p39Wom7MI/view?usp=sharing

Los datos a utilizar son:

https://raw.githubusercontent.com/pratikbarjatya/spark-walmart-data-analysis-exercise/master/walmart_stock.csv

ENUNCIADO PYSparkML
Dado el siguente dataset:

https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv

Cuyas variables representan:

age: edad del beneficiario principal
sex: género del contratante del seguro, femenino, masculino
bmi: índice de masa corporal, que proporciona una comprensión del cuerpo, de los pesos que son relativamente altos o bajos en relación con la altura, índice objetivo de peso corporal (kg / m ^ 2) utilizando la relación entre la altura y el peso, idealmente entre 18,5 y 24,9.
children: número de hijos cubiertos por el seguro de salud / número de dependientes
smoker: si fuma o no
region: área de residencia del beneficiario en EE. UU., noreste, sureste, suroeste, noroeste.
charges: costos médicos individuales facturados por el seguro de salud.
 

1) Primera parte (6 puntos)

Utilizando la API de pandas de PySpark

import pyspark.pandas as ps

Realiza un EDA del dataset anterior.

 

2) Segunda parte (4 puntos)

Luego conviertelós a un DataFrame de Spark normal, realiza las conversiones necesarias para poder hacer machine learning (StringIndexer, StandardScaler, VectorAssembler...) y aplica un modelo de regresión lineal usando pyspark.ml

La variable objetivo a predecir sería charges.

# Machine learning con Python
## Regresión
### Regresión lineal
~~~python
# 1.- Cargar la librería
from sklearn.linear_model import LinearRegression
# 2.- Crear una instancia
reg = LinearRegression()
# 3.- Entrenar el modelo
reg.fit(X, y)
# 4.- Predicción
reg.predict([[1000], [3000]])
~~~

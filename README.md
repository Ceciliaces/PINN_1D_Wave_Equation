# PINN_1D_Wave_Equation
Recientemente se cuenta con una nueva herramienta para la resolución de ecuaciones diferenciales, las redes neuronales físicamente informadas (PINNs). Se diseño una PINN para resolver la ecuación de onda en una dimensión utilizando la librería DeepXDE, y se compararon sus resultados con los obtenidos por el método de diferencias finitas.

# PINN(s): Physics-Informed Neural Network(s) para la ecuación de onda en 1D
Implementamos las PINNs utilizando la biblioteca de funciones DeepXDE con backend de tensorflow para la resolución de la ecuación de onda. Los datos de entrenamiento utilizados en el segundo caso fueron generados sintéticamente de la solución por diferencias finitas de la ecuación de onda. 

## Solución
!https://github.com/Ceciliaces/PINN_1D_Wave_Equation/blob/main/Onda%201D%20DF%20No%20Homogeneo%20Caso%201.gif))


## Uso
Para correr el código de la PINN del caso 1, este se encuentra en <code> PINN caso 1.ipynb </code>. 

## Dependencias
El código se realizó utilizando <code> python 3.8.16 </code> y las siguientes paqueterías:

|Package                      |Version|
| :---: | :---: |
|numpy                        |1.24.3|
|matplotlib                   |3.7.1|
|tensorflow                   |2.13.0|

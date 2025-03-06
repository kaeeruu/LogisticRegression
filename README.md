# LogisticRegression
Para este proyecto se utilizó una base de datos obtenida de [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/464/superconductivty+data) que contiene 81 variables distintas sobre 21,263 materiales superconductores y otra variable de interés la cual es la temperatura crítica de cada uno de estos materiales. El objetivo de la base de datos es poder relacionar las variables con la temperatura crítica, la cual es una característica muy importante para la aplicación de materiales super conductores. Para los propósitos de trabajar con regresión logística y validación cruzada, se usan solamente 5 de las 81 variables:

- 'wtd_std_ThermalConductivity' Desviación Estándar Ponderada de la Conductividad Térmica.
- 'wtd_mean_Valence' Media Ponterada de la Valencia
- 'range_atomic_radius' Rango del Radio Atómico
- 'wtd_entropy_atomic_mass' Entropía Ponderada de la masa atómica
- 'number_of_elements' Número de elementos

Este proyecto contiene los siguientes documentos:

- [Reporte en formato ipynb](A2_1_Regresión_logística_y_validación_cruzada.ipynb)
- [Reporte en formato html](A2_1_Regresión_logística_y_validación_cruzada.html)
- [Base de Datos](train.csv)

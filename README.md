# Taller 2
## Aprendizaje de Máquina para el Análisis del Rendimiento de Ventas en Comercio Electrónico

En este análisis se utiliza el conjunto de datos Online Retail II, disponible en el repositorio de aprendizaje automático de la Universidad de California en Irvine (UCI Machine Learning Repository) https://archive.ics.uci.edu/ml/datasets/Online+Retail+II. Este conjunto de datos recopila todas las transacciones realizadas por un comercio electrónico con sede en el Reino Unido durante el período comprendido entre el 1 de diciembre de 2009 y el 9 de diciembre de 2011. La información registrada incluye detalles como el número de factura, el código y la descripción del producto, la cantidad comprada, la fecha de la transacción, el precio unitario, el código del cliente y el país desde el cual se realizó la compra.

Realizando el análisis exploratorio de datos tenemos que hay 1010532 registros en donde hay datos de diferentes tipos:

| # | Nombre Columna | Recuento No Nulo | Tipo de Dato | Descripción |
|---|----------------|------------------|--------------|-------------|
| 0 | Invoice | 1,010,532 | string | Número de factura/transacción |
| 1 | StockCode | 1,010,532 | string | Código del producto |
| 2 | Description | 1,010,532 | string | Descripción del producto |
| 3 | Quantity | 1,010,532 | int64 | Cantidad de unidades vendidas |
| 4 | InvoiceDate | 1,010,532 | datetime64[ns] | Fecha y hora de la transacción |
| 5 | Price | 1,010,532 | float64 | Precio unitario del producto |
| 6 | Customer ID | 1,010,532 | float64 | Identificador único del cliente |
| 7 | Country | 1,010,532 | string | País donde se realizó la compra |

Los siguientes gráficos nos muestran más detalle de estos datos.

![EDA1](https://github.com/user-attachments/assets/a0675dd5-c972-4875-b5f2-c3b717ff8d9a)

![TOP1](https://github.com/user-attachments/assets/9a9e3977-02d4-4acc-85be-273e6b3d3b41)

![TOP2](https://github.com/user-attachments/assets/89bc06c5-9a88-419a-989c-6aef8bb0364b)

![EDA2](https://github.com/user-attachments/assets/4f576a21-f5ad-4b8e-9535-cae969d4a1fb)

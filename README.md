# Convertidor Recibos PDF a CSV

Este script extrae las tablas de los recibos de haberes de TASA ubicados en la carpeta `.\Recibos`, los unifica y lo exporta en formato CSV.

El script extrae del nombre el año y mes correspondiente al período de liquidación, que debe tener el formato "AAAA-MM" (por ejemplo: `Recibo 2019-10.pdf`).

---

Utiliza **Tabula-Py** para extraer las tablas. Las medidas para delimitar el área de captura se obtienen midiendo las distancias desde los margenes superior e izquierdo del Recibo, medidas en 1/72 de pulgada.

También hace uso de **pandas**, **NumPy** para la manipulación de DataFrames.

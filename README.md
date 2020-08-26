# Convertidor Recibos PDF a CSV

Este script extrae las tablas de los recibos de haberes ubicados en la carpeta `.\Recibos`, los procesa, unifica y exporta en formato CSV.

El script extrae del nombre el año y mes correspondiente al período de liquidación, que debe tener el formato "AAAA-MM" (por ejemplo: `Recibo 2019-10.pdf`).

---

Utiliza **Tabula-Py** para extraer las tablas del PDF. 

Las medidas para delimitar el área de captura y las columnas se obtienen midiendo las distancias desde los margenes superior e izquierdo del Recibo, medidas en pulgadas, y afectandolo por un coeficiente de 72.

Más detalles en este [blog post](https://www.mmuelas.com/post/2019-11-13_extrayendo_tablas_de_un_pdf/).


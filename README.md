# Integración de datos

Cuadernos de Python de Juan José Zapata Valencia para el estudio de estadística descriptiva, muestreo, integración de datos, teoría de credibilidad y agrupación. Se conservan los nombres y las versiones descargadas de la carpeta original.

## Organización

- `clases/`: tendencia central, dispersión, muestreo, COSCO, integración multidimensional y teoría de credibilidad.
- `retos/reto-1/`: caracterización de variables aleatorias del caso de gimnasio.
- `retos/reto-2/`: distintas versiones del segundo reto.
- `retos/reto-3/`: integración y agrupación K-Medoids con datos de seguros de salud.
- `proyectos/gympulse/`: integración y credibilidad del caso GymPulse.
- `evaluaciones/`: parcial sobre credibilidad.

## Abrir y ejecutar

GitHub permite consultar los cuadernos. Para ejecutarlos, abre Google Colab, selecciona **Archivo → Abrir cuaderno → GitHub** y pega la dirección de este repositorio. También puedes descargar un `.ipynb` y subirlo a Colab.

La mayoría de los cuadernos montan Google Drive y usan la ruta `/content/drive/MyDrive/Integracion de datos/`. Conserva esa carpeta en tu Drive o ajusta las rutas del cuaderno a tu propia ubicación. Autoriza el montaje de Drive cuando Colab lo solicite y ejecuta las celdas en orden.

Los archivos Excel no se incluyen en este repositorio público. Según el cuaderno, se necesitan:

- `1. RiesgoOperacional_EVERGREEEN.xlsx`
- `3. Datos COSCO Shipping.xlsx`
- `5. Diabetes Árbol_Int_Mult.xlsx`
- `Reto_1_Clientes_Gimnasio.xlsx`
- `Base_de_Datos_GymPulse_Externa.xlsx`

`Reto3.ipynb` descarga el conjunto `teertha/ushealthinsurancedataset` mediante `kagglehub` y utiliza `scikit-learn-extra` para K-Medoids. Requiere conexión a Internet y un entorno compatible con esas bibliotecas.

## Dependencias

`requirements.txt` reúne las bibliotecas importadas por los cuadernos y el lector de Excel. En Colab puedes instalar las que falten. No se fijaron versiones porque el entorno original no estaba documentado; la compatibilidad de todas las dependencias no se ha comprobado. `google.colab` corresponde al entorno Colab y no se instala con este archivo.

## Conservación y verificación

Se preservaron el código y el texto de las 18 versiones. Las salidas guardadas, los contadores de ejecución y los metadatos de sesión se retiraron de las copias publicables. Los archivos originales de Drive no se modificaron.

Se comprobó que cada archivo es JSON de notebook v4 y que el contenido de las celdas coincide con el original. No se ejecutaron los análisis ni se corrigieron los ejercicios. Pueden requerir ajustes de rutas, variables o dependencias. Los nombres con números entre paréntesis se conservan como versiones; no se presume cuál es la entrega definitiva.

## Índice

- [clases/1.Tendencia central y dispersion.ipynb](clases/1.Tendencia%20central%20y%20dispersion.ipynb) — 13 celdas.
- [clases/3_Integración_Datos_Cosco (2).ipynb](clases/3_Integraci%C3%B3n_Datos_Cosco%20%282%29.ipynb) — 22 celdas.
- [clases/3_Integración_Datos_Cosco.ipynb](clases/3_Integraci%C3%B3n_Datos_Cosco.ipynb) — 23 celdas.
- [clases/4_integracionmultidimencional.ipynb](clases/4_integracionmultidimencional.ipynb) — 7 celdas.
- [proyectos/gympulse/Credibilidad_GymPulse.ipynb](proyectos/gympulse/Credibilidad_GymPulse.ipynb) — 16 celdas.
- [clases/integraciondatosmuestreo.ipynb](clases/integraciondatosmuestreo.ipynb) — 12 celdas.
- [proyectos/gympulse/JuanJoseZapata_GymPulse_Integrado.ipynb](proyectos/gympulse/JuanJoseZapata_GymPulse_Integrado.ipynb) — 51 celdas.
- [evaluaciones/Parcial1_JuanJoseZapata_Credibilidad_Explicada.ipynb](evaluaciones/Parcial1_JuanJoseZapata_Credibilidad_Explicada.ipynb) — 29 celdas.
- [retos/reto-1/RETO1_JuanJoseZapata_JuanitaPineda.ipynb](retos/reto-1/RETO1_JuanJoseZapata_JuanitaPineda.ipynb) — 14 celdas.
- [retos/reto-2/RETO2_JuanJoseZapata (1).ipynb](retos/reto-2/RETO2_JuanJoseZapata%20%281%29.ipynb) — 14 celdas.
- [retos/reto-2/RETO2_JuanJoseZapata (2).ipynb](retos/reto-2/RETO2_JuanJoseZapata%20%282%29.ipynb) — 33 celdas.
- [retos/reto-2/RETO2_JuanJoseZapata (3).ipynb](retos/reto-2/RETO2_JuanJoseZapata%20%283%29.ipynb) — 33 celdas.
- [retos/reto-2/RETO2_JuanJoseZapata(1).ipynb](retos/reto-2/RETO2_JuanJoseZapata%281%29.ipynb) — 33 celdas.
- [retos/reto-2/RETO2_JuanJoseZapata.ipynb](retos/reto-2/RETO2_JuanJoseZapata.ipynb) — 14 celdas.
- [retos/reto-2/RETO2_JuanJoseZapata_COMPLETADO.ipynb](retos/reto-2/RETO2_JuanJoseZapata_COMPLETADO.ipynb) — 29 celdas.
- [retos/reto-2/RETO2_JuanJoseZapata_METODO_CLASE.ipynb](retos/reto-2/RETO2_JuanJoseZapata_METODO_CLASE.ipynb) — 33 celdas.
- [retos/reto-3/Reto3.ipynb](retos/reto-3/Reto3.ipynb) — 3 celdas.
- [clases/Teoriadelacredibilidad.ipynb](clases/Teoriadelacredibilidad.ipynb) — 9 celdas.

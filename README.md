# Laboratorio 7 Spark MLlib

Avance correspondiente a las actividades 1 a 4 del Laboratorio 7: preparación de datos, análisis exploratorio, correlaciones y segmentación con KMeans.

## Integrantes

- Milton Polanco
- Osman de León

## Estructura

- `data/raw/`: bases de Personas y diccionarios oficiales de la ENEIC.
- `data/processed/`: conjuntos analíticos de 2025 y 2026 en formato Parquet.
- `notebooks/`: notebook principal ejecutado.
- `reporte/`: informe del avance en PDF y figuras.

## Ejecución

1. Crear un entorno con Python 3.11.
2. Instalar las dependencias con `pip install -r requirements.txt`.
3. Tener Java disponible y ejecutar `notebooks/avance_lab7.ipynb` de principio a fin.

El notebook descarga los archivos oficiales si no están en `data/raw/`. En Windows, Spark puede requerir `HADOOP_HOME` con `winutils.exe`; el notebook utiliza `.tools/hadoop` cuando esa carpeta está disponible.

## Fuente

Instituto Nacional de Estadística de Guatemala, Encuesta Nacional de Empleo e Ingresos Continua: https://www.ine.gob.gt/encuesta-nacional-de-empleo-e-ingresos/

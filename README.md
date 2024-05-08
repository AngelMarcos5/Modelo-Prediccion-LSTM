# Modelo de Predicción de la Generación Fotovoltaica usando Redes LSTM

Este repositorio contiene los códigos empleados en el desarrollo de un modelo de predicción de la generación fotovoltaica del Edificio SEGAI de la Universidad de La Laguna (ULL) para el Trabajo Fin de Máster titulado "Sistema de monitorización remota en Comunidades Energéticas" desarrollado por Ángel Marcos Trujillo Trujillo.

## Descripción de los Archivos

- **Datos_SEMS_PORTAL.ipynb**: Este notebook extrae los datos de generación y consumo del Edificio SEGAI desde la página de Goodwe para cada día y los guarda en una ruta predefinida.

- **Datos_meteorologicos.ipynb**: Este notebook automatiza la extracción de los datos meteorológicos de la estación de La Laguna desde la página web del Ministerio de Agricultura, Pesca y Alimentación (MAPA).

- **LSTM_MODEL_PART1.ipynb**: Este notebook se encarga de preparar y analizar los datos que posteriormente se utilizarán para crear y entrenar el modelo.

- **LSTM_MODEL_PART2.ipynb**: En este notebook se crea y entrena la Red LSTM, se realizan ajustes de hiperparámetros y pruebas, y se realizan predicciones para diferentes días con el mejor modelo y configuración.

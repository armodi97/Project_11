
# Proyecto de Machine Learning para Seguros: Sure Tomorrow

Este proyecto implementa diversas técnicas de machine learning para la compañía de seguros Sure Tomorrow, con el objetivo de resolver problemas relacionados con marketing, predicción de riesgos y protección de datos.

## Descripción del Proyecto

Sure Tomorrow busca ayuda para resolver cuatro tareas específicas con el uso de modelos de machine learning:

1. **Segmentación de Clientes:** Identificar clientes similares a un cliente objetivo, ayudando así a los agentes en sus estrategias de marketing.
2. **Predicción de Riesgos:** Calcular la probabilidad de que un nuevo cliente reciba una prestación del seguro, evaluando si un modelo predictivo puede superar el rendimiento de un modelo básico (dummy).
3. **Estimación de Prestaciones:** Utilizar un modelo de regresión lineal para predecir el número de prestaciones que podría recibir un nuevo cliente.
4. **Enmascaramiento de Datos:** Implementar un algoritmo de transformación de datos para proteger la información personal de los clientes sin reducir la calidad de los modelos de machine learning.

## Estructura del Proyecto

El notebook contiene las siguientes secciones:

1. **Preprocesamiento y Exploración de Datos:** Incluye la carga de datos, limpieza y exploración inicial para obtener insights preliminares.
2. **Implementación de Modelos de Machine Learning:** Modelos para la segmentación, predicción de riesgos y regresión, con evaluaciones de desempeño y comparación con modelos dummy.
3. **Enmascaramiento de Datos:** Desarrollo de técnicas de ofuscación de datos para proteger la privacidad sin afectar la precisión de los modelos.
4. **Evaluación y Resultados:** Métricas y visualizaciones que muestran el desempeño de cada modelo y el impacto del enmascaramiento en la calidad de las predicciones.

## Requisitos

Este proyecto utiliza las siguientes librerías de Python:

- `numpy`
- `pandas`
- `plotly`
- `seaborn`
- `scikit-learn`

Para instalar todas las dependencias, ejecuta:
```bash
pip install -r requirements.txt
```

## Ejecución

1. Asegúrate de tener todos los paquetes instalados.
2. Ejecuta el notebook completo para procesar los datos, entrenar los modelos y evaluar los resultados.
3. Analiza las métricas de cada modelo en función de su precisión y utilidad para Sure Tomorrow.

## Notas

El proyecto está diseñado como una prueba de concepto para Sure Tomorrow. No se enfoca en optimizar los modelos, sino en demostrar la viabilidad de cada tarea con ejemplos funcionales.

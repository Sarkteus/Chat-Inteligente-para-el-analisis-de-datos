# Chat-Inteligente-para-el-analisis-de-datos

Este proyecto implementa un asistente de análisis de datos basado en la version 1.5 de GEMINI (Google), especializado en el análisis de los resultados de las pruebas Saber en Colombia. Utiliza el modelo Gemini de Google para proporcionar análisis detallados y responder a consultas complejas sobre los datos educativos.

### Características Principales

### 1. Análisis Estadístico Avanzado
- Realiza análisis descriptivos e inferenciales de los datos de las pruebas Saber 11.
- Capacidad para comparar grupos y detectar diferencias significativas.

### 2. Visualización de Datos
- Genera visualizaciones  para una mejor comprensión de los datos.
- Incluye histogramas, gráficos de dispersión y gráficos de tendencias temporales.
- Genera tablas.

### 3. Detección de Anomalías
- Identifica patrones inusuales y valores atípicos en los resultados de las pruebas.
- Proporciona interpretaciones contextuales de las anomalías detectadas.

### 4. Análisis Predictivo
- Utiliza modelos de regresión lineal para predecir puntajes globales.
- Evalúa la confiabilidad de las predicciones y explica las limitaciones del modelo.

### 5. Análisis de Tendencias
- Examina la evolución de los puntajes a lo largo del tiempo.
- Identifica tendencias y patrones en diferentes períodos y regiones.

### 6. Interpretación Contextual
- Proporciona explicaciones detalladas y accesibles de los resultados estadísticos.
- Ofrece insights sobre factores que pueden influir en el rendimiento académico.

### 7. Procesamiento de Lenguaje Natural
- Interpreta consultas en lenguaje natural y genera respuestas coherentes y relevantes.
- Adapta el nivel de complejidad de las explicaciones según el contexto de la pregunta.


## Tecnologías Utilizadas
- Python
- Pandas para manipulación de datos
- Scikit-learn para modelos predictivos
- Matplotlib y Seaborn para visualizaciones
- Google Generative AI (Gemini) para procesamiento de lenguaje natural e IA

## Cómo Usar
1. Asegúrate de tener todas las dependencias instaladas.
2. Configura tu clave API de Google Generative AI.
3. Carga tus datos de las pruebas Saber 11 en formato CSV.
4. Inicia el asistente y comienza a hacer preguntas sobre los datos.

## Ejemplos de Consultas
- "¿Cuál es la distribución de los puntajes globales?"
- "Compara el rendimiento en matemáticas entre zonas urbanas y rurales."
- "¿Cómo ha evolucionado el puntaje promedio en los últimos 5 años?"
- "Identifica los colegios con mejor desempeño en lectura crítica."

## Pasos a seguir.
- Integración con la API de las pruebas saber 11 para actualizar y ampliar la información.
- LIntegracion con la web
- El asistente no tiene acceso a información externa más allá de los datos proporcionados.

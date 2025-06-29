
El objetivo principal es identificar los modelos que mejor se ajusten a los datos para predecir el diagnóstico de tumores (benignos o malignos), utilizando un conjunto de datos de características visuales de los tumores (máximos, mínimos y medias). 

Origen del dataset: Wolberg, W., Mangasarian, O., Street, N., & Street, W. (1993). Breast Cancer Wisconsin (Diagnostic) [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.

### Contenido

- **Análisis Exploratorio de Datos (EDA)**: Incluye la visualización de distribuciones y la identificación de correlaciones.
- **Reducción de Dimensionalidad**: Eliminación de variables con baja correlación respecto a la variable objetivo y aquellas altamente correlacionadas entre si que solo añaden complejidad al modelo.
- **Transformación de Datos**: Normalización y sobre muestreo de datos para mejorar el rendimiento de algunos modelos.
- **Optimización de Hiperparámetros**: Uso de búsqueda bayesiana para encontrar la mejor combinación de hiperparámetros si el modelo lo precisa.
- **Evaluación de Modelos**: Uso de métricas de evaluación como la precisión (accuracy), la matriz de confusión y la curva ROC para comparar el rendimiento de los modelos.

### Instalación

```bash
git clone https://github.com/Rubenvalrom/Analisis-de-modelos-predictivos-contra-el-cancer-de-mama.git

cd Analisis-de-modelos-predictivos-contra-el-cancer-de-mama

python -m venv env
source env/bin/activate  # En Windows: .\env\Scripts\activate

pip install -r requirements.txt
```

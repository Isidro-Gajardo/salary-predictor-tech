# Predictor de Salarios Tech 2025

Análisis de Machine Learning sobre los factores que determinan 
el salario de desarrolladores, basado en la encuesta Stack Overflow 
Developer Survey 2025 (49.191 respuestas, 177 países).

## Hallazgos principales

- La **experiencia laboral** es el factor #1 en el salario (importancia: 29%)
- Los **años programando** son el factor #2 (importancia: 21%)
- **Usar IA** es el factor #3, más importante que el nivel educativo
- Un junior que usa IA gana ~$8.000 USD/año más que uno que no la usa
- EE.UU. lidera salarios con $150K mediano; Chile puede acceder vía trabajo remoto

## Tecnologías usadas

- Python, pandas, numpy
- matplotlib, seaborn
- scikit-learn (RandomForestRegressor)
- Jupyter Notebooks

## Estructura del proyecto



- salary-predictor-tech/
-   data/                          # Dataset Stack Overflow 2025
-   notebooks/
-     01_exploracion.ipynb      # Análisis completo + modelo ML
-   requirements.txt
-   README.md

## Dataset

Descarga el dataset desde Kaggle:
https://www.kaggle.com/datasets/aliaslam25/stack-overflow-developer-survey-2025

Coloca el archivo `survey_results_public.csv` dentro de la carpeta `data/`

## Cómo ejecutar

```bash
pip install -r requirements.txt
jupyter notebook
```

Abrir `notebooks/01_exploracion.ipynb`

## Resultados del modelo

| Perfil | Salario predicho |
|--------|-----------------|
| Junior sin IA (2 años) | $49,834 USD/año |
| Junior con IA (2 años) | $58,204 USD/año |
| Senior Python + IA (10 años) | $81,779 USD/año |
| Expert Rust + Go (15 años) | $144,692 USD/año |

**Autor:** Isidro Gajardo — Ingeniero en Informática  
**Datos:** Stack Overflow Developer Survey 2025

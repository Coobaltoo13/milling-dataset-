# milling-dataset-
Dataset
# Fusión Multimodal de Vibración y Corriente para Predicción de Vida Útil en Fresado

## Descripción

Este proyecto investiga si combinar señales de vibración y corriente eléctrica mejora la predicción de la vida útil de herramientas de fresado, en comparación con usar una sola señal.

Se comparan cuatro enfoques:
1. Solo vibración
2. Solo corriente
3. Concatenación simple de ambas
4. Fusión con MLP + LSTM (arquitectura propuesta)

## Objetivo

Determinar si la integración de múltiples sensores mediante deep learning mejora la precisión en la predicción del desgaste de herramientas, contribuyendo a una producción más sostenible.

## Dataset

**Milling Process Dataset** (Figshare)
- 969 ciclos de fresado con 14 herramientas
- 8 canales de vibración + 12 de corriente
- Etiqueta: `CycleToFailureNormalized` (vida útil normalizada)

🔗 [Descargar dataset](https://doi.org/10.6084/m9.figshare.28589216)

## Tecnologías

- Python 3.10+
- Pandas, NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn
- Google Colab

## Estructura
milling-tool-life-fusion/
├── data/raw/ # Dataset original
├── notebooks/ # Jupyter notebooks
├── results/figures/ # Gráficas
├── requirements.txt
└── README.md


## Cómo Ejecutar

1. Clona el repositorio:
bash
git clone https://github.com/Coobaltoo13/milling-tool-life-fusion.git
Instala dependencias:

bash
pip install -r requirements.txt
Abre el notebook en Colab o Jupyter.

Resultados (en progreso)
Modelo	RMSE	MAE	R²
Solo vibración	-	-	-
Solo corriente	-	-	-
Concatenación simple	-	-	-
MLP + LSTM	-	-	-
 Autora
Andrea Cobos Cervantes

Estudiante de Biotecnológia Genomica

Interesada en Data Science y Producción Sostenible

📄 Licencia
MIT License. Ver LICENSE para más detalles.

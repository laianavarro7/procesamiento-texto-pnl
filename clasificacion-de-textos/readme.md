# **Clasificación de textos con PLN**

En este proyecto se aplican técnicas de Procesamiento del Lenguaje Natural (PLN) para analizar y clasificar textos utilizando modelos estadísticos y de aprendizaje automático. Se realizan etapas de preprocesamiento, vectorización y entrenamiento de modelos para evaluar su capacidad de clasificación y comparar resultados.

Se desarrollan dos proyectos representativos del Procesamiento del Lenguaje Natural:

1. El primero se centra en el **análisis de sentimientos**, comparando un enfoque clásico basado en la extracción de características (TF-IDF + Naive Bayes) frente a un modelo preentrenado basado en **Transformers (BERT)**, con el objetivo de comparar su desempeño en un contexto real.

2. El segundo proyecto aborda el procesamiento y la estructuración de textos clínicos, aplicando técnicas de limpieza, tokenización y reconocimiento de entidades nombradas (NER) para analizar patrones, visualizar la información y transformar texto no estructurado en datos analizables.

**Objetivo:** aplicar técnicas de PLN para clasificar textos automáticamente, comparar distintos enfoques y estructurar información textual mediante extracción de entidades

**Tecnologías usadas:**
- Python
- Scikit-learn
- NLTK / spaCy
- TF-IDF / Bag of Words
- Transformers (BERT)
- spaCy (NER)

**Resultados:**

**Proyecto 1: Análisis de sentimientos**

**Modelo 1: Enfoque clásico (TF-IDF + Naive Bayes)**

- Accuracy: 0.84
- F1 (macro): 0.84
- ROC-AUC: 0.92

El modelo clásico ofrece un rendimiento sólido y equilibrado entre clases, con métricas similares en precisión y recall para reseñas positivas y negativas. Destaca por su simplicidad, eficiencia computacional y buena capacidad de generalización.

**Modelo 2: Transformers (BERT)**

- Accuracy: 0.82
- F1 (macro): 0.82
- ROC-AUC: 0.93

El modelo basado en Transformers muestra una mayor capacidad de separación probabilística (ROC-AUC superior), aunque con una ligera reducción en accuracy respecto al enfoque clásico. Se observa mayor recall en la clase negativa y mayor precisión en la clase positiva.

**Comparación entre modelos:**
- El modelo clásico (TF-IDF + NB) obtiene mejor accuracy global.
- BERT presenta mejor ROC-AUC, indicando mayor capacidad de discriminación probabilística.
- El enfoque clásico demuestra que modelos simples pueden ser altamente competitivos en tareas de clasificación de texto.

**Proyecto 2: Procesamiento de textos clínicos (NER)**

Se aplicó reconocimiento de entidades nombradas (NER) con spaCy para extraer información estructurada a partir de texto clínico no estructurado.

**Resultados:**
- Identificación automática de entidades relevantes.
- Transformación del texto libre en datos estructurados.
- Análisis y visualización de patrones frecuentes.

Este enfoque demuestra la capacidad de convertir texto clínico en información analizable, facilitando su integración en futuros modelos predicitivos o sistemas de apoyo a la decisión.
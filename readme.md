# Proyectos de PLN

Este repositorio agrupa varios trabajos realizados en el ámbito del *Procesamiento de Lenguaje Natural* (PLN). La idea es compartir los notebooks y análisis correspondientes a cada asignatura o práctica, de modo que el repositorio crezca con el tiempo conforme se añadan nuevos proyectos.

> En este momento el repositorio contiene un proyecto completo de clasificación de texto y análisis de entidades, pero se irán incorporando nuevas tareas en el futuro. Cada proyecto reside en su propio notebook y dispone de sus datos específicos.

## Estructura general

- `Clasificación_de_textos_con_PLN.ipynb`: notebook inicial con dos subproyectos (análisis de sentimientos y NER clínico).
- `readme.md`: este archivo de presentación general del repositorio.
- `data/` y `data_clinical/`: directorios usados por el notebook anterior para almacenar los datos descargados.

A medida que se añadan más proyectos, se crearán nuevos notebooks y carpetas asociadas.

## Proyectos actuales

### 1. Clasificación de sentimientos y NER clínico

El único proyecto incluido de momento combina dos tareas:

- **Análisis de sentimientos (IMDB)**: comparación entre un enfoque clásico (TF‑IDF + Naive Bayes) y un modelo basado en Transformers (BERT) para clasificar reseñas de películas.
- **Procesamiento de notas clínicas**: limpieza de textos médicos y extracción de entidades nombradas (NER) usando un modelo de spaCy.

Los resultados y conclusiones de este trabajo aparecen detallados en el notebook `Clasificación_de_textos_con_PLN.ipynb`.

## Tecnologías utilizadas

El repositorio hace uso de herramientas estándar de PLN en Python:

- `scikit-learn`, `nltk`, `pandas`, `matplotlib`
- `spaCy` (con `en_core_web_sm`)
- transformers de 🤗 Hugging Face

También se utilizan notebooks Jupyter como formato principal para documentar los experimentos.

## Cómo empezar

1. Clona el repositorio.
2. Activa un entorno de Python con las dependencias requeridas. Un `requirements.txt` se podrá añadir con el tiempo o simplemente ejecutar las celdas iniciales de cada notebook, que instalan los paquetes necesarios.
3. Abre el notebook del proyecto que desees explorar (por ejemplo, `Clasificación_de_textos_con_PLN.ipynb`).
4. Ejecuta las celdas en orden; los datos se descargan automáticamente en los directorios correspondientes.

> Es recomendable tener conexión a internet para permitir la descarga de datasets y modelos preentrenados.

## Contribuciones futuras

- Se irán añadiendo nuevos notebooks con otros ejercicios de PLN realizados.
- Posiblemente se incluirán scripts auxiliares, conjuntos de datos y documentación adicional conforme el repositorio crezca.

## Licencia y contacto

Proyectos de carácter académico. Para dudas o colaboraciones, contactar al autor a través de su perfil en GitHub cuando el repositorio esté publicado.

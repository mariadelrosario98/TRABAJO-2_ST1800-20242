# TRABAJO-2_ST1800-20242
# Integrantes:
Mariel Viviana Sánchez

Laura Riveros

Maria del Rosario Castro Mantilla

# Punto 1
# Procesamiento de Lenguaje Natural
Se realizó el procesamiento de lenguaje natural con tres diferentes herramientas, estas fueron: NLTK, TweetTokenizer y Gensim.

## Gensim

**Descripción**: Gensim es una biblioteca especializada en el modelado de tópicos y la representación de documentos, particularmente útil para tareas de modelado semántico y aprendizaje no supervisado.

- **Características**:
  - Modelado de Tópicos (LDA, LSI, etc.)
  - Representación de documentos mediante Word2Vec
  - Optimizada para trabajar con grandes volúmenes de texto
  - Eficiente en el uso de memoria

## TweetTokenizer

**Descripción**: TweetTokenizer es parte de NLTK y se especializa en la tokenización de texto en tweets. Tiene en cuenta las peculiaridades del lenguaje en Twitter, como los hashtags, menciones y emoticonos.

- **Características**:
  - Tokenización específica para Twitter
  - Manejo adecuado de hashtags, menciones y emoticonos
  - Ideal para el análisis de datos de redes sociales

## NLTK (Natural Language Toolkit)

**Descripción**: NLTK es una biblioteca muy completa y versátil para el procesamiento del lenguaje natural en Python. Ofrece herramientas para tokenización, análisis gramatical, análisis de sentimientos, y más.

- **Características**:
  - Amplia gama de herramientas para diversas tareas de NLP
  - Soporte para múltiples lenguajes
  - Acceso a una variedad de corpus y recursos lingüísticos
  - Buena documentación y tutoriales disponibles

## Conclusión

La elección entre estas bibliotecas depende de las necesidades específicas de tu proyecto. Gensim es ideal para análisis semántico y modelado de tópicos, TweetTokenizer es perfecto para datos de Twitter, y NLTK es una solución integral para diversas tareas de procesamiento de lenguaje natural.

# Punto 2
Se eligió el modelo de Hugging Face y almacenamiento en Chroma. Se realizaron tres consultas dentro de los embeddings

# Punto 3
Se realizó un análisis inicial de cuántos tópicos únicos había, encontrando que eran 12. Se realiza el entrenamiento de un modelo para encontrar el K-óptimo

# Punto 4
Se realiza el análisis de sentimientos de los tweets y se entrena un modelo de predicción, con la siguiente ROC:
<img width="370" alt="image" src="https://github.com/user-attachments/assets/ee7f46d0-b5e5-4a53-b2c0-ae1325ec1c46">

# Punto 5
Se realizaron las consultas en el punto 2


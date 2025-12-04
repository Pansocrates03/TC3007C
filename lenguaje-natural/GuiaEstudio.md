# Guía de Estudio de examen de término medio

1. Definición y objetivo de NLP. NLU y NLG. Eras del NLP. 

**Definición y Objetivo de NLP**: Natural Language Processing es un campo informatico que combina informática, linguística, I.A, matemáticas y estadística. SU proposito es facilitar la interacicón entre computadoras

2. Definición de lenguaje natural. Modelo de lenguaje natural. Etiquetado POS. 

3. Análisis morfológico y procesamiento de texto: morfemas, tokenización, lematización, stemming (raíz de palabras) y stopwords. Manejo de estas técnicas con la librería NLTK (código) 

4. Modelos (estadísticos) de lenguaje:

    1. N-gramas, modelo de bi-grama y trigrama, suposición de Markov. Evaluación intrínseca y extrínseca de modelos de lenguaje (perplejidad) 

    2. Manejo de escasez de datos: suavizado de Laplace, backoff (retroceso), interpolación, suavizado Kneser-Ney

5. Representación de texto: BoW (Bag Of Words), TF-IDF, One-hot Encoding. Implementación práctica, por ejemplo: CountVectorizer() o BoW from scratch

**STEMMING:** Es una técnica que reduce palabras a su raíz o forma base, eliminando afijos como terminacionces verbales o plurales.

Este proceso ayuda a los sistema de NLP a entender que las palabras como worked, works, y worker están relacionada con `works`, sin embargo también puede generar ambiguedad, ya que `workers` y `works` se reducen a una misma raíz, aunque tienen significados diferentes. (personas vs. acciones u objetos)

La raíz obtenida no siempre es una palabra válida, por ejemplo, `traditional` puede convertirse en `tradit`

6. Clasificadores clásicos de texto: Naive Bayes, Regresión Logística (sigmoide o función logística, aprendizaje, pérdida de entropía cruzada o cross-entropy, SGD-descenso de gradiente, entrenamiento por mini-batches, regularización) y Regresión Softmax

7. Introducción a representación de significado y embeddings de palabras: Semántica léxica, Semántica vectorial, Palabras y vectores, coseno como medida de similitud, ponderación de palabras mediante TF-IDF. 

8. Introducción a PyTorch
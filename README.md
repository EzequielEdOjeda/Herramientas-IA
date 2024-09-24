# Repositorio de Inteligencia Artificial, Prompt Engineering, y APIs Públicas

Este repositorio recopila temas relacionados con **Inteligencia Artificial** y **Prompt Engineering**, además de una lista de **APIs Públicas** útiles para desarrolladores.

# Librerías y Frameworks de Python

Una lista de las principales librerías y frameworks de Python, junto con sus usos más comunes:

| **Librería/Framework**    | **Uso**                                                     |
| ------------------------- | ----------------------------------------------------------- |
| **Kivy**                  | Aplicaciones móviles y multitáctiles.                       |
| **Tkinter**               | Aplicaciones de escritorio con interfaces gráficas.          |
| **Gradio**                | Interfaces interactivas para modelos de machine learning.    |
| **Django**                | Desarrollo de aplicaciones web completas y escalables.       |
| **Flask**                 | Microframework para desarrollo web.                         |
| **PyQt/PySide**           | Aplicaciones de escritorio con interfaces gráficas.          |
| **Pygame**                | Desarrollo de videojuegos.                                  |
| **FastAPI**               | Desarrollo de APIs web rápidas y modernas.                  |
| **Tornado**               | Servidor web asíncrono y framework de redes.                |
| **Streamlit**             | Aplicaciones web interactivas para ciencia de datos.         |
| **Pytest**                | Pruebas y testing en Python.                                |
| **Beautiful Soup**        | Análisis y scraping de HTML y XML.                          |
| **Requests**              | Realización de solicitudes HTTP.                            |
| **Pandas**                | Análisis y manipulación de datos.                           |
| **NumPy**                 | Computación numérica.                                       |
| **Matplotlib**            | Visualización de datos.                                     |
| **Scikit-learn**          | Aprendizaje automático.                                     |
| **TensorFlow/PyTorch**    | Frameworks de Deep Learning.                                |
| **SQLAlchemy**            | Mapeo objeto-relacional (ORM).                              |
| **Celery**                | Gestión de tareas asíncronas.                               |

### ¿Qué es Machine Learning?

El **Machine Learning** (ML) es una rama de la inteligencia artificial que permite a las máquinas aprender de los datos y mejorar su rendimiento sin ser programadas explícitamente para ello. A través de ML, es posible realizar tareas como **clasificación**, **regresión** y **detección de anomalías**.

### Tareas Comunes en Machine Learning
- **Clasificación**: Asignar una etiqueta o categoría a un conjunto de datos (por ejemplo, identificar si un correo es spam o no).
- **Regresión**: Predecir valores continuos (por ejemplo, estimar el precio de una casa).
- **Detección de anomalías**: Identificar datos inusuales o fuera de lo común (por ejemplo, fraudes en transacciones).

### ¿Qué son los Features y Labels?

- **Features** (características): Son los atributos o variables que describen los datos de entrada. Por ejemplo, en el caso de predecir el precio de una casa, los features podrían ser el tamaño de la casa, el número de habitaciones, etc.
- **Labels** o **Target** (etiqueta/objetivo): Es el valor que se desea predecir. En un problema de clasificación, la label sería la categoría (spam/no spam). En un problema de regresión, la label es el valor continuo que se intenta predecir (por ejemplo, el precio de una casa).

### ¿Qué es un Modelo de Machine Learning?

Un **modelo de ML** se construye al combinar:
- Un **algoritmo de Machine Learning**
- Los **datos de entrenamiento**
- El proceso de **entrenamiento** para ajustar los parámetros
- Los **parámetros** que se ajustan durante el entrenamiento

Esto da como resultado un modelo que puede hacer predicciones sobre nuevos datos.

### ¿Cómo Aprende un Algoritmo de Machine Learning?

- **Aprendizaje supervisado**: El algoritmo aprende a partir de datos etiquetados, donde ya se conoce el resultado (la label o target).
- **Aprendizaje no supervisado**: El algoritmo encuentra patrones o relaciones en datos no etiquetados.

### Proceso de Machine Learning

1. **Obtener datos** (dataset): Recolectar los datos necesarios.
2. **Preparar los datos**: Limpiar, normalizar y transformar los datos para usarlos en el modelo.
3. **Separar datos de entrenamiento y prueba**: Dividir los datos en dos conjuntos: uno para entrenar el modelo y otro para evaluarlo.
4. **Entrenar el modelo**: Usar los datos de entrenamiento para ajustar los parámetros del modelo.
5. **Evaluar el modelo**: Probar el modelo con los datos de prueba para medir su precisión.
6. **Utilizar el modelo**: Una vez evaluado, el modelo se usa para hacer predicciones sobre nuevos datos.

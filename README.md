Reconocimiento de Caracteres Manuscritos con CNN y TensorFlow.js
Autor: Omar Alberto Herrera Garcia Institución: Instituto Tecnológico de Ciudad Juárez

Descripción del Proyecto
Este repositorio contiene el código fuente y los recursos de un sistema de Inteligencia Artificial diseñado para reconocer letras manuscritas del alfabeto latino (A-Z). El proyecto fue desarrollado como parte de una residencia profesional y se centra en la implementación de una Red Neuronal Convolucional (CNN) optimizada.

El sistema tiene dos partes:

Entrenamiento (Python): Un modelo de Deep Learning entrenado con el conjunto de datos EMNIST Letters, logrando una precisión del 94.25%.

Aplicación Web: Una interfaz interactiva que utiliza TensorFlow.js para ejecutar el modelo directamente en el navegador, permitiendo al usuario dibujar una letra y recibir una predicción en tiempo real.

Características Técnicas
Modelo: CNN secuencial con activación Swish y optimizador AdamW.

Dataset: EMNIST Letters (26 clases).

Web: Implementación "Client-side" (sin servidores externos), garantizando privacidad y baja latencia.

Rendimiento: Supera el rendimiento base (85.15%) y modelos estándar (>90%) reportados en la literatura.

Estructura de Archivos
/model: Archivos del modelo entrenado y convertido para la web.

/web: Código fuente de la página web (HTML, CSS, JS).

/notebooks: Cuadernos de Jupyter con el proceso de entrenamiento paso a paso.

Cómo Usar
Para probar la aplicación web:

1-Descarga o clona este repositorio.

Abre la carpeta web.

Ejecuta el archivo index.html en tu navegador (se recomienda usar un servidor local simple si el navegador bloquea la carga del modelo por seguridad).

2-Entra a este enlace para acceder a la aplicación web: https://herreraomar12321-arch.github.io/Lector-de-Letras-IA/

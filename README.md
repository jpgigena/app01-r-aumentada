# **Proyecto de Realidad Aumentada con Python**

## Introducción

La Realidad Aumentada representa una de las tecnologías más prometedoras en la intersección entre el mundo físico y digital, permitiendo superponer información virtual sobre el entorno real en tiempo real. En los últimos años, los avances en visión por computadora, particularmente en modelos de detección de objetos como YOLO (You Only Look Once), han revolucionado la capacidad de los sistemas para identificar y clasificar objetos con precisión y velocidad. Paralelamente, los modelos de lenguaje e inteligencia artificial como Mistral han alcanzado niveles de comprensión y generación de texto que permiten contextualizar información de manera natural y adaptativa.

Este proyecto busca la convergencia de estas tres tecnologías —Realidad Aumentada, detección de objetos con YOLO a través de OpenCV, y lenguaje de procesamiento natural con Mistral— para crear una aplicación que no solo detecta objetos en tiempo real, sino que también proporciona información relevante, contextual y útil sobre dichos objetos al usuario. Esta combinación representa un paso significativo hacia sistemas de asistencia cognitiva más intuitivos y accesibles que pueden transformar la manera en que interactuamos con nuestro entorno cotidiano.

## Justificación

La implementación de este proyecto se justifica por múltiples razones de relevancia tecnológica, social y educativa:

1. **Accesibilidad al conocimiento:** En la era de la información, el acceso inmediato a datos relevantes sobre objetos en nuestro entorno puede democratizar el conocimiento y reducir la brecha informativa. Personas con limitaciones de acceso a recursos educativos tradicionales podrían beneficiarse significativamente.  
2. **Asistencia cognitiva:** La aplicación puede servir como herramienta de asistencia para personas con dificultades para reconocer o recordar información sobre objetos, incluyendo adultos mayores o personas con deterioro cognitivo leve.  
3. **Potencial educativo:** En entornos educativos, la aplicación puede transformar cualquier objeto en una oportunidad de aprendizaje interactivo, fomentando la curiosidad y el aprendizaje contextual en estudiantes de todas las edades.  
4. **Innovación tecnológica integrada:** El proyecto representa un ejemplo práctico de integración de tecnologías de vanguardia (RA, visión por computadora e IA generativa) en una solución cohesiva y orientada al usuario, demostrando las posibilidades de la convergencia tecnológica.  
5. **Aplicaciones en Múltiples dominios:** La versatilidad de la solución permite su adaptación a diversos contextos como turismo (información sobre monumentos), mantenimiento industrial (datos técnicos de maquinaria), comercio (información de productos) o asistencia en tareas domésticas.  
6. **Desarrollo de habilidades interdisciplinarias:** El proyecto fomenta la adquisición de competencias en campos diversos como programación, visión por computadora, procesamiento de lenguaje natural y diseño de interfaces, promoviendo un enfoque holístico del desarrollo tecnológico.  
7. **Base para futuras investigaciones:** El sistema propuesto puede servir como plataforma experimental para evaluar la efectividad de diferentes modelos de IA en contextos de asistencia en tiempo real, contribuyendo al avance científico en este campo emergente.

Esta aplicación responde a la creciente necesidad de sistemas que no solo detectan objetos, sino que también proporcionan un contexto significativo sobre ellos, creando puentes entre el mundo físico y la riqueza de información disponible digitalmente, de una manera intuitiva y accesible para usuarios de diversos perfiles y necesidades.

## Requisitos del proyecto

### Requisitos de hardware

* Cámara web de alta resolución (mínimo 720p, recomendado 1080p)  
* Computadora con tarjeta gráfica compatible con CUDA (para acelerar el procesamiento de YOLO)  
* Memoria RAM mínima: 8GB (recomendado 16GB)  
* Espacio de almacenamiento: mínimo 10GB disponibles  
* Opcional: dispositivo con pantalla táctil para una mejor interacción

### Requisitos de software

* Sistema Operativo: Windows 10/11, macOS o Linux (Ubuntu recomendado)  
* Python 3.8 o superior  
* Entorno virtual (virtualenv o conda)  
* Bibliotecas principales:  
  * OpenCV (para procesamiento de imágenes y AR)  
  * PyTorch (para la implementación de YOLO)  
  * Ultralytics YOLO (implementación moderna de YOLO)  
  * Mistral AI (biblioteca para la interacción con el modelo)  
  * NumPy (para cálculos matemáticos)  
  * Matplotlib (para visualización si es necesario)

### Requisitos de Conocimiento

* Programación en Python (nivel intermedio)  
* Conocimientos básicos de visión por computadora.  
* Entendimiento de modelos de detección de objetos (YOLO)  
* Familiaridad con APIs de modelos de lenguaje (Mistral)  
* Conceptos básicos de realidad aumentada.

### Objetos y Entorno

* Base de datos de objetos comunes (puede utilizarse COCO dataset)  
* Entorno con buena iluminación para una detección precisa  
* Variedad de objetos para pruebas (mínimo 10-15 objetos diferentes)  
* Fondos no saturados para mejor contraste

### Funcionalidades necesarias

* Captura de vídeo en tiempo real.  
* Detección y clasificación de objetos usando YOLO  
* Extracción de información relevante sobre los objetos detectados  
* Consulta al modelo Mistral para obtener información adicional sobre los objetos.  
* Visualización de la información superpuesta en la imagen (realidad aumentada)  
* Interfaz de usuario intuitiva

### Requisitos de rendimiento

* Procesamiento de vídeo a mínimo 15 FPS (idealmente 30 FPS)  
* Tiempo de respuesta máximo para la detección: 200ms  
* Tiempo de respuesta máximo para obtener información adicional: 1 segundo  
* Precisión mínima en la detección: 75%

### Requisitos de implementación

* Control de versiones (Git)  
* Documentación del código  
* Pruebas unitarias para los componentes críticos  
* Estructura modular para facilitar el mantenimiento.

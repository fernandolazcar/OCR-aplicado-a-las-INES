## Proyecto de Detección de Patrones y Generación de Hash para Votaciones
Este proyecto está desarrollado en Python y utiliza la tecnología de Reconocimiento Óptico de Caracteres (OCR) de Google para la detección de patrones específicos en credenciales electorales. Posteriormente, los datos extraídos se procesan para generar hashes únicos, los cuales se utilizan para llevar a cabo votaciones seguras y anónimas.

Tecnologías Utilizadas
- Python: Lenguaje de programación principal.
- Google OCR (pytesseract): Tecnología utilizada para la extracción de texto de imágenes.
- Pandas: Biblioteca para la manipulación y análisis de datos.
- Hashlib: Biblioteca para la generación de hashes.


# Funcionalidades del Proyecto
Extracción de Texto:

- Utiliza Google OCR (a través de la biblioteca pytesseract) para extraer texto de imágenes de credenciales electorales.
Detección de Patrones:

- Identifica patrones específicos en los datos extraídos que corresponden a IDs únicos de las credenciales.
Generación de Hash:

- Convierte los IDs detectados en hashes utilizando la biblioteca hashlib para asegurar la integridad y anonimato de los datos.
Almacenamiento de Datos:

Los datos extraídos y sus hashes correspondientes se almacenan en un DataFrame de pandas para una fácil manipulación y análisis.

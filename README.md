# python_pdf_interaction
Python y su interacción con documentos pdf, respositorio con ejemplo práctico de lectura y procesamiento de texto

# Análisis del Guión de Joker (2019)

Este proyecto realiza un análisis detallado del guión de la película "Joker" (2019) utilizando técnicas de procesamiento de texto y análisis de redes. El proyecto incluye análisis de relaciones entre personajes, frecuencia de términos y patrones narrativos.

## Características Principales

- Análisis de redes de personajes usando NetworkX
- Generación de nubes de palabras para análisis de frecuencia
- Visualización de relaciones e interacciones entre personajes
- Análisis estadístico del guión

## Tecnologías Utilizadas

- Python 3.x
- Bibliotecas principales:
  - NetworkX: Análisis y visualización de redes
  - PyPDF2: Extracción de texto de archivos PDF
  - Matplotlib: Visualización de datos
  - WordCloud: Generación de nubes de palabras
  - NumPy: Procesamiento numérico

## Requisitos de Instalación

```bash
pip install networkx matplotlib wordcloud PyPDF2 numpy
```

## Uso

Clone el repositorio
Instale las dependencias
Coloque el archivo PDF del guión en el directorio del proyecto
Execute los scripts de análisis

## Estructura del proyecto

joker-script-analysis/
├── data/
│   └── joker_new_final.pdf
├── src/
│   ├── character_network.py
│   └── word_cloud.py
├── results/
│   ├── network_analysis.png
│   └── word_frequency.png
└── README.md

Tecnologías y Recursos Utilizados
Este proyecto se basa en las siguientes tecnologías y recursos:
Software y Bibliotecas

Python 3.x
NetworkX (https://networkx.org/)
PyPDF2
Matplotlib
WordCloud
NumPy


# Metodología
El análisis se realiza utilizando técnicas de:

## Análisis de redes sociales
Procesamiento de lenguaje natural
Visualización de datos

## Propósito del Proyecto
Este proyecto fue desarrollado con fines educativos y de investigación para:

Demostrar técnicas de análisis de texto y redes en Python
Analizar patrones narrativos en guiones cinematográficos
Visualizar relaciones complejas entre personajes
Proporcionar herramientas para el análisis de contenido narrativo

## Agradecimientos

NetworkX por proporcionar las herramientas de análisis de redes
Comunidad de Python por el desarrollo y mantenimiento de las bibliotecas utilizadas


## Preparación de Datos

Este proyecto requiere el guión de Joker (2019) en formato PDF. Por razones de derechos de autor, el guión no se incluye en este repositorio.

### Configuración:
1. Obtenga una copia legal del guión
2. Renombre el archivo a `joker_new_final.pdf`
3. Colóquelo en la carpeta `data/`
4. Verifique que el archivo sea legible y el texto sea seleccionable

### Estructura de datos esperada:
```text
data/
├── joker_new_final.pdf
└── README.md

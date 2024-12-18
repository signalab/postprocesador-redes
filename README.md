# postprocesador-redes
Cuadernos de código para post-procesar datos extraídos de redes sociodigitales y plataformas (YouTube y Meta AdLibrary).


## Descripción
Cuadernos de código abierto diseñados para limpiar, procesar y hacer un análisis exploratorio de datos inicial sobre listas de videos o canales de YouTube o de anuncios de Meta AdLibrary, importados como datos tabulares en formato CSV o Excel.


## Cuadernos
- **Cuaderno YouTube:** Limpieza y depuración de texto. (Jupyter Notebook / Google Colab)
- **Cuaderno Meta AdLibrary:** Limpieza y depuración de texto. (Jupyter Notebook / Google Colab)

Para profundizar más en las posibilidades de análisis semántico, con *embeddings* y técnicas establecidas de NLP, te recomendamos explorar los cuadernos del proyecto de Signa_Lab ITESO [`generador-embeddings`](https://github.com/signalab/generador-embeddings).

## Fuentes de datos
- YouTube Data Tools ([listas de videos](https://ytdt.digitalmethods.net/mod_videos_list.php) / [listas de canales](https://ytdt.digitalmethods.net/mod_channels_list.php))
- Meta AdLibrary ([listas de anuncios](https://www.facebook.com/ads/library/)). La plataforma web solo permite descargar en CSV anuncios marcados por Meta como *Temas sociales, elecciones o política*.


## Dependencias e instalación (para ejecución local)

### Entorno de ejecución
El código desarrollado y contenido en los cuadernos de este repositorio requiere la instalación de [Python versión 3.9](https://www.python.org/downloads/) o más alta.

Aunque el software para ejecutar los cuadernos de código, [Jupter Notebook](https://jupyter.org/install), puede ser instalado de manera individual, se recomienda hacer la instalación completa de la paquetería contenida en [Anaconda](https://www.anaconda.com/download) que, además de Jupyter Notebook, incluye una gran cantidad de las librerías de software libre requeridas para la ejecución del código en los cuadernos de este repositorio. Su instalación es gratuita y compatible con sistemas operativos de Windows, macOS y Linux.

### Librerías y dependencias de Python
Para instalar las dependencias requeridas, cada **[cuaderno de código](cuadernos/)** contiene una primera celda que debe ejecutarse al inicio para asegurar la correcta instalación de las librerías y herramientas necesarias para replicar el funcionamiento del código.


## Licencia
El código y contenidos de este repositorio están publicados como software libre bajo la [Licencia MIT](LICENSE).


## Créditos
**Realizado por el equipo de Signa_Lab ITESO:**

- **Programación de cuadernos de código (Python)**: 
José Luis Almendarez González (Estudiante ICD) y Diego Arredondo Ortiz

- **Supervisión del desarrollo tecnológico y documentación:** 
Diego Arredondo Ortiz

- **Equipo de Coordinación Signa_Lab ITESO:** 
Paloma López Portillo Vázquez, Víctor Hugo Ábrego Molina y Eduardo G. de Quevedo Sánchez

Noviembre, 2024. Instituto Tecnológico y de Estudios Superiores de Occidente (ITESO) Tlaquepaque, Jalisco, México.

## Referencias
- Bird, S., Loper, E. & Klein, E. (2009). *Natural Language Processing with Python*. O'Reilly Media Inc.
- Hunston, S. (2022). *Corpora in Applied Linguistics* (2a ed.). Cambridge University Press. [https://doi.org/10.1017/9781108616218](https://doi.org/10.1017/9781108616218)
- Meta. (2024) Meta AdLibrary [software]. https://www.facebook.com/ads/library/
- Rieder, B. (2024) YouTube Data Tools [software]. Digital Methods Initiative. https://ytdt.digitalmethods.net/
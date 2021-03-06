# README

# Introducción a la bioinformática e investigación reproducible para análisis genéticos

# Introducción a la Bioinformática para Biólogo/as y Genetistas


[![Join the chat at https://gitter.im/Bioinfo_Mx-Cl/community](https://badges.gitter.im/Bioinfo_Mx-Cl.svg)](https://gitter.im/Bioinfo_Mx-Cl/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Mediante una colaboración entre el Posgrado en Ciencias Biológicas de la Universidad Nacional Autónoma de México, CONABIO y la U. de Chile, ofreceremos un curso intensivo de bioinformática, orientado a entregar las herramientas básicas para análisis de datos genómicos en el contexto de genética, especialmente la genética de poblaciones.

INSTRUCTORES:

**Alicia Mastretta Yanes**, PhD.,
Catedrática CONACYT-CONABIO,
[www.mastrettayanes-lab.org](www.mastrettayanes-lab.org
)

**Lorena Malpica**
Estudiante maestría ITAM-CONABIO

**Ricardo Verdugo Salgado**, PhD.,
Profesor Asistente, Programa de Genética Humana, ICBM, Facultad de Medicina, U. de Chile, [http://genomed.med.uchile.cl](http://genomed.med.uchile.cl)

Los materiales aquí presentados son de acceso libre. 

Transmisión online y videos de clases anteriores en [este canal de Youtube](https://www.youtube.com/channel/UCFXy3RKrbu595t8DyGjGoxg?view_as=subscriber). 

Sala de chat para **anuncios de la clase** y dudas si lo ests viendo remotamente: [en Gitter](https://gitter.im/Bioinfo_Mx-Cl/community)

## Objetivos

El **objetivo general es** brindar a los y las alumnas las herramientas computacionales de software libre, mejores prácticas y metodologías de reproducibilidad de la ciencia para efectuar, documentar y publicar proyectos bioinformáticos de análisis genómicos.

Los **objetivos particulares** son:

1.	Formar a los y las alumnas en los principios de investigación reproducible y metodologías para organizar proyectos bioinformáticos 
2.	Introducir a los alumnos a bash, R, git y Docker
3.	Presentar a los alumnos los tipos de datos genéticos producidos por la secuenciación de siguiente generación 
4.	Introducir a los y las alumnas al análisis e datos genómicos y genomas reducidos
5.	Revisar  a  nivel teórico y  práctico los  métodos  bioinformáticos  clásicos  de  análisis secuencias genómicas
6.	Asesorar a los alumnos en la realización de sus propios proyectos bioinformáticos


### Que sí es este curso

* Una introducción a los métodos y mejores prácticas de la biología computacional, los análisis bioinformáticos y la ciencia reproducible.
* Un resumen general de los tipos de datos utilizados en genómica y las herramientas computacionales para analizarlos.
* Una introducción para saber utilizar la línea de comando y R de forma fluida a través de mucha práctica. **Muchos cursos enfocados en análisis de datos genómicos asumen que ya sabes esto, o dan una introducción flash y luego saltan al otro tema, lo que hace  _muy difícil_ realmente aprovechar el otro tema o te deja con malas prácticas difíciles de borrar.**
* El lenguaje para aprender a entender los manuales de cualquier software bioinformático para poder utilizarlo a fondo por cuenta propia.
* Un curso con mucha práctica de R enfocado en ciencia reproducible, limpieza y graficación de datos biológicos y genéticos.
* El piso básico para poder tomar un curso más avanzado o adentrarse por uno mismo en algún análisis concreto (ensamblado de genomas, análisis transcriotómicos, filogenética con métodos Bayesianos, etc).


### Que NO es este curso

* La respuesta a qué tienes que hacer en tu proyecto de tesis. 
* Una discusión profunda de los diferentes softwares para analizar datos GBS, RAD, genomas, transcriptomas, metabarcoding, etc.

En otras palabras en este curso no te vamos a decir qué programa utilizar ni discutir a profundidad métodos de ensamblado etc. Para eso hay cursos especializados intensivos de un par de días que asumen ya sabes usar chido la terminal.

Algunos ejemplos:

* [Curso Bioinformática Instituto de Biotecnología, Cuernavaca](http://uusmd.unam.mx/curso/).
* [Talleres Internacionales de Genómica del Centro de Ciencias Genómicas, Cuernavaca](http://congresos.nnb.unam.mx/TIB2017/)


## Temario

#### Unidad 1 Introducción a la programación
* Código en computación
* Cómo buscar ayuda (permanentemente)
* Introducción a la consola y línea de comando de bash y R
* Introducción a los Scripts
* Funciones básicas de navegación y manejo de archivos con bash
* Funciones básicas de exploración de archivos con bash
* Redirección con bash
* Loops con bash

#### Unidad 2 Organización de un proyecto bioinformático
* Documentación de scripts y del proyecto
* Markdown
* git
* Manejo de proyectos e issues en Github
* Creación de pipelines

#### Unidad 3 Introducción a R con un enfoque bioinformático
* R y RStudio
* Funciones básicas de R más importantes para bioinformática
* Funciones propias: crear funciones y utilizarlas con source
* Rmarkdown y R Notebook
* Manipulación y limpieza de datos en R
* Graficar en R

#### Unidad 4 Introducción al software especializado
* Utilidad de software especializado
* Documentación de software especializado
* El problema de las versiones y OS para la reproducibilidad
* Docker

#### Unidad 5 Genética de poblaciones con software especializado
* Formatos VCF-tools y plink
* Paquetes de R
* Filtrado de individuos y datos perdidos
* PCA exploratorios
* Análisis básicos de diversidad y diferenciación genética

#### Trabajo en casa en proyectos finales y tareas
 Se dará seguimiento online al proyecto final con las herramientas de la Unidad 2 y se dejarán tareas para mantener la práctica de las unidades anteriores
 
#### Unidad 6 Introducción a la genómica y secuenciación de siguiente generación
* Genomas: estructura y evolución
* Proyectos de secuenciación genómica
* Bases de datos
* Técnicas de secuenciación
* Aplicación de acuerdo al problema de estudio
* Análisis básicos de calidad y limpieza de datos crudos

#### Unidad 7 Ensamblaje de genomas
* Flujo de un proyecto de ensamblaje
* Teoría de ensamble: grafos de De Bujin y comparativos 
* Principales algoritmos y software (Celera, AllPaths, Soap, Velvet, etc)
* Formatos de archivos de datos
* Métricas
* BLAST, modelos de genes
* Algoritmos comparativos y estadísticos de marcación

#### Unidad 8 Resecuenciación de genomas
* Llamado de variantes
* Predicción funcional de variantes
* Interpretación y anotación de variantes

#### Unidad 9 Ensamblaje de representación reducida de genomas
* Metodologías de representación reducida de genomas (RAD, GBS, etc)
* Ensamblaje de novo vs. sobre una referencia
* Principales algoritmos y software (Stacks, pyRAD)
* Uso de replicados para informar el ensamblaje
* Primera inspección de los datos

#### Unidad 10 Predicción estructural y funcional de Proteínas y ARNs
* Conceptos básicos de bioinformática estructural
* Predicción de la estructura secundaria de proteínas
* Predicción de la estructura secundaria de ARN
* Predicción de interacciones moleculares (docking)
* Predicción de efectos funcionales, nociones
 
#### Unidad 11 Análisis de expresión
* Diseño experimental
* Microarreglos
* RNA-seq
* Expresión diferecial
* Clustering

## Dinámica del curso

### ¿Cómo serán las clases?
* Exposición + ejercicos y ejemplos en clase
* Todos los materiales de la clase los iremos subiendo a GitHub conforme avance el semestre
* Dejaremos **lecturas** a casa antes o después de algunos temas. Es una muy buena idea sí leerlas.

* **¿Necesito una computadora?** 
    * El curso es teórico-práctico, por lo que se requiere traigan su laptop con Mac o GNU/Linux (**no** Windows, sorry, lo intenté 2 años y es una pesadilla para todxs) y:

  -  [Docker](https://www.docker.com/) instalado y **FUNCIONANDO** (ocuparemos Docker dentro de un mes)


* **¿Necesito instalar algo más? Sí**
     1. Un editor de texto decente. Listo para la 2da clase. Recomendaciones:
         * Mac o Linux: [Atom](https://atom.io/)
         * Linux: [Gedit](http://sourceforge.net/projects/gedit/) u otro que te guste.
     2. Un editor de Markdown    
         * Mac: [MacDown](http://macdown.uranusjr.com/)
         * Mac o Linux: [Haroopad](http://pad.haroopress.com/)
     3. [R y RStudio](https://www.rstudio.com/products/rstudio/download/).

También necesitas abrir una **cuenta de Github**

 **Si van a tomar notas, que sean ahí o en un editor de Markdown, nooooo en Word, de veritas de veritas**.
     
### Este repositorio

El repositorio está dividido en un folder por Unidad. Dentro de cada folder subiremos los apuntes y código utilizado en cada clase conforme los vayamos viendo en el semestre, así como los enlaces a las tareas. 

Las notas de este repositorio están escritas en formato **Markdown** y, como notarás, el repositorio se encuentra hospedado en **GitHub**. 

Cubriremos ambas herramientas en el curso, pero en resumen: 

* Markdown es un procesador texto-a-HTML que de forma sencilla permite formatear texto `así`. Esto es útil para resaltar los los comandos y los resultados de la terminal del resto del texto en los documentos de clase (y en foros de ayuda).

* GitHub es un repositorio web especializado en software (pero se puede subir cualquier texto, como este). La parte de arriba enlista los archivos y carpetas dentro del repositorio. La nota de texto a su derecha es el comentario que yo realicé al subir o modificar (*commit*) el archivo de mi computadora a GitHub. En la parte de abajo puedes leer el contenido de dichos archivos en formato html. Y si los bajas los verás en formato Markdown.


### Mecanismo de calificación

* ~ una tarea por sesión (en línea)
* Evaluación (examen o proyecto) por sección:

	* Unidades 1-4

	* Unidad 5

	* Unidad 6-11
	
	
Porcentaje aprovación: 60 %


### Copiar o plagiar (tareas, exámenes, trabajo final, lo que sea) es motivo suficiente para reprobarte sin lugar a discusión. 

![](truestory.png)


![](https://qiu.itq.edu.ec/Principal/imgLogin/ITQ.png)
# PROYECTO FINAL
###Asignatura
Administracion de base de datos 
###Carrera 
Desarrollo de software
###Estudiantes
- Michael Guaman 
- Dilan Pachacama
- Cristian Sandoval 

##*Indice de Contenido*
[TOC]
#Introduccion
La Base de datos sobre Elecciones Presidenciales es un reporsitorio de datos que recopilar información, incluyendo resultados de votaciones, candidatos, partidos politicos y otros datos relevantes. La siguiente Base de Datos se ha diseñado para facilitar el análisis de tendecias electorales, prediciones de resultados y otros estudios relaciones con el proceso electoral 
#Objetivo del  Proyecto
- Analizar patrones históricos de votación para identificar a lo largo del tiempo, como cambios en la participación electoral utilizando datos históricos para desarrollar modelos predictivos y poder identificar los faatores que mas influyen en los resultados electorales, como el desempeño economico, movilidad de partidos politicos, la demografia de los votantes Analizando el impacto de diferentes estrategias de campañas.
#Antecedentes
- Las bases de datos electorales suelen contener una variedad de datos, desde resultados electorales hasta información sobre candidatos, partidos, distritos electorales y más. Estos archivos suelen recopilar información de múltiples fuentes, incluidas agencias electorales estatales, comisiones electorales, registros públicos, encuestas de opinión, medios de comunicación y otras fuentes relevantes.
- Es importante considerar el contexto político y social en el que se desarrollan las elecciones, ya que esto influirá en los resultados y la interpretación de los datos. Factores como la demografía, la economía, las cuestiones políticas y sociales y las campañas electorales pueden tener un impacto significativo en los resultados electorales. Estos aspectos deben tenerse en cuenta y seguir prácticas éticas y legales al procesar datos electorales.

#Alcance del Proyecto 
- ####Descripción General
La Base de Datos de Eleccionees tiwene comoobjetivo principal recopilar, almacenar y gestionar datos relacionados con elecciones presidenciales en el pais
La base de datos proporcionara informacion detallada sobre candidatos, resultados de votación, participación electoral y otras variables relevantes para un proceso electoral 
- ####Tipo de Elecciones 
La base de datos se centrará únicamente en las elecciones presidenciales. Esto incluirá tanto las elecciones generales como cualquier elección anticipada o especial.
- ####Datos de Votacion 
La base de datos incluirá resultados de votación detallados a nivel nacional y para áreas geográficas específicas. Incluirá información sobre el total de votos, votos recibidos por cada candidato, porcentaje de votos recibidos y votos nulos y en blanco.
- ####Información de Candidatos y Partidos Políticos
Se recopilará amplia información sobre los candidatos que se postulan para la presidencia, incluidos nombres, historial electoral y cualquier otra información relevante. Además, se registrará información sobre los partidos políticos involucrados, incluidos nombres, líderes y otra información relevante.
- ####Datos Demográficos y Geográficos:
El repositorio incluirá datos demográficos y geográficos relevantes para el análisis electoral. Esto puede incluir información sobre la distribución geográfica de los votos, las características socioeconómicas de los votantes, la participación electoral por región, etc.

#Marco Teorico
- ####Qué es My SQL Workbech?
Es una herramienta visual de diseño de bases de datos para el sistema de base de datos MySQL que integra desarrollo de software, administración de bases de datos, diseño, administración y mantenimiento de bases de datos.
- ####Base de Datos Relacionales
Una base de datos relacional es un tipo de base de datos que almacena y proporciona acceso a puntos de datos relacionados entre sí, Las bases de datos relacionales se basan en el modelo relaciona uan forma intuitiva y directa de representar tablas 
- ####Qué son Tablas en My SQL Workbech?
Una tabla es una estructura de datos que organiza datos en columnas y filas; cada columna es un campo (o atributo) y cada fila es un registro. En la intersección de columnas y filas hay datos específicos, un valor. Cada registro contiene información para cada columna de la tabla.
Cada campo (columna) debe tener un nombre. El nombre del campo hace referencia a la información que se almacenará en él.
Cada campo (columna) también debe definir el tipo de datos que almacenará.


##Relaciónes en bases de datos
- ####Qué es una relación en una base de datos ?
La relacion de una base de datos es el vínculo que se establece entre distintos elementos de las tablas que la conforman. En este tipo de relaciones es fundamental el uso de lso campos de llave primaria (primary key ) que son los que se relacionan con otros registros de otras tablas asi creando las llaves foraneas (foreign key )
- ####Tipos de Relaciones en una base de datos 
- Relación uno a uno (1:1)
Se produce cuando la relación se realiza solo entre un registro de una tabla con un registro de otra tablas
En esta relación los campos establecidos como primary key de ambas tablas están enlazados
- Relación uno a varios (1:N)
En este tipo de relación de uno a varios un registro de una tabla puede enlazarse a varios registros de otra tabla. El primary key está vinculada a varios registros de otra tabla. esta relación es la más utilizada en las bases de datos relacionales 
- Relacoón de varios a varios  (N:N)
Cuando varios registros de una tabla pueden relacionarse con varios registros de otra tabla 

##Comandos Utilizados
- ####Comandos SQL

Las declaraciones del lenguaje de consulta estructurado (SQL) son palabras clave o declaraciones SQL especiales que los desarrolladores utilizan para manipular los datos almacenados en una base de datos relacional.
#####CRUD
CRUD significa Crear, Leer, Actualizar y Eliminar. Este concepto se utiliza para describir cuatro operaciones básicas que se pueden realizar en la mayoría de las bases de datos y sistemas de gestión de información.
* CREATE (CREAR)
Esta fase se utiliza para crear nuevos registros en la base de datos. Para implementar una acción "Crear", debe proporcionar un formulario o interfaz donde los usuarios puedan ingresar datos para nuevos registros.
* READ (LEER)
Esta acción se utiliza para leer datos de la base de datos y mostrárselos al usuario. Para implementar la operación "leer", debe haber una interfaz que permita a los usuarios buscar y recuperar registros existentes.
* UPDATE (ACTUALIZAR)
Esta fase se utiliza para actualizar los datos existentes en la base de datos. Para implementar la operación "Actualizar", es necesario proporcionar una interfaz para que el usuario pueda cambiar los datos de un registro existente.
* INNER JOIN
Seleccion registros que tienen valores coicidentes en ambas tablas 
* LEFT JOIN 
Devuelve todos los registros de la tabla de la izquierda (tabla1) y los registros coincidentes de la tabla de la derecha (tabla2)
* RIGHT JOIN 
Devuelve todos los registros de la tabla de la derecha (tabla2) y los registros coincidentes de la tabla de la izquierda (tabla1)
* COUNT 
Devuelve el numero de filas que coiciden con un criterio especifico 
* MIN AND MAX
MIN = devuelve el valor más pequeño de la columna seleccionada 
MAX =  devuelve el valor más grande de la columna seleccionada 
* SUM
Devuelve la suma total de una columna numérica
* AVG
Devuelve el valor promedio de una columna numérica 
* ORDER BY 
Se utiliza para ordenar el conjunto de resultados en orden ascendente o descendente 
* GROUP BY
Agrupa filas que tiene los mismos valores en filas de resumen
* UNION
Operador se utiliza para combinar el conjunto de resultados de dos o mas declaraciones 
* AS
Cambia temporalmente el nombre de una tabla 
* HAVING 
Se agrego a SQL por que la palabra WHERE no se puede usar con funciones agregadas

#Tablas Creadas en Base de Datos

#Concluciones
La exitosa implementaciòn de la base de datos Elecciones electorales ha demostrado ser un elemento fundamental para mejorar la transparencia, eficiecia y confiabilidad de un proceso electoral. La gestión de datos ha resultado una significatica mejora en la administración datos electorales 
Este proyeccto nos ha brindado valiosas lecciones sobre la importancia de la planificacion detalla sobre una base de datos llevada a temas reales ante la sociedad.
#Recomendaciones 
Se recomienda establecer un plan de mantenimiento continuo para la base de datos que incluya actulizaciónes preiódicas, monitoreo constante a la integridad de los datos 
Considerar la creacion de una interfaz de usuarios para poder hacer una abse de datos más intuitica y accesible tanto para el personal electoral como para los ciudadanos,
Realizar evaluaciones regulares de seguridad para identificar posibles vulnerabilidades y garantizar la protección continua de la base de datos contra amenazas cibernéticas

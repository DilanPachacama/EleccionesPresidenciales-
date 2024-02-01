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
La Base de datos sobre Elecciones Presidenciales es un reporsitorio de datos que recopilar información, incluyendo resultados de votaciones, candidatos, partidos politicos y otros datos relevantes. La siguiente Base de Datos se ha diseñado para facilitar el análisis de tendecias electorales, predicciones de resultados y otros estudios relaciones con el proceso electoral 

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

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422514191_956748939115759_2360324437962602220_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeEsE6bqlh8t1CHLpA1WxXbBh91c31bbuyOH3VzfVtu7I9lnLgWawteERwF-pDaU2_L-PQ2hgrMRKo8Ltq8aYDgX&_nc_ohc=VGCKxH0c78EAX83MSkX&_nc_ht=scontent.fuio16-1.fna&oh=03_AdSs5B7V3V2Oh4hMXxsrnmVdm7FWXxts-HG7xHclG_APZQ&oe=65E2A66F)

#Ejecucion de Comandos:
![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422734456_1059555278603119_6884185972639438354_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeHNYx5ZIFmI5h7Su70r06jPsEv_zuViGI6wS__O5WIYjunAUfeGQ1-JR6J6sH11RqqEE-_rD00b41JsZTQfvx5e&_nc_ohc=k69G2Ydr9IEAX_vxbG1&_nc_ht=scontent.fuio16-1.fna&oh=03_AdSrLaqEGOMgNMlWvT3G0JU8Yld9J_iVGwamAiPxSHARhg&oe=65E2B143)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422787605_1413871439544744_1353129267745718059_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeG5_Vj7R7J9VdtY6CutJBI0mcbpGub8xJeZxuka5vzElzAZyNadSIGCzjMulE8hl0W4jBMJNH2-oM-z172qduTM&_nc_ohc=AIJCXd0ZXxgAX-Xqyem&_nc_ht=scontent.fuio16-1.fna&oh=03_AdTStU2KNR5mjF7MQ9aJMEVmRG1vaUjj30XF6S_EtM_Wow&oe=65E29880)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/423036612_274501452122608_2613746206823119808_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeEUA-iVK3PMD5ORKRRz3rh195KWYAcFTvv3kpZgBwVO-9OlwaOjDUoruRjw2OAZa381HSWaZzj1vpxhFUlT1SY2&_nc_ohc=I7YEOBWjL88AX_GsmNH&_nc_ht=scontent.fuio16-1.fna&oh=03_AdT6Xz0LPMwkTbxdsgXO7cLpHu0RJ9wRSrtcAR4OrF7uSw&oe=65E2ACB7)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422863995_1840999149643939_1362371570151470354_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeF5W91s93dHsZ30jZl73KzpbOYBtHYr5bts5gG0divlu4FxG7hqw2SjO9ML-O0G8q9eLrLuYe30HjkSFZvoXQFJ&_nc_ohc=a7td6mduArYAX9HbAjB&_nc_ht=scontent.fuio16-1.fna&oh=03_AdQ5AfSMup-WHh9eX77qTGqXtSFPsSMpyeehBcZbuWapig&oe=65E2BCA6)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422633552_349545657923667_3750819578648912090_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeHMZLtqmXN3g45MUuKXxjsCvrzH3D5pTLm-vMfcPmlMuU6jCBEmLJemT1w0U3bpNbBbtZcgWsjaaAPJcOZRrMaA&_nc_ohc=g5OEDtDP0DEAX9Lzptq&_nc_ht=scontent.fuio16-1.fna&oh=03_AdTXJGPBwClEkmfp2bdGtq7w7IkqbEeQz9nM7gRLU2xM7A&oe=65E2C6E5)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/420242986_788284789994611_3632296057277423660_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeFsnjjvekLLz7GNGVtezajnRK4wgVzTr0VErjCBXNOvRRRh9PsxCQwI82FWzwO8MXBuGwpzWRvAmY6gPi4R58qL&_nc_ohc=N1hPZYNnN0oAX-DNrZk&_nc_ht=scontent.fuio16-1.fna&oh=03_AdQtkyq29m9HlDCcJ3zot_TKH9cNiVIDgdGrb0aUmTFj5w&oe=65E2C957)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422743678_1552358055523513_1186384861737742438_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeEwZ1pFu3Dx_ADmXLQwshYcjXVAz3wb4_aNdUDPfBvj9jEuamjuRbqR9RYEHSjPDt8iOgXbEVBE5o4PDBJpbldy&_nc_ohc=LT9KgDjSRskAX_k148-&_nc_ht=scontent.fuio16-1.fna&oh=03_AdRctRak9T864Ll-g_OCI85j5ozuP_C9AvX8UjIwsXdzhg&oe=65E2B379)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422580565_673097425033643_4206312014648257109_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeGadZh1SrUN1u3IQZdOPjuIttE1LVrW8Vu20TUtWtbxW39xhOmEG7-iKvKEqiJzTBSp1rj9xv1bV5Akl94qwQL7&_nc_ohc=OWemXdzB9k8AX9tZPuq&_nc_ht=scontent.fuio16-1.fna&oh=03_AdRb46J8riFB1B9-whGuJt4kXyr21xArzw-ETA_9OmYMNg&oe=65E29984)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/423105850_1118627329130780_1995467498736073524_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeFJDPKUImk_4q_oOsY9CzqBgSD-9w3Ms3SBIP73DcyzdNElLAUzllL8rWMJ5Ghl4hVRusoPlYcyAzrT5dBenOnF&_nc_ohc=MuOycvX3gUMAX80XtSq&_nc_ht=scontent.fuio16-1.fna&oh=03_AdRixSrsk1RT3yJqg7qr5wuhdGnKA2bQmymB4dcbeK3_LA&oe=65E29435)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422533636_3713944902174509_2731050518150067510_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeGHTANfqRc5eUTyaCgBQqaSQN_zAepJnPNA3_MB6kmc8z1UA3lbh_68cTL6bh5s-tS11y6JjG_evRYw7iZ7Tudh&_nc_ohc=hMKrxT5KRUwAX_NwXDx&_nc_ht=scontent.fuio16-1.fna&oh=03_AdS4nzmLDD-bNUqp5Hj2YhOxmWaoNKn93IiCZWF-7FSXqw&oe=65E2C056)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/423735575_1140137094024787_6606889550451225287_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeGty8BpkbGZPVx7srWhXfDRppAuXKckz9KmkC5cpyTP0lUZndjP8gupIcEMgISgjgbYs9b6U6mqCUKAADSMaUWR&_nc_ohc=wUeZlE5g7dcAX-dd_hh&_nc_ht=scontent.fuio16-1.fna&oh=03_AdT5-zWSOAi2e5NVWW9hyq36sKQwfxqHGB8k0WM356e7Dw&oe=65E2AD28)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/420330728_714247824166087_4458577974253916655_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeERhIwzZ6lGceQHa4FJk20BaGLIPn68t0doYsg-fry3R9eD5XwkDXT5kVvAmjXH2Rw50RhN3wje2Qv53i9OmOWd&_nc_ohc=0HtaKg4R_lUAX_spRWA&_nc_ht=scontent.fuio16-1.fna&oh=03_AdT0dz5YQXwFtOfTWb9w_C_tLhpgC-fvU0Qwt8FZhZ_2Cw&oe=65E29C05)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422749741_1202643660695087_3485077125979655732_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeHZah7xLfgHo46LuEF_-8ylW8PIZnnTtTdbw8hmedO1N8-rS0SSwoKcgHzqV_hAasOBIshA384g_4_Gv-BnZdRV&_nc_ohc=W600PpmAB-0AX_oHbuE&_nc_ht=scontent.fuio16-1.fna&oh=03_AdTj2R7S2sqxFtINIAN-uIc2mEo3GEe7O8BGMuCFUOEePg&oe=65E2B779)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422929528_393442616594330_7808991150799888389_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeEuO9tVbFVoJVXcz5puFQSfU-E44fKHh7lT4Tjh8oeHue3l0ry0aCmPiFX_oG7bEF9oj3lxd3Z-pVoEBp7OotFh&_nc_ohc=m2Lxw1YVy_EAX85qGVn&_nc_ht=scontent.fuio16-1.fna&oh=03_AdR52Hzu1xkldQ59HBiNEklQvMxbp2b-_c_TwMb1LMOjvw&oe=65E2ABBE)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422749741_7316679571729063_7020740353843907762_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeEcoUWNA2rlycRHephOzY2XChnv103rkLgKGe_XTeuQuMOQ-iWNEGCjEgQPGbOJjZLZqJHmjbW1CtAjro4x1AdN&_nc_ohc=Ny_6e8ShTpcAX8JhOQj&_nc_ht=scontent.fuio16-1.fna&oh=03_AdT_qsJ6Up0TVZ7WGqgTNcD28oLuvN8B_gOHvfijcx7YAw&oe=65E2C617)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422684354_292195933516018_5794504123907783030_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeHjMW7J2mdr1jdTble2PZfPLlZcZJ1yJbQuVlxknXIltLkN1jwRapk-sOAW_Ds2Q5ydsZorzNW6-Jv2x8rCWkl4&_nc_ohc=flxEeeqDOjUAX_w0R03&_nc_ht=scontent.fuio16-1.fna&oh=03_AdRoKEC38NoGYKAytwMnjsFuEcvk-u2zBesmCJA4Idiwtg&oe=65E29C7F)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422779776_3305698659723087_7228454842614927188_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeG-rsM8CDgJuihQZDaSUPQ3qnK_2kgjBx2qcr_aSCMHHVTdEhDoilUei7ab-iC2cp3Ln2bWHGUKaZSfP6ylV86T&_nc_ohc=HBMF7sL1x4wAX8rYxJs&_nc_ht=scontent.fuio16-1.fna&oh=03_AdQq8RzXpZa-YfaaBzSbSAvbD-eSE_FLS4bUz0MO2pJiKQ&oe=65E2CAB9)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422616564_373538388641153_6987193100463512280_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeFrXj0j_bdZ7SQQiNNGaCHkwkPrfIKrlgXCQ-t8gquWBSWeIfoqgqUbMM9XVlG3Znw9AFHKGkwwwOd2YZdlvAch&_nc_ohc=rBxfIQnKrdYAX8vzHkn&_nc_ht=scontent.fuio16-1.fna&oh=03_AdQt1Co0-Blx1BI8o1kmEylfIxdhNQ92wWBGiiLzS-r1rA&oe=65E2B163)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422874822_398946995987157_6079863278345060457_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeGad_YTLIhcAoBVjupMxjIGtxbV31jk3XK3FtXfWOTdcjOj7E2LTnJT-5tpxh4vWgDxxqAqIKkP6BQutRpkscHx&_nc_ohc=qecwGKbhY5oAX8b0TC_&_nc_ht=scontent.fuio16-1.fna&oh=03_AdTRNBS0-cZDjKFtQyTcbRGFNud-kIbTiso8jJjKn6wgFQ&oe=65E29C66)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422648479_686961576978425_4215443716399465281_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeF6V0C3D8Voc1oICSBiAy1pZvG-EN9AZmhm8b4Q30BmaKznhwSpB4JKStRhdd-c7hi9Pxd8whtYdwQukbKteOWe&_nc_ohc=D40O_apWQHoAX_3BWC5&_nc_ht=scontent.fuio16-1.fna&oh=03_AdScCiLSNjoGxuA6MMtPhbAG0wYnByPP80_tVuHe6IaufA&oe=65E2A255)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/420349595_3492441030973023_3465148551268290089_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeHMXfLwjgQIQTQS9fcf9soqhHdhlPxhjY-Ed2GU_GGNj1TTNy044epUrcmGQGTLtQZsdukKt1-hwJKhuA5oE-0-&_nc_ohc=TS9spSaw4hAAX-cSWhM&_nc_ht=scontent.fuio16-1.fna&oh=03_AdSwYMetbAXQXOBl0WX7jIoJq7Y2yUMtCLee68Wasp66_Q&oe=65E2C2E2)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/423063082_691529226483578_6273289984637895179_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeEY34PGxmT3nLXsLJsK5u3MEUQDzdlnO9sRRAPN2Wc72x63hYjPwi4EIO5gDWkc7yo20_YSlOKLJzSRZk6qkW8d&_nc_ohc=prAvSjBUOQ0AX-a0UTJ&_nc_ht=scontent.fuio16-1.fna&oh=03_AdSkIPkKlMbUwXXPuHTSvzwA4lI_omDhmZfxL5GUDUzygw&oe=65E2B3A2)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422746524_928386835541908_1489065130435523282_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeGTJ0cij7PNaT6vV0Om27Vorupjc-5G36Wu6mNz7kbfpaaTMvelt1W0Mr0xN72haENuILioRk6qI7uA7rgKLKZ2&_nc_ohc=PkDHited_OkAX_oPkj1&_nc_ht=scontent.fuio16-1.fna&oh=03_AdTO26g4piNNfbK4pGpfTQezXPPUKdNXne9kaT_XZAb53w&oe=65E297F0)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/423105806_737375998348029_8099599428817748894_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeHfHZoob585GlNrJ5keI0ZV_qX43hgvvJn-pfjeGC-8mc3K0xFNU-ACgLZ-miG4_RQwErwpCdmgLD47RK_cz8Ip&_nc_ohc=LWr9EYqyV2kAX-d4RJM&_nc_ht=scontent.fuio16-1.fna&oh=03_AdQLzb1P7A9m4Vxpm892jYTXYE4wdi7ZriXaTRjqx0O4jw&oe=65E2B2AC)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.15752-9/422581671_1112515639941890_8553876988333272931_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=8cd0a2&_nc_eui2=AeFsMc6BkHfu8-VsuxAfk7sGgwzu4uyv16qDDO7i7K_XqitYgzYCJZ_IoD2iKWpwBjIF-FAW6CUYf5KBVeY28NH7&_nc_ohc=cql0TxdRegIAX_jqv5U&_nc_ht=scontent.fuio16-1.fna&oh=03_AdQv-SrIO2QXCufnzp94XSMW4WaBuoLRcUYoDEf1OekIOg&oe=65E2AB9F)



#Concluciones
La exitosa implementaciòn de la base de datos Elecciones electorales ha demostrado ser un elemento fundamental para mejorar la transparencia, eficiecia y confiabilidad de un proceso electoral. La gestión de datos ha resultado una significatica mejora en la administración datos electorales 
Este proyeccto nos ha brindado valiosas lecciones sobre la importancia de la planificacion detalla sobre una base de datos llevada a temas reales ante la sociedad.
#Recomendaciones 
Se recomienda establecer un plan de mantenimiento continuo para la base de datos que incluya actulizaciónes preiódicas, monitoreo constante a la integridad de los datos 
Considerar la creacion de una interfaz de usuarios para poder hacer una abse de datos más intuitica y accesible tanto para el personal electoral como para los ciudadanos,
Realizar evaluaciones regulares de seguridad para identificar posibles vulnerabilidades y garantizar la protección continua de la base de datos contra amenazas cibernéticas

#Recomendaciones 
Se recomienda establecer un plan de mantenimiento continuo para la base de datos que incluya actulizaciónes preiódicas, monitoreo constante a la integridad de los datos 
Considerar la creacion de una interfaz de usuarios para poder hacer una abse de datos más intuitica y accesible tanto para el personal electoral como para los ciudadanos,
Realizar evaluaciones regulares de seguridad para identificar posibles vulnerabilidades y garantizar la protección continua de la base de datos contra amenazas cibernéticas

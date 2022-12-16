
LINK PROYECTO _
https://public.tableau.com/app/profile/pablo8343/viz/Buscadorinmobiliariourbano/Story1?publish=yes

FUENTE DE DATOS _
https://datos.madrid.es
https://www.kaggle.com

DESCRIPCIÓN _
A la hora de enfrentarnos a la búsqueda de un inmueble, solemos filtrar principalmente en función del precio, en muchos casos dejando de lado numerosos factores que la ciudad nos brinda y que forman parte de los barrios que nos rodean.
En este proyecto se trata de descubrir otras variables urbanas que nos ayuden a encontrar el emplazamiento ideal para cada persona, sin olvidarnos de los factores económicos y físicos convencionales que suponen la compra de un piso.

OBJETIVO_
Generar un buscador que muestre el barrio ideal para la adquisición de un inmueble, basado no solo en conceptos económicos y físicos de la propiedad. Se trata de incluir aspectos sociales, determinados por los equipamientos y servicios que cada barrio o distrito puede ofrecernos. En el buscador se recogen aspectos como el ocio y la cultura, los centros educativos, los centros sanitarios, zonas verdes, etc.

LIMPIEZA DE DATOS _
A partir de los datos obtenidos de diversas fuentes (adjunto link en la parte superior), el primer paso fue el análisis  y limpieza de los mismos, para posteriormente pasar a estructurarlos. Los campos municipales que se han trabajado son los siguientes 

-Actividad económica: Hostelería, restauración y comercio
-Zonas verdes
-Transporte
-Educacion
-Sanidad
-Seguridad
- Equipamientos de ocio y cultura.

ESTRUCTURA DE DATOS_
Una vez con los datos limpios, se introducen en una base de datos MySQL, desde Python, utilizando la herramienta Alquemy,  para su posterior estructuración y arquitectura.
En este proyecto todo gira en torno a los barrios de Madrid, por lo tanto el nexo de unión entre las diferentes tablas y sus valores asociados se articula  a partir de un id_barrio, elemento común en todas ellas, utilizando el código ya preestablecido por la CAM.

VISUALIZACIÓN _
En esta fase del proyecto se trata de representar de la manera más dinámica y accesible posible los datos obtenidos  y las relaciones que existen entre ellos, para ello es indispensable el uso de Tableau.

En este proceso de visualización  se ha hecho especial hincapié en la representación cartográfica de la información, pilar básico del proyecto, tratando de zonificar de manera clara las ubicaciones de cada equipamiento y servicio de los diferentes barrios de Madrid, mediante el uso de recursos gráficos como el heatmap, para ello es básico conocer la latitud y longitud de todos los elementos, proceso realizado en la fase de análisis y limpieza.

Una vez determinadas las localizaciones de cada barrio, con su respectivos servicios, se pasa a visualizar de manera gráfica las relaciones que existen entre ellos y el mercado inmobiliario de la capital.
De esta manera y mediante la utilizacion de filtros se pueden ir cribando aspectos economicos, sociales, urbanos y fisicos de los inmuebles existentes.

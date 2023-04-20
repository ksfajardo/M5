![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

## Introducción a Tableau

Tableau es una herramienta de visualización de datos que nos permite conectar, visualizar y compartir datos de manera efectiva. Es una solución de software que brinda una interfaz gráfica  para explorar y analizar grandes cantidades de datos.

Los beneficios de Tableau incluyen su capacidad para analizar grandes conjuntos de datos de manera rápida y efectiva, crear visualizaciones, personalizarlas, y compartir datos de manera fácil y segura con otros usuarios.

Tableau también se destaca por su facilidad de uso y su enfoque en la experiencia del usuario. A través de su interfaz gráfica, Tableau permite a los usuarios explorar datos y crear visualizaciones de manera intuitiva, sin la necesidad de escribir código.

## Tableau vs Power BI

Tableau y Power BI son dos de las herramientas de visualización de datos más populares en el mercado actual. Ambas herramientas tienen características similares, pero hay algunas diferencias importantes entre ellas.

Tableau se destaca por su enfoque en la visualización de datos y su capacidad para crear visualizaciones personalizadas y complejas. Por otro lado, Power BI se centra en la integración de datos y la creación de informes.

| Característica                 | Tableau                                                                                            | Power BI                                                              |
|--------------------------------|----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|
| Licenciamiento                 | Modelo basado en suscripción anual o mensual                                                       | Modelo basado en licencia perpetua o suscripción anual                |
| Interfaz de usuario            | Interfaz intuitiva y fácil de usar                                                                 | Interfaz similar a la de Microsoft Office                             |
| Conectividad de datos          | Amplia gama de conectores a bases de datos y aplicaciones web                                      | Conectores limitados y dependientes de otros productos de Microsoft   |
| Visualizaciones                | Amplia variedad de tipos de gráficos y capacidades de personalización                              |  Variedad de gráficos y opciones de personalización, Marketplace, Python y R              |
| Análisis de datos              | Capacidad de análisis avanzado, como cálculos de tabla, campos calculados y análisis de tendencias | Funciones de análisis de datos limitadas                              |
| Integración con otros sistemas | Integración con una amplia variedad de sistemas de terceros                                        | Integración con otros productos de Microsoft, como Excel y SharePoint |
| Colaboración                   | Tableau Server y Tableau Online permiten compartir y colaborar en informes                         | Compartir informes a través de Microsoft Teams y SharePoint           |
| Costo                          | Más caro que Power BI                                                                              | Más económico que Tableau                                             |


## Componentes de Tableau
![enter image description here](https://intellipaat.com/mediaFiles/2015/11/tableau1.png)

* Tableau Desktop es la herramienta principal de creación de visualizaciones de Tableau. 
* Tableau Server es una plataforma de colaboración que permite a los usuarios compartir y colaborar en proyectos. 
* Tableau Online es una versión basada en la nube de Tableau Server. 
* Tableau Public es una versión gratuita de Tableau que permite a los usuarios compartir visualizaciones públicamente en línea.
Para la demo del dia de hoy y el homework usaremos tableau Public.

https://public.tableau.com/app/discover

## Conexión a los datos

Tableau permite a los usuarios conectar a diferentes fuentes de datos locales o en la nube, y también ofrece un conector web de datos para acceder a datos en línea. Además, Tableau ofrece herramientas para preparar y limpiar los datos antes de la visualización.



## Exploración de los datos

Tableau Desktop proporciona un entorno de trabajo para explorar y crear visualizaciones. Los usuarios pueden crear hojas de trabajo y dashboards, usar las estanterías para agregar campos y aplicar filtros. También pueden crear cálculos básicos con funciones integradas.

## Modelo de datos en Tableau 
![enter image description here](https://1.bp.blogspot.com/-rURO3knViOY/Xq4TPXTi84I/AAAAAAAAQeg/Lx7EhQt9GLARjTvSc2tPwTseBn4hFsptgCEwYBhgL/s1600/3.png)
Como construir un modelo de datos en Tableau.

1.  Determinar la estructura de los datos: Una vez que hayamos conectado los datos, determinar la estructura de los datos. ¿Cuáles son las tablas y columnas disponibles en la fuente de datos? ¿Cómo están relacionadas las diferentes tablas?
    
2.  Crear tablas y relaciones: En Tableau, se puede crear tablas personalizadas utilizando la opción "Crear tabla" en el menú "Datos". También se puede establecer relaciones entre tablas existentes utilizando la opción "Editar relaciones" en el menú "Datos".
    
3.  Crear cálculos y medidas: Crear cálculos y medidas para agregar contexto y profundidad a sus análisis. Utilizando la opción "Crear cálculo" en el menú "Análisis" para crear cálculos personalizados basados en las columnas existentes en sus tablas.
    
4.  Generar jerarquías y agrupaciones: Crearemos jerarquías y agrupaciones para ayudar a organizar y resumir sus datos. Utilizar la opción "Crear jerarquía" en el menú "Análisis" para crear una jerarquía de columnas relacionadas.


## Cálculos de tabla y campos calculados
![enter image description here](https://help.tableau.com/current/pro/desktop/en-us/Img/calcs_tips1.gif)


Tableau ofrece la capacidad de realizar cálculos de tabla, que son operaciones que se realizan en una tabla de datos. También permite crear campos calculados para agregar nuevas métricas a los datos.

Como creamos campos calculados:

1.  En la estantería "Campos", hacemos clic en el botón "Nuevo campo".
2.  En el cuadro de diálogo "Crear cálculo", escribimos el nombre del nuevo campo calculado y, a continuación, escribimos la fórmula para el cálculo. Por ejemplo, si queremos calcular el margen de beneficio, escribimos "Margen de beneficio" en el cuadro de nombre y, a continuación, escribimos la fórmula "(Ganancia - Costo)/Ganancia".
3.  Hacemos clic en "Aceptar" para crear el nuevo campo calculado.
4.  Arrastramos el nuevo campo calculado a la estantería de fila o columna para agregarlo a nuestra visualización.
5.  Podemos personalizar la visualización y agregar otras medidas o dimensiones según sea necesario para completar nuestro análisis.

### Calculo de Tabla
Los cálculos de tabla se utilizan comúnmente para realizar operaciones agregadas en los datos, como calcular el total de ventas, la media de un conjunto de valores o el porcentaje de cambio de una medida entre dos períodos de tiempo. Los cálculos de tabla también pueden utilizarse para crear variables que se utilizan en otras partes de una visualización, como filtros, cálculos de campo y gráficos.

Para crear un cálculo de tabla en Tableau, se utiliza la opción "Crear cálculo de tabla" en el menú de "Análisis". A continuación, se escribe la fórmula para el cálculo utilizando las funciones y operadores de cálculo disponibles en Tableau. Los cálculos de tabla pueden ser creados en cualquier momento durante el análisis y se pueden agregar a la vista como cualquier otra medida o dimensión.

## Agregar marcas e interactividad a las visualizaciones
![enter image description here](https://help.tableau.com/current/pro/desktop/es-es/Img/size1.gif)


Tableau ofrece herramientas para agregar marcas y crear visualizaciones interactivas. Además, los usuarios pueden mejorar la apariencia y la legibilidad de las visualizaciones mediante el formato y el diseño.

Las marcas en gráficos Tableau son elementos visuales que representan los datos en una visualización. Las marcas son esenciales para la creación de gráficos y la presentación de datos de manera efectiva en Tableau.

Las marcas en un gráfico pueden representar puntos, líneas, barras, áreas y otros tipos de formas para representar los datos. En general, las marcas se utilizan para representar valores de datos individuales en una visualización y pueden ser coloreadas, etiquetadas y organizadas de diversas formas.

En Tableau, las marcas se pueden personalizar para ajustarse a los requisitos de la visualización. Por ejemplo, se puede cambiar el tamaño, el color y la forma de las marcas para enfatizar ciertos datos. Además, las marcas pueden ser etiquetadas con texto y números para proporcionar información adicional sobre los datos.

Las marcas también se utilizan para aplicar filtros y grupos a los datos. Por ejemplo, se puede seleccionar una marca individual o un grupo de marcas y aplicar un filtro para excluir o incluir ciertos datos. Las marcas también se pueden agrupar según una dimensión específica para crear visualizaciones más claras y concisas.

En resumen, las marcas son elementos esenciales en la creación de visualizaciones efectivas en Tableau y se utilizan para representar valores de datos individuales, aplicar filtros y grupos y personalizar la apariencia de la visualización.


## Compartir los datos

Los usuarios pueden publicar sus visualizaciones en Tableau Online para compartirlos con otros usuarios de Tableau. También pueden compartir visualizaciones públicamente a través de Tableau Public.


## Que Visualizaciones usar según mi necesidad analítica

https://public.tableau.com/app/profile/diego.parker/viz/VocabularioVisualES/VisualVocabulary

## Tableau Gallery

En la galería de Tableau, podemos explorar una amplia variedad de visualizaciones y dashboards, desde simples gráficos hasta dashboard complejos. Las visualizaciones están organizadas por categorías, como finanzas, tecnología, salud, marketing y más, lo que facilita la búsqueda de visualizaciones específicas en un área temática determinada.

Además de encontrar inspiración, la galería de Tableau también ofrece la oportunidad de conectarnos con otros usuarios de Tableau y ver cómo han utilizado la herramienta para resolver problemas y mejorar su toma de decisiones. Podemos comentar y compartir visualizaciones y dashboards, y también podemos descargarlos para nuestro propio uso y análisis.

https://www.tableau.com/viz-gallery

Links que pueden ser de interés:

Cualquier estudiente tiene 1 año gratis de Tableau a partir que crea y activa su cuenta: https://www.tableau.com/academic/students

A la par puede realizar los trainings gratuitos en el siguiente link: https://www.tableau.com/learn/training/20231

Luego para ir más alla en su capacitacióin, puede contratar el eLearning o las Classes: https://www.tableau.com/learn/training/elearning
https://www.tableau.com/learn/classroom

Para luego certificarse como experto: https://www.tableau.com/learn/certification

Por último, puede canalizar cualquier duda en help: https://www.tableau.com/support/help

Base de conocimiento: https://www.tableau.com/support/knowledgebase

Community: https://community.tableau.com/s/

Y también puede encontrar miles de tableros de cualquier industria o área en Public: https://public.tableau.com/app/discover

## Homework

Desarrollar un tablero en tableau public, que contenga 4 visualizaciones.

-   Grafico de Lineas
-   Mapa
-   Torta con etiqueta de valores absolutos y porcentuales
-   Dos Filtros
-   Dos Campos Calculados
-   Un calculo de Tabla

# Registro de obras por Colombianos en el Exterior - Q2 2018

![alt text](https://raw.githubusercontent.com/ansegura7/Registro-Obras-Colombianos-Exterior-Q2-2018/master/img/main-banner.jpg)

- Estudiante: Andres Segura Tinoco
- Código: 201711582
- Curso: Visual Analytics
- Tarea 5
- Fecha: 30/10/2018
- Licencia: MIT

## Datos del Proyecto – What
Descripción: El dataset muestra el consolidado del registro de obras protegidas por el Derecho de Autor realizado por solicitantes colombianos en el Exterior, en el 2 trimestre del 2018. Los datos están actualizados para el Julio 10 De 2018

Los datos provienen de los Datos Abiertos de Colombia www.datos.gov.co, y es un dataset del tipo Table, que contiene las siguientes variables (attributes):
- País: categorical.
- Ciudad: categorical.
- Persona que realiza el registro: categorical.
- Enlace: categorical.
- Cantidad Registros: ordered, quantitative, sequencial.

El enlace a los datos es: https://www.datos.gov.co/Cultura/Registro-de-obras-por-Colombianos-en-el-Exterior-2/ags6-6cmc/data

## Objetivos del Proyecto - Why
Crear una visualización web que permita identificar (identify) la dependencia (dependency) que existe entre el precio del barril de petróleo y la producción diaria de petróleo en Colombia.

También, que la Viz permita comparar (compare) las tendencias (trends) del precio del barril de petróleo contra la cantidad de pozos perforados en Colombia.

Por último, que la Viz presente (present) la tendencia (trend) de los ingresos nacionales por conceptos de venta de petróleo, con el objetivo de resaltar el impacto (positivo o negativo) que tiene el precio del barril de petróleo en los ingresos de la Nación.

## Marcas y Canales – How
En los 3 gráficos de líneas, se usaron como marcas puntos conectados por líneas. Tanto los datos del eje X como los del eje Y están ordenados secuencialmente. En cada gráfico se usó un color distinto, asociado a la naturaleza del dato que se deseaba mostrar, por ejemplo, verde para el petróleo, verde oscuro para la venta de petróleo y negro el precio del barril de petróleo.

Con respecto al gráfico de barras, se usaron como marcas líneas verticales ordenadas tanto en el eje Y (para expresar cantidad), como en el eje X (secuencialmente por año) para mayor entendimiento de los datos.

En todos los gráficos se usó la posición vertical, para mostrar el tamaño del valor que se desea graficar. Además, también se usó en cada gráfico un título y un subtítulo descriptivo, para ayudar al usuario a entender la información que se está visualizando.

## Insights
-	Efectivamente existe una dependencia entre el precio del barril de petróleo y la producción diaria de petróleo en Colombia. Cuando el precio del barril está alto, Colombia invierte más en nuevas perforaciones, lo cual influye directamente en la cantidad de barriles de petróleo que se producirán en los próximos meses, que al final, significa más dinero para la Nación.
-	En qué año comenzó la caída en el precio del barril de petróleo a nivel mundial: año 2014.
-	En qué año comenzó la caída de la tasa de producción diaria de petróleo en Colombia: año 2015.
-	De cuanto fue la caída en los ingresos diarios por concepto de venta de petróleo en Colombia: del 2014 al 2015 fue del 46%.

## Tecnologías Usadas
Para el desarrollo del proyecto se usaron las siguientes tecnologías:
-	Se usó Sublime Text 3 como IDE de desarrollo.
-	HTML y CSS, para maquetar el sitio web.
-	Javascript y el framework d3.js para crear los gráficos (de barras y de líneas) y la respectiva interacción con ellos.
-	GitHub para almacenar el código de la Viz, y de los datos usados. A continuación dicho repositorio principal del proyecto: PrecioBarril-Perforacion-Produccion-2007-2018

## Prerrequisitos y Uso
El proyecto sólo depende del acceso a los datos almacenados en el repositorio https://github.com/ansegura7/PrecioBarrilPerforacionProduccion-2007-2018 y a la disponibilidad del servicio de GitHub Pages, que permite el acceso por medio de un Navegador a la página principal proyecto.

Todos los gráficos muestran el año de análisis seleccionado (con una línea roja punteada), dicho año se puede cambiar con el ComboBox: "Año de Corte".

El gráfico de barras depende de la opción seleccionada en el ComboBox: "Dirección del Gráfico".

## Autores
El autor de los datos es el Gobierno Nacional y el sitio web Datos Abiertos de Colombia. Los datos están actualizados hasta el 10 de Julio de 2018.

El autor de la visualización es Andrés Segura Tinoco, CE 201711582.

## Screenshot
A continuación, se presentan unos pantallazo del proyecto:

![alt text](https://raw.githubusercontent.com/ansegura7/Registro-Obras-Colombianos-Exterior-Q2-2018/master/screenshots/Figure1.PNG)

![alt text](https://raw.githubusercontent.com/ansegura7/Registro-Obras-Colombianos-Exterior-Q2-2018/master/screenshots/Figure2.PNG)

## Licencia
Este proyecto está bajo la licencia MIT.

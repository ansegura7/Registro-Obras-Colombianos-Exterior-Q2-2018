# Registro de obras de Colombianos en el Exterior - Q2 2018

![alt text](https://raw.githubusercontent.com/ansegura7/Registro-Obras-Colombianos-Exterior-Q2-2018/master/img/main-banner.jpg)

- Estudiante: Andres Segura Tinoco
- Código: 201711582
- Curso: Visual Analytics
- Tarea 5
- Fecha: 30/10/2018
- Licencia: MIT

## Datos del Proyecto – What
Descripción: El dataset muestra el consolidado del registro de obras protegidas por el Derecho de Autor realizado por solicitantes colombianos en el Exterior, en el 2 trimestre del 2018. Los datos están actualizados hasta el 10 Julio del 2018.

Los datos provienen de los Datos Abiertos de Colombia www.datos.gov.co y son del tipo Table, sin embargo, en la presente visualización se procesan los datos en memoria, para convertirlos en un dataset del tipo Network, que contiene las siguientes variables (attributes):

- Items (Nodes): categorical, para los nodos Persona, Ciudad y País.
- Enlaces (Links): categorical, para las relaciones Persona-Ciudad y Ciudad-País.
- Cantidad (Attribute): ordered, quantitative, sequencial para el peso de los nodos y de los enlaces.
- Tipo (Attribute): categorical, y puede ser Persona, Ciudad o País.

El enlace a los datos originales, es: https://www.datos.gov.co/Cultura/Registro-de-obras-por-Colombianos-en-el-Exterior-2/ags6-6cmc/data

## Objetivos del Proyecto - Why

### Tarea Principal
TP1: Crear una visualización web que permita localizar (locate) los caminos (paths) entre los distintos autores que registran obras en un mismo país (pero en distintas ciudades).

### Tareas Secundarias
TS1: Explorar (explore) la topología (topology) de las ciudades o países, con respecto a la cantidad de autores que registran obras en el extranjero.

TS2: Generar (derive) y contabilizar (summarize) la cantidad de registros de obras (copyrights) que hace un autor en una ciudad en el extranjero (feature).

## Marcas y Canales – How
- Marcas: puntos para los nodos (Persona, Ciudad y País), líneas para los enlaces.
- Canal - Color Hue: cada nodo tendrá un color que permitirá identificar el tipo de nodo: si es una persona, una ciudad o un país.
- Canal - Posición: los nodos tienen una posición espacial en X, determinada por el peso de sus enlaces, la cual también está influenciada por una simulación de fuerzas.
- Reduce: Aggregate.
- Manipulate: Select. Se puede seleccionar un nodo, y se resaltarán los nodos vecinos con sus respectivos enlaces.

## Insights
- Los autores Luis German Perdomo y Monica Maria Palacio, están relacionados (tienen un camino en común), ya que ambos registraron obras en USA, respectivamente en las ciudades Orlando y Miami.
- Jaime Enrique Gutiérrez es el autor colombiano, que más obras registró en el extranjero (Melbourne, Australia) en el segundo trimestre del 2018 (aproximadamente 200).
- La ciudad donde más distintos autores (20) colombianos registraron obras es Caracas.
- Estados Unidos es el país con más distintas ciudades (5), en donde autores colombianos registraron obras.

## Tecnologías Usadas
Para el desarrollo del proyecto se usaron las siguientes tecnologías:

- Se usó Sublime Text 3 y Notepad++ como IDEs de desarrollo.
- HTML y CSS para maquetar el sitio web.
- Javascript y el framework D3.js v5, para crear el gráfico de Red con sus respectivas interacciones.
- GitHub para almacenar el código de la Viz, y de los datos usados. A continuación, el enlace a dicho repositorio principal del proyecto: https://github.com/ansegura7

## Prerrequisitos
El proyecto depende del acceso a los datos almacenados en el repositorio previamente mencionado y a la disponibilidad del servicio de GitHub Pages, que permite el acceso por medio de un Navegador a la página principal proyecto.

Además, al usar el framework D3.js v5, depende de que dicha librería esté disponible para ser usada on-line.

## Uso
- La visualización se cargará completa al ingresar su URL en un navegador web.
- Se puede seleccionar el tipo de alineación de los datos, en el combo-box Alineación. Esta interacción, afectará al orden de los nodos en el gráfico de redes.
- Se pueden mover (arrastrar y soltar) los nodos, para localizar y explorar los caminos y las topologías de la red.
- Se puede hacer click sobre los nodos, y se resaltarán los nodos vecinos de dicho nodo.

## Autores
El autor de los datos es el Gobierno Nacional y el sitio web Datos Abiertos de Colombia. Los datos están actualizados hasta el 10 de Julio de 2018.

El autor de la visualización es Andrés Segura Tinoco, CE 201711582.

## Screenshot
A continuación, se presentan unos pantallazo del proyecto:

![alt text](https://raw.githubusercontent.com/ansegura7/Registro-Obras-Colombianos-Exterior-Q2-2018/master/screenshots/Figure1.PNG)

![alt text](https://raw.githubusercontent.com/ansegura7/Registro-Obras-Colombianos-Exterior-Q2-2018/master/screenshots/Figure2.PNG)

## Licencia
Este proyecto está bajo la licencia MIT.

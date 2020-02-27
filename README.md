# Data Lovers

## Índice

* [1. Preámbulo](#1-preámbulo)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Objetivos de aprendizaje](#3-objetivos-de-aprendizaje)

***

## 1. Preámbulo

  Según [Forbes](https://www.forbes.com/sites/bernardmarr/2018/05/21/how-much-data-do-we-create-every-day-the-mind-blowing-stats-everyone-should-read), el 90% de la data que existe hoy ha sido creada durante los últimos dos años. Cada día generamos 2.5 millones de terabytes de datos, una cifra sin precedentes.

  No obstante, los datos por sí mismos son de poca utilidad. Para que esas grandes cantidades de datos se conviertan en **información** fácil de leer para los usuarios, necesitamos entender, procesar y mostrar estos datos. Una manera simple de hacerlo es creando _interfaces_ y _visualizaciones_.

  En este proyecto **construimos una _página web_ para jugadores de Pokémon Go**, que permite al usuario obtener estadísticas del juego u organizar la informacion. 

## 1. Resumen del proyecto

 Pokémon GO es un videojuego para dispositivos iOS y Android, lanzado en el 2016. Consiste en buscar y capturar personajes de la saga escondidos en ubicaciones del mundo real, por ende implica que el usuario deba desplazarse físicamente para progresar en el juego. La aplicación se ha convertido en un elemento de interacción social y registra mas de 100 millones de descargas.

### Investigacion UX
 
    Los usuarios del juego necesitan:
     
    - Conocer las caracteristicas de cada pokemon (tipo, debilidad, caramelos, peso, multiplicador, etc).
    - Saber cuántas y cuáles son las evoluciones que poseen los personajes.
    - Desean anticipar la frecuencia de aparición de los Pokémons en el juego.

  ![Pokemon](/src/img/final.png "Resultado Final")

  Para satisfacer las necesidades de los usuarios el proyecto web consta de 4 secciones, la primera sección **Pokemons**, lista todos los pokemones y ofrece dos clases de filtros, un buscador a tiempo real donde muestra los pokemons que coincidan con el nombre que se ingresa y otro filtro para ordenarlos en función de sus característica.

  La segunda sección se llama **Pokedex**, incluye un filtro avanzado para buscar los personajes en función de su Tipo y Debilidad.

  **Top 10** es la tercera sección que de manera predeterminada o personalizada lista y grafica los pokemones con mayor probabilidad de aparición en el juego.

  Y la última sección es **Candys**, que muestra los personajes en función de la cantidad de caramelos que necesita para evolucionar en el juego.
     
## Objetivos de aprendizaje

### UX

- Diseñar la aplicación pensando y entendiendo al usuario.
- Crear prototipos para obtener _feedback_ e iterar.
- Planear y ejecutar _tests_ de usabilidad.

### HTML y CSS

- HTML semántico.
- Selectores en CSS.
- `Flexbox` en CSS.

### DOM

- Selectores del DOM (querySelector | querySelectorAll).
- Manejar eventos del DOM. (addEventListener)
- Manipular dinámicamente el DOM. (createElement, appendchild, innerHTML, value)

### Javascript

- Manipular arrays (`filter` | `map` | `sort` | `reduce`).
- Manipular objects (key | value).
- Entender el uso de condicionales (`if-else` | `switch`).
- Entender el uso de bucles (`for` | `forEach`).
- Utilizar funciones (parámetros | argumentos | valor de retorno).
- Entender la diferencia entre tipos de datos atómicos y estructurados.
- Utilizar ES Modules (`import` | `export`).

### Pruebas Unitarias (_testing_)

- Testear funciones (funciones puras).

### Git y GitHub

- Ejecutar comandos de git (`add` | `commit` | `pull` | `status` | `push`).
- Utilizar los repositorios de GitHub (`clone` | `fork` | gh-pages).
- Colaborar en Github (pull requests).

### Buenas prácticas de desarrollo

- Organizar y dividir el código en módulos (Modularización).
- Utilizar identificadores descriptivos (Nomenclatura | Semántica).
- Utilizar linter para seguir buenas prácticas (ESLINT).

     

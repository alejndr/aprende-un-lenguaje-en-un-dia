# Aprende un lenguaje de programación en un día (ejercicio voluntario para subir nota).

## Miembros del grupo

Escribe aquí los miembros del grupo. El primero es el representante o encargado.

* Alejandro de la Maza Villalba
* David Balsas Martín
* Alejandro Ruiz López

## Lenguaje de programación

El profesor llevará una cajita llena de papelitos con los nombres de distintos lenguajes de programación. Los encargados de cada grupo meterán la mano en la caja y sacarán dos papelitos, de los cuales el grupo elegirá uno. Se permite hacer intercambio de papelitos entre grupos.

Escribe el lenguaje de programación elegido por el grupo.

* TypeScript
<img src="imagenes/ts.png">

Los papelitos se han recortado de este [documento](lenguajes_de_programacion.pdf).

## Información sobre el lenguaje

TypeScript es un lenguaje de programación libre y de código abierto desarrollado y mantenido por Microsoft, e implementa muchos de los mecanismos más habituales de la programación orientada a objetos, pudiendo extraer grandes beneficios que serán especialmente deseables en aplicaciones grandes, capaces de escalar correctamente durante todo su tiempo de mantenimiento. Este puede ser usado para desarrollar aplicaciones que se ejecutarán en el lado del cliente o del servidor.
La característica fundamental de TypeScript es que compila en Javascript nativo, por lo que se puede usar en todo proyecto donde este use; y el navegador, o cualquier otra plataforma donde se ejecuta, nunca llegará a enterarse del código original.
En resumen, TypeScript es lo que se conoce como un "superset" de Javascript, aportando herramientas avanzadas para la programación que traen grandes beneficios a los proyectos.
La ventaja de los superset es que los lenguajes basados en un estándar evolucionan mucho más lento que las necesidades de los desarrolladores. Entonces surgen estos para expandir un lenguaje, aportando todas las herramientas que no tienen los originales para desarrollar en mejores condiciones.

## Herramientas de desarrollo

Indica aquí qué software has tenido que instalar para programar en este lenguaje. Añade enlaces y/o capturas de pantalla.

Para empezar a programar en TypeScript, necesitamos instalar primero Node.js, preferiblemente la version LTS que podemos encontrar en su página oficial:

<img src="imagenes/DescargaNodeJS.png">
[Enlace a la página oficial](https://nodejs.org/en/)


Una vez instalado abrimos el terminal y escribimos el comando:
```
npm install typescript -g
```

Si usamos Visual Studio Code no tendremos que seguir pasos adicionales, el mismo reconoce los archivos que creemos con la extension .ts por defecto.
(visualstudiocode.png)
[Descargar Visual Studio Code](https://code.visualstudio.com)

## Poniendo en práctica el lenguaje

Pon en práctica el lenguaje de programación realizando los siguientes ejercicios. Para cada uno de los ejercicios, pega el código fuente de la solución y una captura de pantalla.

### 1. ¡Hola mundo!

Creamos un archivo html:
```html
<html>
<head>
	<title>Hola mundo</title>
</head>
<body>

	<script src="HolaMundo.js"></script>

</body>
</html>
```

Creamos un archivo HolaMundo.ts:

```typescript
alert('hello world in TypeScript!');
```
y lo compilamos poniendo en la consola:

```
tsc C:\ruta del archivo .ts\
```

Como resultado ontendremos el archivo .js al que llamamos en el anterior html, al abrir el html con un navegador nos mostrara la siguiente ventana:

<img src="imagenes/holamundo.png">

Realiza un programa que muestre por pantalla la frase **¡Hola mundo!**.

### 2. Pirámide

Dada una altura introducida por el usuario, realiza un programa que pinte una pirámide a base de asteriscos con la altura indicada.

### 3. Arrays y números aleatorios

Realiza un programa que rellene un array (o una estructura similar) con 20 números enteros aleatorios entre 1 y 100 y que seguidamente los muestre por pantalla. A continuación, se deben pasar los números primos a las primeras posiciones del array y los no primos a las posiciones restantes. Muestra finalmente el array resultado.

## Presentación de resultados

Cada equipo explicará al resto de la clase lo aprendido durante la realización del ejercicio. Todos los miembros de cada equipo deben participar en la explicación. Se puede utilizar como material de base para la presentación el repositorio de GitHub.

## Recompensa

* Todos los alumnos que realicen correctamente la actividad tendrán 0'25 puntos extra en la nota del trimestre.

* Los miembros del equipo más votado ganarán un premio.

:star: Si te ha gustado este ejercicio, dale una estrellita al [repositorio original](https://github.com/LuisJoseSanchez/aprende-un-lenguaje-en-un-dia).


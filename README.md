## Cómo gestionar un repositorio local con Git y subirlo a la nube

1. Inicializamos el repositorio:
    ```bash
    git init
    ```

2. Añadimos el archivo con cambios a la zona de preparación:
    ```bash
    git add <archivo>
    ```

3. Confirmamos los cambios y hacemos un commit:
    ```bash
    git commit -m "mensaje"
    ```

4. Para añadir el repositorio local a GitHub:
    - Copiar la URL del repositorio en GitHub.
    - Añadir el repositorio remoto:
        ```bash
        git remote add origin <URL>
        ```
    - Subir los cambios al repositorio remoto:
        ```bash
        git push -u origin master
        ```

## Apuntes sobre la estructura de una página web (a día 30/09/2024)

Las páginas web están compuestas por:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Mi página web</title>
</head>
<body>
    <!-- Contenido de la página -->
</body>
</html>
<head>

<meta charset="UTF-8"> indica que el documento esta en utf-8
que es un estandar de codificacion de caracteres

<meta> es un contenedor de metadatos a su vez los metadatos son datos que describen otros datos
y sirven para dar informacion sobre la pagina web

<title> es el titulo de la pagina web

</head>
<body>

<h1> es un titulo de nivel 1

id es un atributo que se usa para identificar un elemento

</div> es un contenedor de elementos en html

</p> es un parrafo

lang="en" es un atributo que se usa para indicar el idioma del texto en este caso en ingles
dir="rtl" es un atributo que se usa para indicar la direccion del texto
en este caso de derecha a izquierda
ambos atributos se usan en el parrafo y antes de escribir el texto

<form> es un formulario que se usa para recopilar informacion del usuario
dentro del formulario se pueden poner campos de texto, botones, casillas de verificacion
y otros elementos
<input> es un campo de texto
<textarea> es un campo de texto de varias lineas
<br> es un salto de linea
<label> es un campo de texto que se usa para asociar un texto con un campo de texto
<button> es un boton
<button type="submit"> es un boton de envio

type="email" especifica que el campo de entrada es para direcciones de correo electrónico.

id="correo" asigna un identificador único al campo de entrada
que se usa para asociarlo con la etiqueta.

name="correo" especifica el nombre del campo de entrada
que se usa al enviar los datos del formulario.

title="Introduce tu correo electrónico" proporciona una herramienta emergente
que aparece cuando el usuario pasa el cursor sobre el campo de entrada.

El atributo tabindex en HTML se usa para controlar
el orden de tabulación de los elementos al navegar por una página web usando la tecla Tab.

tabindex="2" establece el orden de tabulación del campo de entrada
determinando el orden en que los elementos reciben el foco cuando
el usuario navega a través del formulario usando la tecla Tab.

</body>

</html>

para hacer un comentario se usa <!-- -->

similar a como se hacia en java, clion y demas lenguajes de programacion
se abre y se cierra en este caso con html se abre y se cierra con <>

HEAD: es la cabecera de la pagina web
BODY: es el cuerpo de la pagina web

head: se usa para poner el titulo de la pagina web, indica como debe
mostrarse la pagina web y que archivos se deben cargar para su correcto
funcionamiento


EJERCICIO CLASE 26/09/2024

Ejercicio 1:
Crea un título de nivel 1 (<h1>) que diga "Mi Página de Práctica". Usa el atributo id para identificar el título como titulo-principal.

Ejercicio 2:
Crea una sección con la etiqueta <div>. Dentro de esta sección, incluye un párrafo de texto cualquiera. Aplica la clase seccion-principal a la etiqueta <div> para poder diferenciarla.

Ejercicio 3:
Añade un párrafo dentro del <div> anterior que tenga el atributo lang="en" y que contenga un texto en inglés. Cambia la dirección del texto para que se muestre de derecha a izquierda.

Ejercicio 4:
Agrega un formulario ("<form>):

Crea un formulario con tres campos: "Nombre", "Correo", y "Mensaje".
Usa la etiqueta <label> para asociar cada campo con un identificador único (id).
Cada campo de entrada (<input> y <textarea>) debe tener el atributo tabindex para definir el orden de navegación del formulario (1, 2, 3).
Añade un botón de envío al final del formulario.

Ejercicio 5:
Usa el atributo title en el campo "Correo" para mostrar un mensaje emergente que diga "Introduce tu correo electrónico".

Ejercicio 6:
Crea dos enlaces al final de la página, uno para "Volver al Inicio" y otro para "Ver Más Información", utilizando tabindex para definir el orden de navegación.








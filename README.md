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
Todos ellos se cierran en el orden en el que se abren (importante).
```

### `<head>`

- `<meta charset="UTF-8">` indica que el documento está en UTF-8, que es un estándar de codificación de caracteres.
- `<meta>` es un contenedor de metadatos. Los metadatos son datos que describen otros datos y sirven para dar información sobre la página web.
- `<title>` es el título de la página web.

### `<body>`

- `<h1>` es un título de nivel 1.
- `id` es un atributo que se usa para identificar un elemento.
- `<div>` es un contenedor de elementos en HTML.
- `<p>` es un párrafo.
- `lang="en"` es un atributo que se usa para indicar el idioma del texto, en este caso, en inglés.
- `dir="rtl"` es un atributo que se usa para indicar la dirección del texto, en este caso, de derecha a izquierda. Ambos atributos se usan en el párrafo y antes de escribir el texto.
- `<form>` es un formulario que se usa para recopilar información del usuario. Dentro del formulario se pueden poner campos de texto, botones, casillas de verificación y otros elementos.
- `<input>` es un campo de texto.
- `<textarea>` es un campo de texto de varias líneas.
- `<br>` es un salto de línea.
- `<label>` es un campo de texto que se usa para asociar un texto con un campo de texto.
- `<button>` es un botón.
- `<button type="submit">` es un botón de envío.

### Atributos de los campos de entrada

- `type="email"` especifica que el campo de entrada es para direcciones de correo electrónico.
- `id="correo"` asigna un identificador único al campo de entrada que se usa para asociarlo con la etiqueta.
- `name="correo"` especifica el nombre del campo de entrada que se usa al enviar los datos del formulario.
- `title="Introduce tu correo electrónico"` proporciona una herramienta emergente que aparece cuando el usuario pasa el cursor sobre el campo de entrada.
- El atributo `tabindex` en HTML se usa para controlar el orden de tabulación de los elementos al navegar por una página web usando la tecla Tab.
- `tabindex="2"` establece el orden de tabulación del campo de entrada, determinando el orden en que los elementos reciben el foco cuando el usuario navega a través del formulario usando la tecla Tab.

### Comentarios

Para hacer un comentario se usa `<!-- -->`, similar a como se hace en Java, CLion y otros lenguajes de programación. Se abre y se cierra con `<>`.

### Estructura de la página web

- **HEAD**: es la cabecera de la página web.
- **BODY**: es el cuerpo de la página web.

El `<head>` se usa para poner el título de la página web, indicar cómo debe mostrarse la página web y qué archivos se deben cargar para su correcto funcionamiento.




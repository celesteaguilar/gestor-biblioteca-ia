# Gestor de Biblioteca Personal

Aplicación web para registrar y administrar una colección personal de libros. Fue desarrollada como módulo práctico para la asignatura **Herramientas Avanzadas para el Desarrollo de Aplicaciones** de la Universidad Técnica Latinoamericana (UTLA), utilizando un asistente de Inteligencia Artificial como apoyo de programación.

* **Estudiante:** Celeste Aguilar
* **Carné:** 0700923
* **Docente:** Ing. Ámilton Abraham Rodríguez Sigüenza

## Descripción

El Gestor de Biblioteca Personal permite llevar un registro organizado de las lecturas o del material bibliográfico personal desde una sola pantalla, sin necesidad de instalar nada ni de usar un servidor. Los datos se guardan en el navegador, por lo que no se pierden al recargar o cerrar la página.

## Funcionalidades

1. **Registrar libros:** permite ingresar título, autor y género/categoría mediante un formulario.
2. **Validar datos:** si algún campo está vacío, la aplicación muestra el aviso "Por favor, completa todos los campos." y no guarda el libro.
3. **Listar libros:** muestra los libros registrados en una tabla con las columnas Título, Autor, Género y Acciones.
4. **Eliminar libros:** cada fila tiene un botón "Eliminar" que quita ese libro del catálogo y actualiza la tabla al instante.
5. **Persistencia de datos:** la información se almacena en `localStorage`, así que se conserva al recargar o cerrar el navegador.

## Tecnologías utilizadas

* **HTML5:** estructura de la interfaz y del formulario.
* **CSS3:** estilos de la interfaz.
* **JavaScript (ES6):** manipulación del DOM, manejo de eventos y uso de `localStorage`.
* **Git y GitHub:** control de versiones y publicación del proyecto.
* **VS Code:** editor y terminal integrada para los comandos de Git.
* **Asistente de IA:** apoyo en la generación, explicación y corrección del código y de los comandos de Git.

## Estructura del proyecto

```
gestor-biblioteca-ia/
├── index.html    # Aplicación completa (HTML, CSS y JavaScript en un solo archivo)
├── README.md     # Documentación del proyecto
└── .gitattributes
```

## Instrucciones para ejecutar

1. Clona o descarga este repositorio:

```bash
   git clone https://github.com/celesteaguilar/gestor-biblioteca-ia.git
   ```

2. Abre el archivo `index.html` con cualquier navegador web moderno (Chrome, Edge, Firefox).
3. Completa el título, el autor y el género, y pulsa **Registrar Libro**.

No requiere instalación de dependencias ni conexión a un servidor.

## Uso de la inteligencia artificial

Durante el desarrollo utilicé un asistente de IA con un enfoque iterativo: pedía una parte del trabajo, revisaba el resultado, lo probaba en el navegador y corregía lo necesario. La IA fue un apoyo; yo revisé y comprendí el código antes de incorporarlo al proyecto.

**Ejemplo 1: generación del código de la aplicación**

> "Crea una aplicación web en un solo archivo HTML que contenga estilos CSS y JavaScript para un gestor de biblioteca personal. Debe permitir agregar libros (título, autor, género), guardarlos en LocalStorage, mostrarlos en una tabla y poder eliminarlos."

La IA generó la estructura HTML con el script incluido. Yo revisé que las funciones `guardarLibro()` y `obtenerLibros()` funcionaran correctamente y comprobé que los selectores del DOM coincidieran con los elementos del formulario y de la tabla.

**Ejemplo 2: limpieza del repositorio con Git**

> "Necesito eliminar un archivo innecesario .txt de mi repositorio usando la terminal de VS Code y luego realizar el commit y push hacia la rama main."

La IA me indicó la secuencia `git add .`, `git commit -m "..."` y `git push origin main`. La ejecuté en la terminal de VS Code con un mensaje de commit descriptivo y eliminé del repositorio el archivo "Nuevo Documento de texto.txt".

**Revisión de lo generado:** al revisar el repositorio detecté que el README había quedado con un fragmento del comando de terminal usado para crearlo. Lo corregí con nuevos commits, lo cual me recordó que siempre hay que verificar lo que la IA o la terminal producen antes de publicarlo.

## Autora

Celeste Aguilar, estudiante de la Facultad de Ingeniería de la UTLA, 2026.


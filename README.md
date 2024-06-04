# Proyecto de API de Libros

## Modificaciones

### Manejo de Excepciones

- Se creó una clase `LibroException` para manejar los casos donde no se encuentra un libro.
- El método `getLibro` ahora lanza una `LibroException` si el libro no existe.
- Se agregó un controlador global de excepciones para manejar `LibroException` y devolver un estado HTTP 404 con un mensaje personalizado.

### Creación de Libros

- El método `postLibro` ahora devuelve el estado HTTP 201 (CREATED) al crear un nuevo libro.

### Estructura del Proyecto

- `libros.demo.com_tuuniversidad_exceptions`: Contiene las excepciones personalizadas.
- `libros.demo.com_tuuniversidad_repository`: Contiene la implementación del repositorio de libros.
- `libros.demo.com_tuuniversidad_controllers`: Contiene los controladores REST.

## Modificación del método getLibro



## Controlador Global de Excepciones



## Modificación del método postLibro

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

![image](https://github.com/Wellington-Granados/Modificar-Web-API-de-Libro/assets/170190822/85a6c67c-4e2b-4f06-9d1b-150ca96a7e31)

## Controlador Global de Excepciones

![image](https://github.com/Wellington-Granados/Modificar-Web-API-de-Libro/assets/170190822/45063bd2-4d97-48c3-9267-bca4c769aa12)

## Modificación del método postLibro

![image](https://github.com/Wellington-Granados/Modificar-Web-API-de-Libro/assets/170190822/4a3a37e1-1fdb-443c-a911-8fac1e94953b)

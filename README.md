# Challenge-LiterAlura

# Proyecto literalura-mariana:

**Descripción**:  
literalura-mariana es una aplicación que permite gestionar una biblioteca virtual. El sistema interactúa con la 
API de Gutendex para obtener información sobre libros y autores, y guarda esos datos en una base de datos local 
usando Spring Boot y PostgreSQL. El proyecto fue diseñado para ser simple, pero extensible, con el objetivo de 
ofrecer una plataforma para consultar y almacenar información sobre libros y autores.

Esta aplicación está sujeta a mejoras futuras.
La clase DatabaseInitializer está comentada porque no he logrado hacer que se cree la base
de datos desde cero al correr el programa por primera vez. Es una posible mejora a futuro.
La clase Resultado está comentada porque, finalmente, no se usó.

---

## Tecnologías Utilizadas:

- **Java 17**: Lenguaje de programación principal.
- **Spring Boot**: Framework para el desarrollo del servicio backend.
- **JPA (Java Persistence API)**: Utilizado para interactuar con la base de datos.
- **PostgreSQL**: Sistema de gestión de base de datos relacional.
- **Lombok**: Biblioteca que simplifica el código Java eliminando la necesidad de escribir métodos repetitivos
(como getters, setters y constructores).
- **Jackson**: Biblioteca utilizada para la conversión de objetos Java a JSON y viceversa.
- **API de Gutendex**: API pública para acceder a libros y autores en formato JSON.

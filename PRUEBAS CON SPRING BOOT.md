# Sobre pruebas con Spring Boot

## Pruebas de integración

- Usar `@SpringBootTest` para cargar el contexto de Spring Boot.
- Usar `@AutoConfigureMockMvc` para cargar el contexto de Spring Boot y configurar un `MockMvc`.

## Pruebas de unit test y Spring Boot

- Usar `@DataJpaTest` para cargar el contexto de Spring Boot y configurar un `TestEntityManager` para pruebas de repositorios.
- Usar `@DataMongoTest` para cargar el contexto de Spring Boot y configurar un `MongoTemplate` para pruebas de MongoDB.
- Usar `@JdbcTest` para cargar el contexto de Spring Boot y configurar un `JdbcTemplate` para pruebas de JDBC.
- Usar `@JsonTest` para cargar el contexto de Spring Boot y configurar un `JacksonTester` para pruebas de serialización y deserialización de JSON.
- Usar `@WebMvcTest` para cargar el contexto de Spring Boot y configurar un `MockMvc` para un controlador específico.
- Usar `@WebFluxTest` para cargar el contexto de Spring Boot y configurar un `WebTestClient` para pruebas de controladores reactivos.

## Pruebas de componentes unitarios

- Usar `@MockBean` para reemplazar un bean por un mock en el contexto de Spring Boot.
- Usar `@SpyBean` para reemplazar un bean por un spy en el contexto de Spring Boot.
- Usar `@InjectMocks` para inyectar mocks en un bean de Spring Boot.
- Usar `@Mock` para crear mocks de clases o interfaces.

## No es una prueba unitaria "Si"

- Si, se accede a la base de datos.
- Si, se accede a un servicio externo.
- Si, se accede a un sistema de archivos.
- Si, se tiene necesidades especiales de configuración o del entorno.
- Si, no se puede ejecutar en paralelo con otras pruebas.
- Si, se necesita un servidor de aplicaciones.

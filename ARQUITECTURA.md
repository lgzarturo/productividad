# Hablemos sobre arquitectura de software

La arquitectura de software es una disciplina que se encarga de definir la estructura de un sistema de software. La arquitectura de software se basa en la idea de que un sistema de software es un conjunto de componentes que interactúan entre sí, y que es necesario definir la forma en que estos componentes se relacionan entre sí.

## Términos importantes

**Escalabilidad**: La escalabilidad es la capacidad de un sistema de software para crecer en tamaño, sin perder rendimiento. La escalabilidad es importante, porque un sistema de software debe ser capaz de crecer a medida que crece el negocio.

Hay tres tipos de escalabilidad: Vertical, Horizontal y Elástica.

- La escalabilidad vertical se basa en el hardware, y consiste en añadir más recursos a un servidor.
- La escalabilidad horizontal se basa en el software, y consiste en añadir más servidores a un sistema. - La escalabilidad elástica se basa en las métricas, y consiste en añadir más recursos a un sistema, en función de la demanda.

**Mantenibilidad**: La mantenibilidad es la capacidad de un sistema de software para ser modificado. La mantenibilidad es importante, porque un sistema de software debe ser capaz de adaptarse a los cambios del negocio.

Hay tres tipos de mantenibilidad: Correctiva, Perfectiva y Adaptativa.

- La mantenibilidad correctiva se basa en la corrección de errores.
- La mantenibilidad perfectiva se basa en la mejora de la calidad del software.
- La mantenibilidad adaptativa se basa en la adaptación del software a los cambios del negocio.

**Disponibilidad**: La disponibilidad es la capacidad de un sistema de software para estar disponible. La disponibilidad es importante, porque un sistema de software debe estar disponible para los usuarios.

Hay tres tipos de disponibilidad: Alta, Media y Baja.

- La disponibilidad alta se basa en la redundancia de los servidores.
- La disponibilidad media se basa en la tolerancia a fallos.
- La disponibilidad baja se basa en la recuperación de desastres.

**Seguridad**: La seguridad es la capacidad de un sistema de software para protegerse de amenazas. La seguridad es importante, porque un sistema de software debe protegerse de amenazas.

Hay tres tipos de seguridad: Confidencialidad, Integridad y Disponibilidad.

- La confidencialidad se basa en la protección de la información.
- La integridad se basa en la protección de la información contra modificaciones no autorizadas.
- La disponibilidad se basa en la protección de la información contra la denegación de servicio.

**Rendimiento**: El rendimiento es la capacidad de un sistema de software para responder a las peticiones de los usuarios. El rendimiento es importante, porque un sistema de software debe ser capaz de responder a las peticiones de los usuarios.

Hay tres tipos de rendimiento: Tiempo de respuesta, Tasa de transferencia y Utilización.

- El tiempo de respuesta se basa en el tiempo que tarda un sistema en responder a una petición.
- La tasa de transferencia se basa en la cantidad de datos que puede transferir un sistema en un tiempo determinado.
- La utilización se basa en el porcentaje de recursos que utiliza un sistema en un tiempo determinado.

**Monitoreo**: El monitoreo es la capacidad de un sistema de software para ser monitorizado. El monitoreo es importante, porque un sistema de software debe ser capaz de ser monitorizado.

Hay tres tipos de monitoreo: Activo, Pasivo y Reactivo.

- El monitoreo activo se basa en la monitorización en tiempo real.
- El monitoreo pasivo se basa en la monitorización en tiempo diferido.
- El monitoreo reactivo se basa en la monitorización en tiempo real, y en la toma de decisiones en tiempo real.

Las características sobre el monitoreo son:

- Centralizado: El monitoreo centralizado se basa en un único punto de control.
- Visual: El monitoreo visual se basa en la representación gráfica de los datos.
- Automatizado: El monitoreo automatizado se basa en la toma de decisiones en tiempo real.
- Escalable: El monitoreo escalable se basa en la capacidad de crecer en tamaño, sin perder rendimiento.
- Flexible: El monitoreo flexible se basa en la capacidad de adaptarse a los cambios del negocio.
- Seguro: El monitoreo seguro se basa en la protección de la información.
- Eficiente: El monitoreo eficiente se basa en la capacidad de responder a las peticiones de los usuarios.
- Efectivo: El monitoreo efectivo se basa en la capacidad de protegerse de amenazas.
- Fácil de usar: El monitoreo fácil de usar se basa en la facilidad de uso.
- Fácil de instalar: El monitoreo fácil de instalar se basa en la facilidad de instalación.

## Factores del desarrollo

- Forma declarativa sobre la configuración: La forma declarativa sobre la configuración se basa en la idea de que la configuración de un sistema de software debe ser declarativa, y no imperativa.
- Claro contrato con el Sistema Operativo.
- El sistema siempre debe estar listo para ser desplegado.
- Es necesario minimizar la diferencia entre los entornos de desarrollo, pruebas y producción.
- El sistema debe ser fácil de escalar.
- El código base es una sola fuente de verdad.
- Es necesario no tener dependencias externas o en el sistema operativo.

## Sobre el código

Un diseño bueno es más fácil de cambiar que un diseño malo.

DRY: No dupliques código a lo largo del sistema.

KISS: Mantén las cosas simples.

Ortogonalidad: No divida una sola porción de código en multiples componentes del sistema.

El desacoplamiento es bueno porque fomenta la buena práctica de que el código base sea más fácil de cambiar.

Los buenos nombres hacen el código que sea más fácil de entender y hay que leerlo para cambiarlo.

El mantenimiento del código base debe ser parte rutinario del proceso de desarrollo completo.

## API Restful

Una API se define como una interfaz de programación de aplicaciones, y es un conjunto de reglas y definiciones que permite a los sistemas de software comunicarse entre sí.

Una API RESTful es una API que se basa en el protocolo HTTP, y que sigue los principios de REST. Se usa para la comunicación entre aplicaciones o servicios.

El objetivo de una API RESTful es compartir recursos entre aplicaciones o servicios, y se basa en los siguientes principios:

- **Recursos**: Los recursos son las entidades que se comparten entre aplicaciones o servicios.
- **URI**: La URI es la forma de identificar un recurso.
- **Métodos HTTP**: Los métodos HTTP son las operaciones que se pueden realizar sobre un recurso.
- **Representaciones**: Las representaciones son las formas en que se pueden representar los recursos.
- **HATEOAS**: HATEOAS es un principio de REST que se basa en la idea de que un recurso debe ser capaz de proporcionar enlaces a otros recursos.
- **Estado**: El estado es la forma en que se puede representar el estado de un recurso.
- **Cache**: La cache es la forma en que se puede almacenar en caché un recurso.
- **Seguridad**: Se basa en la autenticación y autorización de un recurso.
- **Versionado**: Es la versión de un recurso y se basa en la idea de que un recurso sea independiente de su versión.

Una API RESTful se basa en la arquitectura cliente-servidor, y se usa como mecanismo para conectar aplicaciones o servicios.

## Métodos HTTP

Los métodos HTTP son las operaciones que se pueden realizar sobre un recurso, y se basan en los siguientes métodos:

- **GET**: El método GET se basa en la obtención de un recurso.
- **POST**: El método POST se basa en la creación de un recurso.
- **PUT**: El método PUT se basa en la actualización de un recurso.
- **DELETE**: El método DELETE se basa en la eliminación de un recurso.
- **PATCH**: El método PATCH se basa en la actualización parcial de un recurso.
- **HEAD**: El método HEAD se basa en la obtención de los encabezados de un recurso.
- **OPTIONS**: El método OPTIONS se basa en la obtención de las opciones de un recurso.
- **TRACE**: El método TRACE se basa en la obtención de la ruta de un recurso.

## Representar operaciones

- **Crear**: Puede representar un INSERT en una base de datos y se usa el método POST.
- **Leer**: Puede representar un SELECT en una base de datos y se usa el método GET.
- **Actualizar**: Puede representar un UPDATE en una base de datos y se usa el método PUT o PATCH.
- **Eliminar**: Puede representar un DELETE en una base de datos y se usa el método DELETE.

## Indempotencia

Un método es idempotente si el resultado de una operación es el mismo, independientemente de cuántas veces se repita la operación.

- **GET/HEAD**: Son idempotentes, debido a que no producen cambios en el servidor. Solo se usan para recuperar información, lo que normalmente se conoce como operaciones de solo lectura. Ahora se les conoce como operaciones seguras, ya que representan funciones que siempre devuelven el mismo resultado, sin importar cuántas veces se repitan. Este concepto de idempotencia es importante para la caché, ya que permite a los intermediarios almacenar en caché los resultados de las operaciones seguras.
- **PUT/PATCH/DELETE**: Se pueden considerar idempotentes, siempre y cuando el resultado en el estado del servidor, ya que no cambia después de una operación segura. Se tiene que garantizar que el cliente pueda repetir la operación sin causar cambios adicionales en el servidor.
- **POST**: No es idempotente, ya que cada vez que se realiza la operación, se produce un cambio en el servidor.

## Códigos de estado

Los códigos de estado son una forma de comunicar el resultado de una operación, y se basan en los siguientes códigos:

- **1xx**: Respuestas informativas.
- **2xx**: Respuestas satisfactorias.
- **3xx**: Redirecciones.
- **4xx**: Errores del cliente.
- **5xx**: Errores del servidor.

### Códigos aplicados en API RESTful

- Crear un recurso debe devolver un código 201 (_Created_).
- Si no se puede crear un recurso, debe devolver un código 409 (_Conflict_).
- Recuperar los recursos debe devolver un código 200 (_OK_).
- Recuperar un solo recurso debe devolver un código 200 (_OK_).
- Si el recurso no existe, debe devolver un código 404 (_Not Found_).
- Actualizar un recurso debe devolver un código 200 (_OK_).
- Actualizar una parte de un recurso debe devolver un código 200 (_OK_).
- Si no se puede actualizar un recurso, debe devolver un código 409 (_Conflict_).
- Si se elimina un recurso, debe devolver un código 204 (_No Content_).
- Si no se puede eliminar un recurso, debe devolver un código 409 (_Conflict_).
- Si no se puede procesar un método, debe devolver un código 405 (_Method Not Allowed_).
- Si se pasan parámetros incorrectos, debe devolver un código 400 (_Bad Request_).
- Si se necesita autenticación, debe devolver un código 401 (_Unauthorized_).
- Si no se tiene permisos, debe devolver un código 403 (_Forbidden_).
- Si hay un error en el servidor, debe devolver un código 500 (_Internal Server Error_).
- Si hay un error en el servidor, pero es temporal, debe devolver un código 503 (_Service Unavailable_).
- Si hay un error en el servidor, pero es permanente, debe devolver un código 502 (_Bad Gateway_).

## Capas de la arquitectura API RESTful

- **Capa de presentación**: Se encarga de almacenar los controladores, los datos de entrada y salida, y las vistas.
- **Capa de aplicación**: Se encarga de almacenar los servicios, los datos de entrada y salida, y las reglas de negocio. Operaciones de lectura y escritura.
- **Capa de dominio**: Se encarga de almacenar los modelos, los repositorios, y las entidades. Operaciones de lectura y escritura a la base de datos.
- **Capa de infraestructura**: Se encarga de almacenar los adaptadores, los puertos, y las implementaciones de servicios.
- **Capa de persistencia**: Se encarga de almacenar las bases de datos, los esquemas, y las tablas.
- **Capa de seguridad**: Se encarga de almacenar los tokens, los permisos, y las reglas de seguridad.
- **Capa de monitoreo**: Se encarga de almacenar los logs, las métricas, y las alertas.
- **Capa de pruebas**: Se encarga de almacenar los tests, los mocks, y las pruebas unitarias.
- **Capa de documentación**: Se encarga de almacenar la documentación, los ejemplos, y las guías.
- **Capa de despliegue**: Se encarga de almacenar los servidores, los contenedores, y las nubes.
- **Capa de integración continua**: Se encarga de almacenar los pipelines, los builds, y las pruebas de integración.

Para representar la estructura de paquetes en una aplicación Spring Boot siguiendo las capas de la arquitectura API RESTful que has mencionado, puedes organizar tus paquetes de la siguiente manera:

```plaintext
com
└── [company]
    └── [application_name]
        ├── controllers             (Capa de presentación)
        │
        ├── services                (Capa de aplicación)
        │
        ├── models                  (Capa de dominio)
        │   ├── entities            (Entidades del dominio)
        │   └── repositories        (Interfaces de repositorios)
        │
        ├── adapters                (Capa de infraestructura)
        │   └── implementations     (Implementaciones de servicios)
        │
        ├── persistence             (Capa de persistencia)
        │   └── database            (Configuración de base de datos)
        │
        ├── security                (Capa de seguridad)
        │   ├── tokens              (Generación y validación de tokens)
        │   └── rules               (Configuración de seguridad)
        │
        ├── monitoring              (Capa de monitoreo)
        │   ├── logs                (Configuración de logs)
        │   ├── metrics             (Configuración de métricas)
        │   └── alerts              (Configuración de alertas)
        │
        ├── tests                   (Capa de pruebas)
        │   ├── unit                (Pruebas unitarias)
        │   └── integration         (Pruebas de integración)
        │
        ├── documentation           (Capa de documentación)
        │   ├── examples            (Ejemplos de uso de la API)
        │   └── guides              (Guías para desarrolladores)
        │
        ├── deploy                  (Capa de despliegue)
        │   └── servers             (Configuración de servidores)
        │
        └── ci                      (Capa de integración continua)
            └── pipelines           (Configuración de pipelines)
```

## Componentes de una aplicación Spring Boot con API RESTful

1. Interfaz: Define métodos que se van a implementar. Es el contrato que deben cumplir las clases que lo implementen.
2. Controlador: Se encarga de recibir las peticiones HTTP, procesarlas y devolver una respuesta. Aquí se definen los endpoints y la interacción con las solicitudes y respuestas.
3. Servicio: Se encarga de implementar la lógica de negocio. Aquí se definen las operaciones que se pueden realizar sobre los recursos.
4. Repositorio: Se encarga de implementar la persistencia de los datos. Aquí se definen las operaciones de lectura y escritura a la base de datos.
5. Entidad: Se encarga de representar los datos de la base de datos. Aquí se definen las tablas y las relaciones entre ellas.
6. Adaptador: Se encarga de implementar la infraestructura. Aquí se definen las implementaciones de servicios.

## Acciones a considerar

En el desarrollo de un proyecto de software, es necesario considerar las siguientes acciones:

- Realiza pruebas unitarias y de integración.
- Refactoriza el código, solo cuando sea necesario.
- Las pruebas de regresión son importantes.
- La corrección de errores, debe ser una prioridad.
- Las pruebas de aceptación se basan en la idea de que el cliente acepte el producto.
- La documentación debe ser automatizada.
- Piensa siempre en los requerimientos del cliente.
- Pon atención al rendimiento, la escalabilidad y la seguridad.

## Análisis de la arquitectura

- El desarrollo de software debe ser un proceso iterativo.
- Se requiere de una planificación y un diseño.
- Es necesario tener una comprensión del panorama general del proyecto.
- Los casos de uso son una forma de entender los requerimientos del cliente.

### Desarrollo iterativo y gradual

- Se requiere un análisis de los requerimientos.
- Se debe proponer un diseño.
- La implementación debe ser una prioridad.
- La experimentación es una forma de aprender.
- El desarrollo debe ser modular.
- Se debe determinar el alcance del proyecto y este siempre puede cambiar.
- La estimación de tiempos es una forma de adquirir compromisos.
- Siempre pensar en la arquitectura de la información.
- Las pruebas deben ser parte del desarrollo.
- Mientras más grande sea el proyecto, más ceremonias se requieren.
- El objetivo es mantener la ceremonia al mínimo.
- La base de la comunicación debe ser el caso de uso.
- El modelo de dominio es una forma de entender el negocio.
- La arquitectura debe ser una prioridad.
- La calidad es una forma de medir el éxito.
- La documentación es una forma de comunicar.
- La retroalimentación es una forma de mejorar.

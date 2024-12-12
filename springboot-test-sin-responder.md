# Examen de Spring Boot 3.2.1

## Preguntas

### Pregunta 1
¿Cuál es el objetivo principal de la anotación `@EnableAutoConfiguration` en Spring Boot?

- [ ] Escanear paquetes para beans.
- [ ] Habilitar configuraciones predeterminadas.
- [ ] Configurar automáticamente beans con base en las dependencias del classpath.
- [ ] Habilitar la seguridad en la aplicación.

### Pregunta 2
¿Cuál de las siguientes anotaciones se utiliza para marcar una clase como un componente en Spring?

- [ ] @Bean
- [ ] @Component
- [ ] @Service
- [ ] @Controller

### Pregunta 3
¿Qué hace el `Actuator` de Spring Boot?

- [ ] Proporciona endpoints para monitoreo y administración.
- [ ] Habilita la funcionalidad RESTful en la aplicación.
- [ ] Administra dependencias automáticamente.
- [ ] Configura automáticamente las conexiones de base de datos.

### Pregunta 4
¿Qué significa la anotación `@SpringBootApplication`?

- [ ] Marca la clase como un controlador principal de Spring Boot.
- [ ] Configura automáticamente todas las dependencias necesarias.
- [ ] Es una combinación de `@Configuration`, `@EnableAutoConfiguration` y `@ComponentScan`.
- [ ] Define un bean único para la aplicación.

### Pregunta 5
¿Cuál de las siguientes opciones mejor describe el concepto de perfiles (`profiles`) en Spring?

- [ ] Permiten la configuración de múltiples bases de datos.
- [ ] Facilitan el manejo de múltiples controladores REST.
- [ ] Aíslan las configuraciones para diferentes entornos como desarrollo, pruebas y producción.
- [ ] Permiten cambiar dinámicamente configuraciones a través de anotaciones como `@Profile`.

### Pregunta 6
¿Cómo defines un puerto diferente para una aplicación Spring Boot?

- [ ] Cambiando el archivo `application.xml`.
- [ ] Modificando la variable de entorno `SPRING_PORT`.
- [ ] Configurando el archivo `application.properties` con `server.port`.
- [ ] Definiendo el puerto en una clase @Configuration.

### Pregunta 7
¿Cómo puedes personalizar el comportamiento de un `@RestControllerAdvice`?

- [ ] Usando `@Autowired` para inyectar dependencias.
- [ ] Sobrescribiendo métodos para manejar excepciones específicas.
- [ ] Configurando un interceptor.
- [ ] Agregando múltiples clases de servicios.

### Pregunta 8
¿Qué es un `RestController` en Spring Boot?

- [ ] Una combinación de `@Controller` y `@RequestBody`.
- [ ] Una especialización de `@Controller` que simplifica la escritura de controladores RESTful.
- [ ] Un bean configurado para manejar servicios web SOAP.
- [ ] Una herramienta para configurar seguridad web.

### Pregunta 9
¿Para qué sirve el archivo `META-INF/spring.factories` en una aplicación Spring Boot?

- [ ] Configurar la seguridad web.
- [ ] Crear beans a partir de clases en el classpath.
- [ ] Registrar configuraciones de auto-configuración y otros componentes clave.
- [ ] Habilitar el uso de anotaciones como `@Component`.

### Pregunta 10
¿Cuál es la función principal de `application.properties`?

- [ ] Configurar beans en la aplicación.
- [ ] Almacenar datos sensibles.
- [ ] Configurar propiedades de la aplicación.
- [ ] Crear beans globales.

### Pregunta 11
¿Cómo puedes garantizar la inyección de un único bean en caso de conflicto entre múltiples beans del mismo tipo?

- [ ] Usando la anotación `@Primary`.
- [ ] Usando `@Qualifier` para especificar el bean.
- [ ] Cambiando la configuración del archivo `application.properties`.
- [ ] Usando una clase interna para diferenciar beans.

### Pregunta 12
¿Qué ocurre si omites `@Service` en una clase que debe actuar como un servicio en Spring Boot?

- [ ] La clase se registrará automáticamente como un bean.
- [ ] Spring lanzará una excepción al iniciar.
- [ ] La clase no se registrará como un bean.
- [ ] El comportamiento no se verá afectado.

### Pregunta 13
¿Cuál de los siguientes componentes es necesario para habilitar WebFlux en una aplicación Spring Boot?

- [ ] `spring-boot-starter-web`.
- [ ] `spring-boot-starter-data-jpa`.
- [ ] `spring-boot-starter-webflux`.
- [ ] `spring-boot-starter-reactive`.

### Pregunta 14
¿Qué comando usarías para generar un archivo JAR ejecutable en una aplicación Spring Boot?

- [ ] `spring build jar`.
- [ ] `mvn clean package` o `gradle build`.
- [ ] `bootJar`.
- [ ] `spring-boot:build`.

### Pregunta 15
¿Qué es `Reactive Streams` en el contexto de Spring WebFlux?

- [ ] Una especificación para manejar flujos asincrónicos de datos.
- [ ] Un patrón de diseño para aplicaciones monolíticas.
- [ ] Un conjunto de anotaciones para configuraciones reactivas.
- [ ] Un módulo de Spring Boot para soporte web síncrono.

### Pregunta 16
¿Cómo se puede habilitar la seguridad básica en una aplicación Spring Boot?

- [ ] Usando `@SecurityEnabled`.
- [ ] Agregando una dependencia a `spring-boot-starter-security`.
- [ ] Usando ambas opciones: agregando la dependencia y configurando un SecurityConfig.
- [ ] No es posible habilitar seguridad básica en Spring Boot.

### Pregunta 17
¿Cómo se puede monitorear la salud de una aplicación Spring Boot usando Spring Actuator?

- [ ] Verificando el archivo `application.properties`.
- [ ] Accediendo al endpoint `/actuator/health`.
- [ ] Configurando un bean de salud.
- [ ] Creando un controlador REST adicional.

### Pregunta 18
¿Qué ventaja tiene Spring Boot DevTools?

- [ ] Proporciona análisis de rendimiento.
- [ ] Permite reinicios automáticos y refresco del navegador durante el desarrollo.
- [ ] Agrega herramientas de monitoreo de producción.
- [ ] Facilita la configuración de servidores remotos.

### Pregunta 19
¿Qué es una `CommandLineRunner` en Spring Boot?

- [ ] Un controlador REST para líneas de comandos.
- [ ] Una clase que permite crear scripts de línea de comandos.
- [ ] Una clase que inicia servicios asincrónicos.
- [ ] Una interfaz para ejecutar lógica al inicio de la aplicación.

### Pregunta 20
¿Qué ocurre si no defines explícitamente un bean para un repositorio JPA?

- [ ] Spring Boot crea automáticamente un bean para el repositorio.
- [ ] Spring lanzará una excepción al iniciar.
- [ ] La base de datos no será accesible.
- [ ] El repositorio debe declararse manualmente.

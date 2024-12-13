# Examen de Angular 17.3.11

## Preguntas

### Pregunta 1
¿Cuál es el propósito principal del decorador `@NgModule` en Angular?

- [ ] Declarar un módulo que agrupa componentes, directivas, servicios, y otras entidades relacionadas.
- [ ] Crear un servicio global.
- [ ] Configurar rutas para la aplicación.
- [ ] Definir la estructura del DOM.

### Pregunta 2
¿Cómo defines una directiva estructural en Angular?

- [ ] Usando el decorador `@Service`.
- [ ] Usando el decorador `@Directive` y manipulando el DOM mediante el `Renderer2` y `ElementRef`.
- [ ] Extendiendo una clase de la librería principal.
- [ ] Usando el decorador `@Component` y definiendo un selector único.

### Pregunta 3
¿Qué es el `ChangeDetectionStrategy.OnPush` y cómo afecta el rendimiento?

- [ ] Es la estrategia por defecto para la detección de cambios.
- [ ] Optimiza el rendimiento al detectar cambios solo cuando las referencias de los inputs cambian.
- [ ] Es un patrón de diseño para aplicaciones de alto rendimiento.
- [ ] Permite evitar el uso de servicios observables.

### Pregunta 4
¿Qué comando se utiliza para generar un componente en Angular CLI?

- [ ] `ng create component <nombre>`
- [ ] `ng init component <nombre>`
- [ ] `ng generate component <nombre>`
- [ ] `ng new component <nombre>`

### Pregunta 5
¿Cómo puedes optimizar la carga inicial de una aplicación Angular grande?

- [ ] Implementando lazy loading para módulos secundarios.
- [ ] Usando servicios con `providedIn: 'root'` únicamente.
- [ ] Dividiendo el archivo `styles.css` en varios archivos pequeños.
- [ ] Utilizando `ng serve` con el flag `--prod`.

### Pregunta 6
¿Qué propiedad del decorador `@Component` define el archivo HTML del componente?

- [ ] `html`
- [ ] `template`
- [ ] `templateUrl`
- [ ] `selector`

### Pregunta 7
¿Cuál es la diferencia principal entre `ngIf` y `ngSwitch`?

- [ ] `ngIf` evalúa múltiples condiciones mientras que `ngSwitch` solo permite evaluar una condición.
- [ ] `ngIf` permite añadir estilos CSS y `ngSwitch` no.
- [ ] `ngIf` evalúa una condición booleana, mientras que `ngSwitch` selecciona entre múltiples opciones con base en una expresión.
- [ ] `ngIf` requiere un módulo extra para su uso.

### Pregunta 8
¿Cuál de las siguientes es una ventaja de usar Angular Forms (Reactive Forms)?

- [ ] Permite vincular datos directamente al DOM.
- [ ] Proporciona validaciones más estructuradas y reutilizables.
- [ ] Reduce el uso de módulos y servicios.
- [ ] Facilita la manipulación directa del DOM.

### Pregunta 9
¿Cómo se define un interceptor en Angular para manejar solicitudes HTTP?

- [ ] Creando un servicio con el decorador `@HttpInterceptor`.
- [ ] Configurando el interceptor en el archivo `angular.json`.
- [ ] Implementando la interfaz `HttpInterceptor` en un servicio y configurándolo en el `providers` del módulo.
- [ ] Usando un decorador `@Injectable` en un módulo de rutas.

### Pregunta 10
¿Qué rol tiene el archivo `polyfills.ts` en una aplicación Angular?

- [ ] Define la configuración principal del enrutador.
- [ ] Proporciona estilos globales para la aplicación.
- [ ] Incluye polyfills necesarios para soportar navegadores más antiguos.
- [ ] Configura los metadatos del proyecto.

### Pregunta 11
¿Cómo puedes compartir datos entre componentes hermanos en Angular?

- [ ] Usando un servicio común para almacenar y compartir datos.
- [ ] Pasando datos a través de un `@Input` en el componente padre.
- [ ] Usando un servicio compartido con `BehaviorSubject` o `Subject`.
- [ ] Configurando un módulo separado para cada componente.

### Pregunta 12
¿Qué significa la propiedad `useClass` en la configuración de un `provider`?

- [ ] Define qué clase manejará una directiva estructural.
- [ ] Indica qué clase concreta se debe usar para un token de inyección.
- [ ] Permite registrar múltiples instancias de un servicio.
- [ ] Configura las dependencias del servicio en tiempo de ejecución.

### Pregunta 13
¿Cómo funcionan los `Resolvers` en Angular?

- [ ] Permiten resolver conflictos entre rutas dinámicas.
- [ ] Obtienen datos antes de que una ruta sea activada.
- [ ] Validan los parámetros de las rutas.
- [ ] Aseguran que los módulos sean cargados antes de mostrar el contenido.

### Pregunta 14
¿Cuál es el propósito de `ngModel` en Angular Forms?

- [ ] Crear instancias de formularios dinámicos.
- [ ] Realizar un enlace bidireccional de datos en plantillas.
- [ ] Configurar validaciones personalizadas.
- [ ] Generar elementos DOM automáticamente.

### Pregunta 15
¿Qué diferencia hay entre `subject` y `BehaviorSubject` en RxJS?

- [ ] `BehaviorSubject` requiere más memoria que `subject`.
- [ ] `BehaviorSubject` retiene el último valor emitido mientras que `subject` no lo hace.
- [ ] `subject` emite valores solo una vez.
- [ ] `BehaviorSubject` no permite múltiples suscriptores.

### Pregunta 16
¿Qué comando te permite actualizar una aplicación Angular a la última versión?

- [ ] `ng update --all`.
- [ ] `ng update` con las opciones necesarias.
- [ ] `ng upgrade --version latest`.
- [ ] `ng migrate`.

### Pregunta 17
¿Qué es un `ViewChild` y cómo se utiliza?

- [ ] Es una forma de acceder a un elemento o componente hijo en la plantilla desde el código TypeScript.
- [ ] Es una referencia a una ruta secundaria en un módulo.
- [ ] Es un componente creado dinámicamente en tiempo de ejecución.
- [ ] Es un decorador que facilita la inyección de dependencias.

### Pregunta 18
¿Cuál es la función de los `Guards` en Angular?

- [ ] Configurar validaciones para formularios.
- [ ] Restringir el acceso a rutas según condiciones específicas.
- [ ] Implementar enrutamiento dinámico.
- [ ] Sincronizar servicios con componentes.

### Pregunta 19
¿Cómo puedes integrar animaciones personalizadas en Angular?

- [ ] Usando la librería `angular-animations`.
- [ ] Creando estilos CSS en un archivo global.
- [ ] Utilizando el módulo `@angular/animations` y definiendo triggers y estados.
- [ ] Configurando animaciones en `angular.json`.

### Pregunta 20
¿Cuál es la diferencia principal entre `@ViewChild` y `@ContentChild`?

- [ ] `@ContentChild` se usa para componentes padres y `@ViewChild` para componentes secundarios.
- [ ] `@ContentChild` es para directivas mientras que `@ViewChild` para servicios.
- [ ] `@ViewChild` busca elementos en la vista del componente, mientras que `@ContentChild` busca en el contenido proyectado.
- [ ] No existe diferencia entre ambos.


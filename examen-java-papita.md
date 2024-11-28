# Exámen de Java "Papita"
---

#### **1. ¿Qué característica del lenguaje permite crear tareas concurrentes más fácilmente, optimizando el uso de recursos?**  
A. Thread Pools  
B. Fork/Join Framework  
C. Hilos Virtuales  
D. CompletableFuture  

---

#### **2. ¿Cuál es el resultado del siguiente código?**
```java
String text = "Hello World";
System.out.println(text.transform(String::toLowerCase));
```
A. hello world  
B. HELLO WORLD  
C. Error de compilación  
D. null  

---

#### **3. ¿Qué palabra clave permite usar patrones en una estructura `switch`?**  
A. match  
B. instanceof  
C. pattern  
D. switch  

---

#### **4. Dada la siguiente declaración de un tipo de datos especial, ¿qué sucede si intentas crear una instancia con valores nulos?**
```java
record Person(String name, int age) {}
```
A. Se lanza una excepción NullPointerException por defecto.  
B. Se permite la creación de la instancia sin error.  
C. La instancia se crea, pero los valores nulos se convierten en cadenas vacías automáticamente.  
D. No compila debido a restricciones de este tipo de datos.  

---

#### **5. ¿Qué hace el método `try (resource)` en una declaración `try-with-resources`?**  
A. Abre un recurso automáticamente y lo deja abierto al finalizar.  
B. Cierra automáticamente el recurso al finalizar el bloque.  
C. Lanza una excepción si el recurso no es cerrable.  
D. Garantiza que se llame al método `close()` solo si no hay excepciones.  

---

#### **6. En una nueva API de manejo de cadenas, ¿cuál de estas es una ventaja?**  
A. Mejora en la velocidad de concatenación mediante `+`.  
B. Mejoras en la eficiencia al trabajar con patrones.  
C. Soporte para la optimización automática en tiempo de compilación.  
D. Uso exclusivo de StringBuilder internamente.  

---

#### **7. Dado el siguiente código, ¿qué sucede al ejecutarlo?**
```java
Object obj = null;
if (obj instanceof String s) {
    System.out.println(s.toUpperCase());
}
```
A. Lanza una NullPointerException.  
B. Imprime una cadena en mayúsculas.  
C. No imprime nada porque no pasa la verificación.  
D. Error de compilación porque el objeto es null.  

---

#### **8. ¿Cómo se definen métodos con cuerpo en interfaces en Java?**  
A. Usando la palabra clave `static`.  
B. Usando la palabra clave `default`.  
C. Usando la palabra clave `abstract`.  
D. No es posible definir métodos con cuerpo en interfaces.  

---

#### **9. ¿Cuál es el propósito de las clases con herencia restringida?**  
A. Permitir la herencia solo a clases definidas explícitamente.  
B. Proteger las clases contra la serialización.  
C. Garantizar la inmutabilidad de los objetos.  
D. Restringir el acceso a los métodos de instancia.  

---

#### **10. ¿Qué ocurre si se utiliza un bloque `switch` con un patrón que no coincide?**  
A. Se lanza una excepción.  
B. Ejecuta un bloque `default`, si está presente.  
C. No se ejecuta ningún caso.  
D. Error de compilación.  

---

#### **11. ¿Qué sucede si intentas usar un tipo de datos inmutable como clave en un `HashMap`?**  
A. Lanza una excepción debido a la falta de métodos hashCode y equals.  
B. Funciona correctamente ya que implementa hashCode y equals.  
C. Lanza una excepción ya que los valores no son mutables.  
D. No se puede usar como clave de un mapa.  

---

#### **12. ¿Cómo se manejan los métodos con múltiples parámetros opcionales en Java para evitar la sobrecarga excesiva?**  
A. Usando constructores adicionales.  
B. Aplicando el patrón Builder.  
C. Sobrecargando métodos con valores predeterminados.  
D. Usando arrays para encapsular todos los parámetros.  

---

#### **13. ¿Cuál es el propósito de una funcionalidad que permite definir valores específicos y seguros para el contexto de ejecución?**  
A. Compartir valores entre hilos concurrentes de forma segura.  
B. Crear variables globales para el programa.  
C. Evitar NullPointerExceptions en cadenas opcionales.  
D. Definir valores predeterminados para objetos inmutables.  

---

#### **14. En concurrencia, ¿qué diferencia hay entre `synchronized` y una aproximación estructurada a las tareas concurrentes?**  
A. `synchronized` gestiona acceso concurrente, mientras que la otra gestiona dependencias de tareas.  
B. Ambos son métodos equivalentes de concurrencia.  
C. La aproximación estructurada es más lenta.  
D. La aproximación estructurada es específica para sistemas distribuidos.  

---

#### **15. ¿Qué hace el operador `::` en una expresión?**  
A. Referencia un método o constructor.  
B. Evalúa una expresión ternaria.  
C. Ejecuta una llamada de método condicionalmente.  
D. Referencia una variable estática.  

---

#### **16. ¿Cuál es el beneficio de usar bloques `yield` en expresiones `switch`?**  
A. Garantizar el orden de ejecución en los casos.  
B. Proporcionar un valor de retorno flexible para cada caso.  
C. Facilitar la anidación de `switch`.  
D. Forzar la finalización del bloque `switch`.  

---

#### **17. ¿Qué ventaja tienen ciertos hilos optimizados frente a los hilos tradicionales?**  
A. Permiten la programación reactiva sin bloquear la ejecución.  
B. Son más rápidos pero consumen más memoria.  
C. Solo pueden ejecutarse en hardware especializado.  
D. Son exclusivos para procesamiento en paralelo masivo.  

---

#### **18. ¿Cómo se declaran los parámetros inmutables en un tipo de datos inmutable?**  
A. Usando la palabra clave `immutable`.  
B. Son automáticamente inmutables.  
C. Usando el modificador `final`.  
D. Usando anotaciones especiales.  

---

#### **19. ¿Cómo puedes declarar una clase que permita la herencia limitada a un conjunto específico?**  
A. Usando la palabra clave `sealed`.  
B. Definiendo el modificador `abstract`.  
C. Usando clases `final`.  
D. No se puede limitar la herencia.  

---

#### **20. ¿Qué ocurre si no implementas todos los métodos de una interfaz en una clase que la implementa?**  
A. El compilador genera un error.  
B. La clase se convierte automáticamente en abstracta.  
C. No hay error, pero los métodos faltantes generan NullPointerException en tiempo de ejecución.  
D. La JVM lanza una excepción en tiempo de ejecución.  

---
(Si llegaras a requerir las respuestas correctas, te hago un documentito con ellas, pero dudo infinitamente que las necesites, el examen está muy papita).

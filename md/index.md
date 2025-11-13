# Programación en Java — DAM y DAW

Página de inicio de la asignatura de Programación en Java para los ciclos DAM y DAW. Contenidos y prácticas orientados a desarrollar competencias sólidas en programación orientada a objetos y desarrollo de aplicaciones.

## Enlaces del curso
- [Temario](temario.md)
- [Ejercicios](ejercicios.md)
- [Prácticas](practicas.md)
- [Proyecto final](proyecto.md)
- [Recursos](recursos.md)

## Objetivos de aprendizaje
- Comprender la sintaxis y modelo de ejecución de Java.
- Aplicar POO: clases, objetos, herencia, interfaces y polimorfismo.
- Gestionar colecciones, genéricos y flujos de datos.
- Manejar excepciones y escribir código robusto y mantenible.
- Persistir datos con ficheros y JDBC básico.
- Automatizar con Maven/Gradle y versionar con Git.
- Escribir pruebas unitarias con JUnit y usar depuración.

## Contenidos principales
- Fundamentos de Java y tipos de datos.
- Control de flujo, métodos y encapsulación.
- POO avanzada, paquetes y modularización.
- Colecciones, genéricos, streams y lambdas.
- Manejo de excepciones y logging.
- Ficheros (texto/binario), JSON y serialización.
- JDBC básico y acceso a base de datos.
- Testing con JUnit y dobles de prueba.
- Herramientas: Maven/Gradle, Git, CI básica.
- Introducción a aplicaciones de consola; enfoque a backend en DAW y a apps de escritorio/móvil en DAM.

## Requisitos y entorno
- JDK 21 LTS o superior.
- IDE recomendado: IntelliJ IDEA Community (o Eclipse/VS Code con Java).
- Maven o Gradle, Git.

Verificación rápida:
```bash
java -version
javac -version
mvn -v   # opcional
gradle -v  # opcional
```

## Cómo empezar
1. Instalar JDK 21 LTS: https://adoptium.net
2. Instalar un IDE: https://www.jetbrains.com/idea/ o https://www.eclipse.org/ o https://code.visualstudio.com/ con Extension Pack for Java.
3. Configurar Git: https://git-scm.com
4. Crear proyecto y ejecutar prueba:
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hola, Java DAM/DAW");
    }
}
```

## Metodología y evaluación
- Evaluación continua con actividades semanales y revisiones de código.
- Prácticas y ejercicios: 50%
- Proyecto final: 30%
- Pruebas teórico-prácticas: 20%
Criterios: funcionamiento, calidad de código, pruebas y documentación. Requisito mínimo en cada bloque para superar la asignatura.

## Normas y buenas prácticas
- Estilo: Google Java Style Guide con Checkstyle/SpotBugs.
- Control de versiones con ramas y pull requests.
- Pruebas y cobertura mínimas en entregas.
- Documentación breve en README y comentarios Javadoc cuando proceda.

## Recursos recomendados
- Documentación oficial: https://docs.oracle.com/en/java/
- Especificación del lenguaje: https://docs.oracle.com/javase/specs/
- JUnit 5: https://junit.org/junit5/
- Guía de estilo Java: https://google.github.io/styleguide/javaguide.html
- Tutoriales Java (Oracle): https://docs.oracle.com/javase/tutorial/

Sugerencia: crea las páginas enlazadas (temario.md, ejercicios.md, practicas.md, proyecto.md, recursos.md) para completar la navegación del sitio.

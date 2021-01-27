# Apuntes_UF2_1
### Objetivos de las pruebas
    1. Probar si el software hace lo que ha de hacer.
    2. Probar si el software hace lo que no debe hacer.
- Para hacer esto, se requiere de un **Framework**.
---
### FRAMEWORK
- Un framework Está compuesto por: 
    - Conjunto de sus mejores prácticas y suposiciones.
    - Herramientas comunes.
    - Bibliotecas.
- Unifica el desarrollo con los desarrolladores.
---
### Forma de las pruebas
- **Pruebas dinámicas**: Se debe ejecutar la aplicación para analizar como se desarrolla en pleno funcionamiento.
- **Pruebas estáticas**: Se realizan sin ejecutar la aplicación, son para examinar el código fuente del programa para corregir posibles errores.
---
### Estrategias de las pruebas
- **caja negra**: se estudia el sistema desde fuera para ver la funcionalidad del programa, solo importa que el resultado sea deseable.
    - Se trabaja sobre la interfaz.
    - No se tienen en cuenta detalles internos de funcionamiento.
    - Se proporcionan entradas y se revisan las salidas.
-  **Caja blanca**: Se examina el código y su ejecucion para saber como se llega al resultado deseado.
    - Examinación del código fuente y su ejecución.
    - Comprobacion de los flujos de ejecución.(Dentro de la unidad, entre unidades o entre subsistemas).
---
### Tipos de prueba
- **Funcionales**: Evaluan el cumplimiento de los requisitos.
    - Pruebas unitarias.
    - Pruebas de regresión.
    - pruebas de integración.
    - Pruebas de humo.
    - Pruebas del sistema.
    - Pruebas alfa y beta.
    - Pruebas de aceptación.
- **No funcionales**: Evaluan aspectos adicionales como rendimiento, seguridad, ...
    - Pruebas de usabilidad.
    - pruebas de rendimiento.
    - pruebas de stress.
    - Pruebas de seguridad.
    - Pruebas de compatibilidad.
    - Pruebas de portabilidad.
---
### Mecanismos de prueba
- Manual:
    - Realizada por una persona cualificada.
- Automático:
    - Mediante software que compara los resultados de ejecución con los esperados de manera automática.
---
- **Soporte del depurador**
    - Puntos de ruptura.
    - Ejecución paso a paso.
    - Análisis de variables.
- **Automatización de pruebas**
    - Frameworks de pruebas.
        - Java: JUnit, TestNG
        - C++: CppUnit, Google Test
        - PHP: PHPUnit
        - Javascript: Mocha
    - Aserciones.
---
### TDD
- Desarrollo guiado por pruebas de software(Test-Driven Development)
    - **TFD**: Escribir las pruebas primero.
    - **Refactoring**: Refactorización.
---
### Integración
- **Formas de integración**:
    - Integración Big bang
    - Integración Descendente
    - Integración Ascendente
    - Integración Continua (CI)
- **Servidores de integración continua**:
    - CI : Integración continua
    - CD : Entrega continua
        - Jenkins: Software escrito en java de còdigo abierto sacada en 2005.
        - Bamboo: Funciona a través de la interfaz web, escrito en java, sacado en 2007.
        - TravisCI: Bastante unido a GitHub, se configura facilmente con un archivo YAML, codigo abierto.
---
# Cobertura del código
- Porcentaje de código ejecutado durante las pruebas.
- resultado deseado lo más proximo al 100%.
- Si es del 100%, se ejecutó todo el código en la prueba.
- Si es menor es que hay código que no se esta usando en el programa.
- Se puede hacer cobertura desde el IDE o un servicio web apropiado.
---
# Factores de calidad
- **Operación del producto**
    - Corrección: Propiedad del software de arreglar osibles errores.
    - Fiabilidad: Capacidad del software de funcionar bien.
    - Eficiencia: que haga su tarea de la mejor manera posible y con el mínimo de pèrdidas.
    - Seguridad: Que proteja al usuario y al propio programa de posibles males.
    - Facilidad de uso: La facilidad de un usuario nuevo en aprender a usar el programa
    - correctamente.
- **Revisión del producto**
    - Mantenibilidad: Que se puedan hacer mantenimientos periòdicos.
    - Flexibilidad: que se pueda adaptar a errores comunes e incluso solucionarlos.
    - Facilidad de prueba: que sea facil de poner a prueba su funcionamiento bajo ciertas
    - circumstancias.
- **Transición del producto**
    - Portabilidad: que se pueda almacenar en unidades portables(USB, CD...)
    - Reusabilidad: Si un usuario usa el programa, si viene otro usuario luego se pueda
    - volver a usar(Como un instalador por ejemplo).
    - Interoperatividad: Lo bien que funcionan sus enlaces internos de còdigo.

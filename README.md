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
- **Mecanismos de prueba**
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
- **TDD**
- Desarrollo guiado por pruebas de software(Test-Driven Development)
    - ****TFD****: Escribir las pruebas primero.
    -

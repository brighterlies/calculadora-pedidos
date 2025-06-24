# GRUPO 9 Ejercicio Guiado: Pruebas Unitarias con JUnit en una Calculadora de Pedidos

## Preguntas finales

## 1. ¿Qué te ayudaron a identificar las pruebas unitarias?

Las pruebas unitarias ayudaron a detectar errores lógicos en el cálculo del total del pedido y a verificar que los casos límite, como descuentos o tipos de envío, funcionaran correctamente sin ejecutar toda la aplicación.

## 2. ¿Cuál fue el beneficio de usar un mock para simular una dependencia?

El uso de mocks con `Mockito` permitió aislar la lógica de `PedidoService.java`, haciendo que las pruebas fueran rápidas, predecibles y enfocadas solo en la unidad probada.

## 3. ¿Qué pasaría si se modifica la lógica de descuentos sin actualizar las pruebas?

Si no se actualizan las pruebas tras cambios funcionales, pueden generar falsos positivos y pérdida de confianza en la automatización, ocultando errores que lleguen a producción.

## 4. ¿Cómo escalamos esta estrategia para un sistema más grande?

Para escalar la estrategia en un sistema más grande, se debe mantener una organización modular del código y las pruebas, agruparlas por tipo (unitarias, integración, contractuales), automatizar su ejecución en `CI/CD` y usar herramientas como `JaCoCo` para asegurar calidad y cobertura.

----------------

## Capturas de pantalla
- Las capturas de pantalla de las pruebas funcionando se encuentran en la carpeta `screenshots`.
- La captura del workflow corriendo en `GitHub Actions` también se encuentra en `screenshots`.

## Resumen:
Este ejercicio mostró el valor de las pruebas automatizadas, enseñó a estructurarlas, usar `Mockito` para simular dependencias y automatizarlas con `GitHub Actions`, reforzando buenas prácticas de calidad y DevOps.

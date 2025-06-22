# Calculadora de Pedidos – Pruebas Unitarias con JUnit y GitHub Actions

Este proyecto simula una aplicación backend que calcula el total de un pedido aplicando descuentos y costos de envío. Fue desarrollado con enfoque DevOps, incorporando pruebas unitarias, mocks para simular dependencias y automatización de pruebas con GitHub Actions.

## GRUPO 5:
- Juan Villaman  
- Cristóbal de Jesus  
- Victor Figueroa  

---

## ¿Qué te ayudaron a identificar las pruebas unitarias?

Las pruebas unitarias ayudaron a identificar rápidamente si la lógica de cálculo en `PedidoService` era correcta. Además, permitieron detectar errores con precisión y aseguraron que los cambios no rompieran funcionalidades previas del código.

---

## ¿Cuál fue el beneficio de usar un mock para simular una dependencia?

El uso de mocks permitió probar la lógica del servicio de pedidos sin depender de la implementación real del repositorio de descuentos. Esto facilitó pruebas más rápidas, predecibles y controladas, sin necesidad de una base de datos real.

---

## ¿Qué pasaría si se modifica la lógica de descuentos sin actualizar las pruebas?

Podríamos obtener resultados incorrectos sin darnos cuenta. Las pruebas empezarían a fallar, mostrando que algo ha cambiado, pero si no están actualizadas, podrían reportar errores falsos o, peor aún, pasar sin detectar fallos reales.

---

## ¿Cómo escalamos esta estrategia para un sistema más grande?

Dividiendo el sistema en módulos probables por separado, automatizando pruebas en CI/CD, usando inyección de dependencias para facilitar mocks, y manteniendo cobertura de pruebas alta en componentes críticos. Así se asegura calidad al crecer el sistema.

---

## Reflexión final

En un entorno profesional DevOps, lo que hicimos hoy refleja prácticas fundamentales: integración continua, pruebas automatizadas y control de versiones. Al crear una lógica de negocio, probarla con JUnit, simular dependencias con mocks y automatizar todo con GitHub Actions, experimentamos un ciclo completo DevOps. Este flujo garantiza calidad constante, evita errores en producción y permite despliegues seguros. Por ejemplo, si trabajáramos en una aplicación de e-commerce, este mismo enfoque permitiría validar descuentos, envíos y lógica crítica sin intervención manual. Además, aplicar esto en proyectos personales mejora la disciplina técnica, fortalece el portafolio profesional y demuestra habilidades clave muy valoradas en equipos modernos.

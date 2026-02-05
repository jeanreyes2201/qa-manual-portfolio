# 📋 Plan de Pruebas: JPetStore Demo

## 1. Introducción
Este plan define la estrategia de pruebas para la aplicación **JPetStore**. El objetivo es validar los flujos críticos de negocio, asegurando la calidad bajo el ciclo de vida **STLC**.

## 2. Alcance (Scope)
Se realizarán pruebas sobre los siguientes módulos:
* **Módulo de Inventario:** Visualización de productos y categorías.
* **Módulo de Carrito:** Adición, eliminación y actualización de productos.
* **Módulo de Usuario:** Flujo de Login y Registro.

## 3. Tipos de Pruebas a Realizar
* **Pruebas Funcionales:** Validación de requerimientos del sistema.
* **Pruebas Exploratorias:** Sesiones de 30 min para identificar errores no documentados.
* **Pruebas de Rendimiento:** Pruebas de Carga y Estrés con **JMeter** para medir tiempos de respuesta en el catálogo.

## 4. Herramientas (Stack)
* **Gestión de Pruebas:** Jira + Zephyr Scale (Diseño y trazabilidad).
* **Defectos:** Jira Software para el ciclo de vida del bug.
* **Performance:** Apache JMeter.

## 5. Entorno de Pruebas
* **URL:** https://petstore.octoperf.com/
* **Navegador:** Google Chrome (Última versión).
* **Herramientas de soporte:** Chrome DevTools para análisis de consola y red.

## 6. Criterios de Aceptación
* El 100% de los casos de prueba críticos deben estar ejecutados.
* No deben existir bugs abiertos de prioridad "Alta" o "Bloqueante".

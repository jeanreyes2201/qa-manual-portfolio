# Pruebas de Rendimiento 

En esta carpeta detallo la estrategia para evaluar la velocidad y estabilidad de la calculadora.

### Objetivo
Identificar tiempos de respuesta y posibles cuellos de botella cuando hay múltiples usuarios concurrentes mediante pruebas de carga y stress con Jmeter.

### Configuración
Para ejecutar estas pruebas, sigo este flujo de trabajo en la herramienta:

1. **Test Plan:** Creación del plan de pruebas principal.
2. **Thread Group (Usuarios):** Configuración de 50 usuarios virtuales con un *Ramp-up* de 10 segundos.
3. **HTTP Request:** Configuración de la URL de la calculadora y el método (GET) para las operaciones.
4. **Listeners (Resultados):** Implementación de "View Results Tree" y "Summary Report" para analizar los datos.
5. **Generación de Reporte Visual (Dashboard)
Para obtener un análisis profesional, utilizo la línea de comandos de Windows (CMD) para ejecutar la prueba y generar un reporte automático en formato HTML.
6. **Marcar en Rosado en el reporte de excel tomando en cuenta estos valores de referencia si.....
elapsed (ms)	es mayor a 1500
Latency (ms)	es mayor a 1000
Connect (ms)	es mayor a 500
Response Code es diferente a 200 0 302 

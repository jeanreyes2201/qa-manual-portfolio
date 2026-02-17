## Resumen de la Prueba de Estrés 

Se a evaludado la estabilidad y el tiempo de respuesta del servidor de la calculadora ante un aumento progresivo de carga, identificando el comportamiento del sistema bajo una concurrencia de **100 usuarios**.


### Validaciones (Assertions)
Para asegurar la integridad de los datos, no solo se validó la disponibilidad técnica, sino también la funcional:
* **Código de Respuesta HTTP:** Se verificó que todas las peticiones retornaran un código `200 OK`.
* **Validación de Interfaz:** Se confirmó mediante *Response Assertions* que el servidor entregara el campo de resultado (`numberAnswerField`) correctamente bajo carga, asegurando que la lógica de negocio se mantuvo activa.

### Conclusión
La aplicación demostró ser **altamente estable** para el volumen de usuarios probado. Los tiempos de respuesta se mantuvieron consistentes (promedio de 230ms) incluso en el punto máximo de estrés, sin presentar degradación de servicio ni fugas de memoria evidentes durante la ejecución escalonada.

---
*Prueba ejecutada con Apache JMeter 5.6.3 utilizando Stepping Thread Group para carga progresiva.*



<img width="824" height="400" alt="prueba de stress calculadora" src="https://github.com/user-attachments/assets/336cd7fa-b0b6-4097-9cf0-2b4162362180" />




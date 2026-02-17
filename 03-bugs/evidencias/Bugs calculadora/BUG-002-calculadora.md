# BUG: Falta de validación en campos vacíos 
**ID:** `KAN-BUG-02`  
**Estado:** `Nuevo`  
**Prioridad:** `Media`  
**Severidad:** `Menor`

---

### Descripción
El sistema no valida la ausencia de datos en los campos de entrada. Al dejar los campos vacíos y presionar "Calculate", la aplicación procesa la operación asumiendo que el valor es `0` en lugar de exigir una entrada numérica obligatoria.

### Ambiente
- **Navegador:** Brave v.1.86.148
- **Build:** Prototype
- **URL:** https://testsheepnz.github.io/BasicCalculator.html

---

### Pasos para reproducir
1. Entrar a la aplicación de la calculadora.
2. Dejar un campo vacio **Primer numero"** o **"Segundo numero"** vacíos.
3. Seleccionar una operación (ej. "Multiply").
4. Hacer clic en el botón **"Calcular"**.

---

### Evidencia 
<img width="1358" height="1734" alt="BUG-002 CALCULADORA" src="https://github.com/user-attachments/assets/03d51ca5-5c74-428b-839a-778e13dfec12" />




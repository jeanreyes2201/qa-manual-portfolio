# 🐛 Reporte de Bug: KAN-T3

## Título
**[BUG]** Error de validación: Permite el ingreso de caracteres alfabéticos en la operación de multiplicación.

---

## 📄 Información General
- **ID del Defecto:** `KAN-T3`
- **Severidad:** Alta (Afecta la integridad de los cálculos)
- **Prioridad:** Media
- **Estado:** Abierto
- **Ambiente:** Navegador Brave/ Build Prototype

---

## 🛠️ Pasos para Reproducir
1. Abrir la aplicación de la calculadora.
2. Ingresar caracteres alfabéticos (Ej: `"ABC"`) en el primer campo de entrada.
3. Ingresar un valor numérico (Ej: `"10"`) en el segundo campo.
4. Presionar el botón **"Multiplicar"**.

## 🎯 Resultado Esperado
El sistema debe validar la entrada y mostrar un mensaje de advertencia: *"Solo se aceptan valores numéricos"*. N

## ⚠️ Resultado Actual
El sistema permite ingresar datos alfanumericos.

---

## 📸 Evidencia
*(Opcional: Si tienes una captura del error, puedes ponerla aquí)*
![Captura del Error](<img width="1358" height="1742" alt="error datos no numericos" src="https://github.com/user-attachments/assets/4064b352-51ee-4a63-bf95-bb39633c5ff4" />
)

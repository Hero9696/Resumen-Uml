---
title: Hora 10 - Diagramas de Secuencia
hora: 10
tipo: Resumen UML
fecha: 2025-04-12
tags:
  - uml
  - resumen
  - hora10
  - secuencia
  - interacción
  - objetos
---

# 🎯 Objetivo
- Representar la **interacción entre objetos** en el tiempo
- Mostrar el orden cronológico de los mensajes
- Visualizar cómo colaboran los objetos para ejecutar un proceso

---

## 📌 Conceptos clave

- 📦 Objeto: Participante en la interacción (instancia de clase)
- 🕓 Línea de vida: Línea vertical que muestra la existencia del objeto
- 📤 Mensaje: Comunicación entre objetos (llamada a método)
- 🔄 Bucle / condición: Control de flujo con estructuras (`alt`, `loop`, `opt`)

---

## 📐 Notación UML

- Objeto: `Nombre : Clase`
- Línea de vida: Línea vertical bajo el objeto
- Mensajes: Flechas horizontales con nombre del método
- Activación: Rectángulo delgado en la línea de vida (tiempo de ejecución)
- Control de flujo:
  - `alt`: condiciones alternativas
  - `opt`: ejecución opcional
  - `loop`: repetición

---

## 📋 Ejemplo: Proceso de compra en línea

1. Usuario solicita productos
2. Sistema busca productos
3. Usuario selecciona y realiza compra
4. Sistema valida pago
5. Sistema confirma pedido

---

## 🧠 Usos comunes

- Visualizar flujos detallados entre objetos
- Mostrar cómo se ejecuta un caso de uso
- Identificar responsabilidades de clases

---
## ✍️ Reflexión personal
Esta hora me hizo entender mejor cómo los objetos colaboran entre sí. Aprendí que la interacción bien modelada puede prevenir malentendidos en el diseño lógico del sistema.
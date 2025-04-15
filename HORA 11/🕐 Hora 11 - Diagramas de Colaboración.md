---
title: Hora 11 - Diagramas de Colaboración
hora: 11
tipo: Resumen UML
fecha: 2025-04-12
tags:
  - uml
  - resumen
  - hora11
  - colaboración
  - objetos
  - interacción
---

# 🎯 Objetivo
- Mostrar **cómo interactúan los objetos** para cumplir un propósito
- Representar la **estructura estática** y la **dinámica** de una interacción
- Parecido al diagrama de secuencia, pero enfocado en relaciones espaciales

---

## 📌 Conceptos clave

- 📦 Objetos: Instancias que colaboran entre sí
- 🔗 Asociaciones: Conexiones entre los objetos (líneas)
- 🔢 Mensajes numerados: Secuencia de la interacción
- ↪️ Dirección de los mensajes: indica el flujo de control

---

## 🧠 Diferencias con el diagrama de secuencia

| Diagrama de Secuencia      | Diagrama de Colaboración        |
|----------------------------|---------------------------------|
| Enfocado en el **tiempo**  | Enfocado en las **relaciones** |
| Mensajes en orden vertical | Mensajes con números            |
| Ideal para flujos lineales | Ideal para mostrar estructura   |

---

## 📋 Ejemplo: Proceso de pago

1. Usuario inicia pago
2. Sistema valida datos
3. Sistema envía a pasarela de pago
4. Pasarela responde
5. Sistema confirma al usuario

---

## 📐 Notación visual

- Objetos como cajas
- Conectados por líneas con flechas (relaciones)
- Mensajes numerados: `1: iniciarPago()`, `2: validarDatos()`, etc.

---

## 🧠 Usos comunes

- Visualizar la colaboración entre clases
- Complementar los diagramas de secuencia
- Documentar interacciones de sistemas distribuidos

---
## ✍️ Reflexión personal
Me encantó lo gráfico de los diagramas de secuencia. Me ayudaron a ordenar mentalmente los pasos de un proceso y ver los mensajes que fluyen entre objetos. Son excelentes para detectar omisiones.
---
title: Hora 13 - Diagramas de Actividad
hora: 13
tipo: Resumen UML
fecha: 2025-04-13
tags:
  - uml
  - resumen
  - hora13
  - actividad
  - flujo
  - procesos
---

# 🎯 Objetivo
- Modelar **procesos de negocio**, **flujos de trabajo** o **algoritmos**
- Mostrar cómo fluye la actividad de un paso a otro
- Enfocado en la **secuencia de acciones**

---

## 📌 Conceptos clave

- 🔘 Nodo inicial (`•`): Inicio del proceso
- 🟦 Actividad: Acción o tarea (rectángulo con bordes redondeados)
- 🔀 Decisión (`diamante`): Bifurcaciones o condiciones
- 🔄 Bucle: Flujos que regresan al mismo punto
- ➡️ Transición: Flechas entre actividades
- 🛑 Nodo final (`⊗`): Fin del proceso

---

## 📋 Ejemplo: Publicación de artículo

1. Escribir borrador
2. Revisar contenido
3. ¿Aprobado?
   - Sí → Publicar
   - No → Editar y regresar a revisión
4. Fin

---

## 📐 Notación visual

- Flechas indican flujo
- Diamantes para decisiones
- Acciones como bloques
- Posibilidad de paralelismo con barras (`fork` y `join`)

---

## 🧠 Usos comunes

- Procesos de negocio
- Lógica de programas
- Validar condiciones y decisiones

---
## ✍️ Reflexión personal
Esta hora me hizo reflexionar sobre cómo cambian las cosas con el tiempo. Comprender los estados por los que pasa un objeto o sistema me ayudó a ver la importancia del control de flujo y validación en tiempo real.
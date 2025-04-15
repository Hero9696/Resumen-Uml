---
title: Hora 09 - Diagramas de Caso de Uso
hora: 9
tipo: Resumen UML
fecha: 2025-04-12
tags:
  - uml
  - resumen
  - hora09
  - caso
  - de
  - uso
  - usuarios
  - sistema
---

# 🎯 Objetivo
- Representar **interacciones entre los actores y el sistema**
- Modelar los **requerimientos funcionales**
- Describir **qué hace el sistema**, no **cómo lo hace**

---

## 👥 Elementos clave

- 👤 Actor: Usuario u otro sistema externo que interactúa con el sistema
- 🎬 Caso de uso: Función o servicio proporcionado por el sistema
- ⚪ Sistema: Caja que encierra los casos de uso
- ➕ Relaciones:
  - ➕ Include (`<<include>>`): Reutilización obligatoria
  - 🔁 Extend (`<<extend>>`): Opción extendida, condicional

---

## 📋 Ejemplo: Portal de compras

- 👤 Cliente
  - Buscar productos
  - Añadir al carrito
  - Realizar pago
- 👤 Administrador
  - Gestionar catálogo
  - Ver reportes

---

## 📐 Notación visual

- ⭕ Casos de uso: óvalos
- 👤 Actores: figuras humanas (stickman)
- Caja: representa el sistema
- Flechas: interacciones entre actor y caso de uso
- `<<include>>` y `<<extend>>`: relaciones especiales

---

## 🧠 Usos comunes

- Identificar requisitos funcionales del sistema
- Ayudar a la comunicación con el cliente o usuario final
- Crear base para diseño posterior (escenarios, pruebas)

---
## ✍️ Reflexión personal
Vi la diferencia entre lo estático (clases) y lo dinámico (objetos). Me gustó mucho cómo los diagramas de objetos permiten simular momentos precisos del sistema. Me ayudó a pensar en pruebas y validaciones.
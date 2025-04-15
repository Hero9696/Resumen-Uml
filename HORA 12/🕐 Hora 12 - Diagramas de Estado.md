---
title: Hora 12 - Diagramas de Estado
hora: 12
tipo: Resumen UML
fecha: 2025-04-12
tags:
  - uml
  - resumen
  - hora12
  - estado
  - comportamiento
  - máquina
  - de
  - estados
---

# 🎯 Objetivo
- Modelar el **comportamiento dinámico de un objeto**
- Mostrar los **estados posibles** y las **transiciones** entre ellos
- Ideal para objetos que **cambian de estado en respuesta a eventos**

---

## 📌 Conceptos clave

- ⚪ Estado: Situación en la que se encuentra un objeto
- 🔄 Transición: Cambio de estado por un evento o condición
- ▶️ Estado inicial: Punto de partida (`•`)
- ⏹️ Estado final: Punto de término (`⊗`)
- 🧩 Evento: Acción que provoca la transición
- 🛠 Acción: Lo que ocurre durante la transición

---

## 📋 Ejemplo: Pedido en línea

1. `Nuevo` → (confirmar) → `Confirmado`
2. `Confirmado` → (pagar) → `Pagado`
3. `Pagado` → (enviar) → `Enviado`
4. `Enviado` → (recibir) → `Entregado`
5. Cualquier estado → (cancelar) → `Cancelado`

---

## 📐 Notación visual

- Rectángulos redondeados: Estados
- Flechas: Transiciones
- Texto sobre flechas: `evento / acción`
- Punto negro (`•`): Estado inicial
- Círculo con borde (`⊗`): Estado final

---

## 🧠 Usos comunes

- Ciclos de vida de objetos
- Validación de comportamientos esperados
- Modelado de sistemas reactivos o controladores

---
## ✍️ Reflexión personal
Descubrí que los diagramas de colaboración me permiten observar relaciones y dependencias. Ver cómo se estructuran las conexiones entre objetos me dio claridad sobre posibles acoplamientos excesivos.
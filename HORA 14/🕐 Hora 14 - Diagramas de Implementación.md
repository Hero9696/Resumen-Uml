---
title: Hora 14 - Diagramas de Implementación
hora: 14
tipo: Resumen UML
fecha: 2025-04-13
tags:
  - uml
  - resumen
  - hora14
  - implementación
  - despliegue
  - componentes
---

# 🎯 Objetivo
- Representar cómo se **implementa físicamente un sistema**
- Mostrar **nodos de hardware** y **artefactos de software**
- Visualizar cómo se distribuye la aplicación en diferentes entornos

---

## 📌 Conceptos clave

- 🧱 Nodo: Representa un recurso físico (servidores, dispositivos)
- 📦 Componente: Parte lógica o física de una app (bibliotecas, ejecutables)
- 📄 Artefacto: Resultado tangible del desarrollo (archivos `.exe`, `.jar`, etc.)
- 🔗 Asociación: Conexión física o lógica entre nodos

---

## 🧠 Tipos de nodos

- 🌐 Servidor Web
- 💾 Base de datos
- 📱 Cliente móvil o desktop
- ☁️ Nube / contenedor / microservicio

---

## 📋 Ejemplo: App de pedidos en línea

1. Cliente móvil se comunica con el servidor
2. El servidor procesa la lógica del pedido
3. El servidor se conecta con la base de datos
4. Se despliega en contenedores (Docker, etc.)

---

## 📐 Notación visual

- Cajas 3D para nodos
- Cajas normales para componentes o artefactos
- Flechas para relaciones de comunicación o despliegue

---

## 🧠 Usos comunes

- Arquitectura de software
- Planeación del entorno de producción
- Documentación de infraestructura técnica

---
## ✍️ Reflexión personal
Al ver gráficamente los cambios de estado, entendí mejor cómo representar comportamientos complejos. Me resultó útil para pensar en interfaces, menús, ciclos de vida de usuario, etc.
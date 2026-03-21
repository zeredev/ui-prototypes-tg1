# 📚 Sistema de Gestión de Librería: Prototipos UI (TG1)

[![Academic Project](https://img.shields.io/badge/Grado-Ingeniería_de_Computadores-blue)](#)
[![Status](https://img.shields.io/badge/Status-Completado-success)](#)
[![Design](https://img.shields.io/badge/UI_Style-Blue_Night_&_Slate-3b82f6)](#)

Este repositorio contiene la propuesta de interfaces de usuario de alta fidelidad para la asignatura de **Ingeniería del Software (TG1)**. El proyecto presenta una suite integral de herramientas para la gestión operativa y estratégica de una librería técnica.

## 🚀 Demo en Vivo
Si deseas explorar los prototipos sin descargar el código, puedes acceder a la versión desplegada aquí:
👉 **[https://zeredev.github.io/ui-prototypes-tg1/]**

---

## 🎨 Características del Diseño
Se ha implementado un sistema de diseño unificado bajo la estética **"Blue Night & Slate"** (Modo Oscuro), enfocado en la eficiencia profesional:

* **Navegación Centralizada:** Un panel principal (`index.html`) organiza los módulos en una cuadrícula 2x2 optimizada.
* **Consistencia Visual:** Uso de una paleta coherente (Fondo `#0f172a`, Tarjetas `#1e293b`) y tipografía `Segoe UI`.
* **Feedback Interactivo:** Uso de micro-interacciones CSS y ventanas modales para validar flujos de trabajo críticos.
* **Portabilidad:** Cada interfaz es un archivo autocontenido (Single-file), facilitando su revisión inmediata.

---

## 🛠️ Módulos del Sistema

### 1. Centro de Control (`index.html`)
El portal de acceso al ecosistema. Permite al usuario navegar entre las diferentes áreas funcionales mediante un diseño responsivo y equilibrado.

### 2. Análisis Estratégico (`analizar_tendencias.html`)
* **Concepto:** Dashboard de Business Intelligence (BI).
* **Tecnología:** Simulación de integración con **Tableau Cloud**.
* **Funcionalidad:** Filtros dinámicos por género y sistema de **alertas predictivas de stock** para evitar rupturas de inventario.

### 3. Recepción de Imprenta (`procesar_imprenta.html`)
* **Concepto:** Módulo logístico de entrada de mercancía.
* **Lógica de Negocio:** Incluye detección automática de **Pedidos Pendientes**. Si entra un libro con reservas, el sistema despliega un modal interactivo para proceder con la facturación inmediata a clientes.

### 4. Estado de Cuentas (`informe_estado_cuentas.html`)
* **Concepto:** Vista financiera para el Responsable de Tienda.
* **Arquitectura:** Basado en un modelo de datos híbrido que utiliza **MySQL** para transacciones y **Apache Cassandra** para el análisis de históricos de largo volumen (60 meses).
* **Análisis:** Cálculo automático de beneficio neto con alertas visuales de balances negativos.

### 5. Histórico de Libros (`historico_libro.html`)
* **Concepto:** Herramienta de auditoría y trazabilidad.
* **Funcionalidad:** Permite rastrear la evolución de ventas y entradas de cualquier ejemplar desde su primer registro en el sistema.

---

## 💻 Stack Tecnológico
* **Estructura:** HTML5 Semántico.
* **Estilos:** CSS3 (Custom Properties, Grid Layout, Flexbox).
* **Interactividad:** JavaScript nativo (Vanilla JS) para gestión de estados y modales.

## 👥 Autores
* **Ramón Fco. Pérez Villa** - [@zeredev](https://github.com/zeredev)
* **Jorge Alcázar** - [@Jalcazara](https://github.com/Jalcazara)

---
*Este proyecto ha sido desarrollado para la asignatura Ingeniería del Software en el Grado en Ingeniería de Computadores de la UAH - 2026.*

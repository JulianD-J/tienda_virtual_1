# tienda_virtual_1
# Menu colediverti - Sistema Web Futurista

Colediverti 3000 es un proyecto web que integra un **menú digital futurista** con un **PayCenter interactivo**, incluyendo un sistema de seguridad básico y elementos audiovisuales para una experiencia inmersiva.

## 🚀 Características principales

* **Menú Digital Futurista**

  * Presenta productos con sus nombres, precios e imágenes (ubicadas en la carpeta `assets/`).
  * Interfaz clara y moderna con estilo futurista.
  * Integración con PayCenter para procesar pedidos.

* **PayCenter**

  * Simula un sistema de pago futurista.
  * Incluye validación de datos para mayor seguridad.
  * Conexión con el menú para redimir productos.
  * Almacenamiento en **localStorage** para pruebas de persistencia.

* **Seguridad**

  * Sistema de confirmación de pago.
  * Prevención básica de acceso no autorizado con validación de datos.

* **Multimedia**

  * Imágenes de productos en `assets/`.
  * Efectos de sonido (ubicados en `sounds/`) para acciones clave como:

    * Clicks
    * Confirmaciones
    * Escaneo futurista

## 📂 Estructura del proyecto

```
tienda virtual/
│
├── index.html        # Menú principal futurista
├── pago.html         # PayCenter futurista
├── assets/           # Imágenes de productos
├── sounds/           # Archivos de sonido
└── README.md         # Este archivo
```

## 🛠️ Tecnologías utilizadas

* **HTML5** para la estructura.

* **localStorage** para la persistencia de datos.

## 🔒 Seguridad

* Validación de entradas en PayCenter.
* Confirmaciones antes de procesar acciones.
* Uso de `localStorage` para simular un backend seguro (solo pruebas).

## 🎧 Sonidos

Sonidos incluidos en la carpeta `sounds/`

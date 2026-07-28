# 🛡️ Ciberseguridad con Python: Control de Flujo y Filtrado de IP / IDs

Bienvenido a este repositorio. Aquí documento un laboratorio práctico realizado en **Google Colab**, enfocado en el manejo de iteraciones (`for` y `while`), control de acceso a redes mediante listas de IP permitidas (*allow lists*) y monitoreo de IDs de empleados.

---

## 📌 Resumen del Laboratorio

Este cuaderno de Google Colab contiene ejercicios prácticos organizados en tres módulos clave:

1. **Simulación de Intentos de Conexión a Red:**
   * Utilización de bucles `for` y `while` para iterar un número específico de reintentos cuando falla la conexión con un servidor o servicio (`connection could not be established.`).
   
2. **Filtrado y Control de Acceso por Dirección IP (`Allow List`):**
   * Verificación iterativa de direcciones IP dentro de una lista autorizada (`allow_list`).
   * Implementación de condicionales `if/else` para permitir el acceso o activar alertas de investigación adicional (`further investigation of login activity required`).

3. **Monitoreo de Secuencia de IDs de Empleados:**
   * Generación y validación de IDs de empleados en rangos definidos (de `5000` a `5150` con incrementos de 5).
   * Generación de alertas en tiempo real cuando se alcanza un umbral crítico de IDs disponibles (`only 10 valid employee ids remaining`).

---

## 🛠️ Tecnologías y Entorno

* **Lenguaje:** Python 3
* **Entorno de Desarrollo:** Google Colab
* **Estructuras de Control:** `for`, `while`, `if`, `else`
* **Colecciones de Datos:** Listas (`list`), listas de control de acceso (*Allow Lists*)

---

## 🚀 Cómo Ejecutar este Laboratorio

1. Abre el archivo [`Untitled0.ipynb`](./Untitled0.ipynb) directamente en GitHub.
2. Puedes abrirlo directamente en **Google Colab** haciendo clic en el botón de ejecución interactiva para probar o modificar las celdas de código.

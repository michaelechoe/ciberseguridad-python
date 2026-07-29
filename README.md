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

---

### 2. Variables y Lógica de Control de Acceso (`variables_y_logica_seguridad.ipynb`)

* **Descripción:** Aplicación de conceptos fundamentales de almacenamiento de datos y evaluación condicional para simular el comportamiento de un sistema de autenticación y detección de anomalías.
* **Conceptos clave clave:**
  * **Clasificación de datos:** Identificación dinámica del tipo de dato mediante `type()` para garantizar la integridad en operaciones (`str`, `int`, `list`, `bool`).
  * **Gestión de entidades:** Estructuración de listas de usuarios (`list`) para el control de cuentas autorizadas.
  * **Evaluación de políticas de acceso:** Implementación de operadores de comparación (`<=`) para validar si los intentos de inicio de sesión superan los límites de la política de seguridad (`max_logins`).



## 🚀 Cómo Ejecutar este Laboratorio

1. Abre el archivo [`Untitled0.ipynb`](./Untitled0.ipynb) directamente en GitHub.
2. Puedes abrirlo directamente en **Google Colab** haciendo clic en el botón de ejecución interactiva para probar o modificar las celdas de código.

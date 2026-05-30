# 🐍 Python Programming & Automation Portfolio

Este repositorio contiene los laboratorios de programación y automatización realizados durante el programa **AWS re/Start**. El enfoque principal fue dominar Python como herramienta esencial para el desarrollo de scripts, análisis de datos y administración de sistemas en la nube.


## 📂 Estructura del Proyecto

He organizado los ejercicios de manera lógica según la complejidad y el propósito:

```plaintext
/
├── 01_basics/            # Numeric data, Strings, Hello World
├── 02_collections/       # Lists, Tuples, Dictionaries, Categorize values
├── 03_logic/             # Conditionals (if/else), Loops (for/while)
├── 04_insulin_project/   # Data cleaning, String sequences, Weight & Net Charge calc
├── 05_security/          # User-defined functions, Caesar Cipher encryption
├── 06_sys_admin/         # JSON File handlers, os.system, subprocess module
└── README.md
```

## 🚀 Resumen del Módulo

### 1. Fundamentos y Tipos de Datos
* **Tipos Numéricos:** Uso de `int`, `float`, `complex` y `bool`.
* **Strings:** Manipulación avanzada de cadenas, concatenación, entrada de usuario y formateo con `.format()`.
* **Colecciones:** Gestión de estructuras de datos clave:
    * **Lists:** Secuencias ordenadas mutables.
    * **Tuples:** Secuencias inmutables (solo lectura).
    * **Dictionaries:** Mapeo de datos estructurados mediante pares clave-valor.

### 2. Control de Flujo y Lógica
* **Condicionales:** Implementación de toma de decisiones mediante `if`, `elif` y `else`.
* **Bucles:** Automatización de tareas repetitivas con `while` (basado en condiciones) y `for` (basado en secuencias/rangos).
* **Tipos Compuestos:** Creación de estructuras complejas (listas de diccionarios) para manejar inventarios del mundo real.

### 3. Aplicación Práctica: Análisis de Insulina
* **Manipulación de Cadenas:** Limpieza y extracción de secuencias de proteínas de la preproinsulina humana.
* **Cálculo Científico:** Cálculo del peso molecular y la carga neta de la insulina a través de diferentes niveles de pH (0-14).
* **Manejo de Excepciones:** Uso de bloques `try/except` para garantizar la robustez en la lectura de archivos.

### 4. Seguridad y Funciones
* **Funciones de Usuario:** Modularización de código para mejorar la reutilización.
* **Cifrado César:** Implementación de un programa de cifrado y descifrado de mensajes.

### 5. Administración de Sistemas (SysAdmin)
* **Integración con la Shell:** Uso de Python como puente hacia la terminal de Linux.
* **Módulos Críticos:** * `os.system()`: Ejecución de comandos Bash básicos.
    * `subprocess.run()`: Generación de procesos secundarios para obtener información del sistema (`uname`, `ps`, `df`).
* **Manejo de Archivos:** Lectura y parseo de archivos `JSON` para integrar datos externos en scripts.

## 💡 Aprendizajes Clave para Cloud Practitioners

1.  **Automatización:** Reducción drástica de errores manuales en tareas repetitivas del sistema (limpieza de logs, monitoreo de recursos).
2.  **Infraestructura como Código (IaC):** Estos fundamentos de Python son el paso previo esencial para dominar **Boto3** (el SDK de AWS) y automatizar la creación de recursos en la nube.
3.  **Seguridad:** Aplicación de lógica de validación de entradas y principios básicos de cifrado para proteger la integridad de los datos.
4.  **Auditabilidad y Registro:** El uso de Python para tareas de SysAdmin permite un mejor registro (logging) y rastreo de operaciones en comparación con la ejecución de comandos manuales aislados.


## 🛠️ Herramientas Utilizadas
* **IDE:** VS Code / AWS Cloud9 / AWS CloudShell.
* **Control de Versiones:** Git & GitHub.
* **Lenguaje:** Python 3.11.


## 🔗 Código Fuente y Repositorio
Puedes revisar todos los scripts y ejercicios detallados en mi repositorio de GitHub:
👉 [Python Labs repository](https://github.com/Rojerr9241/aws-restart-python-labs)

---
*Generado para el Programa AWS re/Start*
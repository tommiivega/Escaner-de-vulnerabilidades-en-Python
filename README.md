# 🔐 Vulnerability Scanner (Python)

## 📌 Descripción

Este proyecto consiste en el desarrollo de una herramienta de ciberseguridad en Python capaz de realizar escaneo de puertos de forma concurrente, identificar servicios mediante banner grabbing y generar reportes automáticos con posibles vulnerabilidades.

Incluye una interfaz gráfica simple que permite ejecutar análisis de forma intuitiva y visualizar los resultados sin necesidad de utilizar la terminal.

---

## 🚀 Funcionalidades

* 🔍 Escaneo de puertos (1–65535)
* ⚡ Ejecución concurrente mediante multithreading
* 🔒 Control de concurrencia con locks y semaphores
* 🧠 Banner grabbing para identificación de servicios
* 🛡️ Detección básica de vulnerabilidades basada en firmas
* 📄 Generación automática de reportes (report.txt)
* 🖥️ Apertura automática del reporte al finalizar
* 🎨 Interfaz gráfica con Tkinter

---

## 🧠 Tecnologías utilizadas

* Python
* Sockets
* Threading (Multithreading)
* Tkinter

---

## ⚙️ Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/tu-usuario/vulnerability-scanner.git
```

2. Acceder al proyecto:

```bash
cd vulnerability-scanner
```

3. Ejecutar la aplicación:

```bash
python gui.py
```

---

## 🖥️ Uso

1. Ingresar una dirección IP o dominio
2. Presionar el botón **Escanear**
3. Esperar a que finalice el análisis
4. El reporte se abrirá automáticamente

---

## 📄 Ejemplo de reporte

```
=== REPORTE DE ESCANEO ===
Target: 192.168.1.1

Puertos abiertos:
- Puerto 80: Apache/2.4.49
- Puerto 443:

Posibles vulnerabilidades:
- Puerto 80: Vulnerable a Path Traversal (CVE-2021-41773)
- Puerto 443: No se detectaron vulnerabilidades conocidas
```

---

## 🚧 Próximas mejoras

* Identificación automática de servicios por puerto
* Soporte para resolución de dominios (DNS)
* Modo rápido (top puertos más comunes)
* Visualización de resultados dentro de la GUI
* Barra de progreso durante el escaneo

---

## ⚠️ Disclaimer

Esta herramienta fue desarrollada con fines educativos.
No debe utilizarse para escanear sistemas sin autorización.

---

## 👨‍💻 Autor

Tomás Vega

---

## ⭐ Contribuciones

Las contribuciones, mejoras y sugerencias son bienvenidas.

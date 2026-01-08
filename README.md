# Implementación de Autenticación TOTP con Google Authenticator

Este repositorio contiene un componente software desarrollado como parte de una práctica académica, cuyo objetivo es implementar un sistema de autenticación basado en códigos temporales **TOTP (Time-based One-Time Password)**, compatible con aplicaciones móviles como **Google Authenticator**.

El proyecto permite generar un código QR para registrar un servicio en la aplicación móvil y validar posteriormente los códigos TOTP introducidos por el usuario.

---

## 📂 Estructura del proyecto

El contenido del repositorio es el siguiente:

### Descripción de los archivos

- **totp_app.py**  
  Script principal desarrollado en Python. Contiene toda la lógica necesaria para:
  - Generar una clave secreta TOTP
  - Crear la URL de aprovisionamiento compatible con Google Authenticator
  - Generar un código QR
  - Validar los códigos TOTP introducidos por el usuario

- **qr_totp.png**  
  Imagen generada automáticamente al ejecutar el programa. Contiene el código QR que se escanea desde Google Authenticator para añadir el servicio.

- **Resumen_TOTP_Paso_a_Paso.pdf**  
  Documento en PDF que describe en primera persona y paso a paso el trabajo realizado: preparación del entorno, creación de carpetas, desarrollo del código, ejecución y validación del sistema.

- **README.md**  
  Documento descriptivo del repositorio (este archivo).

---

## 📱 Requisitos previos

Para ejecutar el proyecto es necesario disponer de:

- Python 3 instalado
- Librerías Python:
  - `pyotp`
  - `qrcode`
- Aplicación móvil **Google Authenticator** instalada en el dispositivo

Instalación de dependencias:

```bash
pip install pyotp qrcode[pil]




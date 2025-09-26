# 👁️‍🗨️ Sistema de Reconocimiento Facial para el Control de Ingreso en Conferencias de la CCBOL 2024

## 👨‍💻 Autor
- **Nombre:** Navía Condori Eddy  
- **Carrera:** Ing. en Ciencias de la Computación  
- **Universidad:** San Francisco Xavier de Chuquisaca  
- **Año:** 2024  

---

## 📖 Descripción del Proyecto
Este sistema fue desarrollado con el propósito de **automatizar el control de ingreso de participantes** a las conferencias de la **CCBOL 2024**, utilizando **modelos de inteligencia artificial** para la detección y reconocimiento facial en tiempo real.  
El sistema gestiona la base de datos de los asistentes, autentica accesos mediante tokens y genera reportes de las personas registradas en el evento.

---

## ✨ Características del Proyecto
- 👁️ **Detección de rostros** con modelos **YOLOv5** y **SCRFD**.  
- 🧑‍🦲 **Reconocimiento facial** utilizando **ArcFace**.  
- 🗄️ **Base de datos en MySQL** para almacenar participantes y controlar su estado de ingreso.  
- 🌐 **API REST** desarrolladas con **Python (Flask)** para la comunicación entre módulos.  
- 🔐 **Módulo de autenticación con tokens (JWT)** para ingreso seguro al sistema.  
- 📷 **Reportes automáticos** de los participantes que ingresaron a la conferencia.  

---

## 🛠️ Tecnologías Utilizadas
### Modelos de IA:
- **YOLOv5** → Detección de rostros en imágenes y video.  
- **SCRFD** → Detección facial optimizada para escenarios en tiempo real.  
- **ArcFace** → Reconocimiento facial y verificación de identidad.  

### Desarrollo:
- **Python / Flask** → Backend y servicios REST.  
- **MySQL** → Base de datos para gestión de participantes e ingresos.   

---

## 🖼️ Imágenes del Sistema
### 🔐 Pantalla de Login
![Login](./assets/login.png)  
*Interfaz de autenticación de usuarios con tokens.*  

### 👁️‍🗨️ Módulo de Reconocimiento Facial
![Reconocimiento](./assets/face_recognition.png)  
*Ejemplo del sistema detectando y reconociendo participantes en tiempo real.*  

### 📊 Reporte de Ingresos
![Reporte](./assets/report.png)  
*Vista de reportes de los asistentes registrados en la conferencia.*  

---

## 📌 Estado del Proyecto
✅ Sistema finalizado e implementado en la **CCBOL 2024**.  
🔜 Futuras mejoras: optimización de la precisión en condiciones de baja iluminación y escalabilidad para eventos masivos.  

---

> [!IMPORTANT]  
> Por motivos de confidencialidad, no es posible compartir el código fuente del proyecto, pero estoy dispuesto a discutir el proceso de desarrollo y los retos técnicos enfrentados.

# 🛏️ Sistema de Sorteos para Red de Almacenes de Colchones

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![GUI](https://img.shields.io/badge/Interfaz_Gr%C3%A1fica-Swing/JavaFX-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Estado-En_Proceso-yellow?style=for-the-badge)

> Una aplicación de escritorio intuitiva y dinámica desarrollada en Java, diseñada para automatizar, gestionar y visualizar los sorteos mensuales de fidelización de una cadena de almacenes de colchones con múltiples sedes.

---

## 💡 Sobre el Proyecto

Este proyecto resuelve la necesidad de una cadena de colchonerías de gestionar sorteos mensuales para sus clientes más fieles. Para participar, el cliente debe depositar en un sobre al menos 3 tickets de compras realizadas en distintas sedes y en días diferentes. 

El enfoque principal de este desarrollo es la **implementación robusta de lógica de Interfaz Gráfica (GUI)**, garantizando una experiencia de usuario fluida para el administrador del almacén, desde la configuración inicial del sorteo hasta la visualización en vivo de los ganadores.

### 📸 Vista Previa
*(Imagen)*
> `(ruta/imagen.png)`

---

## ✨ Características Principales

* 🎟️ **Generación de Códigos Inteligente:** El sistema maneja una lógica de códigos de participante basada en la fecha de entrega del sobre (día y mes) y los últimos 4 dígitos del ticket de compra de su colchón o accesorios (Ej: `19091058`).
* 📅 **Rangos Dinámicos por Mes:** La aplicación adapta automáticamente el rango de números sorteables según el mes seleccionado por el administrador (por ejemplo, en septiembre va de `01090001` a `30099999`, y en octubre de `01100001` a `31109999`).
* 🏆 **Visualización Acumulativa:** Los números ganadores se revelan uno a uno mediante la interacción con un botón y se organizan visualmente en una tabla en el lado derecho de la pantalla, manteniendo la expectativa y transparencia durante el sorteo.
* 🧹 **Gestión de Estado de la UI:** Cuenta con un botón de cierre/finalización que limpia y vacía todos los campos de la interfaz gráfica, dejándola lista para un nuevo ciclo sin necesidad de reiniciar la app.

---

## 🧠 Arquitectura y Lógica Técnica

Para los equipos de desarrollo y reclutadores técnicos, este proyecto destaca por:
* **Manejo de Estructuras de Datos:** Utilización eficiente de **vectores** para almacenar y ordenar cada número ganador dentro de la posición correspondiente al puesto del premio.
* **Control de Eventos GUI:** Lógica controlada por eventos (listeners) donde el usuario define variables clave como el *número de mes* y la *cantidad de ganadores* (cifra que puede variar mes a mes) antes de iniciar la visualización.
* **Separación de Responsabilidades:** El código está enfocado puramente en mantener limpia la **lógica de la interfaz gráfica**, actualizando componentes visuales (tablas, campos de texto, botones) en tiempo real.

---

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Java (JDK 21.0.12)
* **Interfaz Gráfica:** Java Swing / JavaFX
* **IDE Recomendado:** IntelliJ IDEA

---

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/MishelleBohorquez/Sistemas-de-Sorteos.git

# Sistema POS & Gestión de Inventario (Desktop) 🖊️📒

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-007396?style=for-the-badge&logo=java&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

> **Proyecto:** Aplicación de Escritorio para la administración integral de "Papelería Cooper".
> **Rol:** Desarrollador Único (Full Lifecycle Development).

## 📖 Descripción Técnica
Proyecto individual desarrollado para resolver las necesidades de un punto de venta físico. A diferencia de mis proyectos web, esta solución de escritorio fue construida íntegramente en **Java** para optimizar recursos locales.

Fui responsable de todo el ciclo de vida del software: desde el levantamiento de requerimientos con el cliente hasta el diseño de la base de datos y la programación de la interfaz gráfica.

---

## 💻 Módulos Desarrollados

### 1. Punto de Venta (POS)
Interfaz optimizada para teclados (Hotkeys). Implementé la lógica de cálculo de precios, impuestos y cambio en tiempo real.
![Punto de Venta](assets/pos_system.png)

### 2. Módulo de Seguridad y Auditoría
Diseñé un sistema de logs inmutables que registra cada movimiento sensible (quién borró un producto, quién editó un precio), proporcionando seguridad al dueño del negocio.
![Logs](assets/audit_log.png)

### 3. Gestión Administrativa
CRUDs completos para el manejo de inventario, proveedores y empleados, conectados a una base de datos MySQL local.
![Menú](assets/main_menu.png)

---

## ⚙️ Arquitectura
* **Patrón MVC:** Separación estricta entre la lógica de negocio y la interfaz JavaFX.
* **Maven:** Gestión de dependencias automatizada.
* **MySQL:** Base de datos relacional para asegurar la integridad transaccional.

---

### 📬 Contacto
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/eddaann)

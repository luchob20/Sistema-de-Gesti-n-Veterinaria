# 🐾 Sistema de Gestión Veterinaria  
**Proyecto Académico – Panel Administrativo con Java SE & Swing**

---

## 📌 Descripción del Proyecto

El **Sistema de Gestión Veterinaria** es una aplicación de escritorio desarrollada en **Java SE utilizando Swing**, que permite administrar la información principal de una clínica veterinaria.

El sistema simula un entorno real donde el usuario puede gestionar:

- 👤 Dueños  
- 🐶 Mascotas  
- 🩺 Veterinarios  
- 📅 Citas veterinarias  

Cada módulo cuenta con funcionalidades de **Crear, Leer, Actualizar y Eliminar (CRUD)** completamente conectadas a una **base de datos PostgreSQL**.

Además, incluye un **menú principal con navegación moderna e íconos gráficos**, ventanas independientes y control total de datos.

---

## 📂 Características Principales

### 🔧 Gestión del Menú
- Ventana principal tipo dashboard.
- Botones con iconos para navegar a cada módulo.
- Cierre seguro mediante opción centralizada.

### 📁 CRUD Funcionales
Cada módulo permite:
- Registrar nuevos datos  
- Editar información existente  
- Eliminar registros  
- Buscar y visualizar en tablas dinámicas  

### 💾 Conexión a Base de Datos PostgreSQL
- Uso de JDBC con una clase de conexión centralizada.
- Persistencia real en tablas relacionadas.
- Manejo de llaves foráneas y borrado en cascada.

### 🔗 Relaciones Implementadas
- Un dueño puede tener múltiples mascotas.  
- Una mascota puede tener múltiples citas.  
- Cada cita está asignada a un veterinario.

---


## 🛠️ Tecnologías Utilizadas

- **Java SE 8+**
- **Swing (JFrame, JPanel, JTable, JComboBox, etc.)**
- **PostgreSQL 15+**
- **JDBC**
- **NetBeans 19**
- **Modelo DAO**
- **Manejo de eventos ActionListener / MouseListener**

---

## 🗄️ Script de Base de Datos (PostgreSQL)

El proyecto utiliza esta base de datos totalmente funcional:

👉 **Incluye:**  
✓ Dueños  
✓ Mascotas  
✓ Veterinarios  
✓ Citas  
✓ Registros iniciales  
}
## 🚀 Instalación y Ejecución

### 1️⃣ Requisitos previos
Asegúrate de tener instalado:

- Java JDK 8 o superior
- PostgreSQL
- NetBeans / IntelliJ / Eclipse

### 2️⃣ Configurar la Base de Datos
1. Abrir pgAdmin o consola de PostgreSQL  
2. Ejecutar el archivo SQL proporcionado  
3. Confirmar creación de tablas y datos

### 3️⃣ Configurar Conexión en Java
En la clase:

Actualizar:

```java
private static final String URL = "jdbc:postgresql://localhost:5432/veterinaria";
private static final String USER = "postgres";
private static final String PASS = "TU_CONTRASEÑA";

###4️⃣ Ejecutar el Proyecto

1.Abrir NetBeans
2.Cargar el proyecto
3.Limpiar y construir
4.Ejecutar Principal.java

🎉 ¡El programa iniciará mostrando el panel principal!

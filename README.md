# Sistema CRUD para Kiosco

Un sistema completo de gestión para kioscos, diseñado como un CRUD (Crear, Leer, Actualizar, Eliminar) con funcionalidad adicional para registrar ventas y manejar roles de usuarios.

---

## 📖 Descripción

Este proyecto es un sistema CRUD desarrollado en C++ con conexión a una base de datos MySQL. Es ideal para gestionar un kiosco, permitiendo:
- Administración de productos.
- Registro de ventas.
- Manejo de roles de usuarios (dueños y empleados).

---

## 🛠️ Tecnologías y herramientas utilizadas

- **Lenguaje**: C++
- **Base de datos**: MySQL
- **Librerías**:
  - `mysql.h`: Para la conexión con MySQL.
  - `iostream`: Entrada y salida estándar en C++.
  - `sstream`: Formateo de strings en consultas SQL.

---

## 🎯 Funcionalidades

### 1. Roles de usuario
El sistema soporta dos roles:
- **Dueño**:
  - Crear, leer, actualizar y eliminar productos.
  - Registrar ventas.
- **Empleado**:
  - Leer productos.
  - Registrar ventas.

### 2. Gestión de productos
Permite manejar productos del kiosco:
- Crear nuevos productos con nombre, precio y stock.
- Leer la lista de productos disponibles.
- Actualizar la información de un producto.
- Eliminar productos del sistema.

### 3. Registro de ventas
- Los usuarios pueden seleccionar productos, indicar la cantidad y registrar la venta.
- Los detalles de cada venta se almacenan en la base de datos.
- Calcula subtotales y totales automáticamente.

### 4. Conexión a base de datos
- Todas las operaciones CRUD interactúan con una base de datos MySQL.

---
## 📂 Estructura del proyecto
/SistemaCRUDKiosco
----- Conexionbd.h           # Conexión a MySQL
----- producto.h             # Gestión de productos
----- usuario.h              # Gestión de usuarios y roles
----- venta.h                # Registro de ventas
----- ventadetalle.h         # Detalles de ventas
----- main.cpp               # Programa principal


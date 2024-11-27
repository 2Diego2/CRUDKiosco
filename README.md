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
- Conexionbd.h (# Conexión a MySQL)
- producto.h (# Gestión de productos)
- usuario.h  (# Gestión de usuarios y roles)
- venta.h    (# Registro de ventas)
- ventadetalle.h   (# Detalles de ventas)
- main.cpp         (# Programa principal)
---
## 🖼️ Capturas de pantalla
- Sistema De login
- ![image](https://github.com/user-attachments/assets/8e0f492d-d03c-4cf2-bb14-94497888693b)
- ![image](https://github.com/user-attachments/assets/f6cbba15-f5e2-413a-acfb-a5b867188490)
- ![image](https://github.com/user-attachments/assets/53b136da-deeb-40c9-ae98-66cfd2e4950d)

- Menú principal (Propietario)
- ![image](https://github.com/user-attachments/assets/f2335044-b155-4013-943c-2be64506290c)
- Menú principal (Empleado)
- ![image](https://github.com/user-attachments/assets/c66b28f6-e5e6-4f34-bb3c-1985bb1f84b7)
- 1.Crear un Producto
- ![image](https://github.com/user-attachments/assets/c291b46d-24f8-492f-aaac-e1ce2dfb82d7)
- ![image](https://github.com/user-attachments/assets/169b8a40-481b-48e0-9cd9-5d95cfb0222e)
- ![image](https://github.com/user-attachments/assets/cf048216-ccfb-4b26-ba81-d4e5b917f3f7)
- 2. Leer Productos
- ![image](https://github.com/user-attachments/assets/d207f518-6abb-4d62-b1dc-6e9d1008b7ec)
-3.Modificar un Producto
- ![image](https://github.com/user-attachments/assets/2f5e37bf-728b-46a6-bf9c-15f0a75df2b2)
- ![image](https://github.com/user-attachments/assets/cb3d8c41-830d-450f-b0b7-2935eb8d083e)
- ![image](https://github.com/user-attachments/assets/494430ce-25f2-42cd-9aa3-210d10474266)
- ![image](https://github.com/user-attachments/assets/359ce9f2-6722-4d9b-8972-2d92af1c1d00)
- 4. Eliminar un Producto
- ![image](https://github.com/user-attachments/assets/431e9202-f46e-42cb-9cb2-5175e3e0e6bb)
- ![image](https://github.com/user-attachments/assets/9bcefd40-9446-4cf3-a5c6-58548bc976ce)
- 5. Registrar una venta
- ![image](https://github.com/user-attachments/assets/e2d12409-0308-4590-b325-bd3f5d5b935c)
- ![image](https://github.com/user-attachments/assets/9477f16d-e08f-4f63-b86f-18d218de307d)
- ![image](https://github.com/user-attachments/assets/2de9c4f7-b5ed-4cef-a650-c01784150f37)
- ![image](https://github.com/user-attachments/assets/e5d2f116-df8a-48bb-8f3e-ef3db3498351)
- 6.Crear Usuario
- ![image](https://github.com/user-attachments/assets/3e6ec517-f5cf-47b2-88bc-ddcd3eb7fd2c)
- ![image](https://github.com/user-attachments/assets/5813bbd1-b253-44ff-9d25-a108c3e8ebf1)
- ![image](https://github.com/user-attachments/assets/a3408ddf-7aed-4c49-9080-e54d02c68320)
- ![image](https://github.com/user-attachments/assets/152c3ad6-e7fc-4a66-b983-a102bdf05e4b)
- 7.Eliminar Usuario
- ![image](https://github.com/user-attachments/assets/30a6a31b-01da-4b33-bb6d-0cd6a6a97f9c)
- 8.Mostrar Ventas
- ![image](https://github.com/user-attachments/assets/2e8bf4e6-9a13-4413-b0b7-98242adca6e2)
- 9.Salir
- ![image](https://github.com/user-attachments/assets/d3af378d-8d76-4dd8-b089-9d7fd7cd0b13)

---
## 📧 Contacto
- Si tienes preguntas o comentarios sobre este proyecto, no dudes en contactarme: diegoabelleyra74@gmail.com











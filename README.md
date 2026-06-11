# 🏨 Sistema de Reservas para un Hotel

Aplicación de escritorio desarrollada en Java para la gestión de reservas hoteleras y la venta de servicios adicionales. El sistema permite administrar habitaciones, clientes, reservas y consumos, facilitando el control de las operaciones diarias de un hotel.

## 🚀 Características Principales

✅ Registro y gestión de huéspedes.

✅ Administración de habitaciones y disponibilidad.

✅ Creación, modificación y cancelación de reservas.

✅ Registro de servicios adicionales consumidos por los clientes.

✅ Cálculo automático de costos y generación de facturas.

✅ Gestión de información mediante base de datos relacional.

✅ Interfaz gráfica amigable desarrollada en Java Swing.

---

## 🛠️ Tecnologías Utilizadas

### Backend

- Java
- Programación Orientada a Objetos (POO)
- JDBC

### Base de Datos

- MySQL

### Herramientas

- NetBeans IDE
- MySQL Workbench
- Git y GitHub

---

## 📂 Estructura del Proyecto

```text
src/
├── com.mycompany.modelos
├── com.mycompany.dao
├── com.mycompany.interfaces
├── com.mycompany.db
└── com.mycompany.main

database/
└── hotel.sql
```

---

## 🎯 Funcionalidades Implementadas

### 👤 Gestión de Clientes

- Registro de huéspedes.
- Actualización de información.
- Consulta y búsqueda de clientes.

### 🏨 Gestión de Habitaciones

- Registro de habitaciones.
- Control de disponibilidad.
- Clasificación por tipo de habitación.

### 📅 Gestión de Reservas

- Creación de reservas.
- Modificación y cancelación de reservas.
- Control de fechas de ingreso y salida.

### 🛎️ Servicios Adicionales

- Registro de consumos adicionales.
- Asociación de servicios a una reserva.
- Cálculo automático del importe total.

### 💳 Facturación

- Generación de comprobantes.
- Cálculo de montos por hospedaje y servicios.

---

## 🗄️ Base de Datos

El sistema utiliza MySQL para el almacenamiento de información.

### Tablas Principales

- clientes
- habitaciones
- reservas
- servicios
- detalle_servicios
- usuarios

### Relaciones

- Un cliente puede realizar múltiples reservas.
- Una reserva puede incluir varios servicios adicionales.
- Cada habitación puede estar asociada a diferentes reservas en fechas distintas.

---

## 📚 Conceptos Aplicados

- Programación Orientada a Objetos (POO).
- Arquitectura por capas.
- Patrón DAO (Data Access Object).
- CRUD completo.
- JDBC para conexión a bases de datos.
- Modelado Entidad-Relación.
- Diseño de interfaces gráficas con Java Swing.

---

## 🎓 Proyecto Académico

Proyecto desarrollado como parte de la formación en Ingeniería de Sistemas, aplicando conocimientos de programación orientada a objetos, bases de datos relacionales, modelado de sistemas y desarrollo de aplicaciones de escritorio con Java.

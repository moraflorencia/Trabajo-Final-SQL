# 🗄️ Trabajo Final SQL - Base de Datos de Ofertas Laborales

Este proyecto consiste en el diseño y construcción de una **base de datos relacional** para un sitio web de ofertas laborales, realizado como **trabajo final de SQL**.

El desarrollo incluyó el diseño en **dbdiagram.io**, la creación de las tablas y sus relaciones en **SQL Server (SSMS)**, y la carga de datos de prueba mediante sentencias **SQL**.

---

## 📋 Objetivos del Proyecto

- Diseñar un modelo de base de datos para un portal de empleos.
- Implementar el diseño en SQL Server siguiendo las correcciones del diagrama.
- Generar un diagrama en SSMS para visualizar las relaciones.
- Poblar la base con datos de ejemplo realistas.

---

## 🏗️ Requerimientos Funcionales

La base de datos debe cumplir con las siguientes características:

- **Empresas**
  - Pueden publicar ofertas laborales.
  - Cada oferta incluye: título, tipo de jornada (parcial / completa), modalidad (presencial / remoto / híbrido), ubicación y requisitos.
  - Pueden visualizar postulaciones a sus ofertas y marcarlas como *entrevistadas, descartadas o aceptadas*.

- **Usuarios**
  - Deben registrarse con su email para postularse.
  - Pueden cargar su **perfil** con estudios y experiencia laboral (lugar, puesto, fechas).
  - Pueden postularse a ofertas laborales adjuntando su CV.
  - **Restricción:** No pueden postularse más de una vez a la misma oferta.

---

## 🗂️ Estructura de la Base de Datos

### Tablas principales:
- `Empresa`
- `OfertaLaboral`
- `Usuario`
- `Postulacion`
- `Estudio`
- `ExperienciaLaboral`

### Relaciones:
- Una **empresa** puede tener muchas **ofertas laborales**.
- Un **usuario** puede tener varios **estudios** y experiencias.
- Un **usuario** puede realizar múltiples **postulaciones**, pero solo una por oferta.

---

## 📊 Herramientas Utilizadas

- [dbdiagram.io](https://dbdiagram.io/) → diseño inicial del modelo E/R.
- **SQL Server Management Studio (SSMS)** → creación de tablas, relaciones y diagrama.
- **Lenguaje SQL** → inserción de datos.



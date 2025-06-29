# Sistema de Gestión de Alumnos (Java + Swing + MySQL)

Este proyecto es una aplicación de escritorio desarrollada en Java utilizando **Swing** para la interfaz gráfica y **MySQL** como sistema gestor de base de datos. Su objetivo principal es permitir la gestión de registros de alumnos (crear, consultar,visualizar tabla , actualizar y eliminar) de forma sencilla desde una interfaz visual amigable.

## 🧩 Características

- ✅ Conexión a la base de datos.
- 📝 Añadir nuevos registros de alumnos.
- 🔍 Consulta por ID o mostrar todos los registros.
- ✏️ Actualización de nombre de alumno mediante su ID.
- 🗑️ Eliminación con validación.
- 🧼 Botón "Limpiar" para resetear campos del formulario.
- 💻 Interfaz hecha con `Swing` en NetBeans.

## ⚙️ Configuración

1. Crea la base de datos en XAMPP o simplemete bajarla del repositorio (alumnosbd.sql):

```sql

CREATE DATABASE alumnosbd;
USE alumnosbd;

CREATE TABLE alumnos (
    ID INT PRIMARY KEY,
    Nombre VARCHAR(100),
    Grupo INT
);
```


> “Nota: Asegurate de que la conexion a tu base de datos sea correcta (user,pass)”




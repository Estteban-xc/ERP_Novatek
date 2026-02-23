# Arquitectura Inicial del Sistema

## Lenguaje de Programación
C# será utilizado como lenguaje principal para el desarrollo del sistema ERP.

## Tipo de Aplicación
Aplicación de escritorio basada en Windows Forms (WinForms).

## Base de Datos
Se empleará SQL Server como sistema gestor de base de datos relacional.

## Conexión a Base de Datos
La aplicación se conectará a SQL mediante SQL Connector para .NET.

## Enfoque arquitectónico

El sistema seguirá una arquitectura modular por capas:

### 1. Capa de Presentación (UI)
Formularios WinForms, dashboard y menús del sistema.

### 2. Capa de Lógica de Negocio
Procesamiento de ventas, validaciones y reglas del sistema.

### 3. Capa de Acceso a Datos
Conexión a SQL, consultas SQL y gestión de persistencia.

### 4. Modelos del Sistema
Clases que representan entidades como Producto, Cliente y Venta.

## Objetivo de la arquitectura
Permitir un sistema organizado, mantenible y escalable, facilitando futuras ampliaciones del ERP.

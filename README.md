# GOCA-Control
Aplicación web para el control de maquinaria, trabajos y finanzas. Construida con React 19, C++17 (Drogon) y MySQL 8.4.
Para la sección "About" del repositorio en GitHub:
  
JRGC Control de Maquinaria

Aplicación web diseñada para operar en una red local o servidor propio en Windows x64. Su función es administrar el registro de maquinaria, el catálogo de empresas cliente y el control de trabajos mediante formatos específicos para camiones de volteo, pipas (CV-01) y bitácoras de viajes (BV-01).

### Características principales

* **Gestión de trabajos:** Registro de servicios, cálculo automático de horas de renta, ingresos por número de viajes y volúmenes.


* **Control financiero:** Seguimiento del estado de los trabajos (cobrado o por cobrar) y registro de gastos operativos y generales.


* **Reportes:** Generación de resúmenes por mes, por maquinaria, por empresa y por categorías de gastos, con opción de exportación completa a Excel.


* **Importación masiva:** Carga de registros históricos y trabajos nuevos directamente desde plantillas de Excel (`.xlsx`).


* **Seguridad:** Autenticación por sesiones con mitigación CSRF, contraseñas procesadas con BCrypt y transporte cifrado mediante HTTPS.



### Stack Tecnológico

* **Frontend:** React 19.2, TypeScript y Vite.


* **Backend:** API REST desarrollada en C++17 empleando el framework Drogon. Se compila con CMake y requiere el entorno MSVC.


* **Base de datos:** MySQL 8.4.


* **Servidor:** Exclusivo para sistemas operativos Windows (Server 2022/2025 o 10/11 Pro de 64 bits) debido al uso de APIs nativas de criptografía.

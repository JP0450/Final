# 🚗 Proyecto Final ASP.NET Core MVC - Gestión de Coches

Este proyecto es una aplicación web desarrollada con **ASP.NET Core MVC** que permite gestionar una base de datos de coches conectada a **PostgreSQL** mediante **NeonDB (base de datos en la nube)**.

---

## 📦 Requisitos

Para ejecutar este proyecto en cualquier computadora necesitas:

- [.NET SDK 8.0 o superior](https://dotnet.microsoft.com/en-us/download)
- Visual Studio 2022 (con el workload de **ASP.NET y desarrollo web**)
- Acceso a internet (para conectarse a la base de datos NeonDB)

---

## 🔧 Configuración inicial

1. **Clona o descomprime** este proyecto en tu computadora.
2. Abre la solución `Final_proyecto.sln` en Visual Studio.
3. Asegúrate de que el archivo `appsettings.json` contenga esta cadena de conexión:

```json
"ConnectionStrings": {
  "DefaultConnection": "Host=ep-soft-wildflower-a598r4kh-pooler.us-east-2.aws.neon.tech;Port=5432;Database=neondb;Username=neondb_owner;Password=npg_geT1zqna6Cop;SSL Mode=Require;Trust Server Certificate=true"
}

4.Abre la Consola del Administrador de Paquetes (Tools > NuGet Package Manager > Package Manager Console) y ejecuta:

Update-Database

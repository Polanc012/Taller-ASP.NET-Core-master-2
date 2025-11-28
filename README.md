# Proyecto ASP.NET Core – Lista de Tareas Personalizada
Este repositorio contiene el proyecto desarrollado durante el taller “Uso de ASP.NET Core”, donde se implementa una aplicación web completa utilizando el patrón Modelo-Vista-Controlador (MVC).
Cada usuario puede autenticarse y gestionar su propia lista de tareas personalizadas.

✨ Características principales
•	Aplicación web construida con ASP.NET Core MVC.
•	Autenticación de usuarios mediante ASP.NET Identity.
•	Cada usuario accede únicamente a sus propias tareas.
•	Funcionalidades CRUD completas:
o	Crear nuevas tareas.
o	Leer y visualizar tareas.
o	Editar tareas existentes.
o	Eliminar tareas.
•	Filtrado / ordenamiento basado en la propiedad Order.
•	Soporte para subida de imágenes en cada tarea.
•	Persistencia usando SQLite (MyTaskManager.db).

🚀 Instrucciones para ejecutar el proyecto

1️⃣ Clonar el repositorio
git clone https://github.com/Polanc012/Taller-ASP.NET-Core-master-2.git
2️⃣ Abrir el proyecto

Puedes abrirlo en:
•	Visual Studio Code
•	Visual Studio 2022
•	JetBrains Rider

Abre la carpeta que contiene:
Taller ASP.NET Core.csproj

3️⃣ Configurar la base de datos

El proyecto usa una base SQLite incluida dentro del repositorio.

Archivo:
appsettings.json
Cadena de conexión:
"ConnectionStrings": {
  "DefaultConnection": "Data Source=MyTaskManager.db"
}
No necesitas migraciones.
La base MyTaskManager.db ya tiene las tablas.

4️⃣ Ejecutar la aplicación

En la terminal:
dotnet run
Abrir en navegador:
http://localhost:5152

🧪 Credenciales de prueba

Usuario: america1295@outlook.com
Contraseña: Tampico_86

🛠 Tecnologías utilizadas
•	ASP.NET Core 7.0
•	Entity Framework Core
•	ASP.NET Identity
•	SQLite
•	Bootstrap
•	C#

📁 Estructura del proyecto
Taller ASP.NET Core/
│── Areas/Identity/
│── Controllers/
│── Data/
│── Migrations/
│── Models/
│── Views/
│── wwwroot/
│── appsettings.json
│── MyTaskManager.db
│── Program.cs
│── Taller ASP.NET Core.csproj
└── README.md

📄 Licencia

Este proyecto se distribuye bajo la licencia MIT.

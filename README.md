<h1 align="center" id="title">DOJANKWON - BACKEND</h1>

<p align="center"><img src="https://socialify.git.ci/Amorfinaa/DOJANKWON-BACKEND/image?description=1&amp;font=Jost&amp;language=1&amp;name=1&amp;stargazers=1&amp;theme=Auto" alt="project-image"></p>

<p id="description">API REST para el sistema de gestión de la academia de Taekwondo DOJANKWON desarrollada con ASP.NET Core 8 y SQL Server.</p>
<h3>Frontend</h3>
https://github.com/Amorfinaa/DOJANKWON

<h2>🛠️ Installation Steps:</h2>

<p>1. Clona el repositorio</p>

```
git clone https://github.com/Amorfinaa/DOJANKWON-BACKEND.git
```

<p>2. Abre el proyecto en Visual Studio 2022</p>

```
Abre el archivo Dojanwonk.sln
```

<p>3. Ejecuta el script de base de datos</p>

```
Abre SQL Server Management Studio (SSMS) u otra herramienta SQL. 
```

<p>4. Ejecuta el script ubicado en la raíz del proyecto para crear la base de datos y las tablas necesarias.</p>

```
scriptDojanwonk.sql
```

<p>5. Configura la cadena de conexión en</p>

```
appsettings.json
```

<p>6. asegúrate de tener la cadena de conexión adecuada. Ejemplo:</p>

```
"ConnectionStrings": {   "DefaultConnection": "Server=localhost;Database=DojanwonkDB;Trusted_Connection=True;TrustServerCertificate=True;" }
```

<p>7. Ejecuta el proyecto selecciona el proyecto API como proyecto de inicio y presiona F5 o Ctrl + F5</p>

<p>8. Desde terminal:</p>

```
dotnet run --project Dojanwonk
```

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   ASP.NET Core 8 (Web API)
*   C#
*   SQL Server
*   Entity Framework Core
*   JWT
*   Visual Studio 2022

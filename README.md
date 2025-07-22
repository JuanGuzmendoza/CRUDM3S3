 CRUD de Usuarios – M3S3
Este es un proyecto de CRUD de usuarios desarrollado con HTML, Bootstrap y Node.js, utilizando json-server como API REST simulada.
Permite crear, leer, actualizar y eliminar usuarios desde una interfaz amigable y simple.

✅ Requisitos Previos
Asegúrate de tener instaladas las siguientes herramientas:

Node.js

npx (se instala con Node.js)

Puedes verificar si ya están instalados ejecutando:

bash
Copiar
Editar
node -v
npx -v
📦 Instalación de json-server
Instala json-server de forma global con el siguiente comando:

bash
Copiar
Editar
npm install -g json-server
⚙️ Cómo Ejecutar el Proyecto
1️⃣ Clona el repositorio
bash
Copiar
Editar
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo
2️⃣ Inicia el servidor
Asegúrate de estar en la carpeta donde se encuentra db.json, luego ejecuta:

bash
Copiar
Editar
json-server --watch db.json --port 3000
Esto iniciará un servidor en:

🌐 http://localhost:3000

3️⃣ Abre el archivo index.html
Puedes abrirlo directamente en tu navegador:

Opción 1: Doble clic en el archivo

Opción 2: Click derecho → “Abrir con navegador”

💡 Para una mejor experiencia, puedes usar la extensión Live Server de VSCode.

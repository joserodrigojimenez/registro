# registro
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <title>Cine Center</title>
</head>
<body class="bg-blue-900 h-screen flex items-center justify-center">

  <div class="bg-white p-8 rounded-lg shadow-md w-96">
    <!-- Registro -->
<h2 class="text-2xl font-bold mb-6">Registro</h2>
<form action="#" method="POST">
  <div class="mb-4">
    <label for="name" class="block text-gray-700 text-sm font-bold mb-2">Nombre:</label>
    <input type="text" id="name" name="name" class="w-full border-2 border-gray-300 p-2 rounded-md focus:outline-none focus:border-blue-500">
  </div>
  <div class="mb-4">
    <label for="email" class="block text-gray-700 text-sm font-bold mb-2">Correo electrónico:</label>
    <input type="email" id="email" name="email" class="w-full border-2 border-gray-300 p-2 rounded-md focus:outline-none focus:border-blue-500">
  </div>
  <div class="mb-4">
    <label for="dob" class="block text-gray-700 text-sm font-bold mb-2">Fecha de nacimiento:</label>
    <input type="date" id="dob" name="dob" class="w-full border-2 border-gray-300 p-2 rounded-md focus:outline-none focus:border-blue-500">
  </div>
  <div class="mb-4">
    <label for="address" class="block text-gray-700 text-sm font-bold mb-2">Dirección:</label>
    <input type="text" id="address" name="address" class="w-full border-2 border-gray-300 p-2 rounded-md focus:outline-none focus:border-blue-500">
  </div>
  <div class="mb-4">
    <label for="gender" class="block text-gray-700 text-sm font-bold mb-2">Género:</label>
    <select id="gender" name="gender" class="w-full border-2 border-gray-300 p-2 rounded-md focus:outline-none focus:border-blue-500">
      <option value="male">Masculino</option>
      <option value="female">Femenino</option>
      <option value="other">Otro</option>
    </select>
  </div>
  <div class="mb-6">
    <label for="password" class="block text-gray-700 text-sm font-bold mb-2">Contraseña:</label>
    <input type="password" id="password" name="password" class="w-full border-2 border-gray-300 p-2 rounded-md focus:outline-none focus:border-blue-500">
  </div>
  <button type="submit" class="w-full bg-blue-500 text-white p-3 rounded-md">Registrarse</button>
</form>

   
  </body>
  </html>

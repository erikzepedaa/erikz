<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portafolio - Tu Nombre</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-900">

  <!-- Header -->
  <header class="bg-white shadow">
    <div class="max-w-6xl mx-auto px-6 py-6 flex items-center justify-between">
      <h1 class="text-2xl font-bold">Tu Nombre Completo</h1>
      <nav class="space-x-4 text-sm">
        <a href="#proyectos" class="hover:underline">Proyectos</a>
        <a href="#about" class="hover:underline">Biografía</a>
        <a href="#contacto" class="hover:underline">Contacto</a>
      </nav>
    </div>
  </header>

  <main class="max-w-6xl mx-auto px-6 py-12">

    <!-- Hero -->
    <section class="flex flex-col lg:flex-row items-center gap-8">
      <div class="w-full lg:w-1/2">
        <h2 class="text-3xl md:text-4xl font-extrabold">Hola — soy Tu Nombre</h2>
        <p class="mt-4 text-lg leading-relaxed text-gray-700">
          Soy [tu carrera], me especializo en [tus especialidades]. En esta web publico mis proyectos, trabajos de la carrera y artículos técnicos.
        </p>
        <div class="mt-6 flex items-center gap-3">
          <a href="#proyectos" class="inline-block px-4 py-2 bg-indigo-600 text-white rounded-lg shadow hover:bg-indigo-700">Ver proyectos</a>
          <a href="#contacto" class="inline-block px-4 py-2 border border-gray-300 rounded-lg hover:bg-gray-100">Contactarme</a>
        </div>
        <ul class="mt-6 text-sm text-gray-600 space-y-1">
          <li><strong>Ubicación:</strong> Ciudad, País</li>
          <li><strong>Formación:</strong> Lic. en [Tu Carrera] — Universidad</li>
          <li><strong>Disponibilidad:</strong> Freelance / Contrato / Prácticas</li>
        </ul>
      </div>
      <div class="w-full lg:w-1/2 flex justify-center">
        <div class="w-56 h-56 rounded-2xl overflow-hidden shadow-lg bg-white flex items-center justify-center">
          <img src="images/profile.jpg" alt="Foto de perfil" class="object-cover w-full h-full" />
        </div>
      </div>
    </section>

    <!-- Proyectos -->
    <section id="proyectos" class="mt-16">
      <div class="flex items-center justify-between">
        <h3 class="text-2xl font-bold">Proyectos y trabajos</h3>
        <p class="text-sm text-gray-600">Aquí están los proyectos que he creado durante mi carrera y en trabajos personales.</p>
      </div>
      <div class="mt-6 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">

        <!-- Proyecto ejemplo -->
        <article class="bg-white rounded-2xl shadow-sm overflow-hidden hover:shadow-lg transition-shadow">
          <div class="h-40 bg-gray-100 overflow-hidden">
            <img src="images/project1.jpg" alt="Proyecto 1" class="object-cover w-full h-full" />
          </div>
          <div class="p-4">
            <h4 class="font-semibold text-lg">Proyecto 1 - Sistema de Gestión</h4>
            <p class="mt-2 text-sm text-gray-600">App web para gestionar inventarios y ventas. Tecnologías: HTML, CSS, JS.</p>
            <div class="mt-3 flex items-center justify-between">
              <div class="flex gap-2 text-xs flex-wrap">
                <span class="px-2 py-1 border rounded-full text-gray-600">HTML</span>
                <span class="px-2 py-1 border rounded-full text-gray-600">CSS</span>
                <span class="px-2 py-1 border rounded-full text-gray-600">JS</span>
              </div>
              <div class="flex gap-2">
                <a href="#" class="text-sm px-3 py-1 border rounded hover:bg-gray-50">Repo</a>
                <a href="#" class="text-sm px-3 py-1 bg-indigo-600 text-white rounded hover:bg-indigo-700">Demo</a>
              </div>
            </div>
          </div>
        </article>

        <!-- Más proyectos puedes copiar el bloque de arriba -->

      </div>
    </section>

    <!-- Biografía -->
    <section id="about" class="mt-16 bg-white rounded-2xl shadow p-6">
      <h3 class="text-2xl font-bold">Biografía</h3>
      <div class="mt-4 grid grid-cols-1 md:grid-cols-3 gap-4 items-start">
        <div class="md:col-span-1">
          <div class="w-full h-48 rounded-xl overflow-hidden bg-gray-100">
            <img src="images/profile.jpg" alt="Foto" class="object-cover w-full h-full" />
          </div>
        </div>
        <div class="md:col-span-2 text-gray-700">
          <p class="leading-relaxed">
            [Escribe aquí tu biografía: lugar de origen, trayectoria, intereses, lenguajes y herramientas que manejas, logros académicos o profesionales, y qué tipo de proyectos te gusta desarrollar.]
          </p>
          <ul class="mt-4 space-y-2 text-sm">
            <li><strong>Lenguajes:</strong> JavaScript, Python, C#</li>
            <li><strong>Herramientas:</strong> Git, Docker, Linux</li>
            <li><strong>Áreas de interés:</strong> IA, visión por computadora, sistemas embebidos</li>
            <li><strong>Contacto profesional:</strong> LinkedIn / GitHub</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Contacto -->
    <section id="contacto" class="mt-12">
      <div class="bg-indigo-50 rounded-2xl p-6 flex flex-col md:flex-row items-center justify-between gap-4">
        <div>
          <h4 class="text-xl font-bold">¿Quieres colaborar o hablar sobre un proyecto?</h4>
          <p class="text-sm text-gray-700 mt-1">Mándame un mensaje y con gusto lo reviso.</p>
        </div>
        <div class="flex gap-3 items-center">
          <a href="mailto:tu.email@ejemplo.com" class="px-4 py-2 bg-indigo-600 text-white rounded-lg">tu.email@ejemplo.com</a>
          <a href="https://github.com/tu-usuario" class="px-4 py-2 border rounded-lg">GitHub</a>
        </div>
      </div>
      <div class="mt-6 text-sm text-gray-500">© 2025 Tu Nombre — Todos los derechos reservados.</div>
    </section>

  </main>
</body>
</html>
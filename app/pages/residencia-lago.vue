
<template>
    <section class="container mx-auto px-4 py-12">
    <!-- Hero -->
    <div class="relative h-96 rounded-xl overflow-hidden shadow-lg mb-8">
        <img src="https://images.unsplash.com/photo-1580587771525-78b9dba3b914?auto=format&fit=crop&w=1600&q=80"
            alt="Residencia Lago Azul"
            class="w-full h-full object-cover">
        <div class="absolute top-6 left-6 bg-green-600 text-white px-4 py-2 rounded-full">Residencial</div>
        <div class="absolute top-6 right-6 bg-white text-green-600 font-bold px-4 py-2 rounded-full">Completado</div>
    </div>

    <!-- Título -->
    <h1 class="text-4xl font-bold mb-4">Residencia Lago Azul</h1>
    <p class="flex items-center text-gray-600 mb-6">
        <span class="material-symbols-outlined mr-2 text-gray-500">location_on</span>
        Valle de Bravo
    </p>

    <!-- Ficha técnica -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-10">
        <div class="bg-gray-100 p-4 rounded-lg shadow">
        <p class="text-sm text-gray-500">Área</p>
        <p class="text-lg font-semibold">480 m²</p>
        </div>
        <div class="bg-gray-100 p-4 rounded-lg shadow">
        <p class="text-sm text-gray-500">Tiempo de construcción</p>
        <p class="text-lg font-semibold">12 meses</p>
        </div>
        <div class="bg-gray-100 p-4 rounded-lg shadow">
        <p class="text-sm text-gray-500">Estilo</p>
        <p class="text-lg font-semibold">Contemporáneo</p>
        </div>
    </div>

    <!-- Descripción -->
    <p class="text-gray-700 leading-relaxed mb-10">
        Situada a orillas del lago, la Residencia Lago Azul integra arquitectura moderna con un entorno natural único.
        El diseño incorpora terrazas panorámicas, ventanales de doble altura y materiales locales como piedra y madera.
        Ideal para escapadas de descanso y vida en contacto con la naturaleza.
    </p>

    <!-- Galería -->
    <h2 class="text-2xl font-bold mb-4">Galería</h2>
    <div class="grid grid-cols-2 md:grid-cols-3 gap-4 mb-12">
        <img src="https://images.unsplash.com/photo-1600585154204-9859b5f3e9f3?auto=format&fit=crop&w=800&q=80" class="rounded-lg shadow">
        <img src="https://images.unsplash.com/photo-1600585152939-fd1d3f5a9a57?auto=format&fit=crop&w=800&q=80" class="rounded-lg shadow">
        <img src="https://images.unsplash.com/photo-1600607687706-7b92d1c21241?auto=format&fit=crop&w=800&q=80" class="rounded-lg shadow">
    </div>

    <!-- Botón volver
    <div class="text-center">
        <a href="/proyectos" class="px-6 py-3 bg-green-600 text-white rounded-lg hover:bg-green-700 transition">
        ← Volver a Proyectos
        </a>
    </div> -->
    </section>
</template>


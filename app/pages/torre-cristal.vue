<template>

    <section class="container mx-auto px-4 py-12">
    <!-- Hero -->
    <div class="relative h-96 rounded-xl overflow-hidden shadow-lg mb-8">
        <img src="https://images.unsplash.com/photo-1577493340887-b7bfff550145?auto=format&fit=crop&w=1600&q=80"
            alt="Distrito Nacional"
            class="w-full h-full object-cover">
        <div class="absolute top-6 left-6 bg-blue-600 text-white px-4 py-2 rounded-full">Comercial</div>
        <div class="absolute top-6 right-6 bg-white text-blue-600 font-bold px-4 py-2 rounded-full">Completado</div>
    </div>

    <!-- Título -->
    <h1 class="text-4xl font-bold mb-4">Edificio Corporativo Torre Cristal</h1>
    <p class="flex items-center text-gray-600 mb-6">
        <span class="material-symbols-outlined mr-2 text-gray-500">location_on</span>
        Distrito Nacional
    </p>

    <!-- Ficha técnica -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-10">
        <div class="bg-gray-100 p-4 rounded-lg shadow">
        <p class="text-sm text-gray-500">Área</p>
        <p class="text-lg font-semibold">12,000 m²</p>
        </div>
        <div class="bg-gray-100 p-4 rounded-lg shadow">
        <p class="text-sm text-gray-500">Tiempo de construcción</p>
        <p class="text-lg font-semibold">24 meses</p>
        </div>
        <div class="bg-gray-100 p-4 rounded-lg shadow">
        <p class="text-sm text-gray-500">Estilo</p>
        <p class="text-lg font-semibold">Contemporáneo</p>
        </div>
    </div>

    <!-- Descripción -->
    <p class="text-gray-700 leading-relaxed mb-10">
        La Torre Cristal es un rascacielos corporativo con fachada de vidrio de alto rendimiento que maximiza la entrada de luz natural.
        Con espacios de oficinas de última generación, sistemas inteligentes de energía y un diseño sustentable, este edificio
        es un ícono en el Distrito Nacional.
    </p>

    <!-- Galería -->
    <h2 class="text-2xl font-bold mb-4">Galería</h2>
    <div class="grid grid-cols-2 md:grid-cols-3 gap-4 mb-12">
        <img src="https://images.unsplash.com/photo-1529429617124-95b109e86bb8?auto=format&fit=crop&w=800&q=80" class="rounded-lg shadow">
        <img src="https://images.unsplash.com/photo-1559136555-9303baea8e2e?auto=format&fit=crop&w=800&q=80" class="rounded-lg shadow">
        <img src="https://images.unsplash.com/photo-1497032628192-86f99bcd76bc?auto=format&fit=crop&w=800&q=80" class="rounded-lg shadow">
    </div>

    <!-- Botón volver
    <div class="text-center">
        <a href="/" class="px-6 py-3 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition">
        ← Volver a Proyectos
        </a>
    </div> -->
    </section>

</template>



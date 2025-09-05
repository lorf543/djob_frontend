<template
    ><div id="webcrumbs">
        <div class="flex flex-col min-h-screen bg-gray-100">
            <header class="sticky top-0 z-10 bg-white shadow-md z-30">
                <div class="container mx-auto px-4 py-3 flex items-center justify-between">
                    <div class="flex items-center space-x-2">
                        <span class="material-symbols-outlined text-primary-600">architecture</span>
                        <h1 class="text-xl font-bold text-primary-600">ArquiConstrucción</h1>
                    </div>
                    <div class="hidden md:flex items-center space-x-6">
                        <a
                            href="#"
                            class="flex items-center space-x-1 px-3 py-2 rounded-full bg-gray-100 text-primary-600 hover:bg-gray-200 transition-colors"
                        >
                            <span class="material-symbols-outlined">home</span> <span>Inicio</span>
                        </a>
                        <a
                            href="#proyectos"
                            class="flex items-center space-x-1 px-3 py-2 rounded-full hover:bg-gray-100 transition-colors"
                        >
                            <span class="material-symbols-outlined">view_in_ar</span> <span>Proyectos</span>
                        </a>
                        <a
                            href="#servicios"
                            class="flex items-center space-x-1 px-3 py-2 rounded-full hover:bg-gray-100 transition-colors"
                        >
                            <span class="material-symbols-outlined">engineering</span> <span>Servicios</span>
                        </a>
                        <a
                            href="#contacto"
                            class="flex items-center space-x-1 px-3 py-2 rounded-full hover:bg-gray-100 transition-colors"
                        >
                            <span class="material-symbols-outlined">mail</span> <span>Contacto</span>
                        </a>
                    </div>
                    <div class="flex items-center space-x-4">
                        <div class="relative hidden md:block">
                            <input
                                type="text"
                                placeholder="Buscar proyectos..."
                                class="pl-9 pr-4 py-2 rounded-full bg-gray-100 focus:outline-none focus:ring-2 focus:ring-primary-500 w-40 md:w-64 transition-all"
                            />
                            <span class="material-symbols-outlined absolute left-3 top-2.5 text-gray-500">search</span>
                        </div>
                        <button
                            class="flex items-center space-x-2 px-4 py-2 bg-primary-600 text-white rounded-lg hover:bg-primary-700 transition-all"
                        >
                            <span class="material-symbols-outlined">person</span>
                            <span class="hidden md:inline">Iniciar Sesión</span>
                        </button>
                        <button
                            class="md:hidden flex items-center justify-center w-10 h-10 rounded-full bg-gray-200 hover:bg-gray-300 transition-colors"
                        >
                            <span class="material-symbols-outlined">menu</span>
                        </button>
                    </div>
                </div>
            </header>
            <main class="flex-grow">
                <section
                    class="relative h-[500px] md:h-[600px] lg:h-[700px] bg-cover bg-center">
                    <div class="absolute inset-0 bg-opacity-50" style="background-image:url('https://images.unsplash.com/photo-1503387762-592deb58ef4e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1631&q=80')" ></div>
                    <div class="container mx-auto px-4 h-full flex items-center relative z-10">
                        <div class="max-w-2xl text-white">
                            <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold mb-4 leading-tight">
                                Diseño y Construcción de Excelencia
                            </h1>
                            <p class="text-xl md:text-2xl mb-8">
                                Transformamos ideas en espacios extraordinarios con diseños innovadores y construcción
                                de alta calidad.
                            </p>
                            <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                                <button
                                    class="px-6 py-3 bg-primary-600 text-white rounded-lg hover:bg-primary-700 transition-all transform hover:-translate-y-1"
                                >
                                    Ver Proyectos
                                </button>
                                <button
                                    class="px-6 py-3 bg-white text-primary-600 rounded-lg hover:bg-gray-100 transition-all transform hover:-translate-y-1"
                                >
                                    Agendar Consulta
                                </button>
                            </div>
                        </div>
                    </div>

                </section>

                <section id="proyectos" class="container mx-auto px-4 py-">
                    <div class="text-center mb-12">
                        <h2 class="text-3xl md:text-4xl font-bold mb-4">Proyectos Destacados</h2>
                        <p class="text-gray-600 max-w-2xl mx-auto">
                            Explora nuestra selección de proyectos arquitectónicos y de construcción en diferentes
                            estilos y locaciones.
                        </p>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                        <div
                            class="bg-white rounded-xl shadow-md overflow-hidden transform transition-all hover:shadow-xl hover:-translate-y-2"
                        >
                            <div class="relative h-64">
                                <img
                                    src="https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&amp;auto=format&amp;fit=crop&amp;w=1453&amp;q=80"
                                    alt="Casa Moderna Minimalista"
                                    class="w-full h-full object-cover"
                                    keywords="modern house, minimalist, architecture, design"
                                />
                                <span
                                    class="absolute top-4 left-4 bg-primary-600 text-white text-sm px-3 py-1 rounded-full"
                                    >Residencial</span
                                >
                                <span
                                    class="absolute top-4 right-4 bg-white bg-opacity-90 text-primary-600 font-bold px-3 py-1 rounded-full"
                                    >Completado</span
                                >
                            </div>
                            <div class="p-6">
                                <h3 class="text-xl font-bold mb-2">Casa Moderna Minimalista</h3>
                                <p class="flex items-center text-gray-600 mb-4">
                                    <span class="material-symbols-outlined mr-2 text-gray-500">location_on</span> Valle
                                    Verde
                                </p>
                                <div class="flex justify-between mb-6">
                                    <div class="flex items-center">
                                        <span class="material-symbols-outlined mr-1 text-gray-500">square_foot</span>
                                        <span class="text-gray-700">350 m²</span>
                                    </div>
                                    <div class="flex items-center">
                                        <span class="material-symbols-outlined mr-1 text-gray-500">schedule</span>
                                        <span class="text-gray-700">8 meses</span>
                                    </div>
                                    <div class="flex items-center">
                                        <span class="material-symbols-outlined mr-1 text-gray-500">category</span>
                                        <span class="text-gray-700">Minimalista</span>
                                    </div>
                                </div>
                                
                                <NuxtLink class="w-full py-3  bg-blue-600 text-white text-sm px-3  font-medium rounded-lg hover:bg-primary-100 transition-colors" to="casa-moderna"> Ver Detalles</NuxtLink>
                                    
                          
                            </div>
                        </div>
                        <div
                            class="bg-white rounded-xl shadow-md overflow-hidden transform transition-all hover:shadow-xl hover:-translate-y-2"
                        >
                            <div class="relative h-64">
                                <img
                                    src="https://images.unsplash.com/photo-1577493340887-b7bfff550145?ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&amp;auto=format&amp;fit=crop&amp;w=1470&amp;q=80"
                                    alt="Edificio Corporativo Torre Cristal"
                                    class="w-full h-full object-cover"
                                    keywords="office building, commercial architecture, glass tower, corporate"
                                />
                                <span
                                    class="absolute top-4 left-4 bg-blue-600 text-white text-sm px-3 py-1 rounded-full"
                                    >Comercial</span
                                >
                                <span
                                    class="absolute top-4 right-4 bg-white bg-opacity-90 text-blue-600 font-bold px-3 py-1 rounded-full"
                                    >Completado</span
                                >
                            </div>
                            <div class="p-6">
                                <h3 class="text-xl font-bold mb-2">Edificio Corporativo Torre Cristal</h3>
                                <p class="flex items-center text-gray-600 mb-4">
                                    <span class="material-symbols-outlined mr-2 text-gray-500">location_on</span>
                                    Distrito Nacional
                                </p>
                                <div class="flex justify-between mb-6">
                                    <div class="flex items-center">
                                        <span class="material-symbols-outlined mr-1 text-gray-500">square_foot</span>
                                        <span class="text-gray-700">12,000 m²</span>
                                    </div>
                                    <div class="flex items-center">
                                        <span class="material-symbols-outlined mr-1 text-gray-500">schedule</span>
                                        <span class="text-gray-700">24 meses</span>
                                    </div>
                                    <div class="flex items-center">
                                        <span class="material-symbols-outlined mr-1 text-gray-500">category</span>
                                        <span class="text-gray-700">Contemporáneo</span>
                                    </div>
                                </div>
                                <NuxtLink class="w-full py-3  bg-blue-600 text-white text-sm px-3  font-medium rounded-lg hover:bg-primary-100 transition-colors" to="casa-moderna"> Ver Detalles</NuxtLink>
                            </div>
                        </div>
                        <div
                            class="bg-white rounded-xl shadow-md overflow-hidden transform transition-all hover:shadow-xl hover:-translate-y-2"
                        >
                            <div class="relative h-64">
                                <img
                                    src="https://images.unsplash.com/photo-1580587771525-78b9dba3b914?ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&amp;auto=format&amp;fit=crop&amp;w=1374&amp;q=80"
                                    alt="Residencia Lago Azul"
                                    class="w-full h-full object-cover"
                                    keywords="lakefront house, residential architecture, modern home, waterfront"
                                />
                                <span
                                    class="absolute top-4 left-4 bg-primary-600 text-white text-sm px-3 py-1 rounded-full"
                                    >Residencial</span
                                >
                                <span
                                    class="absolute top-4 right-4 bg-white bg-opacity-90 text-primary-600 font-bold px-3 py-1 rounded-full"
                                    >Completado</span
                                >
                            </div>
                            <div class="p-6">
                                <h3 class="text-xl font-bold mb-2">Residencia Lago Azul</h3>
                                <p class="flex items-center text-gray-600 mb-4">
                                    <span class="material-symbols-outlined mr-2 text-gray-500">location_on</span> Valle
                                    de Bravo
                                </p>
                                <div class="flex justify-between mb-6">
                                    <div class="flex items-center">
                                        <span class="material-symbols-outlined mr-1 text-gray-500">square_foot</span>
                                        <span class="text-gray-700">480 m²</span>
                                    </div>
                                    <div class="flex items-center">
                                        <span class="material-symbols-outlined mr-1 text-gray-500">schedule</span>
                                        <span class="text-gray-700">12 meses</span>
                                    </div>
                                    <div class="flex items-center">
                                        <span class="material-symbols-outlined mr-1 text-gray-500">category</span>
                                        <span class="text-gray-700">Contemporáneo</span>
                                    </div>
                                </div>
                                <NuxtLink class="w-full py-3  bg-blue-600 text-white text-sm px-3  font-medium rounded-lg hover:bg-primary-100 transition-colors" to="torre-cristal"> Ver Detalles</NuxtLink>
                            </div>
                        </div>
                    </div>
                    <div class="text-center mt-12">
                        <button
                            class="px-6 py-3 bg-white border border-primary-600 text-primary-600 rounded-lg hover:bg-primary-50 transition-all inline-flex items-center"
                        >
                            Ver Todos los Proyectos <span class="material-symbols-outlined ml-2">arrow_forward</span>
                        </button>
                    </div>
                </section>


                <section class="bg-gray-50 py-20">
                    <div class="container mx-auto px-4">
                        <div class="text-center mb-12">
                            <h2 class="text-3xl md:text-4xl font-bold mb-4">¿Por qué elegirnos?</h2>
                            <p class="text-gray-600 max-w-2xl mx-auto">
                                Nos enorgullecemos de ofrecer un servicio excepcional y una experiencia sin igual en
                                proyectos arquitectónicos y de construcción.
                            </p>
                        </div>
                        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                            <div
                                class="bg-white p-6 rounded-xl shadow-md text-center transform transition-all hover:-translate-y-2 hover:shadow-lg"
                            >
                                <div
                                    class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4"
                                >
                                    <span class="material-symbols-outlined text-3xl text-primary-600">verified</span>
                                </div>
                                <h3 class="text-xl font-bold mb-2">Experiencia Comprobada</h3>
                                <p class="text-gray-600">
                                    Más de 15 años de experiencia en el mercado de arquitectura y construcción con un
                                    historial comprobado de éxitos.
                                </p>
                            </div>
                            <div
                                class="bg-white p-6 rounded-xl shadow-md text-center transform transition-all hover:-translate-y-2 hover:shadow-lg"
                            >
                                <div
                                    class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4"
                                >
                                    <span class="material-symbols-outlined text-3xl text-primary-600"
                                        >architecture</span
                                    >
                                </div>
                                <h3 class="text-xl font-bold mb-2">Diseño Innovador</h3>
                                <p class="text-gray-600">
                                    Soluciones creativas y funcionales que combinan estética, sostenibilidad y la visión
                                    única de cada cliente.
                                </p>
                            </div>
                            <div
                                class="bg-white p-6 rounded-xl shadow-md text-center transform transition-all hover:-translate-y-2 hover:shadow-lg"
                            >
                                <div
                                    class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4"
                                >
                                    <span class="material-symbols-outlined text-3xl text-primary-600">engineering</span>
                                </div>
                                <h3 class="text-xl font-bold mb-2">Equipo Especializado</h3>
                                <p class="text-gray-600">
                                    Arquitectos e ingenieros altamente calificados que entienden tus necesidades y
                                    ofrecen soluciones personalizadas.
                                </p>
                            </div>
                            <div
                                class="bg-white p-6 rounded-xl shadow-md text-center transform transition-all hover:-translate-y-2 hover:shadow-lg"
                            >
                                <div
                                    class="w-16 h-16 bg-primary-100 rounded-full flex items-center justify-center mx-auto mb-4"
                                >
                                    <span class="material-symbols-outlined text-3xl text-primary-600">landscape</span>
                                </div>
                                <h3 class="text-xl font-bold mb-2">Construcción Sostenible</h3>
                                <p class="text-gray-600">
                                    Compromiso con prácticas de construcción ecoamigables y materiales sostenibles para
                                    un futuro mejor.
                                </p>
                            </div>
                        </div>
                    </div>
                </section>
                <section id="servicios" class="container mx-auto px-4 py-20">
                    <div class="text-center mb-12">
                        <h2 class="text-3xl md:text-4xl font-bold mb-4">Nuestros Servicios</h2>
                        <p class="text-gray-600 max-w-2xl mx-auto">
                            Servicios integrales de arquitectura y construcción adaptados a tus necesidades específicas.
                        </p>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                        <div class="bg-white rounded-xl shadow-md overflow-hidden flex flex-col md:flex-row">
                            <div class="md:w-2/5">
                                <img
                                    src="https://images.unsplash.com/photo-1486312338219-ce68d2c6f44d?ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&amp;auto=format&amp;fit=crop&amp;w=1472&amp;q=80"
                                    alt="Diseño Arquitectónico"
                                    class="w-full h-full object-cover"
                                    keywords="architectural design, blueprint, architecture service, design planning"
                                />
                            </div>
                            <div class="p-6 md:w-3/5">
                                <h3 class="text-xl font-bold mb-3">Diseño Arquitectónico</h3>
                                <p class="text-gray-600 mb-4">
                                    Creamos diseños únicos que reflejan tu visión, necesidades funcionales y estéticas,
                                    transformando conceptos en planos detallados.
                                </p>
                                <ul class="space-y-2 mb-4">
                                    <li class="flex items-center">
                                        <span class="material-symbols-outlined text-primary-600 mr-2"
                                            >check_circle</span
                                        >
                                        <span class="text-gray-700">Conceptualización y diseño esquemático</span>
                                    </li>
                                    <li class="flex items-center">
                                        <span class="material-symbols-outlined text-primary-600 mr-2"
                                            >check_circle</span
                                        >
                                        <span class="text-gray-700">Modelado 3D y visualización</span>
                                    </li>
                                    <li class="flex items-center">
                                        <span class="material-symbols-outlined text-primary-600 mr-2"
                                            >check_circle</span
                                        >
                                        <span class="text-gray-700">Planos detallados de construcción</span>
                                    </li>
                                    <li class="flex items-center">
                                        <span class="material-symbols-outlined text-primary-600 mr-2"
                                            >check_circle</span
                                        >
                                        <span class="text-gray-700">Gestión de permisos y normativas</span>
                                    </li>
                                </ul>
                                <NuxtLink class="w-full py-3  bg-blue-600 text-white text-sm px-3  font-medium rounded-lg hover:bg-primary-100 transition-colors" to="residencia-lago"> Ver Detalles</NuxtLink>
                            </div>
                        </div>
                        <div class="bg-white rounded-xl shadow-md overflow-hidden flex flex-col md:flex-row">
                            <div class="md:w-2/5">
                                <img
                                    src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?ixlib=rb-4.0.3&amp;ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&amp;auto=format&amp;fit=crop&amp;w=1631&amp;q=80"
                                    alt="Construcción y Gestión de Proyectos"
                                    class="w-full h-full object-cover"
                                    keywords="construction management, building project, construction site, architecture project"
                                />
                            </div>
                            <div class="p-6 md:w-3/5">
                                <h3 class="text-xl font-bold mb-3">Construcción y Gestión de Proyectos</h3>
                                <p class="text-gray-600 mb-4">
                                    Supervisamos cada fase del proyecto, desde la planificación inicial hasta la entrega
                                    final, garantizando calidad y cumplimiento de plazos.
                                </p>
                                <ul class="space-y-2 mb-4">
                                    <li class="flex items-center">
                                        <span class="material-symbols-outlined text-primary-600 mr-2"
                                            >check_circle</span
                                        >
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </section>
            </main>
        </div>
    </div>
    </template>

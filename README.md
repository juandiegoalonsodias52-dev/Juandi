# Juandi
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Footwear Elegance - Suéteres de Fútbol</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            color: #1f2937;
        }
        .text-shadow {
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
    </style>
</head>
<body class="antialiased">
    <!-- Contenedor principal para la página -->
    <div class="min-h-screen flex flex-col">

        <!-- Barra de navegación -->
        <header class="bg-white shadow-lg py-4 px-6 fixed top-0 left-0 w-full z-50">
            <nav class="container mx-auto flex justify-between items-center">
                <a href="#" class="text-2xl font-bold text-gray-900">
                    Footwear <span class="text-blue-600">Elegance</span>
                </a>
                <div class="hidden md:flex space-x-6">
                    <a href="#productos" class="text-gray-600 hover:text-blue-600 transition-colors">Productos</a>
                    <a href="#historia" class="text-gray-600 hover:text-blue-600 transition-colors">Nuestra Historia</a>
                    <a href="#contacto" class="text-gray-600 hover:text-blue-600 transition-colors">Contacto</a>
                </div>
                <button class="md:hidden text-gray-600 hover:text-blue-600 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                    </svg>
                </button>
            </nav>
        </header>

        <!-- Sección principal (Hero) -->
        <main class="flex-grow">
            <section class="relative h-96 md:h-screen bg-cover bg-center flex items-center justify-center p-4" style="background-image: url('https://placehold.co/1920x1080/4F46E5/ffffff?text=Su%C3%A9teres+de+F%C3%BAtbol');">
                <div class="absolute inset-0 bg-black opacity-50"></div>
                <div class="relative text-center text-white">
                    <h1 class="text-4xl md:text-6xl font-extrabold mb-4 text-shadow">Viste tu Pasión por el Fútbol</h1>
                    <p class="text-lg md:text-2xl mb-8 font-light text-shadow">Suéteres con estilo y la historia de los equipos más grandes.</p>
                    <a href="#productos" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-transform transform hover:scale-105">
                        Explorar Colección
                    </a>
                </div>
            </section>

            <!-- Sección de productos -->
            <section id="productos" class="py-16 bg-white">
                <div class="container mx-auto px-4">
                    <h2 class="text-center text-3xl font-bold text-gray-800 mb-12">Nuestros Suéteres Más Populares</h2>
                    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                        <!-- Producto 1 -->
                        <div class="bg-gray-100 rounded-xl shadow-lg overflow-hidden transition-transform transform hover:scale-105">
                            <img src="https://placehold.co/600x400/1e40af/ffffff?text=Su%C3%A9ter+Equipo+A" alt="Suéter del Equipo A" class="w-full h-56 object-cover">
                            <div class="p-6">
                                <h3 class="text-xl font-semibold text-gray-900 mb-2">Suéter Equipo Clásico</h3>
                                <p class="text-gray-600 mb-4">Un diseño retro inspirado en las leyendas.</p>
                                <span class="text-blue-600 text-2xl font-bold">$75.00</span>
                                <button class="mt-4 w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 rounded-lg transition-colors">
                                    Comprar Ahora
                                </button>
                            </div>
                        </div>

                        <!-- Producto 2 -->
                        <div class="bg-gray-100 rounded-xl shadow-lg overflow-hidden transition-transform transform hover:scale-105">
                            <img src="https://placehold.co/600x400/4f46e5/ffffff?text=Su%C3%A9ter+Equipo+B" alt="Suéter del Equipo B" class="w-full h-56 object-cover">
                            <div class="p-6">
                                <h3 class="text-xl font-semibold text-gray-900 mb-2">Suéter Edición Especial</h3>
                                <p class="text-gray-600 mb-4">Colección limitada con materiales de alta calidad.</p>
                                <span class="text-blue-600 text-2xl font-bold">$90.00</span>
                                <button class="mt-4 w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 rounded-lg transition-colors">
                                    Comprar Ahora
                                </button>
                            </div>
                        </div>

                        <!-- Producto 3 -->
                        <div class="bg-gray-100 rounded-xl shadow-lg overflow-hidden transition-transform transform hover:scale-105">
                            <img src="https://placehold.co/600x400/3b82f6/ffffff?text=Su%C3%A9ter+Equipo+C" alt="Suéter del Equipo C" class="w-full h-56 object-cover">
                            <div class="p-6">
                                <h3 class="text-xl font-semibold text-gray-900 mb-2">Suéter de Entrenamiento</h3>
                                <p class="text-gray-600 mb-4">Ligero y transpirable para el máximo confort.</p>
                                <span class="text-blue-600 text-2xl font-bold">$60.00</span>
                                <button class="mt-4 w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 rounded-lg transition-colors">
                                    Comprar Ahora
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Sección de nuestra historia -->
            <section id="historia" class="py-16 bg-gray-200">
                <div class="container mx-auto px-4 flex flex-col md:flex-row items-center gap-8">
                    <div class="md:w-1/2">
                        <img src="https://placehold.co/800x600/6b7280/ffffff?text=Nuestra+Historia" alt="Personas trabajando en suéteres" class="rounded-xl shadow-lg w-full">
                    </div>
                    <div class="md:w-1/2 text-gray-800">
                        <h2 class="text-3xl font-bold mb-4">El Legado de los Suéteres de Fútbol</h2>
                        <p class="mb-4 text-lg">
                            En Footwear Elegance, creemos que un suéter es más que una prenda: es un símbolo de identidad, de historia y de pasión. Cada diseño que creamos rinde homenaje a los momentos más emblemáticos del fútbol, desde los goles históricos hasta los equipos que marcaron una era. Utilizamos solo los mejores materiales para garantizar que tu suéter no solo sea un tributo, sino también una pieza de confort y durabilidad.
                        </p>
                        <p class="text-lg">
                            Únete a nuestra comunidad y viste con orgullo la historia que amas.
                        </p>
                    </div>
                </div>
            </section>

        </main>

        <!-- Pie de página -->
        <footer id="contacto" class="bg-gray-900 text-gray-300 py-10 px-4">
            <div class="container mx-auto grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-xl font-semibold mb-4 text-white">Footwear Elegance</h3>
                    <p class="text-sm">Vistiendo la pasión del fútbol, un suéter a la vez.</p>
                </div>
                <div>
                    <h3 class="text-xl font-semibold mb-4 text-white">Enlaces Rápidos</h3>
                    <ul class="space-y-2">
                        <li><a href="#productos" class="hover:text-white transition-colors">Productos</a></li>
                        <li><a href="#historia" class="hover:text-white transition-colors">Nuestra Historia</a></li>
                        <li><a href="#contacto" class="hover:text-white transition-colors">Contacto</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-semibold mb-4 text-white">Síguenos</h3>
                    <div class="flex space-x-4">
                        <a href="#" class="hover:text-white transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                                <path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" />
                            </svg>
                        </a>
                        <a href="#" class="hover:text-white transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                                <path d="M12 2C6.477 2 2 6.477 2 12c0 5.084 2.946 9.387 7.234 11.226.5.09.682-.218.682-.483 0-.237-.008-.868-.013-1.703-2.847.618-3.434-1.209-3.434-1.209-.464-1.171-1.12-1.487-1.12-1.487-.912-.619.069-.607.069-.607 1.004.07 1.532 1.03 1.532 1.03.892 1.53 2.341 1.088 2.91.832.092-.644.351-1.088.636-1.338-2.22-.253-4.555-1.11-4.555-4.942 0-1.09.39-1.984 1.029-2.675-.103-.253-.446-1.27-.098-2.651 0 0 .84-.269 2.75 1.022.799-.222 1.647-.333 2.5-.337.853.004 1.701.115 2.5.337 1.909-1.291 2.747-1.022 2.747-1.022.348 1.381.005 2.398-.098 2.651.64.691 1.028 1.585 1.028 2.675 0 3.841-2.339 4.686-4.562 4.935.359.307.678.915.678 1.846 0 1.33-.012 2.408-.012 2.748 0 .265.18.574.687.48a10.01 10.01 0 005.137-5.013C22 6.477 17.523 2 12 2z" />
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
            <div class="mt-8 text-center text-sm">
                © 2024 Footwear Elegance. Todos los derechos reservados.
            </div>
        </footer>
    </div>
</body>
</html>



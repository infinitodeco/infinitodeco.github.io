<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arte en Cuadros | Decoración para tu hogar</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Raleway:wght@300;400;600&display=swap');
        
        body {
            font-family: 'Raleway', sans-serif;
        }
        
        .title-font {
            font-family: 'Playfair Display', serif;
        }
        
        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1579762715118-a6f1d4b934f1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1400&q=80');
            background-size: cover;
            background-position: center;
        }
        
        .artwork-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .artwork-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        
        .testimonial-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(5px);
        }
        
        .gallery-item {
            transition: all 0.3s ease;
        }
        
        .gallery-item:hover {
            transform: scale(1.03);
            z-index: 10;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header/Navbar -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center">
                <i class="fas fa-palette text-2xl text-amber-600 mr-2"></i>
                <span class="title-font text-2xl font-bold text-gray-800">Arte en Cuadros</span>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#inicio" class="text-gray-700 hover:text-amber-600 transition">Inicio</a>
                <a href="#galeria" class="text-gray-700 hover:text-amber-600 transition">Galería</a>
                <a href="#nosotros" class="text-gray-700 hover:text-amber-600 transition">Nosotros</a>
                <a href="#testimonios" class="text-gray-700 hover:text-amber-600 transition">Testimonios</a>
                <a href="#contacto" class="text-gray-700 hover:text-amber-600 transition">Contacto</a>
            </nav>
            <button class="md:hidden text-gray-700">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="inicio" class="hero min-h-screen flex items-center justify-center text-center text-white">
        <div class="container mx-auto px-4">
            <h1 class="title-font text-4xl md:text-6xl font-bold mb-6">Transforma tus espacios con arte</h1>
            <p class="text-xl md:text-2xl mb-8 max-w-2xl mx-auto">Cuadros decorativos únicos hechos a mano para dar vida a tus paredes</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#galeria" class="bg-amber-600 hover:bg-amber-700 text-white font-semibold py-3 px-8 rounded-full transition duration-300 transform hover:scale-105">Ver colección</a>
                <a href="#contacto" class="bg-transparent hover:bg-white hover:text-gray-800 border-2 border-white text-white font-semibold py-3 px-8 rounded-full transition duration-300 transform hover:scale-105">Encargar obra</a>
            </div>
        </div>
    </section>

    <!-- Featured Artworks -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="title-font text-3xl md:text-4xl font-bold text-center text-gray-800 mb-12">Obras Destacadas</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Artwork 1 -->
                <div class="artwork-card bg-gray-50 rounded-lg overflow-hidden shadow-md">
                    <img src="https://images.unsplash.com/photo-1579762715118-a6f1d4b934f1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro abstracto" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="title-font text-xl font-semibold mb-2">Armonía Abstracta</h3>
                        <p class="text-gray-600 mb-4">Técnica mixta sobre lienzo, 60x80 cm</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-amber-600">$45.000</span>
                            <button class="bg-gray-800 hover:bg-gray-700 text-white py-2 px-4 rounded-full text-sm transition">Agregar al carrito</button>
                        </div>
                    </div>
                </div>
                
                <!-- Artwork 2 -->
                <div class="artwork-card bg-gray-50 rounded-lg overflow-hidden shadow-md">
                    <img src="https://images.unsplash.com/photo-1579547945413-497e1b99dac0?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro paisaje" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="title-font text-xl font-semibold mb-2">Atardecer en la Montaña</h3>
                        <p class="text-gray-600 mb-4">Óleo sobre lienzo, 50x70 cm</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-amber-600">$38.000</span>
                            <button class="bg-gray-800 hover:bg-gray-700 text-white py-2 px-4 rounded-full text-sm transition">Agregar al carrito</button>
                        </div>
                    </div>
                </div>
                
                <!-- Artwork 3 -->
                <div class="artwork-card bg-gray-50 rounded-lg overflow-hidden shadow-md">
                    <img src="https://images.unsplash.com/photo-1490750967868-88aa4486c946?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro flores" class="w-full h-64 object-cover">
                    <div class="p-6">
                        <h3 class="title-font text-xl font-semibold mb-2">Flores Silvestres</h3>
                        <p class="text-gray-600 mb-4">Acrílico sobre madera, 40x60 cm</p>
                        <div class="flex justify-between items-center">
                            <span class="font-bold text-amber-600">$32.000</span>
                            <button class="bg-gray-800 hover:bg-gray-700 text-white py-2 px-4 rounded-full text-sm transition">Agregar al carrito</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="text-center mt-12">
                <a href="#galeria" class="inline-block border-2 border-amber-600 text-amber-600 hover:bg-amber-600 hover:text-white font-semibold py-3 px-8 rounded-full transition duration-300">Ver más obras</a>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="galeria" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="title-font text-3xl md:text-4xl font-bold text-center text-gray-800 mb-12">Nuestra Galería</h2>
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
                <!-- Gallery items will be added here -->
                <div class="gallery-item overflow-hidden rounded-lg shadow-md">
                    <img src="https://images.unsplash.com/photo-1578926375605-eaf7559b1458?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro 1" class="w-full h-full object-cover">
                </div>
                <div class="gallery-item overflow-hidden rounded-lg shadow-md">
                    <img src="https://images.unsplash.com/photo-1531913764164-f85c52e6e654?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro 2" class="w-full h-full object-cover">
                </div>
                <div class="gallery-item overflow-hidden rounded-lg shadow-md">
                    <img src="https://images.unsplash.com/photo-1515405295579-ba7b45403062?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro 3" class="w-full h-full object-cover">
                </div>
                <div class="gallery-item overflow-hidden rounded-lg shadow-md">
                    <img src="https://images.unsplash.com/photo-1493612276216-2dd6f9a01c82?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro 4" class="w-full h-full object-cover">
                </div>
                <div class="gallery-item overflow-hidden rounded-lg shadow-md">
                    <img src="https://images.unsplash.com/photo-1500462918059-b1a0cb512f1d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro 5" class="w-full h-full object-cover">
                </div>
                <div class="gallery-item overflow-hidden rounded-lg shadow-md">
                    <img src="https://images.unsplash.com/photo-1519681393784-d120267933ba?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro 6" class="w-full h-full object-cover">
                </div>
                <div class="gallery-item overflow-hidden rounded-lg shadow-md">
                    <img src="https://images.unsplash.com/photo-1493612276216-2dd6f9a01c82?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro 7" class="w-full h-full object-cover">
                </div>
                <div class="gallery-item overflow-hidden rounded-lg shadow-md">
                    <img src="https://images.unsplash.com/photo-1579783902614-a3fb3927b6a5?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Cuadro 8" class="w-full h-full object-cover">
                </div>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="nosotros" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <img src="https://images.unsplash.com/photo-1547891654-e66ed7ebb968?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Artista trabajando" class="rounded-lg shadow-xl w-full">
                </div>
                <div class="md:w-1/2">
                    <h2 class="title-font text-3xl md:text-4xl font-bold text-gray-800 mb-6">Nuestra Historia</h2>
                    <p class="text-gray-600 mb-4">Arte en Cuadros nació en 2018 como un pequeño emprendimiento familiar con la misión de llevar arte accesible y de calidad a todos los hogares.</p>
                    <p class="text-gray-600 mb-6">Cada pieza es creada con materiales de primera calidad y mucho amor, buscando transmitir emociones y personalidad a través del color y las texturas.</p>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <i class="fas fa-paint-brush text-amber-600 mt-1 mr-3"></i>
                            <div>
                                <h4 class="font-semibold text-gray-800">Técnicas diversas</h4>
                                <p class="text-gray-600">Trabajamos con óleo, acrílico, acuarela y técnicas mixtas para ofrecer variedad en texturas y estilos.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <i class="fas fa-leaf text-amber-600 mt-1 mr-3"></i>
                            <div>
                                <h4 class="font-semibold text-gray-800">Materiales ecológicos</h4>
                                <p class="text-gray-600">Utilizamos materiales sostenibles y procesos respetuosos con el medio ambiente.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <i class="fas fa-heart text-amber-600 mt-1 mr-3"></i>
                            <div>
                                <h4 class="font-semibold text-gray-800">Hecho a mano</h4>
                                <p class="text-gray-600">Cada obra es única, pintada a mano por nuestros artistas con atención a cada detalle.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonios" class="py-16 bg-amber-50">
        <div class="container mx-auto px-4">
            <h2 class="title-font text-3xl md:text-4xl font-bold text-center text-gray-800 mb-12">Lo que dicen nuestros clientes</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="testimonial-card p-6 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full bg-gray-300 overflow-hidden mr-4">
                            <img src="https://randomuser.me/api/portraits/women/43.jpg" alt="Cliente 1" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-semibold">María González</h4>
                            <div class="flex text-amber-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600">"El cuadro que compré es exactamente como lo vi en la foto, pero en persona es aún más hermoso. La calidad del lienzo y los colores son impresionantes. ¡Totalmente recomendado!"</p>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="testimonial-card p-6 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full bg-gray-300 overflow-hidden mr-4">
                            <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Cliente 2" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-semibold">Carlos Martínez</h4>
                            <div class="flex text-amber-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600">"Encargué un cuadro personalizado para mi esposa y quedó espectacular. El artista captó perfectamente lo que quería y el resultado superó todas mis expectativas."</p>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="testimonial-card p-6 rounded-lg shadow-md">
                    <div class="flex items-center mb-4">
                        <div class="w-12 h-12 rounded-full bg-gray-300 overflow-hidden mr-4">
                            <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="Cliente 3" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-semibold">Laura Fernández</h4>
                            <div class="flex text-amber-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600">"Compré tres cuadros para mi sala de estar y han transformado completamente el espacio. La atención al cliente fue excelente y el envío llegó perfectamente embalado."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contacto" class="py-16 bg-gray-800 text-white">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row">
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <h2 class="title-font text-3xl md:text-4xl font-bold mb-6">Contáctanos</h2>
                    <p class="mb-6">¿Tienes preguntas sobre nuestras obras? ¿Quieres encargar un cuadro personalizado? Escríbenos y te responderemos a la brevedad.</p>
                    
                    <div class="space-y-4 mb-8">
                        <div class="flex items-center">
                            <i class="fas fa-map-marker-alt text-amber-400 mr-4 text-xl"></i>
                            <span>Calle Artística 123, Santiago, Chile</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-phone text-amber-400 mr-4 text-xl"></i>
                            <span>+56 9 1234 5678</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-envelope text-amber-400 mr-4 text-xl"></i>
                            <span>contacto@arteenquadros.cl</span>
                        </div>
                    </div>
                    
                    <div>
                        <h3 class="title-font text-xl font-semibold mb-4">Síguenos en redes</h3>
                        <div class="flex space-x-4">
                            <a href="#" class="w-10 h-10 rounded-full bg-gray-700 flex items-center justify-center hover:bg-amber-600 transition">
                                <i class="fab fa-instagram"></i>
                            </a>
                            <a href="#" class="w-10 h-10 rounded-full bg-gray-700 flex items-center justify-center hover:bg-amber-600 transition">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                            <a href="#" class="w-10 h-10 rounded-full bg-gray-700 flex items-center justify-center hover:bg-amber-600 transition">
                                <i class="fab fa-pinterest-p"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="md:w-1/2">
                    <form class="bg-gray-700 p-6 rounded-lg shadow-lg">
                        <div class="mb-4">
                            <label for="name" class="block mb-2">Nombre</label>
                            <input type="text" id="name" class="w-full px-4 py-2 bg-gray-800 border border-gray-600 rounded focus:outline-none focus:ring-2 focus:ring-amber-400">
                        </div>
                        <div class="mb-4">
                            <label for="email" class="block mb-2">Email</label>
                            <input type="email" id="email" class="w-full px-4 py-2 bg-gray-800 border border-gray-600 rounded focus:outline-none focus:ring-2 focus:ring-amber-400">
                        </div>
                        <div class="mb-4">
                            <label for="subject" class="block mb-2">Asunto</label>
                            <select id="subject" class="w-full px-4 py-2 bg-gray-800 border border-gray-600 rounded focus:outline-none focus:ring-2 focus:ring-amber-400">
                                <option value="">Selecciona un tema</option>
                                <option value="question">Consulta sobre productos</option>
                                <option value="custom">Encargo personalizado</option>
                                <option value="other">Otro</option>
                            </select>
                        </div>
                        <div class="mb-6">
                            <label for="message" class="block mb-2">Mensaje</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 bg-gray-800 border border-gray-600 rounded focus:outline-none focus:ring-2 focus:ring-amber-400"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-amber-600 hover:bg-amber-700 text-white font-semibold py-3 px-4 rounded transition duration-300">Enviar mensaje</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-8">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <div class="flex items-center">
                        <i class="fas fa-palette text-2xl text-amber-600 mr-2"></i>
                        <span class="title-font text-xl font-bold text-white">Arte en Cuadros</span>
                    </div>
                    <p class="mt-2 text-sm">Decorando hogares con arte desde 2018</p>
                </div>
                <div class="text-sm">
                    <p>&copy; 2023 Arte en Cuadros. Todos los derechos reservados.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Back to top button -->
    <button id="backToTop" class="fixed bottom-6 right-6 w-12 h-12 bg-amber-600 text-white rounded-full shadow-lg flex items-center justify-center opacity-0 invisible transition-all duration-300">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script>
        // Back to top button
        const backToTopButton = document.getElementById('backToTop');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('opacity-0', 'invisible');
                backToTopButton.classList.add('opacity-100', 'visible');
            } else {
                backToTopButton.classList.remove('opacity-100', 'visible');
                backToTopButton.classList.add('opacity-0', 'invisible');
            }
        });
        
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Mobile menu toggle (would need more implementation)
        const mobileMenuButton = document.querySelector('button.md\\:hidden');
        mobileMenuButton.addEventListener('click', () => {
            // Here you would typically toggle a mobile menu
            alert('Menú móvil se abriría aquí. En una implementación completa, esto mostraría/ocultaría el menú.');
        });
    </script>
</body>
</html>

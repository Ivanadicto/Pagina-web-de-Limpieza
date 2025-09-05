# Pagina-web-de-Limpieza
Esta es una pagina web que hice a un cliente

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Servicios de Limpieza </title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .service-card:hover { transform: translateY(-5px); transition: all 0.3s ease; }
        .contact-form { background: rgba(255, 255, 255, 0.95); backdrop-filter: blur(10px); }
    </style>
    <script src="https://cdn.emailjs.com/dist/email.min.js"></script>
    <script>
        (function(){
            emailjs.init("service_vs20mgf"); 
        })();
    </script>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="gradient-bg text-white shadow-lg">
        <nav class="container mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-2">
       
                      
                    </div>
                 
                </div>
                <div class="hidden md:flex space-x-6">
                    <a href="#inicio" class="hover:text-blue-200 transition-colors">Inicio</a>
                    <a href="#servicios" class="hover:text-blue-200 transition-colors">Servicios</a>
                    <a href="#contacto" class="hover:text-blue-200 transition-colors">Contacto</a>
                </div>
            </div>
        </nav>
    </header>
    

    <!-- Hero Section -->
    <section id="inicio" class="gradient-bg text-white py-20">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-5xl font-bold mb-6">Limpieza Profesional a tu Alcance</h2>
            <p class="text-xl mb-8 max-w-2xl mx-auto">¡Hola! Soy Alexandra, tu especialista en limpieza y organización,
he convertido mi pasión por los espacios impecables en un servicio profesional de limpieza que superará tus expectativas. Me encanta transformar hogares y espacios de trabajo en lugares relucientes, frescos y acogedores.
</p>
            <a href="#contacto" class="bg-white text-blue-600 px-8 py-3 rounded-full font-semibold hover:bg-blue-50 transition-colors inline-block">
                Solicitar Cotización
            </a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="servicios" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12">
                <h3 class="text-4xl font-bold text-gray-800 mb-4">Mis Servicios</h3>
                <p class="text-gray-600 max-w-2xl mx-auto">Ofrezco una amplia gama de servicios de limpieza adaptados a tus necesidades específicas</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="service-card bg-gradient-to-br from-blue-50 to-indigo-100 p-8 rounded-xl shadow-lg">
                    <div class="text-4xl mb-4">🏠</div>
                    <h4 class="text-xl font-semibold mb-3 text-gray-800">Limpieza Residencial</h4>
                    <p class="text-gray-600 mb-4">Limpieza completa de hogares, apartamentos y casas. Incluye todas las habitaciones y áreas comunes.</p>
                    <ul class="text-sm text-gray-600 space-y-1">
                        <li>• Cocinas y baños</li>
                        <li>• Dormitorios y salas</li>
                        <li>• Aspirado y trapeado</li>
                        <li>• Limpieza de ventanas</li>
                    </ul>
                </div>

                <div class="service-card bg-gradient-to-br from-green-50 to-emerald-100 p-8 rounded-xl shadow-lg">
                    <div class="text-4xl mb-4">🏢</div>
                    <h4 class="text-xl font-semibold mb-3 text-gray-800">Limpieza Comercial</h4>
                    <p class="text-gray-600 mb-4">Servicios especializados para oficinas, locales comerciales y espacios de trabajo.</p>
                    <ul class="text-sm text-gray-600 space-y-1">
                        <li>• Oficinas y cubículos</li>
                        <li>• Casas y departamentos</li>
                        <li>• Áreas de recepción</li>
                        <li>• Salas de juntas</li>
                        <li>• Mantenimiento regular</li>
                    </ul>
                </div>

                <div class="service-card bg-gradient-to-br from-purple-50 to-violet-100 p-8 rounded-xl shadow-lg">
                    <div class="text-4xl mb-4">🧽</div>
                    <h4 class="text-xl font-semibold mb-3 text-gray-800">Limpieza Profunda</h4>
                    <p class="text-gray-600 mb-4">Limpieza, mantenimiento periódico profundo.</p>
                    <ul class="text-sm text-gray-600 space-y-1">
                        <li>• Limpieza de alfombras</li>
                        <li>• Electrodomésticos</li>
                        <li>• Áreas difíciles</li>
                        <li>• Desinfección total</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contacto" class="py-16 gradient-bg">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12">
                <h3 class="text-4xl font-bold text-white mb-4">Contáctanos</h3>
                <p class="text-blue-100 max-w-2xl mx-auto">¿Listo para tener un espacio impecable? Contáctanos para una cotización gratuita</p>
            </div>
            

            <div class="grid lg:grid-cols-2 gap-12 max-w-6xl mx-auto">
                <!-- Contact Info -->
                <div class="text-white">
                    <h4 class="text-2xl font-semibold mb-6">Información de Contacto</h4>
                    
                    <div class="space-y-6">
                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-white bg-opacity-20 rounded-full flex items-center justify-center">
                                <span class="text-xl">📞</span>
                            </div>
                            <div>
                                <h5 class="font-semibold">Teléfono</h5>
                                <p class="text-blue-100">54 9 2604107055</p>
                            </div>
                            <a href="https://wa.me/5492604107055?text=Hola,%20quiero%20consultar%20por%20servicios%20de%20limpieza" 
                               target="_blank"
                               class="flex items-center bg-green-500 hover:bg-green-600 text-white font-semibold px-4 py-2 rounded-lg shadow-lg transition-colors duration-300 ml-2">
                                <span class="text-xl mr-2">💬</span>
                                WhatsApp
                            </a>
                        </div>

                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-white bg-opacity-20 rounded-full flex items-center justify-center">
                                <span class="text-xl">✉️</span>
                            </div>
                            <div>
                                <h5 class="font-semibold">Email</h5>
                                <p class="text-blue-100">pardoayelen110@gmail.com</p>
                            </div>
                        </div>

                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-white bg-opacity-20 rounded-full flex items-center justify-center">
                                <span class="text-xl">📍</span>
                            </div>
                            <div>
                                <h5 class="font-semibold">Ubicación</h5>
                                <p class="text-blue-100">zona centro de San Rafael-Mendoza</p>
                            </div>
                        </div>

                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-white bg-opacity-20 rounded-full flex items-center justify-center">
                                <span class="text-xl">🕒</span>
                            </div>
                            <div>
                                <h5 class="font-semibold">Horarios</h5>
                                <p class="text-blue-100">(consultar disponibilidad)</p>
                                <p class="text-blue-100"></p>
                            </div>
                        </div>
                    </div>

                    <div class="mt-8">
                        <h5 class="font-semibold mb-4">¿Por qué elegirnos?</h5>
                        <ul class="space-y-2 text-blue-100">
                            <li>✓ Capacitada y confiable</li>
                            <li>✓ Precios competitivos</li>
                            <li>✓ Garantía de satisfacción 100%</li>
                            <li>✓ Disponibilidad flexible</li>
                        </ul>
                    </div>
                </div>

                <!-- Contact Form -->
                <div class="contact-form p-8 rounded-xl shadow-2xl">
                    <h4 class="text-2xl font-semibold mb-6 text-gray-800">Solicita tu Cotización</h4>
                    
                    <form id="contactForm" class="space-y-4">
                        <div class="grid md:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">Nombre *</label>
                                <input type="text" id="nombre" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                            </div>
                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">Teléfono *</label>
                                <input type="tel" id="telefono" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                            </div>
                        </div>

                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Email *</label>
                            <input type="email" id="email" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                        </div>

                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Tipo de Servicio *</label>
                            <select id="servicio" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                                <option value="">Selecciona un servicio</option>
                                <option value="residencial">Limpieza Residencial</option>
                                <option value="comercial">Limpieza Comercial</option>
                                <option value="profunda">Limpieza Profunda</option>
                                <option value="otro">Otro (especificar en mensaje)</option>
                            </select>
                        </div>

                        <div class="grid md:grid-cols-2 gap-4">
                      
                            <div>
                                <label class="block text-sm font-medium text-gray-700 mb-2">Frecuencia</label>
                                <select id="frecuencia" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                                    <option value="">Seleccionar</option>
                                    <option value="una-vez">Una sola vez</option>
                                    <option value="semanal">Semanal</option>
                                    <option value="quincenal">Quincenal</option>
                                    <option value="mensual">Mensual</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Mensaje</label>
                            <textarea id="mensaje" rows="4" placeholder="Cuéntanos más detalles sobre lo que necesitas..." class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent resize-none"></textarea>
                        </div>

                        <button type="submit" class="w-full bg-gradient-to-r from-blue-600 to-purple-600 text-white py-3 px-6 rounded-lg font-semibold hover:from-blue-700 hover:to-purple-700 transition-all duration-300 transform hover:scale-105">
                            Enviar Solicitud de Cotización
                        </button>
                    </form>

                    <div id="successMessage" class="hidden mt-4 p-4 bg-green-100 border border-green-400 text-green-700 rounded-lg">
                        <div class="flex items-center">
                            <span class="text-xl mr-2">✅</span>
                            <div>
                                <strong>¡Mensaje enviado exitosamente!</strong>
                                <p class="text-sm">Te contactaremos dentro de las próximas 24 horas con tu cotización personalizada.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->


        

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Contact form handling con EmailJS
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();

            // Get form data
            const formData = {
                nombre: document.getElementById('nombre').value,
                telefono: document.getElementById('telefono').value,
                email: document.getElementById('email').value,
                servicio: document.getElementById('servicio').value,
                frecuencia: document.getElementById('frecuencia').value,
                mensaje: document.getElementById('mensaje').value
            };

            // Validate required fields
            if (!formData.nombre || !formData.telefono || !formData.email || !formData.servicio) {
                alert('Por favor completa todos los campos obligatorios (*)');
                return;
            }

            // Validate email format
            const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (!emailRegex.test(formData.email)) {
                alert('Por favor ingresa un email válido');
                return;
            }

            const submitButton = e.target.querySelector('button[type="submit"]');
            const originalText = submitButton.textContent;
            submitButton.textContent = 'Enviando...';
            submitButton.disabled = true;

            // Cambia "TU_TEMPLATE_ID" por el ID real de tu plantilla en EmailJS
            emailjs.send("service_vs20mgf", "template_fqfv7fp", formData)
                .then(() => {
                    document.getElementById('successMessage').classList.remove('hidden');
                    e.target.reset();
                    submitButton.textContent = originalText;
                    submitButton.disabled = false;
                    setTimeout(() => {
                        document.getElementById('successMessage').classList.add('hidden');
                    }, 5000);
                    document.getElementById('successMessage').scrollIntoView({
                        behavior: 'smooth',
                        block: 'center'
                    });
                }, (error) => {
                    alert('Ocurrió un error al enviar el mensaje. Por favor intenta nuevamente.');
                    submitButton.textContent = originalText;
                    submitButton.disabled = false;
                    console.error('EmailJS Error:', error);
                });
        });

        // Add animation to service cards on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        // Observe service cards
        document.querySelectorAll('.service-card').forEach(card => {
            card.style.opacity = '0';
            card.style.transform = 'translateY(30px)';
            card.style.transition = 'all 0.6s ease';
            observer.observe(card);
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'979fd8175050df02',t:'MTc1NzAxMzYyNS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>

## Hi there 👋

<!--
**Dysheel/Dysheel** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dysheel - Productos 100% Naturales | Belleza que te define</title>
    <meta name="description" content="Dysheel - Productos caseros 100% naturales. Jabón artesanal de aloe vera y aceite de aguacate puro. Transformamos vidas promoviendo un estilo de vida saludable y sostenible.">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            scroll-behavior: smooth;
        }

        /* Header */
        .header {
            background: linear-gradient(135deg, #2d5016, #4a7c26);
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .nav-container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 2rem;
        }

        .logo {
            /* Eliminamos el font-size y font-weight porque ahora es una imagen */
        }

        .nav-menu {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        .nav-menu a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
        }

        .nav-menu a:hover {
            color: #90EE90;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #f0f8e8, #e8f5e8);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 80px 2rem 2rem;
        }

        .hero-content {
            max-width: 800px;
            animation: fadeInUp 1s ease-out;
        }

        .hero h1 {
            font-size: 3.5rem;
            color: #2d5016;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }

        .hero-tagline {
            font-size: 1.3rem;
            color: #4a7c26;
            margin-bottom: 2rem;
            font-style: italic;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            color: #555;
        }

        .cta-button {
            display: inline-block;
            background: linear-gradient(135deg, #4a7c26, #2d5016);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.1rem;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.3);
        }

        /* Sections */
        .section {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .section h2 {
            font-size: 2.5rem;
            color: #2d5016;
            text-align: center;
            margin-bottom: 1rem;
        }

        .section-subtitle {
            text-align: center;
            color: #4a7c26;
            font-size: 1.2rem;
            margin-bottom: 3rem;
            font-style: italic;
        }

        /* Mission & Vision */
        .mission-vision {
            background: linear-gradient(135deg, #f8fff8, #f0f8e8);
            border-radius: 20px;
            padding: 3rem;
            margin: 2rem 0;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        .mission, .vision {
            margin-bottom: 2rem;
        }

        .mission h3, .vision h3 {
            color: #2d5016;
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        /* Features Grid */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }

        .feature-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            border-left: 4px solid #4a7c26;
        }

        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }

        .feature-card h3 {
            color: #2d5016;
            margin-bottom: 1rem;
            font-size: 1.3rem;
        }

        /* Products */
        .products {
            background: linear-gradient(135deg, #f0f8e8, #e8f5e8);
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 3rem;
            margin: 3rem 0;
        }

        .product-card {
            background: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

        .product-card:hover {
            transform: translateY(-10px);
        }

        .product-image {
            height: 200px;
            background: linear-gradient(135deg, #90EE90, #98FB98);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 4rem;
            color: white;
        }

        .product-content {
            padding: 2rem;
        }

        .product-price {
            font-size: 2rem;
            color: #2d5016;
            font-weight: bold;
            margin: 1rem 0;
        }

        .product-benefits {
            list-style: none;
            margin: 1rem 0;
        }

        .product-benefits li {
            padding: 0.5rem 0;
            position: relative;
            padding-left: 1.5rem;
        }

        .product-benefits li:before {
            content: "✓";
            color: #4a7c26;
            font-weight: bold;
            position: absolute;
            left: 0;
        }

        /* Contact */
        .contact {
            background: linear-gradient(135deg, #2d5016, #4a7c26);
            color: white;
            text-align: center;
        }

        .contact h2 {
            color: white;
        }

        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }

        .contact-item {
            background: rgba(255,255,255,0.1);
            padding: 2rem;
            border-radius: 15px;
            backdrop-filter: blur(10px);
        }

        .contact-item h3 {
            margin-bottom: 1rem;
            color: #90EE90;
        }

        /* Footer */
        .footer {
            background: #1a2f0a;
            color: white;
            text-align: center;
            padding: 2rem;
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .fade-in {
            animation: fadeInUp 0.8s ease-out;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .nav-menu {
                display: none;
            }
            
            .section {
                padding: 2rem 1rem;
            }
        }

        /* Logo integration */
        .hero-logo {
            max-width: 200px; /* Ajusta el tamaño máximo de tu logo en la sección hero */
            margin-bottom: 2rem;
            filter: drop-shadow(0 4px 8px rgba(0,0,0,0.1));
        }

        .nav-logo {
            max-width: 120px; /* Ajusta el tamaño máximo de tu logo en el header */
            height: auto;
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="nav-container">
            <div class="logo">
                <img src="logo.jpg" alt="Logo de Dysheel" class="nav-logo">
            </div>
            <nav>
                <ul class="nav-menu">
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#nosotros">Nosotros</a></li>
                    <li><a href="#productos">Productos</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="inicio" class="hero">
        <div class="hero-content">
            <img src="logo.jpg" alt="Logo de Dysheel" class="hero-logo">
            <p class="hero-tagline">La belleza que te define</p>
            <p>Transformamos vidas a través de productos caseros 100% naturales, promoviendo un estilo de vida más saludable y sostenible.</p>
            <a href="#productos" class="cta-button">Conoce Nuestros Productos</a>
        </div>
    </section>

    <section id="nosotros" class="section">
        <h2>Nuestra Filosofía</h2>
        <p class="section-subtitle">Compromiso con la naturaleza y tu bienestar</p>
        
        <div class="mission-vision fade-in">
            <div class="mission">
                <h3>🌱 Nuestra Misión</h3>
                <p>En Dysheel, buscamos transformar vidas a través de productos caseros naturales, promoviendo un estilo de vida más saludable y sostenible.</p>
            </div>
            
            <div class="vision">
                <h3>🌟 Nuestra Visión</h3>
                <ul>
                    <li>Crear productos que capturen la esencia de lo natural</li>
                    <li>Establecer relaciones sólidas con nuestros clientes y comunidades</li>
                    <li>Expandir nuestra visión para generar un cambio positivo global</li>
                </ul>
            </div>
        </div>

        <div class="features-grid">
            <div class="feature-card">
                <h3>🏺 Proceso Artesanal</h3>
                <p>Cada producto es elaborado de forma artesanal con ingredientes cuidadosamente seleccionados, garantizando la más alta calidad en cada lote.</p>
            </div>
            
            <div class="feature-card">
                <h3>🔬 Control de Calidad</h3>
                <p>Realizamos pruebas constantes para asegurar que cada producto cumple con su propósito: nutrir, proteger y regenerar de forma natural.</p>
            </div>
            
            <div class="feature-card">
                <h3>🚚 Distribución Personalizada</h3>
                <p>Entrega domiciliar directa con empaques premium, cuidando cada detalle para brindarte una experiencia única.</p>
            </div>
            
            <div class="feature-card">
                <h3>🌍 Compromiso Ambiental</h3>
                <p>Procesos manuales que eliminan contaminación, promoviendo estrategias bioambientales en cada paso de producción.</p>
            </div>
            
            <div class="feature-card">
                <h3>💚 Valores Éticos</h3>
                <p>Cada decisión se toma pensando en el impacto positivo para nuestros clientes y el planeta que compartimos.</p>
            </div>
            
            <div class="feature-card">
                <h3>💰 Precios Justos</h3>
                <p>Evaluamos cuidadosamente nuestros costos para ofrecer calidad premium a precios accesibles para todos.</p>
            </div>
        </div>
    </section>

    <section id="productos" class="section products">
        <h2>Nuestros Productos</h2>
        <p class="section-subtitle">100% Naturales, 100% Efectivos</p>
        
        <div class="products-grid">
            <div class="product-card fade-in">
                <div class="product-image">🧼</div>
                <div class="product-content">
                    <h3>Jabón Artesanal Neutro</h3>
                    <p><strong>Aloe Vera + Aceite de Coco</strong></p>
                    <ul class="product-benefits">
                        <li>Limpieza suave y profunda</li>
                        <li>Hidratación natural</li>
                        <li>pH balanceado</li>
                        <li>Ideal para todo tipo de piel</li>
                        <li>Especialmente recomendado para piel sensible</li>
                    </ul>
                    <div class="product-price">RD$75</div>
                    <p><em>Elaborado artesanalmente con los mejores ingredientes naturales</em></p>
                </div>
            </div>
            
            <div class="product-card fade-in">
                <div class="product-image">🥑</div>
                <div class="product-content">
                    <h3>Aceite de Aguacate Puro</h3>
                    <p><strong>100% Natural Extraído Artesanalmente</strong></p>
                    <ul class="product-benefits">
                        <li>Nutrición profunda</li>
                        <li>Rico en antioxidantes naturales</li>
                        <li>Reparación celular</li>
                        <li>Ideal para piel seca</li>
                        <li>Perfecto para cabello dañado</li>
                    </ul>
                    <div class="product-price">RD$70</div>
                    <p><em>Aceite puro sin aditivos químicos, directo de la naturaleza</em></p>
                </div>
            </div>
        </div>
    </section>

    <section id="contacto" class="section contact">
        <h2>¡Únete a la Revolución Natural!</h2>
        <p class="section-subtitle" style="color: #90EE90;">Belleza joven, actitud única</p>
        
        <div class="contact-info">
            <div class="contact-item">
                <h3>📦 Entrega a Domicilio</h3>
                <p>Llevamos nuestros productos frescos directamente a tu puerta en toda la zona de República Dominicana</p>
            </div>
            
            <div class="contact-item">
                <h3>📞 Contáctanos por Teléfono</h3>
                <p><a href="tel:+18498894211" style="color: white; text-decoration: none;">+1 (849) 889-4211</a></p>
                <p style="font-size: 0.9rem;">(Disponible de Lunes a Viernes, 9 AM - 5 PM)</p>
            </div>

            <div class="contact-item">
                <h3>🎁 Empaque Premium</h3>
                <p>Cada producto viene en empaques cuidadosamente diseñados que reflejan la calidad de nuestros ingredientes</p>
            </div>
            
            <div class="contact-item">
                <h3>✅ Garantía Natural</h3>
                <p>100% de satisfacción garantizada. Si no quedas completamente satisfecho, hablemos y lo solucionamos</p>
            </div>
        </div>
        
        <div style="margin-top: 3rem;">
            <h3 style="color: #90EE90; margin-bottom: 1rem;">¿Listos para sentir la diferencia?</h3>
            <p style="font-size: 1.2rem; margin-bottom: 2rem;">Haz tu pedido hoy y experimenta la transformación que solo lo natural puede brindar</p>
            <a href="#inicio" class="cta-button">Contactar Ahora</a>
        </div>
    </section>

    <footer class="footer">
        <p>&copy; 2024 Dysheel - Productos 100% Naturales | República Dominicana</p>
        <p style="margin-top: 0.5rem; color: #90EE90;">Transformando vidas, cuidando el planeta</p>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Add fade-in animation on scroll
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

        // Observe all cards and sections
        document.querySelectorAll('.feature-card, .product-card, .contact-item').forEach(el => {
            el.style.opacity = '0';
            el.style.transform = 'translateY(20px)';
            el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
            observer.observe(el);
        });

        // Header background change on scroll
        window.addEventListener('scroll', () => {
            const header = document.querySelector('.header');
            if (window.scrollY > 100) {
                header.style.background = 'linear-gradient(135deg, #1a2f0a, #2d5016)';
            } else {
                header.style.background = 'linear-gradient(135deg, #2d5016, #4a7c26)';
            }
        });
    </script>
</body>
</html>

## Hi there 👋

<!--
**digitalimur/Digitalimur** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
    <title>Digitalimur - Agencia de Marketing Digital</title>
    <style>
        :root {
            --primary: #0056b3;
            --secondary: #6c757d;
            --accent: #ff4d4d;
            --light: #f8f9fa;
            --dark: #343a40;
            --white: #ffffff;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: #333;
            background-color: #fff;
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            background-color: var(--primary);
            color: var(--white);
            padding: 1.5rem 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            z-index: 100;
        }
        
        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            font-size: 2rem;
            font-weight: 700;
            color: var(--white);
            text-decoration: none;
        }
        
        .logo span {
            color: var(--accent);
        }
        
        nav ul {
            display: flex;
            list-style: none;
        }
        
        nav ul li {
            margin-left: 1.5rem;
        }
        
        nav ul li a {
            color: var(--white);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        nav ul li a:hover {
            color: var(--accent);
        }
        
        .hero {
            background: linear-gradient(rgba(0, 86, 179, 0.8), rgba(0, 86, 179, 0.8)), url('/api/placeholder/1200/600') no-repeat center center;
            background-size: cover;
            height: 100vh;
            display: flex;
            align-items: center;
            text-align: center;
            padding-top: 60px;
        }
        
        .hero-content {
            color: var(--white);
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1.5rem;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        
        .btn {
            display: inline-block;
            padding: 0.8rem 1.5rem;
            background-color: var(--accent);
            color: var(--white);
            text-decoration: none;
            border-radius: 4px;
            font-weight: 500;
            transition: background 0.3s;
        }
        
        .btn:hover {
            background-color: #e63c3c;
        }
        
        section {
            padding: 5rem 0;
        }
        
        .section-header {
            text-align: center;
            margin-bottom: 3rem;
        }
        
        .section-header h2 {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 1rem;
        }
        
        .section-header p {
            color: var(--secondary);
            max-width: 700px;
            margin: 0 auto;
        }
        
        .services {
            background-color: var(--light);
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .service-card {
            background: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-icon {
            height: 180px;
            background-color: var(--primary);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            font-size: 3rem;
        }
        
        .service-content {
            padding: 1.5rem;
        }
        
        .service-content h3 {
            color: var(--primary);
            margin-bottom: 1rem;
        }
        
        .why-us {
            background-color: var(--white);
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
        }
        
        .feature {
            display: flex;
            align-items: flex-start;
        }
        
        .feature-icon {
            background-color: var(--primary);
            color: var(--white);
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 1rem;
            flex-shrink: 0;
        }
        
        .results {
            background-color: var(--light);
            text-align: center;
        }
        
        .counter-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
        }
        
        .counter {
            padding: 2rem;
            background-color: var(--white);
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .counter .number {
            font-size: 3rem;
            font-weight: 700;
            color: var(--accent);
            margin-bottom: 0.5rem;
        }
        
        .contact {
            background-color: var(--light);
        }
        
        .contact-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2rem;
        }
        
        .contact-info {
            display: flex;
            flex-direction: column;
        }
        
        .contact-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 1.5rem;
        }
        
        .contact-icon {
            width: 50px;
            height: 50px;
            background-color: var(--primary);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            margin-right: 1rem;
            flex-shrink: 0;
        }
        
        .contact-form {
            background-color: var(--white);
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
        }
        
        .form-group textarea {
            resize: vertical;
            min-height: 150px;
        }
        
        footer {
            background-color: var(--dark);
            color: var(--white);
            padding: 3rem 0;
            text-align: center;
        }
        
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
            text-align: left;
        }
        
        .footer-section h3 {
            color: var(--accent);
            margin-bottom: 1.5rem;
            font-size: 1.5rem;
        }
        
        .footer-links {
            list-style: none;
        }
        
        .footer-links li {
            margin-bottom: 0.8rem;
        }
        
        .footer-links a {
            color: var(--white);
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .footer-links a:hover {
            color: var(--accent);
        }
        
        .social-links {
            display: flex;
            justify-content: flex-start;
            list-style: none;
        }
        
        .social-links li {
            margin-right: 1rem;
        }
        
        .social-links a {
            color: var(--white);
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        
        .social-links a:hover {
            color: var(--accent);
        }
        
        .copyright {
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            padding-top: 1.5rem;
        }
        
        @media screen and (max-width: 768px) {
            .header-content {
                flex-direction: column;
            }
            
            nav ul {
                margin-top: 1rem;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .features-grid, .contact-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container header-content">
            <a href="#" class="logo">Digital<span>imur</span></a>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#servicios">Servicios</a></li>
                    <li><a href="#nosotros">Por qué nosotros</a></li>
                    <li><a href="#resultados">Resultados</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero" id="inicio">
        <div class="container hero-content">
            <h1>Llevamos tu marca al mundo digital con resultados extraordinarios</h1>
            <p>En Digitalimur, transformamos la presencia digital de tu empresa para generar alto impacto, reconocimiento de marca y aumento en ventas.</p>
            <a href="#contacto" class="btn">Potencia tu marca hoy</a>
        </div>
    </section>

    <section class="services" id="servicios">
        <div class="container">
            <div class="section-header">
                <h2>Nuestros Servicios</h2>
                <p>Soluciones digitales completas para llevar tu marca al siguiente nivel</p>
            </div>
            <div class="services-grid">
                <div class="service-card">
                    <div class="service-icon">
                        <img src="/api/placeholder/100/100" alt="Estrategia Digital">
                    </div>
                    <div class="service-content">
                        <h3>Estrategia Digital</h3>
                        <p>Desarrollamos planes estratégicos personalizados que alinean tus objetivos de negocio con acciones digitales concretas para maximizar resultados.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <img src="/api/placeholder/100/100" alt="Gestión de Redes Sociales">
                    </div>
                    <div class="service-content">
                        <h3>Gestión de Redes Sociales</h3>
                        <p>Creamos y gestionamos contenido de alto impacto que conecta con tu audiencia, aumenta el engagement y fortalece la presencia de tu marca.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <img src="/api/placeholder/100/100" alt="Publicidad Digital">
                    </div>
                    <div class="service-content">
                        <h3>Publicidad Digital</h3>
                        <p>Campañas publicitarias optimizadas en múltiples plataformas para llegar a tu público objetivo y maximizar el retorno de inversión.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <img src="/api/placeholder/100/100" alt="Creación de Contenido">
                    </div>
                    <div class="service-content">
                        <h3>Creación de Contenido</h3>
                        <p>Diseñamos contenido relevante y atractivo que conecta con tu audiencia a través de múltiples formatos: vídeo, imagen, texto y más.</p>
                    </div>
                </div>
                <div class="service-card">
                    <div class="service-icon">
                        <img src="/api/placeholder/100/100" alt="Analítica y Resultados">
                    </div>
                    <div class="service-content">
                        <h3>Analítica y Resultados</h3>
                        <p>Medimos y optimizamos constantemente cada acción para garantizar el máximo rendimiento y alcanzar tus objetivos comerciales.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="why-us" id="nosotros">
        <div class="container">
            <div class="section-header">
                <h2>¿Por qué elegirnos?</h2>
                <p>Somos especialistas en potenciar marcas y empresas en el entorno digital</p>
            </div>
            <div class="features-grid">
                <div class="feature">
                    <div class="feature-icon">1</div>
                    <div>
                        <h3>Enfoque estratégico</h3>
                        <p>Desarrollamos estrategias con una visión clara de objetivos, públicos y resultados. Cada acción tiene un porqué y un para qué.</p>
                    </div>
                </div>
                <div class="feature">
                    <div class="feature-icon">2</div>
                    <div>
                        <h3>Capacidad de adaptación</h3>
                        <p>Nos adaptamos a cada cliente, mercado y tendencia digital, manteniéndonos al día con los cambios en algoritmos, herramientas y plataformas.</p>
                    </div>
                </div>
                <div class="feature">
                    <div class="feature-icon">3</div>
                    <div>
                        <h3>Resultados medibles</h3>
                        <p>No vendemos "humo", sino datos: tráfico, conversiones, ROI y engagement. Usamos herramientas de analítica para optimizar constantemente.</p>
                    </div>
                </div>
                <div class="feature">
                    <div class="feature-icon">4</div>
                    <div>
                        <h3>Comunicación clara</h3>
                        <p>Explicamos lo técnico en términos entendibles y escuchamos al cliente en lugar de imponer soluciones predeterminadas.</p>
                    </div>
                </div>
                <div class="feature">
                    <div class="feature-icon">5</div>
                    <div>
                        <h3>Creatividad con propósito</h3>
                        <p>Creamos campañas atractivas siempre alineadas con los objetivos del negocio, equilibrando diseño, copywriting y estrategia.</p>
                    </div>
                </div>
                <div class="feature">
                    <div class="feature-icon">6</div>
                    <div>
                        <h3>Enfoque multicanal</h3>
                        <p>Dominamos redes sociales, email marketing, branding y desarrollo web, integrando todos los canales de forma coherente.</p>
                    </div>
                </div>
                <div class="feature">
                    <div class="feature-icon">7</div>
                    <div>
                        <h3>Equipo especializado</h3>
                        <p>Contamos con expertos en diferentes áreas: diseño, contenidos, publicidad, desarrollo y análisis, para ofrecer soluciones completas.</p>
                    </div>
                </div>
                <div class="feature">
                    <div class="feature-icon">8</div>
                    <div>
                        <h3>Transparencia y ética</h3>
                        <p>No prometemos milagros ni vendemos servicios innecesarios. Somos honestos con tiempos, presupuestos y expectativas.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="results" id="resultados">
        <div class="container">
            <div class="section-header">
                <h2>Resultados que hablan por sí mismos</h2>
                <p>Ayudamos a nuestros clientes a lograr un alto impacto en el mundo digital</p>
            </div>
            <div class="counter-grid">
                <div class="counter">
                    <div class="number">150+</div>
                    <p>Clientes satisfechos</p>
                </div>
                <div class="counter">
                    <div class="number">89%</div>
                    <p>Aumento promedio en engagement</p>
                </div>
                <div class="counter">
                    <div class="number">75%</div>
                    <p>Incremento medio en conversiones</p>
                </div>
                <div class="counter">
                    <div class="number">200+</div>
                    <p>Campañas exitosas</p>
                </div>
            </div>
        </div>
    </section>

    <section class="contact" id="contacto">
        <div class="container">
            <div class="section-header">
                <h2>Contacta con nosotros</h2>
                <p>Estamos listos para impulsar tu marca al siguiente nivel</p>
            </div>
            <div class="contact-grid">
                <div class="contact-info">
                    <div class="contact-item">
                        <div class="contact-icon">
                            <img src="/api/placeholder/30/30" alt="Ubicación">
                        </div>
                        <div>
                            <h3>Ubicación</h3>
                            <p>Murcia, España</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <img src="/api/placeholder/30/30" alt="Email">
                        </div>
                        <div>
                            <h3>Email</h3>
                            <p>digitalimur@gmail.com</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <img src="/api/placeholder/30/30" alt="Teléfono">
                        </div>
                        <div>
                            <h3>Teléfono</h3>
                            <p>692 455 159</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <img src="/api/placeholder/30/30" alt="Horario">
                        </div>
                        <div>
                            <h3>Horario</h3>
                            <p>Lunes a Viernes: 9:30 - 18:00</p>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <form>
                        <div class="form-group">
                            <label for="name">Nombre</label>
                            <input type="text" id="name" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="email" id="email" name="email" required>
                        </div>
                        <div class="form-group">
                            <label for="phone">Teléfono</label>
                            <input type="tel" id="phone" name="phone">
                        </div>
                        <div class="form-group">
                            <label for="message">Mensaje</label>
                            <textarea id="message" name="message" required></textarea>
                        </div>
                        <button type="submit" class="btn">Enviar mensaje</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Digitalimur</h3>
                    <p>Agencia de marketing digital especializada en potenciar marcas y empresas en el entorno digital, logrando alto impacto y resultados medibles.</p>
                </div>
                <div class="footer-section">
                    <h3>Servicios</h3>
                    <ul class="footer-links">
                        <li><a href="#">Estrategia Digital</a></li>
                        <li><a href="#">Gestión de Redes Sociales</a></li>
                        <li><a href="#">Publicidad Digital</a></li>
                        <li><a href="#">Creación de Contenido</a></li>
                        <li><a href="#">Analítica y Resultados</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Enlaces rápidos</h3>
                    <ul class="footer-links">
                        <li><a href="#inicio">Inicio</a></li>
                        <li><a href="#servicios">Servicios</a></li>
                        <li><a href="#nosotros">Por qué nosotros</a></li>
                        <li><a href="#resultados">Resultados</a></li>
                        <li><a href="#contacto">Contacto</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Síguenos</h3>
                    <ul class="social-links">
                        <li><a href="#">FB</a></li>
                        <li><a href="#">IG</a></li>
                        <li><a href="#">TW</a></li>
                        <li><a href="#">LI</a></li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 Digitalimur. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>
</body>
</html>

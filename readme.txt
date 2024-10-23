<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./Styles.css"
    <link href="https://fonts.googleapis.com/css?family=Roboto:400,700" rel="stylesheet">
    <title>Agencia de Marketing</title>
    

</head>
<body>
    <!-- Header -->
    <header>
        <nav>
            <div class="logo">
            </div>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#about">Acerca de</a></li>
                <li><a href="#services">Servicios</a></li>
                <li><a href="#portfolio">Portafolio</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home section -->
    <section id="home" class="hero">
        <h1>Transformamos ideas en estrategias que conectan marcas con personas.</h1>
        <p>Impulsa tu marca con soluciones creativas y efectivas en marketing, diseño y publicidad.</p>
        <a href="#services" class="cta"></a>
        <button>Descubre más</button>
    </section>

    <!-- Servicios Destacados -->
    <section class="services-highlights">
        <h2>Nuestros Servicios</h2>
        <div class="service">
            <h3>Marketing Digital</h3>
            <p>Potenciamos tu marca en redes sociales y motores de búsqueda.</p>
        </div>
        <div class="service">
            <h3>Diseño Gráfico</h3>
            <p>Creamos identidades visuales memorables que comunican tu esencia.</p>
        </div>
        <div class="service">
            <h3>Publicidad</h3>
            <p>Estrategias publicitarias que generan resultados medibles.</p>
        </div>
    </section>

    <!-- Testimonios -->
    <section class="testimonials">
        <h2>Lo que dicen nuestros clientes</h2>
        <blockquote>
            <p>"Trabajar con [Nombre de la agencia] nos permitió incrementar nuestra visibilidad en un 40% en solo 6 meses. Su enfoque creativo y estratégico es incomparable."</p>
            <cite>Cliente X</cite>
        </blockquote>
    </section>
</body>
</html>



<section id="about" class="about-us">
    <h2>Acerca de Nosotros</h2>
    <p>En [Nombre de la agencia], somos un equipo apasionado por la creatividad y los resultados. Desde el diseño gráfico hasta estrategias publicitarias completas, nos dedicamos a conectar marcas con audiencias de manera efectiva y memorable.</p>

    <h3>Nuestro equipo</h3>
    <div class="team-member">
        <img src="ruta-a-la-imagen.jpg" alt="Foto del miembro del equipo">
        <h4>Nombre del miembro</h4>
        <p>Especialidad y breve descripción del rol.</p>
    </div>

    <h3>Nuestros Valores</h3>
    <ul>
        <li><strong>Creatividad:</strong> Buscamos soluciones innovadoras en cada proyecto.</li>
        <li><strong>Compromiso:</strong> Nos involucramos profundamente en cada detalle de tu campaña.</li>
        <li><strong>Resultados:</strong> Medimos el éxito en función de los resultados tangibles que obtenemos.</li>
    </ul>
</section>





<section id="services" class="services">
    <h2>Nuestros Servicios</h2>
    <div class="service-item">
        <h3>Marketing Digital</h3>
        <p>Con nuestras estrategias de marketing digital, tu marca logrará destacar entre la competencia. Implementamos campañas en redes sociales, SEO, Google Ads y más para generar resultados que impulsan tu negocio.</p>
    </div>
    <div class="service-item">
        <h3>Diseño Gráfico</h3>
        <p>Desarrollamos identidades visuales que comunican la esencia de tu marca. Desde logotipos hasta material promocional, nuestro equipo de diseño crea piezas que atraen y convencen.</p>
    </div>
    <div class="service-item">
        <h3>Publicidad</h3>
        <p>Creamos campañas publicitarias estratégicas y creativas que conectan con tu público objetivo. Desde medios tradicionales hasta digitales, adaptamos nuestras ideas a tu necesidad y mercado.</p>
    </div>
</section>





<section id="portfolio" class="portfolio">
    <h2>Portafolio</h2>
    <div class="portfolio-item">
        <img src="https://www.fulllife.com.mx/wp-content/uploads/2023/06/nota_2_desktop_signos-de-felicidad_feb_image.jpg)" alt="Proyecto 1">
        <h3>Proyecto 1</h3>
        <p>Desarrollo de campaña publicitaria para [Nombre de cliente]. Aumento del 35% en conversiones y un impacto notable en la visibilidad online.</p>
    </div>
    <div class="portfolio-item">
        <img src="https://www.fulllife.com.mx/wp-content/uploads/2023/06/nota_2_desktop_signos-de-felicidad_feb_image.jpg)" alt="Proyecto 2">
        <h3>Proyecto 2</h3>
        <p>Diseño gráfico y branding para [Nombre de cliente]. Resultado: identidad visual coherente y diferenciada.</p>
    </div>
</section>




<section id="blog" class="blog">
    <h2>Blog</h2>
    <div class="blog-post">
        <img src="https://www.fulllife.com.mx/wp-content/uploads/2023/06/nota_2_desktop_signos-de-felicidad_feb_image.jpg)" alt="Título del post">
        <h3>Título del artículo</h3>
        <p>Breve descripción del artículo.</p>
        <a href="#" class="cta">Leer más</a>
    </div>
    <div class="blog-post">
        <img src="ruta-a-la-imagen-blog2.jpg" alt="Título del post">
        <h3>Título del artículo</h3>
        <p>Breve descripción del artículo.</p>
        <a href="#" class="cta">Leer más</a>
    </div>
</section>





<section id="contact" class="contact">
    <h2>Contacto</h2>
    <p>¿Listo para llevar tu marca al siguiente nivel? Contáctanos hoy mismo.</p>
    <form action="enviar.php" method="post">
        <input type="text" name="nombre" placeholder="Tu nombre" required>
        <input type="email" name="email" placeholder="Tu correo electrónico" required>
        <input type="tel" name="teléfono" placeholder="Tu teléfono" requiered>
        <textarea name="mensaje" placeholder="Tu mensaje" required></textarea>
        <button type="submit">Enviar</button>
        
    </form>
    <div class="contact-info">
        <p>También puedes escribirnos a <a href="mailto:correo@agencia.com">correo@agencia.com</a> o llamarnos al +123456789.</p>
    </div>
   
   


   
    <div class="contenedor">
        <h1>El call to action va acá.<span>&#160;</span></h1>
    </div>
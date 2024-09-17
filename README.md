<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Empresa</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: #333;
            background-color: #f4f4f4;
        }
        .header {
            background-color: #2e8b57; /* Verde oscuro */
            color: #fff;
            padding: 15px;
            text-align: center;
        }
        .header img {
            max-width: 150px;
        }
        .nav {
            background-color: #fff;
            border-bottom: 2px solid #2e8b57;
            display: flex;
            justify-content: center;
        }
        .nav a {
            display: block;
            padding: 14px 20px;
            color: #2e8b57;
            text-decoration: none;
            text-align: center;
            cursor: pointer;
        }
        .nav a.active {
            background-color: #e0f7e0; /* Color verde claro para la pestaña activa */
        }
        .container {
            padding: 20px;
        }
        .section {
            display: none;
        }
        .section img {
            max-width: 100%;
            height: auto;
        }
        .footer {
            background-color: #2e8b57;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="header">
        <img src="https://blogger.googleusercontent.com/img/a/AVvXsEhRZntESu9b5W1lqh9ucFuM2rAjwvv3gokdU-yO1rl9VO7tflpiW87-jkL6CuBa6AKSSuuYi-ax4n0CStoQgMZFc_d_pkCJJB4kH1ube8dx6hptZQfr5Fjw0w0UMq7K4VEeXb_9s4h5D-sOQJOds2gfgUv5RKOLU4BGVGzBQ-eU6xj86qki96jENbjeXsS-" alt="Logo de la Empresa">
        <h1>Innovatech Systems</h1>
    </div>
    <div class="nav">
        <a id="tab-inicio" class="active" onclick="showSection('inicio')">Inicio</a>
        <a id="tab-vision" onclick="showSection('vision')">Visión</a>
        <a id="tab-mision" onclick="showSection('mision')">Misión</a>
        <a id="tab-servicios" onclick="showSection('servicios')">Servicios</a>
        <a id="tab-contacto" onclick="showSection('contacto')">Contacto</a>
    </div>
    <div class="container">
        <div id="inicio" class="section" style="display: block;">
            <h2>Inicio</h2>
            <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgaqR9nZ9ozJD5MMmpXUFRqxD4a4p4_RL54uLFwEiP6PvxQDrVz1LMPpxMJ0y8RlkpyYyEPhMYq6KGYURgWG9SEMHIRjm4AryFlO9Sw7LZh9WLhhCRJw2g-uwGLPJtHga0c7qWke7IvvdDWFvv4ekaJHzIM6Yg94CXcw9ar5EjlS0U4zf-e8dW8uESWJWzw/s320/AASASASAS.jpg" alt="Imagen de Inicio">
            <p>En Innovatech Systems, nos enorgullece ser tu socio estratégico en el mundo de la tecnología y la informática. Nuestra misión es ofrecerte soluciones innovadoras y de alta calidad que no solo cumplan, sino que superen tus expectativas. Explora nuestro sitio y descubre cómo nuestras tecnologías avanzadas y nuestro compromiso con la excelencia pueden ayudarte a alcanzar tus objetivos. Desde la venta de equipos de alto rendimiento hasta el soporte técnico especializado y la consultoría personalizada, estamos aquí para ofrecerte lo mejor en cada paso del camino. Únete a nosotros en esta emocionante jornada tecnológica y experimenta el futuro de la informática hoy mismo. En [Nombre de la Empresa], tu satisfacción y éxito son nuestra prioridad.</p>
        </div>
        <div id="vision" class="section">
            <h2>Visión</h2>
            <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhjnJ4HnBHkSt62r5LMUB-suN03hqYEjD6egP_mKLUqGofWM30G8ho4rC5AYTrCXI1P0IPwOtXB6EPdc5DFQ40L3URFDMEqjPQcq4jH-V3pVBN10PEMCLhCHMTcMXbJ4F5k5p3jMFKTqEoQJ8f-Rf9O6I5XA48_sUxs0f2_P72xWnXqCqCV4VXk7BihiGmU/s320/v.png" alt="Imagen de Visión">
            <p>En Innovatech Systems, aspiramos a ser reconocidos como líderes en nuestra industria, distinguiéndonos por nuestra capacidad para ofrecer servicios excepcionales que superen las expectativas de nuestros clientes. Nuestra visión es transformar la experiencia de nuestros clientes mediante un enfoque innovador y personalizado, combinando la más alta calidad en productos y servicios con un profundo compromiso con la excelencia. Creemos que el éxito de nuestra empresa está intrínsecamente ligado al éxito de nuestros clientes. Por ello, nos dedicamos a entender a fondo sus necesidades y desafíos, proporcionando soluciones tecnológicas avanzadas que impulsan su crecimiento y eficiencia. Nos esforzamos por ser un socio estratégico en su camino hacia el éxito, ofreciendo un servicio al cliente inigualable y una atención minuciosa a cada detalle. Nos comprometemos a mantenernos a la vanguardia de la innovación tecnológica, adaptándonos rápidamente a los cambios y tendencias del mercado para ofrecer las soluciones más efectivas y confiables. Nuestro equipo de expertos está en constante formación y actualización para garantizar que nuestras soluciones no solo sean las más avanzadas, sino también las más adecuadas para cada situación específica. Además, valoramos profundamente la sostenibilidad y la responsabilidad social. Trabajamos para minimizar nuestro impacto ambiental y contribuir positivamente a la comunidad, buscando siempre prácticas empresariales responsables y éticas. En resumen, nuestra visión es construir un futuro donde nuestras soluciones y servicios no solo cumplan, sino que superen las expectativas de nuestros clientes, estableciendo nuevos estándares de calidad y rendimiento en la industria.</p>
        </div>
        <div id="mision" class="section">
            <h2>Misión</h2>
            <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgD7C5NyP9n6gJSIB6_lAyR1vY6loZ5xVxxD_V2-CR8jWewTb1H9IGaja_5PpBRhOtF8BQqKJ1qL9vjPtFtDon1fko9LQuLe_eMSer8uf37cUw_u3jOl_7sPaJ7oGxC7W2N1DZINLYDwKuQ4k7fiI84hCUrhTlkcrcrnwUZiXHvVeA8YKqxfOha1soatfVQ/s320/mejora%20mision.jpg" alt="Imagen de Misión"> <!-- Ejemplo de imagen, cámbiala por la que desees -->
            <p>Nuestra misión es proporcionar soluciones tecnológicas integrales que mejoren la eficiencia y el rendimiento de nuestros clientes. Nos comprometemos a ofrecer productos y servicios innovadores y de alta calidad, respaldados por un servicio al cliente excepcional. Buscamos no solo satisfacer, sino superar las expectativas de nuestros clientes mediante un enfoque personalizado y soluciones a medida. Estamos dedicados a la mejora continua y a la innovación constante para mantenernos a la vanguardia de la tecnología y asegurar que nuestros clientes siempre reciban lo mejor.</p>
        </div>
        <div id="servicios" class="section">
            <h2>Servicios</h2>
            <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgAnCeb0mn5UWYswS9hz6T8U4f9b_f9c6MWXqfYHCEt-OvOGCOK7tp1_rAxhXRp_PWTNASB0p58dncqJJgOBLQxYy3jbT3RGErOA-TtzmAet9sqwrbp37HlMUnNUNRffKOhTZfVipZm0GAtA1tfNhMRL_pxoGDtTLfopOK4lhagvD7bBW9pAnj0XVx4I2Jr/s320/s.png" alt="Imagen de Servicios">
            <ul>
                <li><strong>Venta de Computadoras:</strong> Ofrecemos una amplia gama de computadoras de alto rendimiento, desde equipos de escritorio hasta laptops, adaptados a tus necesidades específicas.</li>
                <li><strong>Soporte Técnico:</strong> Nuestro equipo de expertos está disponible para resolver cualquier problema técnico que puedas enfrentar con tu equipo. Esto incluye diagnóstico, reparación y mantenimiento.</li>
                <li><strong>Instalación de Software:</strong> Instalamos y configuramos software necesario para tu equipo, ya sea para uso personal o profesional. Incluye sistemas operativos, aplicaciones, y software especializado.</li>
                <li><strong>Consultoría en TI:</strong> Proporcionamos asesoría personalizada para ayudarte a seleccionar las mejores soluciones tecnológicas para tu negocio o uso personal. Incluye recomendaciones sobre hardware, software y redes.</li>
                <li><strong>Servicios de Red y Conectividad:</strong> Configuración e instalación de redes locales (LAN), redes inalámbricas (Wi-Fi) y soluciones de conectividad para garantizar que tu equipo esté siempre en línea.</li>
                <li><strong>Backup y Recuperación de Datos:</strong> Soluciones para la copia de seguridad de tus datos importantes y recuperación en caso de pérdida o daño. Protege tu información valiosa contra cualquier eventualidad.</li>
                <li><strong>Venta de Accesorios:</strong> Disponemos de una variedad de accesorios para mejorar tu experiencia informática, incluyendo teclados, ratones, monitores, impresoras y más.</li>
            </ul>
        </div>
        <div id="contacto" class="section">
            <h2>Contacto</h2>
            <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgxEWEP5ACIuznoNhkZvuz1tRy99gzimPwODBLazbMS7mNYIhyphenhyphenb6oTDAfjhQmv2VWRgb5WFEwcV1_u6Pda0WLMgJCvykZeRtJj9zUty0Sk8icwygXj6AnSUI4v_7u3Epa3QP6Q0Ah1RBXwGWgruGwxRwaPA_gemtrvRsiFvphvL1Vo7e1xTGc4m99JyFlWV/s320/contactos.jpg" alt="Imagen de Contacto">
            <p>Para más información, no dudes en contactarnos a través de los siguientes medios:</p>
            <p>Email: santiago_otalorac@soy.sena.edu.co</p>
            <p>Teléfono: (123) 3203781142</p>
        </div>
    </div>
    <div class="footer">
        &copy; 2024 Mi Empresa. Todos los derechos reservados.
    </div>

    <script>
        function showSection(sectionId) {
            // Ocultar todas las secciones
            var sections = document.querySelectorAll('.section');
            sections.forEach(function(section) {
                section.style.display = 'none';
            });

            // Eliminar la clase activa de todas las pestañas
            var tabs = document.querySelectorAll('.nav a');
            tabs.forEach(function(tab) {
                tab.classList.remove('active');
            });

            // Mostrar la sección seleccionada
            document.getElementById(sectionId).style.display = 'block';

            // Añadir la clase activa a la pestaña seleccionada
            document.getElementById('tab-' + sectionId).classList.add('active');
        }
    </script>
</body>
</html>

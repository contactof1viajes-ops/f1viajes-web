<!DOCTYPE html>

<html lang="es">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>F1 Viajes</title>

<style>

    body { font-family: 'Poppins', sans-serif; margin:0; padding:0; background:#f4f4f4; color:#333; }

    header { background: #00aaff; color: white; padding: 20px; text-align: center; }

    header img { max-height: 80px; }

    h1, h2 { margin: 10px 0; }

    .container { width: 90%; max-width: 1200px; margin: 0 auto; padding: 20px 0; }

    .trips { display: grid; grid-template-columns: repeat(auto-fit,minmax(300px,1fr)); gap: 20px; }

    .trip-card { background: white; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); padding: 15px; position: relative; display:flex; flex-direction:column; }

    .trip-card img { width: 100%; height: 200px; object-fit: cover; border-radius: 10px; }

    .trip-card h3 { margin: 10px 0; }

    .trip-card ul { list-style:none; padding:0; margin:0 0 10px 0; }

    .trip-card ul li { margin-bottom: 5px; }

    .trip-card .price { font-weight:bold; margin-bottom: 10px; }

    .trip-card button { background:#00aaff; color:white; border:none; padding:10px; border-radius:5px; cursor:pointer; transition:0.3s; }

    .trip-card button:hover { background:#0077aa; }

    footer { background:#333; color:white; text-align:center; padding:20px 10px; margin-top:40px; }

    .whatsapp-btn { position:fixed; bottom:20px; right:20px; background:#25D366; color:white; padding:15px 20px; border-radius:50px; text-decoration:none; font-weight:bold; box-shadow:0 4px 8px rgba(0,0,0,0.2); }

    .whatsapp-btn:hover { background:#1ebe5d; }

</style>

</head>

<body>


<header>

    <img src="https://via.placeholder.com/200x80.png?text=F1+Viajes" alt="F1 Viajes Logo">

    <h1>Bienvenido a F1 Viajes</h1>

    <p>Excelencia en viajes grupales, aventura y diversión</p>

</header>


<div class="container">

    <h2>Próximos Viajes</h2>

    <div class="trips">


        <!-- Oktoberfest -->

        <div class="trip-card">

            <img src="https://via.placeholder.com/400x200.png?text=Oktoberfest" alt="Oktoberfest">

            <h3>🍺 Oktoberfest 🍺</h3>

            <ul>

                <li>Salida: 20/11/25</li>

                <li>Regreso: 24/11/25</li>

                <li>3 Noches de alojamiento con desayuno</li>

                <li>Bus mix o semicama</li>

                <li>Traslados al parque cervecero</li>

            </ul>

            <div class="price">Desde $349,900</div>

            <button onclick="window.open('https://wa.me/5491126916396?text=Hola,%20quiero%20informacion%20sobre%20Oktoberfest','_blank')">Consultar cupo</button>

        </div>


        <!-- Oktoberfest Receptivo -->

        <div class="trip-card">

            <img src="https://via.placeholder.com/400x200.png?text=Oktoberfest+Receptivo" alt="Oktoberfest Receptivo">

            <h3>🍺 Oktoberfest Receptivo 🍺</h3>

            <ul>

                <li>Check-in: 21/11/25</li>

                <li>Check-out: 24/11/25</li>

                <li>3 Noches de alojamiento con desayuno</li>

                <li>Traslados al parque cervecero</li>

            </ul>

            <div class="price">Desde $249,900</div>

            <button onclick="window.open('https://wa.me/5491126916396?text=Hola,%20quiero%20informacion%20sobre%20Oktoberfest%20Receptivo','_blank')">Consultar cupo</button>

        </div>


        <!-- San Rafael, Mendoza -->

        <div class="trip-card">

            <img src="https://via.placeholder.com/400x200.png?text=San+Rafael+Mendoza" alt="San Rafael Mendoza">

            <h3>🗻 San Rafael, Mendoza 🗻</h3>

            <ul>

                <li>Salida: 20/11/25 20:30 hs</li>

                <li>Regreso: 25/11/25 01:00 hs</li>

                <li>Bus MIX ida y vuelta</li>

                <li>Cabañas Villa del Luján con desayuno y piscina</li>

                <li>Excursiones incluidas: Bodegas, Los Reyunos, Valle Grande, Cañón del Atuel</li>

            </ul>

            <div class="price">$369,900</div>

            <button onclick="window.open('https://wa.me/5491126916396?text=Hola,%20quiero%20informacion%20sobre%20San+Rafael+Mendoza','_blank')">Consultar cupo</button>

        </div>


        <!-- Piriápolis -->

        <div class="trip-card">

            <img src="https://via.placeholder.com/400x200.png?text=Piriapolis" alt="Piriápolis">

            <h3>🏖️ Piriápolis 🏖️</h3>

            <ul>

                <li>Salida: 17/01/26</li>

                <li>Regreso: 23/01/26</li>

                <li>Bus mix ida y vuelta</li>

                <li>Hotel SELECT con desayuno, piscina y sauna</li>

                <li>Excursiones incluidas: Punta del Este, Fuente de Venus, Cerro del Toro</li>

            </ul>

            <div class="price">USD 510</div>

            <button onclick="window.open('https://wa.me/5491126916396?text=Hola,%20quiero%20informacion%20sobre%20Piriapolis','_blank')">Consultar cupo</button>

        </div>


        <!-- Florianópolis 1 -->

        <div class="trip-card">

            <img src="https://via.placeholder.com/400x200.png?text=Florianopolis+1" alt="Florianópolis 1">

            <h3>🇧🇷 Florianópolis 1 🇧🇷</h3>

            <ul>

                <li>Salidas: Dic 26, Ene 02,09,16,23,30, Feb 06,13,20,27, Mar 06,13,20,27, Abr 03</li>

                <li>Bus cama ida y vuelta</li>

                <li>Hospedaje en Posadas Stefany, Floripa y Jurerê</li>

                <li>Excursiones: playas, fiesta y actividades Premium</li>

            </ul>

            <div class="price">USD 999-1099</div>

            <button onclick="window.open('https://wa.me/5491126916396?text=Hola,%20quiero%20informacion%20sobre%20Florianopolis%201','_blank')">Consultar cupo</button>

        </div>


        <!-- Florianópolis 2 -->

        <div class="trip-card">

            <img src="https://via.placeholder.com/400x200.png?text=Florianopolis+2" alt="Florianópolis 2">

            <h3>🇧🇷 Florianópolis 2 🇧🇷</h3>

            <ul>

                <li>Salida: 06/03/26</li>

                <li>Bus mix ida y vuelta</li>

                <li>Hospedaje en Complejo Hanna</li>

                <li>Excursiones a playas y actividades nocturnas</li>

            </ul>

            <div class="price">Desde USD 690</div>

            <button onclick="window.open('https://wa.me/5491126916396?text=Hola,%20quiero%20informacion%20sobre%20Florianopolis%202','_blank')">Consultar cupo</button>

        </div>


    </div>

</div>


<a href="https://wa.me/5491126916396?text=Hola,%20quiero%20informacion%20sobre%20F1%20Viajes" class="whatsapp-btn">WhatsApp F1 Viajes</a>


<footer>

    <p>© 2025 F1 Viajes | Todos los derechos reservados</p>

</footer>


</body>

</html>

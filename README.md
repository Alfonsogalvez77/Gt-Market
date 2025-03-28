# Gt-Market
Supermercado en Linea
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GT Market</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #ff5733;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 40px;
            text-align: center;
        }
        #inicio {
            background: url('images/banner.jpg') no-repeat center center/cover;
            color: white;
            padding: 60px 20px;
        }
        .categoria {
            background-color: white;
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .producto {
            display: inline-block;
            margin: 10px;
            text-align: center;
        }
        .producto img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
        }
        .descuento {
            color: red;
            font-weight: bold;
            text-decoration: line-through;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>GT Market</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#tienda">Tienda</a></li>
                <li><a href="#quienes-somos">¿Quiénes Somos?</a></li>
                <li><a href="#politica">Política y Privacidad</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="inicio">
        <h2>Bienvenidos a GT Market</h2>
        <p>Encuentra los mejores productos a precios increíbles.</p>
        <h3>Productos Más Vendidos</h3>
    </section>
    
    <section id="tienda">
        <h2>Nuestra Tienda</h2>
        
        <div class="categoria" id="lacteos">
            <h3>Lácteos</h3>
            <div class="producto"><img src="images/leche.jpg" alt="Leche"><p>Leche - $10</p></div>
            <div class="producto"><img src="images/yogur.jpg" alt="Yogur"><p>Yogur - <span class="descuento">$8</span> $6</p></div>
        </div>
        
        <div class="categoria" id="quesos-embutidos">
            <h3>Quesos y Embutidos</h3>
            <div class="producto"><img src="images/queso_cheddar.jpg" alt="Queso Cheddar"><p>Queso Cheddar - $15</p></div>
            <div class="producto"><img src="images/salchichas.jpg" alt="Salchichas"><p>Salchichas - <span class="descuento">$12</span> $9</p></div>
        </div>
        
        <div class="categoria" id="carnes-mariscos">
            <h3>Carnes y Mariscos</h3>
            <div class="producto"><img src="images/carne_res.jpg" alt="Carne de Res"><p>Carne de Res - $20</p></div>
            <div class="producto"><img src="images/camarones.jpg" alt="Camarones"><p>Camarones - <span class="descuento">$25</span> $18</p></div>
        </div>
        
        <div class="categoria" id="bebidas">
            <h3>Bebidas</h3>
            <div class="producto"><img src="images/jugo_naranja.jpg" alt="Jugo de Naranja"><p>Jugo de Naranja - $5</p></div>
            <div class="producto"><img src="images/refresco.jpg" alt="Refresco"><p>Refresco - <span class="descuento">$4</span> $3</p></div>
        </div>
        
        <div class="categoria" id="productos-limpieza">
            <h3>Productos de Limpieza</h3>
            <div class="producto"><img src="images/detergente.jpg" alt="Detergente"><p>Detergente - $8</p></div>
            <div class="producto"><img src="images/desinfectante.jpg" alt="Desinfectante"><p>Desinfectante - <span class="descuento">$7</span> $5</p></div>
        </div>
        
        <div class="categoria" id="cuidado-personal">
            <h3>Cuidado Personal e Higiene</h3>
            <div class="producto"><img src="images/shampoo.jpg" alt="Shampoo"><p>Shampoo - $10</p></div>
            <div class="producto"><img src="images/pasta_dental.jpg" alt="Pasta Dental"><p>Pasta Dental - <span class="descuento">$6</span> $4</p></div>
        </div>
    </section>
    
    <section id="quienes-somos">
        <h2>¿Quiénes Somos?</h2>
        <p>Somos GT Market, tu tienda de confianza con los mejores productos.</p>
    </section>
    
    <section id="politica">
        <h2>Política y Privacidad</h2>
        <p>Consulta nuestra política de privacidad y términos de uso.</p>
    </section>
    
    <footer>
        <p>&copy; 2025 GT Market. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

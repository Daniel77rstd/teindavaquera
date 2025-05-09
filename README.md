<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Tienda Online</title>
    <link rel="stylesheet" href="estilotienda.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        .productos {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
            gap: 20px;
        }
        .producto {
            background-color: white;
            border-radius: 10px;
            width: 250px;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }
        .producto img {
            width: 100%;
            border-radius: 10px;
        }
        .producto h3 {
            margin: 10px 0;
        }
        .producto p {
            color: #555;
        }
        .btn-comprar {
            display: inline-block;
            padding: 10px 20px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
        .btn-comprar:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<header>
    <h1>BOTAS DANIEL</h1>
    <h2>Tu mejor elección</h2>
    <p>¡Artículos Vaqueros!</p>
</header>

<section class="productos">
    <div class="producto">
        <img src="Bota Yaquiz.jpg" alt="Botas Yaquiz talla 17.5 Mexicano">
        <h3>Botas Yaquiz</h3>
        <h5>Talla 17.5</h5>
        <p>Q920.00</p>
        <a href="https://wa.me/50241005102?text=Hola,%20quiero%20comprar%20las%20Botas%20Yaquiz%20talla%2017.5%20por%20Q920.00" class="btn-comprar" target="_blank">Comprar</a>
    </div>
    <div class="producto">
        <img src="Bota Yaquiz C.jpg" alt="Botas Yaquiz talla 25.5 Mexicano">
        <h3>Botas Yaquiz</h3>
        <h5>Talla 25.5</h5>
        <p>Q1,150.00</p>
        <a href="https://wa.me/50241005102?text=Hola,%20quiero%20comprar%20las%20Botas%20Yaquiz%20talla%2025.5%20por%20Q1,150.00" class="btn-comprar" target="_blank">Comprar</a>
    </div>
    <div class="producto">
        <img src="Bota Cheyenne.jpg" alt="Botas Cheyenne talla 22.5 Mexicano">
        <h3>Botas Cheyenne</h3>
        <h5>Talla 22.5</h5>
        <p>Q890.00</p>
        <a href="https://wa.me/50241005102?text=Hola,%20quiero%20comprar%20las%20Botas%20Cheyenne%20talla%2022.5%20por%20Q890.00" class="btn-comprar" target="_blank">Comprar</a>
    </div>
    <div class="producto">
        <img src="Bota el  malcreado .jpg" alt="Botas el Malcreado talla 27 Mexicano">
        <h3>Botas el Malcreado</h3>
        <h5>Talla 27</h5>
        <p>Q1,500.00</p>
        <a href="https://wa.me/50241005102?text=Hola,%20quiero%20comprar%20las%20Botas%20el%20Malcreado%20talla%2027%20por%20Q1,500.00" class="btn-comprar" target="_blank">Comprar</a>
    </div>
    <div class="producto">
        <img src="img.jpg"alt="producto5">
        <h3>Botas Rodeo</h3>
        <h5>Talla 35</h5>
        <p>Q2,000.00</p>
        <a href="https://wa.me/50241005102?text=Hola,%20quiero%20comprar%20las%20Botas%20el%20Rodeo%20talla%2035%20por%20Q2,000.00" class="btn-comprar" target="_blank">Comprar</a>
</div>
</section>

</body>
</html>


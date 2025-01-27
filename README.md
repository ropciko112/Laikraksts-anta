<!DOCTYPE html>
<html lang="lv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galerija</title>
    <style>
        /* CSS Stili */
        body {
            font-family: "Georgia", "Times New Roman", serif;
            background-color: #a1832b;
            margin: 0;
            padding: 0;
            color: #333;
        }

        .gallery {
            padding: 30px;
            background-color: white;
            margin: 20px auto;
            border-radius: 10px;
            width: 80%;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .gallery h3 {
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
            color: #2c2c2c;
            margin-bottom: 15px;
        }

        .gallery img {
            display: block;
            margin: 10px auto;
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            border: 2px solid #ccc;
        }

        footer {
            background-color: #2c2c2c;
            color: white;
            text-align: center;
            padding: 15px;
            font-family: 'Georgia', serif;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        footer p {
            margin: 0;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <!-- Galerijas sadaļa -->
    <div class="gallery">
        <h3>Galerija</h3>
        <img src="https://raw.githubusercontent.com/ropciko112/Laikrakstsanta/refs/heads/main/Image/9i0vkz.jpg" alt="Galerijas attēls 1">
        <img src="https://via.placeholder.com/800x400.png?text=Galerijas+Attēls+2" alt="Galerijas attēls 2">
        <img src="https://via.placeholder.com/800x400.png?text=Galerijas+Attēls+3" alt="Galerijas attēls 3">
    </div>

    <footer>
        <p>&copy; 2025 Galerija. Visas tiesības aizsargātas.</p>
    </footer>
</body>
</html>

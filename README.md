# html-css
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Galeria de Imagens</title>
</head>
<body>
    <h1>Galeria de Imagens</h1>
    <div class="galeria">
        <img src="imagem1.jpg" alt="Descrição da imagem 1" width="300" height="200" title="Título da imagem 1">
        <img src="imagem2.jpg" alt="Descrição da imagem 2" width="300" height="200" title="Título da imagem 2">
        <img src="imagem3.jpg" alt="Descrição da imagem 3" width="300" height="200" title="Título da imagem 3">
        <img src="imagem4.jpg" alt="Descrição da imagem 4" width="300" height="200" title="Título da imagem 4">
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background-color: #f4f4f4;
}

.galeria {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.galeria img {
    border: 2px solid #333;
    border-radius: 10px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.5);
    margin: 10px;
    transition: transform 0.2s;
}

.galeria img:hover {
    transform: scale(1.05);
}

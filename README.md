<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Vídeos</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Catálogo de Vídeos</h1>
    </header>
    <main>
        <div class="video-catalog">
            <div class="video-item">
                <img src="caminho_para_imagem_1.jpg" alt="Descrição do Vídeo 1">
                <h2>Título do Vídeo 1</h2>
                <p>Descrição breve do vídeo 1.</p>
            </div>
            <div class="video-item">
                <img src="caminho_para_imagem_2.jpg" alt="Descrição do Vídeo 2">
                <h2>Título do Vídeo 2</h2>
                <p>Descrição breve do vídeo 2.</p>
            </div>
            <!-- Adicione mais vídeos conforme necessário -->
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Seu Nome. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

main {
    padding: 20px;
}

.video-catalog {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
}

.video-item {
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    margin: 10px;
    padding: 20px;
    width: 300px;
    text-align: center;
    transition: transform 0.2s;
}

.video-item:hover {
    transform: scale(1.05);
}

.video-item img {
    max-width: 100%;
    border-radius: 8px;
}

.video-item h2 {
    color: #333;
    font-size: 1.5em;
    margin: 10px 0;
}

video-item p {
    color: #666;
}


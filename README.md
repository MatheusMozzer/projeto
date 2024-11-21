<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Vídeos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .video-card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            overflow: hidden;
            margin-bottom: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .video-card img {
            width: 100%;
            height: auto;
        }
        .video-card .content {
            padding: 15px;
        }
        .video-card .content h2 {
            margin: 0 0 10px 0;
            font-size: 1.5em;
            color: #333;
        }
        .video-card .content p {
            margin: 0 0 15px 0;
            color: #666;
        }
        .video-card .content a {
            display: inline-block;
            padding: 10px 15px;
            background-color: #007BFF;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        .video-card .content a:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Catálogo de Vídeos</h1>
        <div class="video-card">
            <img src="video-thumbnail1.jpg" alt="Thumbnail do Vídeo 1">
            <div class="content">
                <h2>Título do Vídeo 1</h2>
                <p>Descrição curta do vídeo 1.</p>
                <a href="link-do-video1" target="_blank">Assistir</a>
            </div>
        </div>
        <div class="video-card">
            <img src="video-thumbnail2.jpg" alt="Thumbnail do Vídeo 2">
            <div class="content">
                <h2>Título do Vídeo 2</h2>
                <p>Descrição curta do vídeo 2.</p>
                <a href="link-do-video2" target="_blank">Assistir</a>
            </div>
        </div>
        <!-- Adicione mais vídeos aqui -->
    </div>
</body>
</html>

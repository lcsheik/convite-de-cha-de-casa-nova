<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .img {
            position: relative; /* Permite posicionar elementos filhos */
            display: inline-block; /* Para que os ícones se posicionem corretamente */
        }
        .img img {
            max-width: 100%; /* Ajusta a largura máxima da imagem */
            height: auto;    /* Mantém a proporção da imagem */
        }
        .icon {
            position: absolute; /* Posiciona o ícone de presente */
            bottom: 50px; /* Distância do fundo da imagem */
            left: 50%; /* Ajusta a posição do ícone de presente */
            transform: translateX(-50%); /* Ajusta a posição para centralizar */
            color: rgb(14, 12, 12); /* Cor do ícone */
            font-size: 60px; /* Tamanho do ícone */
            cursor: pointer; /* Muda o cursor para indicar que é clicável */
        }
        .text {
            position: absolute; /* Permite posicionar o texto dentro da imagem */
            bottom: 10px; /* Distância do fundo da imagem */
            left: 50%; /* Centraliza horizontalmente com o ícone */
            transform: translateX(-50%); /* Ajusta a posição para centralizar */
            color: rgb(14, 12, 12); /* Cor do texto */
            font-size: 16px; /* Tamanho do texto */
            text-align: center; /* Centraliza o texto */
        }
        .location-icon {
            position: absolute; /* Posiciona o ícone de localização */
            bottom: 30px; /* Distância do fundo da imagem */
            left: 60%; /* Ajusta a posição do ícone de localização */
            transform: translateX(-50%); /* Ajusta a posição para centralizar */
            color: rgb(14, 12, 12); /* Cor do ícone */
            cursor: pointer; /* Muda o cursor para indicar que é clicável */
            font-size: 70px; /* Tamanho do ícone */
        }
        .location-text {
            position: absolute; /* Permite posicionar o texto dentro da imagem */
            bottom: -30px; /* Distância do fundo da imagem */
            left: 50%; /* Centraliza horizontalmente com o ícone */
            transform: translateX(-50%); /* Ajusta a posição para centralizar */
            color: rgb(14, 12, 12); /* Cor do texto */
            font-size: 16px; /* Tamanho do texto */
            text-align: center; /* Centraliza o texto */
        }
    </style>
</head>
<body>
    <div class="img">
        <img src="./Você está convidado para o Chá de Panela!.png" alt="">
        
        <a href="https://www.finalfeliz.de/alessandra-de-araujo-iuri-henrique">
            <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" class="icon bi bi-gift" viewBox="0 0 16 16">
                <path d="M3 2.5a2.5 2.5 0 0 1 5 0 2.5 2.5 0 0 1 5 0v.006c0 .07 0 .27-.038.494H15a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1v7.5a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 1 14.5V7a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h2.038A3 3 0 0 1 3 2.506zm1.068.5H7v-.5a1.5 1.5 0 1 0-3 0c0 .085.002.274.045.43zM9 3h2.932l.023-.07c.043-.156.045-.345.045-.43a1.5 1.5 0 0 0-3 0zM1 4v2h6V4zm8 0v2h6V4zm5 3H9v8h4.5a.5.5 0 0 0 .5-.5zm-7 8V7H2v7.5a.5.5 0 0 0 .5.5z"/>
            </svg>
            <div class="text">Lista de Presentes</div>
        </a>

        <a href="https://maps.app.goo.gl/C9q58HYpGA1aAWtx6" class="location-icon">
            <svg xmlns="https://maps.app.goo.gl/C9q58HYpGA1aAWtx6" width="48" height="48" fill="currentColor" class="bi bi-geo-alt" viewBox="0 0 16 16">
                <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A32 32 0 0 1 8 14.58a32 32 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10"/>
                <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4m0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6"/>
            </svg>
            <div class="location-text">Localização do Evento</div>
        </a>
    </div>
</body>
</html>

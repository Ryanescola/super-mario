# super-mario
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Super Mario Quiz</title>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            height: 100vh;
            margin: 0;
            background-color: #87CEEB; /* Azul claro inspirando o céu do Reino dos Cogumelos */
            font-family: 'Roboto', sans-serif;
            overflow: hidden;
        }

        .card-container {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            gap: 30px;
            margin-top: 50px;
        }

        .card {
            width: 320px;
            height: 450px;
            background-color: #ffcc00; /* Amarelo brilhante para representar o tema do Super Mario */
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 22px;
            font-family: 'Press Start 2P', cursive;
            border-radius: 20px;
            cursor: pointer;
            box-shadow: 0 12px 24px rgba(0, 0, 0, 0.2);
            transform-style: preserve-3d;
            transition: transform 0.6s ease, box-shadow 0.3s ease;
            will-change: transform;
            overflow: hidden;
        }

        .card-content {
            display: flex;
            justify-content: center;
            align-items: center;
            position: absolute;
            backface-visibility: hidden;
            padding: 20px;
            text-align: center;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.8);
        }

        .card-front {
            background: #ff5733; /* Cor vermelha vibrante, remetendo ao chapéu do Mario */
            border-radius: 20px;
            box-sizing: border-box;
        }

        .card-back {
            background: #2980b9; /* Azul de fundo, representando o céu do Reino dos Cogumelos */
            transform: rotateY(180deg);
            border-radius: 20px;
            color: #fff;
        }

        .card:hover {
            transform: rotateY(180deg);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
        }

        h3 {
            margin: 0;
            font-size: 24px;
            color: #fff;
        }

        p {
            font-size: 20px;
            margin-top: 10px;
            font-weight: 500;
            color: #fff;
        }

        .title {
            font-size: 35px;
            font-weight: 700;
            color: #fff;
            text-align: center;
            margin-bottom: 40px;
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.6);
        }

        /* Responsividade */
        @media (max-width: 1024px) {
            .card-container {
                gap: 20px;
            }
            .card {
                width: 280px;
                height: 400px;
            }
        }

        @media (max-width: 768px) {
            .card-container {
                flex-direction: column;
                gap: 15px;
            }
            .card {
                width: 90%;
                height: 350px;
            }
        }
    </style>
</head>
<body>
    <div class="title">Super Mario Quiz</div>
    <div class="card-container">
        <!-- Cartões com perguntas e respostas sobre Super Mario -->
        
        <div class="card">
            <div class="card-content card-front">
                <h3>Quem é o criador de Super Mario?</h3>
            </div>
            <div class="card-content card-back">
                <p>Shigeru Miyamoto é o criador de Super Mario!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Qual é o nome do irmão de Mario?</h3>
            </div>
            <div class="card-content card-back">
                <p>O nome do irmão de Mario é Luigi!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Qual é a principal inimiga de Mario?</h3>
            </div>
            <div class="card-content card-back">
                <p>A principal inimiga de Mario é a Princesa Peach, que é sequestrada por Bowser!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Qual é o nome do vilão principal de Super Mario?</h3>
            </div>
            <div class="card-content card-back">
                <p>O principal vilão é Bowser, o rei dos Koopas!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Onde Mario geralmente mora?</h3>
            </div>
            <div class="card-content card-back">
                <p>Mario mora no Reino dos Cogumelos, um mundo cheio de aventura!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Quem é Yoshi?</h3>
            </div>
            <div class="card-content card-back">
                <p>Yoshi é um dinossauro e amigo leal de Mario!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Qual é o nome do sapo amigo de Mario?</h3>
            </div>
            <div class="card-content card-back">
                <p>O sapo amigo de Mario se chama Toad!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Qual o nome do jogo onde Mario vai ao espaço?</h3>
            </div>
            <div class="card-content card-back">
                <p>O jogo é "Super Mario Galaxy", onde Mario viaja pelo espaço!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Qual é o nome da princesa que Mario sempre tenta resgatar?</h3>
            </div>
            <div class="card-content card-back">
                <p>A princesa que Mario resgata é a Princesa Peach!</p>
            </div>
        </div>

   

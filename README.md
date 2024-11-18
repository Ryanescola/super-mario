# super-mario
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Super Mario Flex Card</title>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            height: 100vh;
            margin: 0;
            background: linear-gradient(135deg, #ffcc00, #ff6699);
            font-family: 'Roboto', sans-serif;
            overflow: hidden;
        }

        .card-container {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .card {
            width: 300px;
            height: 400px;
            background: linear-gradient(135deg, #ff9e00, #ff6347);
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 20px;
            font-family: 'Press Start 2P', cursive;
            border-radius: 15px;
            cursor: pointer;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
            transform-style: preserve-3d;
            transition: transform 0.6s ease, box-shadow 0.3s ease;
            will-change: transform;
        }

        .card-content {
            display: flex;
            justify-content: center;
            align-items: center;
            position: absolute;
            backface-visibility: hidden;
            padding: 20px;
            text-align: center;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.6);
        }

        .card-front {
            background: rgba(0, 0, 0, 0.4);
            border-radius: 15px;
        }

        .card-back {
            background: rgba(255, 99, 71, 0.9);
            transform: rotateY(180deg);
            border-radius: 15px;
        }

        .card:hover {
            transform: rotateY(180deg);
            box-shadow: 0 12px 20px rgba(0, 0, 0, 0.3);
        }

        h3 {
            margin: 0;
            font-size: 22px;
        }

        p {
            font-size: 18px;
            margin-top: 10px;
            font-weight: 500;
        }

        .title {
            font-size: 28px;
            font-weight: 700;
            color: #fff;
            text-align: center;
            margin-bottom: 30px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
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

        <div class="card">
            <div class="card-content card-front">
                <h3>Qual é o poder de Mario ao comer uma flor de fogo?</h3>
            </div>
            <div class="card-content card-back">
                <p>Quando Mario come uma flor de fogo, ele pode atirar bolas de fogo!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Como Mario consegue se transformar em uma estrela?</h3>
            </div>
            <div class="card-content card-back">
                <p>Mario se transforma em uma estrela quando pega uma Super Estrela!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Quem é o irmão de Luigi?</h3>
            </div>
            <div class="card-content card-back">
                <p>Luigi tem um irmão chamado Mario!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Qual é o nome do carro que Mario usa em "Mario Kart"?</h3>
            </div>
            <div class="card-content card-back">
                <p>Mario usa o "Macho Mario" no jogo "Mario Kart"!</p>
            </div>
        </div>

        <div class="card">
            <div class="card-content card-front">
                <h3>Qual é o nome do mundo onde Mario vive?</h3>
            </div>
            <div class="card-content card-back">
                <p>Mario vive no "Reino dos Cogumelos"!</p>
            </div>
        </div>
    </div>

    <script>
        // Efeito de rotação 3D e transições já estão controlados pelo CSS
    </script>
</body>
</html>

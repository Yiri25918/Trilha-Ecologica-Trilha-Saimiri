<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trilha Ecológica Saimiri</title>
    <style>
        * {
            box-sizing: border-box;
        }
        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #245613;
            margin: 0;
            padding: 25px;
        }
        header {
            max-width: 1200px;
            margin: 0 auto 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
            color: white;
        }
        header h2 {
            margin: 0;
        }
        nav {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            display: flex;
            align-items: center;
            max-width: 1200px;
            margin: auto;
            display: flex;
            background: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        .esquerda{
            margin: auto;
            align-items: center;
             height:auto;
            object-fit: cover;
        } 
        img {
            padding: 10px;
            background-color: white;
            border-radius: 30px;
        }       
        .direita {
            width: 50%;
            margin: auto;
            align-items: center;
            text-align: justify;
        }
        .esquerda img {
            width: 100%;
        }
        .direita {
            padding: 45px;
        }
        .direita h1 {
            color: #2e7d32;
            font-size: 36px;
        }
        .direita p {
            color: #444;
            font-size: 17px;
            line-height: 1.8;
        }
        .botao {
            display: inline-block;
            background: #2e7d32;
            color: white;
            padding: 13px 24px;
            margin-top: 15px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
        }
        .botao:hover {
            background: #1b5e20;
        }
        footer {
            color: white;
            text-align: center;
            margin-top: 25px;
            font-size: 14px;
        }
        @media (max-width: 700px) {
            body {
                padding: 15px;
            }
        header {
            flex-direction: column;
            align-items: flex-start;
        }
        .container {
            flex-direction: column;
        }
        .esquerda,
        .direita {
        width: 100%;
        }
                .direita {
            padding: 25px;
        }
        .direita h1 {
            font-size: 29px;
        }
    }
    </style>
</head>
<body>
    <header>
        <h2>🌿🐒Trilha Ecológica Saimiri</h2>
        <nav>
            <a href="index.html">Início</a>
            <a href= "sobre.html" >Sobre o projeto</a>
            <a href="p.html">Questionário</a>
        </nav>
    </header>
    <main class="container" id="inicio">    
        <div class="esquerda">
            <img src="https://uploads.onecompiler.io/456uqbvvt/457eypbbw/Macaco%20de%20cheiro.png"
                alt="Floresta verde com árvores e vegetação natural">
        </div>
        <div class="direita">
            <h1>Seja bem-vindo!</h1>
            <p>
            Seja bem-vindo ao projeto da Trilha Ecológica Saimiri!
            Convidamos você a conhecer esse espaço natural,
            descobrir sua biodiversidade e compreender a importância
            de preservar a natureza e o ambiente ao nosso redor.
            </p>
            <p>
            Essas áreas verdes são de grande importância para a 
            redução dos efeitos atuais e futuros causados pela 
            urbanização de Manaus. Teremos a oportunidade de 
            experimentar um passeio onde veremos a importância 
            desses ecossistemas, e também constatar os impactos 
            causados pelas alterações locais. Desse modo, poderemos 
            compreender que esses ecossistemas naturais são 
            essenciais à manutenção dos recursos hídricos superficiais 
            e subterrâneos, como também ao controle de estresse térmico 
            da região.
            </p>
            <p>
            Explore nosso site e descubra como a educação ambiental
            pode contribuir para a conservação da floresta amazônica.
            </p>
            <a class="botao" href="sobre.html">
                Conheça o projeto
            </a>
        </div>
    </main>
    <footer>
        <p>Projeto de divulgação para Trilha Ecológica Saimiri — IFAM/CMDI</p>
    </footer>
</body>
</html>

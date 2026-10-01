<!DOCTYPE html>
<html lang="pt-BR">

<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <title>uma coisinha pra você ♡</title>

    <style>

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            min-height: 100vh;

            display: flex;
            justify-content: center;
            align-items: center;

            background:
                radial-gradient(circle at top,
                #fff8fb,
                #ffeaf2);

            color: #704457;

            font-family: Georgia, serif;

            text-align: center;
        }

        .pagina {
            width: 90%;
            max-width: 600px;

            padding: 35px 25px;

            animation: aparecer 1s ease;
        }

        .decoracao {
            font-size: 28px;
            letter-spacing: 5px;
        }

        h1 {
            font-size: 36px;
            font-weight: normal;

            margin-bottom: 15px;
        }

        h2 {
            font-size: 27px;
            font-weight: normal;
        }

        p {
            font-size: 18px;
            line-height: 1.7;
        }

        .subtitulo {
            font-size: 17px;
        }

        button {
            margin-top: 20px;

            border: none;
            border-radius: 30px;

            padding: 14px 28px;

            background: #e7a5bb;
            color: white;

            font-size: 16px;

            font-family: Georgia, serif;

            cursor: pointer;

            transition: 0.2s;
        }

        button:hover {
            transform: scale(1.06);
        }

        button:active {
            transform: scale(0.95);
        }

        .cartinha {
            background: rgba(255,255,255,0.7);

            border-radius: 20px;

            padding: 22px;

            margin-top: 25px;

            box-shadow:
                0 8px 25px rgba(160, 90, 120, 0.12);
        }

        .coracoes {
            font-size: 24px;
        }

        .foto {
            width: 100%;
            max-width: 300px;

            border-radius: 18px;

            margin: 10px;

            box-shadow:
                0 5px 18px rgba(120,70,90,0.2);
        }

        .minchan {
            font-size: 30px;
        }

        .final {
            font-size: 20px;
        }

        @keyframes aparecer {

            from {
                opacity: 0;
                transform: translateY(15px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }

        }

    </style>

</head>


<body>

    <main class="pagina" id="conteudo">

        <p class="decoracao">
            ♡ ⋆｡°✩
        </p>

        <h1>
            uma coisinha pra você...
        </h1>

        <p class="subtitulo">
            fiz isso pensando em você ♡
        </p>

        <button onclick="abrirSite()">
            abrir 💗
        </button>

    </main>


    <script>

        function abrirSite() {

            document.getElementById("conteudo").innerHTML = `

                <p class="decoracao">
                    ♡ ⋆｡°✩
                </p>

                <h1>
                    oi, Valen 💗
                </h1>

                <div class="cartinha">

                    <p>
                        eu fiz esse cantinho especialmente
                        pra você.
                    </p>

                    <p>
                        porque você é uma pessoa muito
                        especial pra mim. ♡
                    </p>

                    <p>
                        e eu queria deixar algumas
                        coisinhas aqui pra você.
                    </p>

                </div>

                <button onclick="mensagem()">
                    continuar 💌
                </button>

            `;
        }


        function mensagem() {

            document.getElementById("conteudo").innerHTML = `

                <p class="coracoes">
                    🌷 ♡ 🌷
                </p>

                <h1>
                    uma pequena mensagem
                </h1>

                <div class="cartinha">

                    <p>
                        Valentina,
                    </p>

                    <p>
                        às vezes é difícil colocar em
                        palavras o quanto alguém
                        significa pra gente.
                    </p>

                    <p>
                        mas eu queria tentar fazer isso
                        de um jeitinho diferente.
                    </p>

                    <p>
                        então fiz esse pequeno cantinho
                        pensando em você. 💗
                    </p>

                </div>

                <button onclick="fotos()">
                    algumas lembranças 📸
                </button>

            `;
        }


        function fotos() {

            document.getElementById("conteudo").innerHTML = `

                <p class="coracoes">
                    📸 ♡ 📸
                </p>

                <h1>
                    um cantinho de fotos
                </h1>

                <p>
                    aqui vão ficar algumas fotinhas
                    especiais pra gente. ♡
                </p>

                <div class="cartinha">

                    <p>
                        📷 foto 1
                    </p>

                    <p>
                        📷 foto 2
                    </p>

                    <p>
                        📷 foto 3
                    </p>

                </div>

                <button onclick="minchan()">
                    agora... Minchan 🐺🐰
                </button>

            `;
        }


        function minchan() {

            document.getElementById("conteudo").innerHTML = `

                <p class="minchan">
                    🐺 ♡ 🐰
                </p>

                <h1>
                    nosso pequeno momento Minchan
                </h1>

                <div class="cartinha">

                    <p>
                        porque, obviamente,
                        essa parte precisava existir. 😭
                    </p>

                    <p>
                        Minho pra você,
                        Chan pra mim.
                    </p>

                    <p>
                        equilíbrio perfeito, né? ♡
                    </p>

                </div>

                <button onclick="finalSite()">
                    última coisinha 💗
                </button>

            `;
        }


        function finalSite() {

            document.getElementById("conteudo").innerHTML = `

                <p class="coracoes">
                    ♡ ⋆｡°✩ ♡ ⋆｡°✩
                </p>

                <h1>
                    Valentina...
                </h1>

                <div class="cartinha">

                    <p class="final">
                        obrigada por ser você.
                    </p>

                    <p>
                        eu espero que você tenha gostado
                        desse pequeno cantinho que fiz
                        pensando em você.
                    </p>

                    <p>
                        você é muito especial pra mim. 💗
                    </p>

                    <p>
                        com carinho,
                        Lissa ♡
                    </p>

                </div>

                <p>
                    fim... ou talvez só o começo? ♡
                </p>

            `;

        }

    </script>

</body>

</html>

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog</title>
    <style>
        header {
            background-color: #2c3e50;
            color: #ffffff;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
            padding: 16px;
        }

        main {
            background-color: #f9f9f9;
            color: #333333;
            max-width: 800px;
            margin: 0 auto;
            padding: 16px;
        }

        article {
            display: flex;<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog</title>
    <style>
        header {
            background-color: #2c3e50;
            color: #ffffff;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
            padding: 16px;
        }

        main {
            background-color: #f9f9f9;
            color: #333333;
            max-width: 800px;
            margin: 0 auto;
            padding: 16px;
        }

        article {
            display: flex;
            gap: 16px;
            margin-bottom: 20px;
            align-items: center;
        }

        img {
            width: 80px;
            height: 80px;
            object-fit: cover;
        }

        .artigo-autor {
            font-weight: bold;
        }
    </style>
</head>

<body>
    <header>
        <h1>Nome do Blog</h1>
        <p>Vou compartilhar sobre… </p>
    </header>
    <main>
        <article>
            <img src="imagem-blog.png" alt="Descrição curta da imagem no máximo 2 linhas.">
            <div>
                <h2>Título do 1º post</h2>
                <p class="artigo-autor">Por: Meu Nome</p>
                <p>Boas-vindas ao meu novo blog! Aqui vou compartilhar sobre...</p>
                <button>❤️ <span>0</span></button>
                <button>👍 <span>0</span></button>
            </div>
        </article>
        <article>
            <img src="imagem-blog.png" alt="Descrição curta da imagem no máximo 2 linhas.">
            <div>
                <h2>Título do 2º post</h2>
                <p class="artigo-autor">Por: Meu Nome</p>
                <p>Escrita do 2º post.</p>
                <button>❤️ <span>0</span></button>
                <button>👍 <span>0</span></button>
            </div>
        </article>
    </main>

    <script>
        const botoes = document.querySelectorAll("button");

        botoes.forEach(function (botao) {
            let curtiu = false;
            botao.addEventListener("click", botaoClicado);

            function botaoClicado() {
                console.log("fui clicado");
                let texto = botao.querySelector("span");
                if (curtiu === false) {
                    texto.textContent++;
                    curtiu = true;
                } else {
                    texto.textContent--;
                    curtiu = false;
                }
            }
        });
    </script>
</body>

</html>
            gap: 16px;
            margin-bottom: 20px;
            align-items: center;
        }

        img {
            width: 80px;
            height: 80px;
            object-fit: cover;
        }

        .artigo-autor {
            font-weight: bold;
        }
    </style>
</head>

<body>
    <header>
        <h1>Nome do Blog</h1>
        <p>Vou compartilhar sobre… </p>
    </header>
    <main>
        <article>
            <img src="imagem-blog.png" alt="Descrição curta da imagem no máximo 2 linhas.">
            <div>
                <h2>Título do 1º post</h2>
                <p class="artigo-autor">Por: Meu Nome</p>
                <p>Boas-vindas ao meu novo blog! Aqui vou compartilhar sobre...</p>
                <button>❤️ <span>0</span></button>
                <button>👍 <span>0</span></button>
            </div>
        </article>
        <article>
            <img src="imagem-blog.png" alt="Descrição curta da imagem no máximo 2 linhas.">
            <div>
                <h2>Título do 2º post</h2>
                <p class="artigo-autor">Por: Meu Nome</p>
                <p>Escrita do 2º post.</p>
                <button>❤️ <span>0</span></button>
                <button>👍 <span>0</span></button>
            </div>
        </article>
    </main>

    <script>
        const botoes = document.querySelectorAll("button");

        botoes.forEach(function (botao) {
            let curtiu = false;
            botao.addEventListener("click", botaoClicado);

            function botaoClicado() {
                console.log("fui clicado");
                let texto = botao.querySelector("span");
                if (curtiu === false) {
                    texto.textContent++;
                    curtiu = true;
                } else {
                    texto.textContent--;
                    curtiu = false;
                }
            }
        });
    </script>
</body>

</html>

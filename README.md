@import url("https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap");

:root{
    --cor-principal: #6e859f;
    --cor-secundaria: #284260;
    --cor-destaque: #c92bfc;
}

body {
    font-family: 'Chakra Petch', sans-serif;
}

h1, h2, h5 {
    color: var(--cor-secundaria);
    font-weight: 700;
}

footer a {
    color: var(--cor-principal);
}

footer a:hover {
    color: var(--cor-destaque);
}
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4Q6Gf2aSP4eDXB8Miphtr37CMZZQ5oXLH2yaXMJ2w8e2ZtHTl7GptT4jmndRuHDT" crossorigin="anonymous">
    <link rel="stylesheet" href="style.css">
    <title>Meu Portifólio</title>
</head>
<body>
    <header class="container text-center">
        <img src="imagens/ghost.png" alt="Avatar de Pedro" class="rounded-circle" width="150" height="150" srcset="">
        <p class="lead">I am Steve_</p>
        <h1>As pessoas são aquilo que elas querem parecer ser.</h1>
        <p>Cursando 3o ano do Ensino Médio na escola PEI Prefeito Antônio Baldusco</p>
        <p>Minhas habilidades</p>
        <div>
            <p class="badge bg-secondary">Oratória</p>
        </div>
    </header>

    <main class="container mt-5">
        <h2>Meus projetos</h2>
        <div class="row">
            <!-- Prijeto 1 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="imagens/projeto-1.png" class="card-img-top" alt="imagem do Projeto da Biblioteca Virtual">
                    <div class="card-body">
                        <h5 class="card-title">Minha Biblioteca: Uma Webpage Personalizada</h5>
                        <p class="card-text">Este projeto é uma página web que apresenta uma lista dos meus livros favoritos, incluindo informações sobre os autores, datas de publicação e links para compra na Amazon. A página é estilizada com CSS para uma visualização agradável e usa fontes externas do Google Fonts.</p>
                        <button type="button" class="btn btn-link">Vejo o Projeto</button>
                    </div>
                </div>
            </div>
            <!-- Projeto 2 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="imagens/projeto-1.png" class="card-img-top" alt="imagem do Projeto da Biblioteca Virtual">
                    <div class="card-body">
                        <h5 class="card-title">Minha Biblioteca: Uma Webpage Personalizada</h5>
                        <p class="card-text">Este projeto é uma página web que apresenta uma lista dos meus livros favoritos, incluindo informações sobre os autores, datas de publicação e links para compra na Amazon. A página é estilizada com CSS para uma visualização agradável e usa fontes externas do Google Fonts.</p>
                        <button type="button" class="btn btn-link">Vejo o Projeto</button>
                    </div>
                </div>
            </div>

            <!-- Projeto 3 -->
            <div class="col-md-4">
                <div class="card">
                    <img src="imagens/projeto-1.png" class="card-img-top" alt="imagem do Projeto da Biblioteca Virtual">
                    <div class="card-body">
                        <h5 class="card-title">Minha Biblioteca: Uma Webpage Personalizada</h5>
                        <p class="card-text">Este projeto é uma página web que apresenta uma lista dos meus livros favoritos, incluindo informações sobre os autores, datas de publicação e links para compra na Amazon. A página é estilizada com CSS para uma visualização agradável e usa fontes externas do Google Fonts.</p>
                        <button type="button" class="btn btn-link">Vejo o Projeto</button>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <footer class="container py-5">
        <h2>Entre em contato</h2>
        <div>
            <a href="https://github.com/settings/profile">GitHub</a>
        </div>
        <p class="my-5 text center">© Copyright 2025. Produzido por Pedro Henrique Batista de Jesus</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/js/bootstrap.bundle.min.js" integrity="sha384-j1CDi7MgGQ12Z7Qab0qlWQ/Qqz24Gc6BM0thvEMVjHnfYGF0rmFCozFSxQBxwHKO" crossorigin="anonymous"></script>
</body>
</html>

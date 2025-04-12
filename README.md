<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Liga Acadêmica de Direito</title>
    <style>
        body {
            margin: 0;
            font-family: 'Georgia', serif;
            background-color: #0f0f0f;
            color: #ffffff;
        }
        header {
            background-color: #1a1a1a;
            padding: 20px;
            text-align: center;
        }
        header img {
            max-height: 150px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #2a2a2a;
            padding: 10px;
            flex-wrap: wrap;
        }
        nav a {
            color: #ffd700;
            text-decoration: none;
            margin: 10px 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 40px;
        }
        section {
            margin-bottom: 50px;
            background-color: #1a1a1a;
            padding: 20px;
            border-radius: 10px;
        }
        h1, h2 {
            color: #ffd700;
        }
        footer {
            background-color: #1a1a1a;
            text-align: center;
            padding: 20px;
            color: #aaa;
        }
        textarea, input[type="text"] {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            border: none;
            margin-top: 10px;
            margin-bottom: 10px;
            background-color: #333;
            color: #fff;
        }
        .form-section {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            background-color: #ffd700;
            border: none;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo_liga.png" alt="Logo da Liga Acadêmica de Direito">
        <h1>Liga Acadêmica de Direito</h1>
        <p>Unindo conhecimento, pesquisa e prática no universo jurídico</p>
    </header>

    <nav>
        <a href="#sobre">O que é</a>
        <a href="#enquete">Enquete</a>
        <a href="#ideias">Ideias Acadêmicas</a>
        <a href="#projetos">Projetos de Extensão</a>
        <a href="#aprimoramento">Aprimoramento Estudantil</a>
        <a href="#estudos">Avanços de Estudos</a>
        <a href="#civil">Direito Civil</a>
        <a href="#penal">Direito Penal</a>
        <a href="#constitucional">Direito Constitucional</a>
    </nav>

    <main>
        <section id="sobre">
            <h2>O que é a Liga Acadêmica de Direito?</h2>
            <p>A Liga Acadêmica de Direito é uma organização estudantil voltada ao desenvolvimento acadêmico, científico e profissional dos alunos de Direito. Nossa missão é promover debates, pesquisas, extensão universitária e ações sociais que contribuam para o aprimoramento do saber jurídico e o impacto positivo na comunidade.</p>
        </section>

        <section id="enquete">
            <h2>Enquete Inicial</h2>
            <p><strong>De qual área do Direito você mais se inspira?</strong></p>
            <form>
                <input type="text" placeholder="Digite aqui sua resposta...">
                <button type="submit">Enviar</button>
            </form>
        </section>

        <section id="ideias">
            <h2>Ideias Acadêmicas</h2>
            <p>Espaço para publicação de ideias, artigos e iniciativas acadêmicas.</p>
            <div class="form-section">
                <textarea placeholder="Compartilhe sua ideia..."></textarea>
                <button>Enviar Ideia</button>
            </div>
        </section>

        <section id="projetos">
            <h2>Projetos de Extensão</h2>
            <p>Conheça e proponha projetos de impacto social e jurídico.</p>
            <div class="form-section">
                <textarea placeholder="Descreva seu projeto de extensão..."></textarea>
                <button>Cadastrar Projeto</button>
            </div>
        </section>

        <section id="aprimoramento">
            <h2>Aprimoramento Estudantil</h2>
            <p>Compartilhe ações de capacitação, eventos ou cursos relevantes.</p>
            <div class="form-section">
                <textarea placeholder="Sugira ações de aprimoramento estudantil..."></textarea>
                <button>Publicar Sugestão</button>
            </div>
        </section>

        <section id="estudos">
            <h2>Avanços de Estudos</h2>
            <p>Atualizações sobre pesquisas, teses e grupos de estudos.</p>
            <div class="form-section">
                <textarea placeholder="Compartilhe os avanços dos estudos jurídicos..."></textarea>
                <button>Registrar Avanço</button>
            </div>
        </section>

        <section id="civil">
            <h2>Direito Civil</h2>
            <p>Espaço para reflexões sobre contratos, família, sucessões e obrigações.</p>
            <div class="form-section">
                <textarea placeholder="Compartilhe conteúdos de Direito Civil..."></textarea>
                <button>Contribuir</button>
            </div>
        </section>

        <section id="penal">
            <h2>Direito Penal</h2>
            <p>Debates, artigos e jurisprudência criminal em destaque.</p>
            <div class="form-section">
                <textarea placeholder="Compartilhe análises ou estudos do Direito Penal..."></textarea>
                <button>Enviar Conteúdo</button>
            </div>
        </section>

        <section id="constitucional">
            <h2>Direito Constitucional</h2>
            <p>Discussões sobre a Constituição, direitos fundamentais e democracia.</p>
            <div class="form-section">
                <textarea placeholder="Compartilhe conteúdos sobre Direito Constitucional..."></textarea>
                <button>Postar Ideia</button>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Liga Acadêmica de Direito. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

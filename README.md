# grace-hopper

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grace Hopper - Pioneira da Computação</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            overflow: hidden;
        }
        
        header {
            background: #2c3e50;
            color: white;
            padding: 30px 20px;
            text-align: center;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .hero-image {
            width: 100%;
            height: 300px;
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="400" height="300" viewBox="0 0 400 300"><rect width="400" height="300" fill="%232c3e50"/><text x="200" y="150" font-family="Arial" font-size="24" fill="white" text-anchor="middle">Imagem de Grace Hopper</text></svg>');
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5rem;
            text-align: center;
            padding: 20px;
        }
        
        .content {
            padding: 30px;
        }
        
        .section {
            margin-bottom: 40px;
        }
        
        h2 {
            color: #2c3e50;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
            margin-bottom: 20px;
            font-size: 1.8rem;
        }
        
        h3 {
            color: #2980b9;
            margin: 15px 0 10px;
        }
        
        p {
            margin-bottom: 15px;
            text-align: justify;
        }
        
        .timeline {
            position: relative;
            padding-left: 30px;
        }
        
        .timeline:before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            bottom: 0;
            width: 4px;
            background: #3498db;
        }
        
        .timeline-item {
            position: relative;
            margin-bottom: 20px;
        }
        
        .timeline-item:before {
            content: '';
            position: absolute;
            left: -36px;
            top: 5px;
            width: 16px;
            height: 16px;
            border-radius: 50%;
            background: #2980b9;
            border: 3px solid white;
            box-shadow: 0 0 0 3px #2980b9;
        }
        
        .quote {
            background: #f8f9fa;
            border-left: 4px solid #3498db;
            padding: 20px;
            margin: 20px 0;
            font-style: italic;
        }
        
        .quote p {
            margin-bottom: 10px;
        }
        
        .quote-author {
            text-align: right;
            font-weight: bold;
            color: #7f8c8d;
        }
        
        .contributions {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .contribution-card {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .contribution-card:hover {
            transform: translateY(-5px);
        }
        
        .contribution-card h3 {
            color: #2c3e50;
            margin-top: 0;
        }
        
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .contributions {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Grace Murray Hopper</h1>
            <p class="subtitle">Pioneira da Ciência da Computação e Almirante da Marinha dos EUA</p>
        </header>
        
        <div class="hero-image">
            "Era mais fácil pedir desculpas do que permissão." - Grace Hopper
        </div>
        
        <div class="content">
            <section class="section">
                <h2>Quem foi Grace Hopper?</h2>
                <p>Grace Brewster Murray Hopper (1906-1992) foi uma cientista da computação e contra-almirante da Marinha dos Estados Unidos. Ela foi uma das primeiras programadoras do computador Harvard Mark I e criadora da primeira linguagem de programação de alto nível, o COBOL.</p>
                
                <div class="quote">
                    <p>"Um navio no porto é seguro, mas não é para isso que os navios são feitos. Navegue para o mar e faça coisas novas."</p>
                    <p class="quote-author">- Grace Hopper</p>
                </div>
            </section>
            
            <section class="section">
                <h2>Linha do Tempo</h2>
                <div class="timeline">
                    <div class="timeline-item">
                        <h3>1906</h3>
                        <p>Nascimento em Nova Iorque, Estados Unidos.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>1928</h3>
                        <p>Graduou-se em Matemática e Física no Vassar College.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>1934</h3>
                        <p>Obteve seu doutorado em Matemática pela Universidade de Yale.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>1943</h3>
                        <p>Ingressou na Marinha dos Estados Unidos durante a Segunda Guerra Mundial.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>1944</h3>
                        <p>Tornou-se uma das primeiras programadoras do Harvard Mark I.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>1952</h3>
                        <p>Desenvolveu o primeiro compilador, o A-0 System.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>1959</h3>
                        <p>Participou da criação da linguagem COBOL (Common Business-Oriented Language).</p>
                    </div>
                    <div class="timeline-item">
                        <h3>1967-1977</h3>
                        <p>Diretora do Grupo de Programação de Linguagens da Marinha.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>1985</h3>
                        <p>Tornou-se Contra-Almirante.</p>
                    </div>
                    <div class="timeline-item">
                        <h3>1992</h3>
                        <p>Faleceu em Arlington, Virgínia, aos 85 anos.</p>
                    </div>
                </div>
            </section>
            
            <section class="section">
                <h2>Contribuições para a Computação</h2>
                <div class="contributions">
                    <div class="contribution-card">
                        <h3>Primeiro Compilador</h3>
                        <p>Desenvolveu o primeiro compilador em 1952, que traduzia instruções em linguagem humana para código de máquina.</p>
                    </div>
                    <div class="contribution-card">
                        <h3>Linguagem COBOL</h3>
                        <p>Criou a primeira linguagem de programação de alto nível voltada para negócios, ainda em uso hoje.</p>
                    </div>
                    <div class="contribution-card">
                        <h3>Termo "Debugging"</h3>
                        <p>Popularizou o termo após remover uma mariposa (bug) presa no Harvard Mark II.</p>
                    </div>
                    <div class="contribution-card">
                        <h3>Programação Automática</h3>
                        <p>Pioneira na ideia de linguagens de programação independentes de máquina.</p>
                    </div>
                </div>
            </section>
            
            <section class="section">
                <h2>Legado e Reconhecimentos</h2>
                <p>Grace Hopper recebeu inúmeras honrarias ao longo de sua vida, incluindo:</p>
                <ul>
                    <li>Medalha de Serviço Distinto da Defesa (1986)</li>
                    <li>National Medal of Technology (1991)</li>
                    <li>Prêmio Mulher do Ano da Associação de Mulheres em Computação (1987)</li>
                    <li>Mais de 40 doutorados honorários</li>
                </ul>
                
                <p>Hoje, a conferência Grace Hopper Celebration é o maior encontro mundial de mulheres em tecnologia, inspirando novas gerações a seguirem seus passos.</p>
                
                <div class="quote">
                    <p>"A frase mais perigosa na linguagem é: 'Sempre fizemos assim'."</p>
                    <p class="quote-author">- Grace Hopper</p>
                </div>
            </section>
        </div>
        
        <footer>
            <p>© 2023 - Apresentação sobre Grace Hopper - Pioneira da Computação</p>
        </footer>
    </div>
</body>
</html>

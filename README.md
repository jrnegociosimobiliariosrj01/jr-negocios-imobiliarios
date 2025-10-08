<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jr Negócios Imobiliários RJ
    Compre seu apê na planta hoje mesmo</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* --- ESTILOS GERAIS --- */
        :root {
            --cor-principal: #0056b3; /* Azul escuro */
            --cor-secundaria: #0056b3; /* Azul mais escuro */
            --cor-fundo: #f4f4f9; /* Cinza Suave */
            --cor-texto: #333333;
            --cor-card-fundo: #fff;
            --sombra-card: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: var(--cor-fundo);
            color: var(--cor-texto);
            line-height: 1.6;
        }

        /* --- CABEÇALHO (HEADER) --- */
        header {
            background-color: var(--cor-principal);
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2em;
            margin-bottom: 5px;
        }

        .contato-rapido a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            margin: 0 10px;
            display: inline-block;
            transition: opacity 0.3s;
        }

        .contato-rapido a:hover {
            opacity: 0.8;
        }

        .contato-rapido i {
            margin-right: 5px;
        }
        
        /* --- SEÇÃO DE IMÓVEIS --- */
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 15px;
        }

        h2 {
            text-align: center;
            color: var(--cor-secundaria);
            margin-bottom: 30px;
            font-size: 2em;
        }

        .imoveis-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .card-imovel {
            background-color: var(--cor-card-fundo);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: var(--sombra-card);
            transition: transform 0.3s, box-shadow 0.3s;
            text-align: center;
        }

        .card-imovel:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .card-imovel img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            display: block;
        }

        .card-conteudo {
            padding: 15px;
        }

        .card-conteudo h3 {
            font-size: 1.3em;
            color: var(--cor-secundaria);
            margin-bottom: 5px;
        }

        .card-conteudo p {
            margin-bottom: 10px;
            color: #555;
        }

        .preco {
            font-size: 1.5em;
            color: #28a745; /* Cor verde para destaque de preço */
            font-weight: bold;
            margin-bottom: 15px;
            display: block;
        }

        .btn-contato {
            display: inline-block;
            background-color: #25D366; /* Cor do WhatsApp */
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .btn-contato i {
            margin-right: 5px;
        }

        .btn-contato:hover {
            background-color: #1EBE62;
        }
        
        /* --- RODAPÉ (FOOTER) --- */
        footer {
            background-color: var(--cor-secundaria);
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }

        footer p {
            margin: 0;
            font-size: 0.9em;
        }

        /* --- MEDIA QUERIES (Responsividade) --- */
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.5em;
            }
            .contato-rapido {
                display: flex;
                justify-content: center;
                flex-wrap: wrap;
            }
            .contato-rapido a {
                margin: 5px;
            }
            h2 {
                font-size: 1.5em;
            }
        }

    </style>
</head>
<body>

    <header>
        <h1>JR Negócios Imobiliários RJ</h1>
        <div class="contato-rapido">
            <a href="https://wa.me/5521993416454" target="_blank">
                <i class="fab fa-whatsapp"></i> WhatsApp
            </a>
            <a href="https://instagram.com/jrnegociosimobiliariosrj01" target="_blank">
                <i class="fab fa-instagram"></i> Instagram
            </a>
        </div>
    </header>

    <div class="container">
        <h2>Imóveis em Destaque</h2>
        <div class="imoveis-grid">
            
            <div class="card-imovel">
                <img src="https://https://www.instagram.com/p/DOtcXOnkxOw/?img_index=1>
                <div class="card-conteudo">
                    <h3>Apartamento na Planta</h3>
                    <p>1, 2 e 3 Quartos, com opcões de Suíte, e Vaga.</p>
                    <span class="preco"> A partir de R$360.000</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse em comprar Apartamento na Planta (CÓDIGO 01)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://https://www.instagram.com/p/DOI9Lu9kXol/>
                <div class="card-conteudo">
                    <h3>Apartamento a venda em Niterói</h3>
                    <p>1 e 2 Quartos com opção de suíte e vaga, Área de Lazer Completa, Segurança 24h.</p>
                    <span class="preco">A partir de R$275.000 </span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel na Planta em Niterói (CÓDIGO 02)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://https://www.instagram.com/p/DNJBOWCAr-0/?img_index=1>
                <div class="card-conteudo">
                    <h3>Apartamento de 1 ou 2 quartos</h3>
                    <p>Ideal para investimento ou primeira moradia, localizado em São Cristoão RJ.</p>
                    <span class="preco">A apartir de R$ 288.000</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no apartamento na planta em São Cristovão RJ
                    </a>
                </div>
            </div>
            
            <div class="card-imovel">
                <img src="https://https://www.instagram.com/p/DOJBcholB_E/?img_index=1>
                <div class="card-conteudo">
                    <h3>Seu primeiro apê</h3>
                    <p>Apartmento de 2 ou 3 quartos em Irajá RJ.</p>
                    <span class="preco"> A partir R$253.000</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no apartamento em Irajá RJ (CÓDIGO 04)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

           <footer>
        <p>&copy; 2024 JR Negócios Imobiliários RJ. Todos os direitos reservados.</p>
        <p>Rio de Janeiro - RJ</p>
    </footer>
    
</body>
</html>

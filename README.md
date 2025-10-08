<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jr Negócios Imobiliários RJ</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* --- ESTILOS GERAIS --- */
        :root {
            --cor-principal: #007bff; /* Azul vibrante */
            --cor-secundaria: #0056b3; /* Azul mais escuro */
            --cor-fundo: #f4f4f9; /* Fundo suave */
            --cor-texto: #333;
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
                <img src="https://via.placeholder.com/400x200?text=Sua+Foto+Aqui" alt="Foto do Imóvel 1">
                <div class="card-conteudo">
                    <h3>Apartamento Moderno na Tijuca</h3>
                    <p>2 Quartos, Suíte, Varanda Gourmet e Vaga. Excelente localização.</p>
                    <span class="preco">R$ 450.000</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel Apartamento Moderno na Tijuca (CÓDIGO 01)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Sua+Foto+Aqui" alt="Foto do Imóvel 2">
                <div class="card-conteudo">
                    <h3>Casa com Piscina em Niterói</h3>
                    <p>3 Suítes, Área de Lazer Completa, Segurança 24h. Pronto para morar.</p>
                    <span class="preco">R$ 890.000</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel Casa com Piscina em Niterói (CÓDIGO 02)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Sua+Foto+Aqui" alt="Foto do Imóvel 3">
                <div class="card-conteudo">
                    <h3>Loft Compacto no Centro</h3>
                    <p>Ideal para investimento ou primeira moradia. Perto de metrô e comércio.</p>
                    <span class="preco">R$ 220.000</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel Loft Compacto no Centro (CÓDIGO 03)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>
            
            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+4" alt="Imóvel 4">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 4 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 04)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+5" alt="Imóvel 5">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 5 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 05)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+6" alt="Imóvel 6">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 6 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 06)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+7" alt="Imóvel 7">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 7 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 07)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+8" alt="Imóvel 8">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 8 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 08)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+9" alt="Imóvel 9">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 9 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 09)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+10" alt="Imóvel 10">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 10 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 10)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+11" alt="Imóvel 11">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 11 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 11)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+12" alt="Imóvel 12">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 12 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 12)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+13" alt="Imóvel 13">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 13 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 13)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+14" alt="Imóvel 14">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 14 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 14)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+15" alt="Imóvel 15">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 15 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 15)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+16" alt="Imóvel 16">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 16 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 16)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+17" alt="Imóvel 17">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 17 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 17)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+18" alt="Imóvel 18">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 18 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 18)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+19" alt="Imóvel 19">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 19 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 19)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>

            <div class="card-imovel">
                <img src="https://via.placeholder.com/400x200?text=Em+Breve+Imóvel+20" alt="Imóvel 20">
                <div class="card-conteudo">
                    <h3>Seu Imóvel 20 Aqui</h3>
                    <p>Descrição curta do seu novo imóvel.</p>
                    <span class="preco">R$ 0,00</span>
                    <a href="https://wa.me/5521993416454?text=Olá! Tenho interesse no imóvel (CÓDIGO 20)." class="btn-contato" target="_blank">
                        <i class="fab fa-whatsapp"></i> Fale Conosco
                    </a>
                </div>
            </div>
            
        </div>
    </div>

    <footer>
        <p>&copy; 2024 JR Negócios Imobiliários RJ. Todos os direitos reservados.</p>
        <p>Rio de Janeiro - RJ</p>
    </footer>
    
</body>
</html>

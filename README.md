
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Cantina Escolar Online - Lista Completa</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; background: linear-gradient(to bottom, #e8f5e8, #f4f4f4); color: #333; line-height: 1.6; }
        header { background: linear-gradient(90deg, #4CAF50, #66BB6A); color: white; text-align: center; padding: 22px 20px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
        nav { background-color: #333; color: white; padding: 12px; text-align: center; position: sticky; top: 0; z-index: 100; display: flex; justify-content: center; flex-wrap: wrap; gap:10px; }
        nav a { color: white; margin: 0 8px; text-decoration: none; font-weight: bold; transition: color 0.3s; padding: 6px 10px; border-radius: 6px; }
        nav a:hover { color: #4CAF50; background-color: rgba(255,255,255,0.06); }
        section { padding: 30px; max-width: 1100px; margin: 20px auto; background: white; border-radius: 12px; box-shadow: 0 2px 10px rgba(0,0,0,0.06); }
        h2 { margin-top: 0; }
        .menu-category { margin-bottom: 30px; }
        .menu-item { display: flex; justify-content: space-between; align-items: center; margin: 12px 0; padding: 12px; border-bottom: 1px solid #eee; border-radius: 8px; transition: background-color 0.2s; }
        .menu-item:hover { background-color: #fafafa; }
        .menu-item .left { display:flex; align-items:center; gap:12px; }
        .menu-item img { width: 60px; height: 60px; border-radius: 8px; object-fit: cover; }
        .menu-item .info { line-height:1.2; }
        .menu-item .price { font-weight: 700; margin-left: 12px; min-width:80px; text-align:right; }
        button { background: linear-gradient(90deg, #4CAF50, #66BB6A); color: white; border: none; padding: 10px 14px; cursor: pointer; border-radius: 6px; transition: transform 0.15s, box-shadow 0.15s; font-size: 14px; }
        button:hover { transform: translateY(-2px); box-shadow: 0 6px 12px rgba(0,0,0,0.12); }
        #cart { margin-top: 20px; background: #f9f9f9; padding: 16px; border-radius: 8px; }
        #cart-list { list-style: none; padding: 0; margin: 0 0 10px 0; }
        #cart-list li { padding: 6px 0; display: flex; justify-content: space-between; gap:10px; }
        .small-btn { padding:6px 8px; font-size:13px; border-radius:6px; }
        .remove { background: #f44336; }
        .promo { background: #FFF3CD; padding: 12px; border-radius: 8px; margin-bottom: 16px; border-left: 5px solid #FFC107; }
        .testimonial { background: #e8f5e8; padding: 12px; margin: 10px 0; border-radius: 8px; border-left: 5px solid #4CAF50; }
        footer { text-align: center; padding: 16px; background: #333; color: white; margin-top: 30px; }
        .category-buttons { display:flex; justify-content:center; gap:12px; flex-wrap:wrap; margin-top:16px; }
        @media (max-width:768px){
            .menu-item { flex-direction: column; align-items:flex-start; gap:8px; }
            .menu-item .price { text-align:left; }
            nav { flex-direction: column; gap:8px; padding:10px; }
        }
    </style>
</head>
<body>
    <div id="notification" style="position:fixed; top:20px; right:20px; background:#4CAF50; color:white; padding:12px 16px; border-radius:8px; box-shadow:0 4px 8px rgba(0,0,0,0.16); display:none; z-index:1000;"></div>

   <header>
        <img src="logoif.webp" alt="Logo IFES Santa Teresa">
        <h1>Cantina Escolar Online — Lista Completa (2025)</h1>
        <p style="margin:6px 0 0;">Todos os itens da lista da cantina, organizados por categoria. Adicione ao carrinho e finalize o pedido.</p>
    </header>
    <nav>
        <a href="#menu">Menu</a>
        <a href="#bebidas">Bebidas</a>
        <a href="#doces">Doces</a>
        <a href="#sobremesas">Sobremesas</a>
        <a href="#salgados">Biscoitos & Salgados</a>
        <a href="#embalagem">Embalagem</a>
        <a href="#pedidos">Meus Pedidos</a>
    </nav>

<div class="cantina-wrapper" style="display:flex; gap:40px; align-items:flex-start; padding:50px; flex-wrap:nowrap;">
  <img src="cantina.jpeg" 
       alt="Cantina IFES" 
       style="width:100%; max-width:450px; border-radius:16px; display:block;">
       
  <div class="cantina-text" style="flex:1; min-width:250px; font-size:28px; line-height:1.4; padding:50px; background:#f7f7f7; border-radius:12px;">
      <p>A cantina do Instituto Federal do Espírito Santo (Ifes) em Barracão é o coração pulsante do campus. Localizada estrategicamente, oferece um refúgio acolhedor para estudantes e servidores. Com um cardápio variado, desde lanches rápidos até refeições completas, a cantina atende a todos os gostos e necessidades.

O ambiente é sempre animado. O atendimento é cordial e eficiente, criando um espaço onde todos se sentem bem-vindos. Além da comida saborosa, a cantina é um ponto de encontro, um lugar para fazer amigos e fortalecer laços.

Seja para um café da manhã reforçado, um almoço revigorante ou um lanche.</p>
</div>

</div>

        <!-- BEBIDAS 1-26 -->
        <div class="menu-category" id="bebidas">
            <h3>🥤 Bebidas (itens 1 a 26)</h3>

            <!-- For each item: image placeholder, name, price, button -->
            <div class="menu-item">
                <div class="left">
                    <img src="agua.png" alt="Água c/ gas">
                    <div class="info"><strong>Água c/ Gás 500ml</strong><div style="font-size:13px;">UND</div></div>
                </div>
                <div class="price">R$ 3,25</div>
                <div><button onclick="addToCart('Água c/ Gás 500ml', 3.25)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="aguaS.png" alt="Água s/ gas">
                    <div class="info"><strong>Água s/ Gás 500ml</strong><div style="font-size:13px;">UND</div></div>
                </div>
                <div class="price">R$ 3,00</div>
                <div><button onclick="addToCart('Água s/ Gás 500ml', 3.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="chalata.webp" alt="Chá preto">
                    <div class="info"><strong>Chá preto c/ gás Limão Leão lata 290 ml</strong></div>
                </div>
                <div class="price">R$ 5,50</div>
                <div><button onclick="addToCart('Chá preto c/ gás Limão Leão lata 290 ml', 5.50)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="monster.png" alt="Monster">
                    <div class="info"><strong>Energético Monster 473 ml</strong></div>
                </div>
                <div class="price">R$ 13,25</div>
                <div><button onclick="addToCart('Energético Monster 473 ml', 13.25)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="guaravita1.webp" alt="Guaravita">
                    <div class="info"><strong>Guaravita copo 290 ml</strong></div>
                </div>
                <div class="price">R$ 4,00</div>
                <div><button onclick="addToCart('Guaravita copo 290 ml', 4.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="tonica.jpeg" alt="Água tônica">
                    <div class="info"><strong>Refri. Água Tônica 350 ml</strong></div>
                </div>
                <div class="price">R$ 6,00</div>
                <div><button onclick="addToCart('Refri. Água Tônica 350 ml', 6.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="coca.webp" alt="Coca Cola 350ml">
                    <div class="info"><strong>Refri. lata 350 ml Coca Cola</strong></div>
                </div>
                <div class="price">R$ 6,00</div>
                <div><button onclick="addToCart('Refri. lata 350 ml Coca Cola', 6.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="cocaZero.webp" alt="Coca Cola Zero">
                    <div class="info"><strong>Refri. lata 350 ml Coca Cola Zero</strong></div>
                </div>
                <div class="price">R$ 6,00</div>
                <div><button onclick="addToCart('Refri. lata 350 ml Coca Cola Zero', 6.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="sprite.jpeg" alt="Sprite">
                    <div class="info"><strong>Refri. lata 350 ml Sprite</strong></div>
                </div>
                <div class="price">R$ 6,00</div>
                <div><button onclick="addToCart('Refri. lata 350 ml Sprite', 6.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="fanta guarana.jpeg" alt="Fanta Guaraná">
                    <div class="info"><strong>Refri. lata 350 ml Fanta Guaraná</strong></div>
                </div>
                <div class="price">R$ 6,00</div>
                <div><button onclick="addToCart('Refri. lata 350 ml Fanta Guaraná', 6.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="uva.webp" alt="Fanta Uva">
                    <div class="info"><strong>Refri. lata 350 ml Fanta Uva</strong></div>
                </div>
                <div class="price">R$ 6,00</div>
                <div><button onclick="addToCart('Refri. lata 350 ml Fanta Uva', 6.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="laranja.webp" alt="Fanta Laranja">
                    <div class="info"><strong>Refri. lata 350 ml Fanta Laranja</strong></div>
                </div>
                <div class="price">R$ 6,00</div>
                <div><button onclick="addToCart('Refri. lata 350 ml Fanta Laranja', 6.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="juninho.webp" alt="Juninho">
                    <div class="info"><strong>Refri. Juninho Coroa</strong></div>
                </div>
                <div class="price">R$ 3,50</div>
                <div><button onclick="addToCart('Refri. Juninho Coroa', 3.50)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="coroa.webp" alt="Coroa 600ml">
                    <div class="info"><strong>Refri. 600 ml Coroa</strong></div>
                </div>
                <div class="price">R$ 7,00</div>
                <div><button onclick="addToCart('Refri. 600 ml Coroa', 7.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="coca600.webp" alt="Coca 600ml">
                    <div class="info"><strong>Refri. 600 ml Coca Cola</strong></div>
                </div>
                <div class="price">R$ 8,50</div>
                <div><button onclick="addToCart('Refri. 600 ml Coca Cola', 8.50)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="H2O.jpeg" alt="H2O 500ml">
                    <div class="info"><strong>H2O 500 ml</strong></div>
                </div>
                <div class="price">R$ 6,00</div>
                <div><button onclick="addToCart('H2O 500 ml', 6.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="ICE tea.jpeg" alt="Ice Tea">
                    <div class="info"><strong>Beb. Ice Tea Leão garrafinha</strong></div>
                </div>
                <div class="price">R$ 4,25</div>
                <div><button onclick="addToCart('Beb. Ice Tea Leão garrafinha', 4.25)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="isotonico.jpeg" alt="Isotônico">
                    <div class="info"><strong>Beb. Isotônico (powead) 500 ml</strong></div>
                </div>
                <div class="price">R$ 8,00</div>
                <div><button onclick="addToCart('Beb. Isotônico 500 ml', 8.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="Beb. Achocolatado caixa 200ml Ibituruna.webp" alt="Achocolatado">
                    <div class="info"><strong>Beb. Achocolatado caixa 200ml Ibituruna</strong></div>
                </div>
                <div class="price">R$ 3,00</div>
                <div><button onclick="addToCart('Beb. Achocolatado caixa 200ml Ibituruna', 3.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="Beb. Suco de Frutas caixinha 200 ml.webp" alt="Suco caixinha">
                    <div class="info"><strong>Beb. Suco de Frutas caixinha 200 ml</strong></div>
                </div>
                <div class="price">R$ 3,25</div>
                <div><button onclick="addToCart('Beb. Suco de Frutas caixinha 200 ml', 3.25)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="Beb. Vitamina Ibituruna de frutas caixa 200 ml.webp" alt="Vitamina">
                    <div class="info"><strong>Beb. Vitamina Ibituruna de frutas caixa 200 ml</strong></div>
                </div>
                <div class="price">R$ 3,00</div>
                <div><button onclick="addToCart('Beb. Vitamina Ibituruna 200 ml', 3.00)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="Café 150 ml.webp" alt="Café 150ml">
                    <div class="info"><strong>Café 150 ml</strong></div>
                </div>
                <div class="price">R$ 2,50</div>
                <div><button onclick="addToCart('Café 150 ml', 2.50)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="Suco de Polpa 200 ml.webp" alt="Suco de polpa">
                    <div class="info"><strong>Suco de Polpa 200 ml</strong></div>
                </div>
                <div class="price">R$ 4,25</div>
                <div><button onclick="addToCart('Suco de Polpa 200 ml', 4.25)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="com café 200ml.webp" alt="Leite com café 200ml">
                    <div class="info"><strong>Leite com Café 200 ml</strong></div>
                </div>
                <div class="price">R$ 4,75</div>
                <div><button onclick="addToCart('Leite com Café 200 ml', 4.75)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="leite.webp" alt="Leite 150ml">
                    <div class="info"><strong>Leite 150 ml</strong></div>
                </div>
                <div class="price">R$ 3,25</div>
                <div><button onclick="addToCart('Leite 150 ml', 3.25)">Adicionar</button></div>
            </div>

            <div class="menu-item">
                <div class="left">
                    <img src="Leite com Achocolatado 200 ml.webp" alt="Leite achocolatado">
                    <div class="info"><strong>Leite com Achocolatado 200 ml</strong></div>
                </div>
                <div class="price">R$ 4,25</div>
                <div><button onclick="addToCart('Leite com Achocolatado 200 ml', 4.25)">Adicionar</button></div>
            </div>

        </div>

        <!-- DOCES 27-64 -->
        <div class="menu-category" id="doces">
            <h3>🍬 Doces & Balas (itens 27 a 64)</h3>

            <div class="menu-item"><div class="left"><img src="Amassyup.jpeg" alt=""><div class="info"><strong>Amassyup</strong></div></div><div class="price">R$ 1,75</div><div><button onclick="addToCart('Amassyup', 1.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Amendoim Japonês Dori 70 g.webp" alt=""><div class="info"><strong>Amendoim Japonês Dori 70 g</strong></div></div><div class="price">R$ 3,50</div><div><button onclick="addToCart('Amendoim Japonês Dori 70 g', 3.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bala Halls (drop).webp" alt=""><div class="info"><strong>Bala Halls (drop)</strong></div></div><div class="price">R$ 2,50</div><div><button onclick="addToCart('Bala Halls (drop)', 2.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bala Fruttella.webp" alt=""><div class="info"><strong>Bala Fruttella</strong></div></div><div class="price">R$ 4,00</div><div><button onclick="addToCart('Bala Fruttella', 4.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bala Mentos (tubo).jpeg" alt=""><div class="info"><strong>Bala Mentos (tubo)</strong></div></div><div class="price">R$ 3,25</div><div><button onclick="addToCart('Bala Mentos (tubo)', 3.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bala Yogurte 100.webp" alt=""><div class="info"><strong>Bala Yogurte 100</strong></div></div><div class="price">R$ 0,50</div><div><button onclick="addToCart('Bala Yogurte 100', 0.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bala Freegells.webp" alt=""><div class="info"><strong>Bala Freegells</strong></div></div><div class="price">R$ 0,50</div><div><button onclick="addToCart('Bala Freegells', 0.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Biscoito Individual Club Social.webp" alt=""><div class="info"><strong>Biscoito Individual Club Social</strong></div></div><div class="price">R$ 0,50</div><div><button onclick="addToCart('Biscoito Individual Club Social', 0.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bisc. Torcida 70 g.webp" alt=""><div class="info"><strong>Bisc. Torcida 70 g</strong></div></div><div class="price">R$ 4,00</div><div><button onclick="addToCart('Bisc. Torcida 70 g', 4.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bisc. Recheado Fazendinha 160 g.webp" alt=""><div class="info"><strong>Bisc. Recheado Fazendinha 160 g</strong></div></div><div class="price">R$ 5,00</div><div><button onclick="addToCart('Bisc. Recheado Fazendinha 160 g', 5.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bisc. Waffer Fazendinha 160 g.webp" alt=""><div class="info"><strong>Bisc. Waffer Fazendinha 160 g</strong></div></div><div class="price">R$ 5,00</div><div><button onclick="addToCart('Bisc. Waffer Fazendinha 160 g', 5.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bombom Ouro Branco.webp" alt=""><div class="info"><strong>Bombom Ouro Branco</strong></div></div><div class="price">R$ 2,25</div><div><button onclick="addToCart('Bombom Ouro Branco', 2.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Bombom Serenata.webp" alt=""><div class="info"><strong>Bombom Serenata</strong></div></div><div class="price">R$ 2,50</div><div><button onclick="addToCart('Bombom Serenata', 2.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Chiclete Plutonita 12x18gr individual.webp" alt=""><div class="info"><strong>Chiclete Plutonita 12x18gr individual</strong></div></div><div class="price">R$ 0,75</div><div><button onclick="addToCart('Chiclete Plutonita 12x18gr', 0.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Chiclete Plutonita 4 unidades.webp" alt=""><div class="info"><strong>Chiclete Plutonita c/ 4 unidades</strong></div></div><div class="price">R$ 2,00</div><div><button onclick="addToCart('Chiclete Plutonita c/4', 2.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Chiclete Trident.webp" alt=""><div class="info"><strong>Chiclete Trident</strong></div></div><div class="price">R$ 3,25</div><div><button onclick="addToCart('Chiclete Trident', 3.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Chiclete Terror Zone.jpeg" alt=""><div class="info"><strong>Chiclete Terror Zone</strong></div></div><div class="price">R$ 1,00</div><div><button onclick="addToCart('Chiclete Terror Zone', 1.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. 5Star.webp" alt=""><div class="info"><strong>Choc. 5Star</strong></div></div><div class="price">R$ 4,50</div><div><button onclick="addToCart('Choc. 5Star', 4.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. Baton 16 g.webp" alt=""><div class="info"><strong>Choc. Baton 16 g</strong></div></div><div class="price">R$ 2,25</div><div><button onclick="addToCart('Choc. Baton 16 g', 2.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. BIS Xtra 45 g.webp" alt=""><div class="info"><strong>Choc. BIS Xtra 45 g</strong></div></div><div class="price">R$ 5,00</div><div><button onclick="addToCart('Choc. BIS Xtra 45 g', 5.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. Chokito.webp" alt=""><div class="info"><strong>Choc. Chokito</strong></div></div><div class="price">R$ 3,75</div><div><button onclick="addToCart('Choc. Chokito', 3.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. Disqueti 18 g.webp" alt=""><div class="info"><strong>Choc. Disqueti 18 g</strong></div></div><div class="price">R$ 2,00</div><div><button onclick="addToCart('Choc. Disqueti 18 g', 2.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. Mini Talento.webp" alt=""><div class="info"><strong>Choc. Mini Talento</strong></div></div><div class="price">R$ 3,75</div><div><button onclick="addToCart('Choc. Mini Talento', 3.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. Tortuguita.webp" alt=""><div class="info"><strong>Choc. Tortuguita</strong></div></div><div class="price">R$ 2,25</div><div><button onclick="addToCart('Choc. Tortuguita', 2.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. Trento.webp" alt=""><div class="info"><strong>Choc. Trento</strong></div></div><div class="price">R$ 4,00</div><div><button onclick="addToCart('Choc. Trento', 4.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. Snickers.webp" alt=""><div class="info"><strong>Choc. Snickers</strong></div></div><div class="price">R$ 4,75</div><div><button onclick="addToCart('Choc. Snickers', 4.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Choc. KitKat.webp" alt=""><div class="info"><strong>Choc. KitKat</strong></div></div><div class="price">R$ 6,25</div><div><button onclick="addToCart('Choc. KitKat', 6.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Doce de pote brigadeiro.webp" alt=""><div class="info"><strong>Doce de pote brigadeiro</strong></div></div><div class="price">R$ 3,25</div><div><button onclick="addToCart('Doce de pote brigadeiro', 3.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Doce de pote brigadeiro.webp" alt=""><div class="info"><strong>Doce pé de moça</strong></div></div><div class="price">R$ 3,00</div><div><button onclick="addToCart('Doce pé de moça', 3.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Espeto doce amendoim.webp" alt=""><div class="info"><strong>Espeto doce amendoim</strong></div></div><div class="price">R$ 3,25</div><div><button onclick="addToCart('Espeto doce amendoim', 3.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Fini Tubes 180 g.webp" alt=""><div class="info"><strong>Fini Tubes 180 g</strong></div></div><div class="price">R$ 2,00</div><div><button onclick="addToCart('Fini Tubes 180 g', 2.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Goma Dori.webp" alt=""><div class="info"><strong>Goma Dori</strong></div></div><div class="price">R$ 2,00</div><div><button onclick="addToCart('Goma Dori', 2.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Goma Jubes.webp" alt=""><div class="info"><strong>Goma Jubes</strong></div></div><div class="price">R$ 2,75</div><div><button onclick="addToCart('Goma Jubes', 2.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Mariola Fardin 58 g.webp" alt=""><div class="info"><strong>Mariola Fardin 58 g</strong></div></div><div class="price">R$ 2,00</div><div><button onclick="addToCart('Mariola Fardin 58 g', 2.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Paçoca 20 g.webp" alt=""><div class="info"><strong>Paçoca 20 g</strong></div></div><div class="price">R$ 1,50</div><div><button onclick="addToCart('Paçoca 20 g', 1.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Pirulito Blong.webp" alt=""><div class="info"><strong>Pirulito Blong</strong></div></div><div class="price">R$ 1,50</div><div><button onclick="addToCart('Pirulito Blong', 1.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Pipoca Doce Gulozinha 100 g.webp" alt=""><div class="info"><strong>Pipoca Doce Gulozinha 100 g</strong></div></div><div class="price">R$ 3,75</div><div><button onclick="addToCart('Pipoca Doce Gulozinha 100 g', 3.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="Trio Cereais (cx com 12 und).webp" alt=""><div class="info"><strong>Trio Cereais (cx com 12 und)</strong></div></div><div class="price">R$ 2,75</div><div><button onclick="addToCart('Trio Cereais (cx c/12)', 2.75)">Adicionar</button></div></div>

        </div>

        <!-- SOBREMESAS 65-74 -->
        <div class="menu-category" id="sobremesas">
            <h3>🍰 Sobremesas (itens 65 a 74)</h3>

            <div class="menu-item"><div class="left"><img src="mousse.webp" alt=""><div class="info"><strong>Mousse (130 g)</strong></div></div><div class="price">R$ 4,75</div><div><button onclick="addToCart('Mousse (130 g)', 4.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="pave.webp" alt=""><div class="info"><strong>Pavê (220 g)</strong></div></div><div class="price">R$ 7,75</div><div><button onclick="addToCart('Pavê (220 g)', 7.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="pudim.webp" alt=""><div class="info"><strong>Pudim (130 g)</strong></div></div><div class="price">R$ 5,25</div><div><button onclick="addToCart('Pudim (130 g)', 5.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="paradinha.webp" alt=""><div class="info"><strong>Paradinha</strong></div></div><div class="price">R$ 2,25</div><div><button onclick="addToCart('Paradinha', 2.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="picolesimples.webp" alt=""><div class="info"><strong>Pic. Simples Guri</strong></div></div><div class="price">R$ 3,50</div><div><button onclick="addToCart('Pic. Simples Guri', 3.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="picolecobertura.webp" alt=""><div class="info"><strong>Pic. Cobertura Guri</strong></div></div><div class="price">R$ 4,75</div><div><button onclick="addToCart('Pic. Cobertura Guri', 4.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="salada.webp" alt=""><div class="info"><strong>Salada de Frutas (150 g)</strong></div></div><div class="price">R$ 4,75</div><div><button onclick="addToCart('Salada de Frutas (150 g)', 4.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="sorvete.webp" alt=""><div class="info"><strong>Sorv. pote 200 ml Guri</strong></div></div><div class="price">R$ 5,50</div><div><button onclick="addToCart('Sorv. pote 200 ml Guri', 5.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="acai.webp" alt=""><div class="info"><strong>Açaí 200 ml</strong></div></div><div class="price">R$ 13,50</div><div><button onclick="addToCart('Açaí 200 ml', 13.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="sunday.webp" alt=""><div class="info"><strong>Sunday 200 ml Guri</strong></div></div><div class="price">R$ 6,00</div><div><button onclick="addToCart('Sunday 200 ml Guri', 6.00)">Adicionar</button></div></div>
        </div>

        <!-- BISCOITOS E SALGADOS 75-87 -->
        <div class="menu-category" id="salgados">
            <h3>🧂 Biscoitos & Salgados (itens 75 a 87)</h3>

            <div class="menu-item"><div class="left"><img src="aipim.webp" alt=""><div class="info"><strong>Aipim Chips (70 g)</strong></div></div><div class="price">R$ 8,00</div><div><button onclick="addToCart('Aipim Chips (70 g)', 8.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="batata.webp" alt=""><div class="info"><strong>Batata Chips (70 g)</strong></div></div><div class="price">R$ 8,00</div><div><button onclick="addToCart('Batata Chips (70 g)', 8.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="banana.webp" alt=""><div class="info"><strong>Banana Chips (70 g)</strong></div></div><div class="price">R$ 8,00</div><div><button onclick="addToCart('Banana Chips (70 g)', 8.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="salgadov.webp" alt=""><div class="info"><strong>Salg. Variados</strong></div></div><div class="price">R$ 8,25</div><div><button onclick="addToCart('Salg. Variados', 8.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="hamburguer.webp" alt=""><div class="info"><strong>Salg. Hamburguer</strong></div></div><div class="price">R$ 9,00</div><div><button onclick="addToCart('Salg. Hamburguer', 9.00)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="pipoca.webp" alt=""><div class="info"><strong>Pipoca de Microondas</strong></div></div><div class="price">R$ 6,25</div><div><button onclick="addToCart('Pipoca de Microondas', 6.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="paodequeijo.webp" alt=""><div class="info"><strong>Pão de Queijo</strong></div></div><div class="price">R$ 4,75</div><div><button onclick="addToCart('Pão de Queijo', 4.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="paomanteiga.webp" alt=""><div class="info"><strong>Pão com Manteiga</strong></div></div><div class="price">R$ 3,75</div><div><button onclick="addToCart('Pão com Manteiga', 3.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="paoqueijo.webp" alt=""><div class="info"><strong>Pão com Queijo</strong></div></div><div class="price">R$ 5,50</div><div><button onclick="addToCart('Pão com Queijo', 5.50)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="paopresunto.webp" alt=""><div class="info"><strong>Pão com Presunto</strong></div></div><div class="price">R$ 4,75</div><div><button onclick="addToCart('Pão com Presunto', 4.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="paopresuntoqueijo.webp" alt=""><div class="info"><strong>Pão com Presunto e Queijo</strong></div></div><div class="price">R$ 6,75</div><div><button onclick="addToCart('Pão com Presunto e Queijo', 6.75)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="sanduiche.webp" alt=""><div class="info"><strong>Sanduíche Natural</strong></div></div><div class="price">R$ 8,25</div><div><button onclick="addToCart('Sanduíche Natural', 8.25)">Adicionar</button></div></div>

            <div class="menu-item"><div class="left"><img src="tortapao.webp" alt=""><div class="info"><strong>Torta de Pão (110 g)</strong></div></div><div class="price">R$ 6,50</div><div><button onclick="addToCart('Torta de Pão (110 g)', 6.50)">Adicionar</button></div></div>
        </div>

        <!-- EMBALAGEM 88 -->
        <div class="menu-category" id="embalagem">
            <h3>📦 Embalagem</h3>
            <div class="menu-item">
                <div class="left">
                    <img src="marmitex.webp" alt="Embalagem Marmitex">
                    <div class="info"><strong>Valor da embalagem Marmitex</strong></div>
                </div>
                <div class="price">R$ 1,00</div>
                <div><button onclick="addToCart('Valor da embalagem Marmitex', 1.00)">Adicionar</button></div>
            </div>
        </div>

        <!-- CARRINHO -->
        <div id="cart">
            <h3>🛒 Carrinho</h3>
            <ul id="cart-list"></ul>
            <p>Total: R$ <span id="total">0.00</span></p>
            <div style="margin-top:8px;">
                <button onclick="checkout()">Finalizar Pedido</button>
                <button onclick="clearCart()" style="background:#f44336; margin-left:8px;">Limpar Carrinho</button>
            </div>
            <div style="margin-top:10px; font-size:13px; color:#555;">Observação: promoção aplicada automaticamente no checkout.</div>
        </div>
    </section>

    <section id="pedidos" style="max-width:1100px; margin:auto;">
        <h2>Meus Pedidos</h2>
        <p>Aqui fica o histórico de pedidos finalizados (simulado localmente).</p>
    </footer>
<!-- Exemplo de item decorado -->
<!-- 💳 NOVA SESSÃO DE PAGAMENTO -->
<section id="pagamento" style="padding: 40px 20px; text-align:center; background:#f8fff8; margin-top:40px; border-top:3px solid #4CAF50;">
<h2 style="font-size:28px; font-weight:700; color:#2e7d32; margin-bottom:15px;">💳 Formas de Pagamento</h2>
<p style="font-size:18px; color:#444; margin-bottom:25px;">Selecione a forma como deseja pagar seu pedido:</p>


<div style="display:flex; justify-content:center; gap:20px; flex-wrap:wrap;">
<button style="padding:15px 25px; font-size:18px; background:#4CAF50; color:white; border:none; border-radius:12px; cursor:pointer; box-shadow:0 4px 10px rgba(0,0,0,0.15); transition:0.3s;">💵 Dinheiro</button>


<button onclick="abrirCartao()" style="padding:15px 25px; font-size:18px; background:#2196F3; color:white; border:none; border-radius:12px; cursor:pointer; box-shadow:0 4px 10px rgba(0,0,0,0.15); transition:0.3s;">💳 Cartão</button>


<button onclick="abrirPix()" style="padding:15px 25px; font-size:18px; background:#8e24aa; color:white; border:none; border-radius:12px; cursor:pointer; box-shadow:0 4px 10px rgba(0,0,0,0.15); transition:0.3s;">⚡ PIX</button>
</div>


<!-- MODAL PIX -->
<div id="pixModal" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.6); justify-content:center; align-items:center;">
<div style="background:white; padding:30px; border-radius:20px; width:320px; text-align:center; box-shadow:0 4px 12px rgba(0,0,0,0.3); animation:show 0.3s ease;">
<h3 style="font-size:24px; margin-bottom:10px; color:#7b1fa2;">Pagamento via PIX</h3>
<p style="margin-bottom:20px;">Escaneie o QR Code abaixo:</p>
<div style="width:180px; height:180px; background:#eee; border-radius:12px; margin:0 auto 20px; display:flex; justify-content:center; align-items:center; font-size:14px; color:#666;">
QR CODE
</div>


<button onclick="fecharPix()" style="padding:10px 20px; background:#7b1fa2; color:white; border:none; border-radius:10px; cursor:pointer;">Fechar</button>
</div>
</div>


<script>
function abrirPix() {
document.getElementById('pixModal').style.display = 'flex';
}
function fecharPix() {
document.getElementById('pixModal').style.display = 'none';
}
</script>




<!-- 💳 CARTÃO - NOVO MODAL COMPLETO -->
<div id="cartaoModal" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.6); justify-content:center; align-items:center;">
<div style="background:white; padding:30px; border-radius:20px; width:340px; text-align:center; box-shadow:0 4px 12px rgba(0,0,0,0.3); animation:show 0.3s ease;">
<h3 style="font-size:24px; margin-bottom:15px; color:#1565c0;">💳 Pagamento com Cartão</h3>


<label style="display:block; text-align:left; font-weight:600; margin-bottom:5px;">Nome no Cartão</label>
<input type="text" placeholder="Seu nome" style="width:100%; padding:10px; border-radius:10px; border:1px solid #bbb; margin-bottom:15px;">


<label style="display:block; text-align:left; font-weight:600; margin-bottom:5px;">Número do Cartão</label>
<input type="text" maxlength="16" placeholder="0000 0000 0000 0000" style="width:100%; padding:10px; border-radius:10px; border:1px solid #bbb; margin-bottom:15px;">


<div style="display:flex; gap:10px;">
<div style="flex:1;">
<label style="display:block; text-align:left; font-weight:600; margin-bottom:5px;">Validade</label>
<input type="text" placeholder="MM/AA" maxlength="5" style="width:100%; padding:10px; border-radius:10px; border:1px solid #bbb; margin-bottom:15px;">
</div>
<div style="flex:1;">
<label style="display:block; text-align:left; font-weight:600; margin-bottom:5px;">CVV</label>
<input type="text" maxlength="3" placeholder="123" style="width:100%; padding:10px; border-radius:10px; border:1px solid #bbb; margin-bottom:15px;">
</div>
</div>


<label style="display:block; text-align:left; font-weight:600; margin-bottom:5px;">Tipo de Pagamento</label>
<select style="width:100%; padding:10px; border-radius:10px; border:1px solid #bbb; margin-bottom:20px;">
<option>Crédito</option>
<option>Débito</option>
</select>


<button style="padding:12px 20px; background:#1565c0; color:white; border:none; border-radius:10px; cursor:pointer; width:100%; margin-bottom:10px; font-size:16px;">Confirmar Pagamento</button>


<button onclick="fecharCartao()" style="padding:10px 15px; background:#555; color:white; border:none; border-radius:10px; cursor:pointer; width:100%;">Cancelar</button>
</div>
</div>


<script>
function abrirCartao() {
document.getElementById('cartaoModal').style.display = 'flex';
}
function fecharCartao() {
document.getElementById('cartaoModal').style.display = 'none';
}
</script>


</section>
<ul id="order-history" style="background:white; padding:16px; border-radius:8px; box-shadow:0 2px 6px rgba(0,0,0,0.06);"></ul>
    </section>

    <footer>
        <p>&copy; 2025 Cantina Escolar Online. Lista importada das imagens fornecidas. Desenvolvido para uso interno da escola.</p>

</body>
</html>

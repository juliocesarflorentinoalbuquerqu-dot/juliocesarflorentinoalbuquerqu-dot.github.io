<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Práticas Pedagógicas de Experimentação em Química</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&amp;family=Open+Sans:wght@600&amp;display=swap" rel="stylesheet"/>
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet"/>
<style>
html {
    scroll-behavior: smooth;
}
body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    color: #333;
}
header {
    background: linear-gradient(135deg, #4CAF50 0%, #45a049 100%);
    color: white;
    text-align: center;
    padding: 2em 1em 1.2em;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    position: relative;
    min-height: 110px;
}
header h1 {
    font-family: 'Open Sans', sans-serif;
    font-size: 2.2em;
    margin: 0;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    padding-top: 8px;
    text-transform: uppercase;
    letter-spacing: 1px;
}
header p {
    font-size: 1.0em;
    margin: 0.5em 0 0;
}
nav {
    background: rgba(255,255,255,0.08);
    padding: 0.8em;
    margin: 1em auto 0;
    border-radius: 0 0 10px 10px;
    max-width: 1100px;
}
nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}
nav li {
    margin: 0 0.8em;
}
nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s, background 0.3s;
    padding: 0.4em 0.9em;
    border-radius: 5px;
    display: inline-block;
}
nav a:hover {
    color: #FFD700;
    background: rgba(255,255,255,0.14);
}
main {
    max-width: 1000px;
    margin: 2em auto;
    padding: 0 1em 2em;
    background: white;
    box-shadow: 0 0 20px rgba(0,0,0,0.08);
    border-radius: 10px;
    overflow: hidden;
}
section {
    margin-bottom: 2em;
    padding: 2em;
    border-left: 5px solid #4CAF50;
    background: #fafafa;
    transition: transform 0.3s, box-shadow 0.3s;
    scroll-margin-top: 100px;
}
section:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.06);
}
.secao-azul {
    border-left-color: #2196F3 !important;
    background: linear-gradient(to right, rgba(33, 150, 243, 0.04), #fafafa);
}
.secao-vermelha {
    border-left-color: #F44336 !important;
    background: linear-gradient(to right, rgba(244, 67, 54, 0.04), #fafafa);
}
.secao-roxa {
    border-left-color: #9C27B0 !important;
    background: linear-gradient(to right, rgba(156, 39, 176, 0.04), #fafafa);
}
h1, h2, h3 {
    font-family: 'Open Sans', sans-serif;
    color: #2E7D32;
}
h2 {
    font-size: 1.6em;
    display: flex;
    align-items: center;
    gap: 0.6em;
    margin-bottom: 1em;
}
h2 i { color: #4CAF50; font-size: 1.2em; }
ul, ol {
    margin: 1em 0;
    padding-left: 1.5em;
}
.observacao {
    background: #e8f5e8;
    padding: 1em;
    border-radius: 5px;
    border-left: 4px solid #4CAF50;
    margin: 1em 0;
}
.seguranca {
    background: linear-gradient(135deg, #fff3cd 0%, #ffeaa7 100%);
    border-left-color: #FF6B35;
    border: 1px solid #ffeaa7;
    padding: 1.5em;
}
.seguranca h2 i { color: #FF6B35; }
.card-material {
    background: white;
    border: 1px solid #e6e6e6;
    padding: 1em;
    border-radius: 8px;
    margin-bottom: 1em;
}
.procedimento li { margin-bottom: 0.6em; }
footer {
    text-align: center;
    padding: 1.5em;
    background: linear-gradient(135deg, #4CAF50 0%, #45a049 100%);
    color: white;
    margin-top: 2em;
    font-family: 'Roboto', sans-serif;
}
footer i { margin-right: 0.5em; }
.video-container {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden;
    max-width: 100%;
    background: #000;
    border-radius: 8px;
    margin-top: 1em;
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}
.video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
@media (max-width: 768px) {
    header h1 { font-size: 1.6em; }
    nav ul { flex-direction: column; gap: 0.4em; }
    section { padding: 1.2em; scroll-margin-top: 80px; }
}
</style>
</head>
<body>
<header>
  <div style="text-align:center;">
    <img alt="Logo IFES" class="logo-ifes" src="logo ifes.jpeg" style="position:static; height:120px; margin-bottom:10px;">
  </div>
  <h1><i class="fas fa-flask"></i> PRÁTICAS PEDAGÓGICAS DE EXPERIMENTAÇÃO EM QUÍMICA</h1>
  <p>Projeto com três práticas pedagógicas: Relógio de Iodo, Sangue do Diabo e pH no Repolho Roxo</p>
  <nav>
    <ul>
      <li><a href="#introducao">Introdução</a></li>
      <li><a href="#seguranca">Segurança</a></li>
      <li><a href="#relogio-iodo">Relógio de Iodo</a></li>
      <li><a href="#sangue-diabo">Sangue do Diabo</a></li>
      <li><a href="#repolho-roxo">pH no Repolho Roxo</a></li>
      <li><a href="#conclusao">Conclusão</a></li>
    </ul>
  </nav>
</header>

<main>
<section id="introducao">
<h2><i class="fas fa-info-circle"></i> Introdução</h2>
<p>Este projeto compõe três práticas pedagógicas de experimentação em química: Relógio de Iodo, Sangue do Diabo e pH no Repolho Roxo. Esses experimentos demonstram, por meio de reações visuais e controladas, conceitos fundamentais das reações químicas, abordando temas como velocidade de reação, reações redox e indicadores ácido-base. O objetivo é tornar o aprendizado da química mais dinâmico e compreensível.</p>
<h3>Objetivos Gerais</h3>
<p>Demonstrar, por meio de experimentos visuais e controlados, os conceitos fundamentais das reações químicas, abordando temas como velocidade de reação, reações redox e indicadores ácido-base, com o intuito de tornar o aprendizado da química mais dinâmico e compreensível.</p>
<h3>Objetivos Específicos</h3>
<ul>
<li>Observar a variação da velocidade das reações químicas por meio do experimento do Relógio de Iodo;</li>
<li>Determinar o pH de diferentes soluções utilizando o extrato natural de repolho roxo como indicador ácido-base;</li>
<li>Investigar o comportamento de indicadores ácido-base utilizando o experimento Sangue do Diabo;</li>
<li>Estimular práticas seguras e supervisionadas em laboratório escolar.</li>
</ul>
</section>

<section class="seguranca" id="seguranca">
<h2><i class="fas fa-exclamation-triangle"></i> Critérios de Segurança</h2>
<p>Antes de realizar qualquer experimento, é essencial seguir as normas de segurança: usar jaleco, luvas e óculos de proteção. Realize os experimentos em um local ventilado. Todos os procedimentos devem ser realizados sob supervisão de um professor qualificado.</p>
<div class="observacao">
<i class="fas fa-lightbulb"></i> <strong>Dica:</strong> Sempre leia os procedimentos com antecedência, organize os materiais e evite misturar substâncias sem orientação profissional.
</div>
</section>

<section class="secao-azul" id="relogio-iodo">
<h2><i class="fas fa-clock"></i> Relógio de Iodo</h2>
<h3>Introdução</h3>
<p>O Relógio de Iodo é um experimento clássico de cinética química em que duas soluções incolores reagem para produzir, de forma repentina, uma coloração azul-escura devido à formação de um complexo amido-iodo. A velocidade da mudança de cor depende de fatores como concentração e temperatura.</p>
<h3>Materiais</h3>
<div class="card-material">
<ul>
<li>250 mL de água destilada</li>
<li>1 solução de vitamina C</li>
<li>1 solução de tintura de iodo</li>
<li>1 solução de água oxigenada</li>
<li>Amido (1–2% em água)</li>
<li>Proveta, béqueres, pipetas e cronômetro</li>
</ul>
</div>
<h3>Procedimento</h3>
<ol class="procedimento">
<li>Preparar três soluções: A (vitamina C + água), B (tintura de iodo + água), C (água oxigenada + amido).</li>
<li>Misturar volumes medidos de A e B em um béquer e iniciar o cronômetro.</li>
<li>Adicionar rapidamente a solução C e mexer suavemente.</li>
<li>Observar o tempo até a solução ficar azul-escura e registrar.</li>
<li>Repetir variando concentrações ou temperatura para comparar tempos.</li>
</ol>
<h3>Explicação Química</h3>
<p>Durante a reação, o peróxido de hidrogênio oxida o iodeto (I⁻) a iodo (I₂). O iodo em presença de amido forma um complexo azul. O tiossulfato atua como agente redutor, reagindo com o iodo produzido e adiando a coloração até que se esgote — por isso a mudança é repentina quando o tiossulfato acaba.</p>
<div class="observacao">
<i class="fas fa-eye"></i> Registre as variações no tempo de mudança de cor ao alterar concentração e temperatura para discutir cinética química com a turma.
</div>
<!-- VÍDEO DO RELÓGIO DE IODO -->
<div class="video-container">
    <iframe src="https://www.youtube.com/embed/WtFXtxZE6Ls" title="Vídeo do Relógio de Iodo" frameborder="0" allowfullscreen></iframe>
</div>
</section>

<section class="secao-vermelha" id="sangue-diabo">
<h2><i class="fas fa-tint"></i> Sangue do Diabo</h2>
<h3>Introdução</h3>
<p>O experimento Sangue do Diabo demonstra visualmente reações de oxidação/redução e o comportamento de indicadores que mudam de cor conforme o ambiente químico. A aparência semelhante a sangue chama a atenção dos estudantes, facilitando discussões sobre processos químicos e segurança.</p>
<h3>Materiais</h3>
<div class="card-material">
<ul>
<li>Fenolftaleína (ou corante similar)</li>
<li>Hidróxido de sódio (NaOH) diluído</li>
<li>Peróxido de hidrogênio (H<sub>2</sub>O<sub>2</sub>) ou outro oxidante suave</li>
<li>Água destilada</li>
<li>Proveta, béquer e bastão de vidro</li>
</ul>
</div>
<h3>Procedimento</h3>
<ol class="procedimento">
<li>Preparar uma solução diluída de NaOH em água (solução básica).</li>
<li>Adicionar algumas gotas de fenolftaleína — a solução ficará rosa em meio básico.</li>
<li>Adicionar cuidadosamente o oxidante (H<sub>2</sub>O<sub>2</sub>) e observar mudanças de cor e formação de bolhas se ocorrer liberação de oxigênio.</li>
<li>Registrar as mudanças de cor e discutir o que acontece quando o meio oxida o corante.</li>
</ol>
<h3>Explicação Química</h3>
<p>Em meio básico, a fenolftaleína adquire coloração rosa. A presença de um oxidante pode oxidar espécies orgânicas ou provocar reações que alteram a estrutura do corante, mudando a cor ou degradando o pigmento. Esse experimento ilustra como o pH e agentes oxidantes influenciam a cor e a estabilidade de indicadores.</p>
<div class="observacao">
<i class="fas fa-eye"></i> Trabalhe com concentrações diluídas e supervisão para evitar riscos — sempre use EPI.
</div>
<!-- VÍDEO DO SANGUE DO DIABO -->
<div class="video-container">
    <iframe src="https://www.youtube.com/embed/-xdcutoPoEQ" title="Vídeo do Sangue do Diabo" frameborder="0" allowfullscreen></iframe>
</div>
</section>

<section class="secao-roxa" id="repolho-roxo">
<h2><i class="fas fa-leaf"></i> pH no Repolho Roxo</h2>
<h3>Introdução</h3>
<p>O repolho roxo contém antocianinas, pigmentos que mudam de cor conforme o pH do meio. O extrato de repolho roxo é um indicador natural, ótimo para atividades escolares que mostram diferenças entre ácidos e bases com cores visíveis.</p>
<h3>Materiais</h3>
<div class="card-material">
<ul>
<li>1/2 repolho roxo</li>
<li>Água destilada</li>
<li>Frascos ou béqueres para testar soluções</li>
<li>Vinagre (ácido acético), bicarbonato de sódio (básico), água (neutro)</li>
<li>Filtro ou peneira</li>
</ul>
</div>
<h3>Procedimento</h3>
<ol class="procedimento">
<li>Picar o repolho roxo e ferver em água por 10–15 minutos para extrair a cor.</li>
<li>Coar o extrato e deixar esfriar; este será o indicador.</li>
<li>Adicionar pequenas porções do extrato em diferentes frascos contendo vinagre, água e solução de bicarbonato.</li>
<li>Observar e registrar as mudanças de cor: ácido → rosa/vermelho, neutro → roxo, básico → verde/azul.</li>
</ol>
<h3>Explicação Química</h3>
<p>As antocianinas alteram sua estrutura eletrônica conforme a concentração de íons H⁺ no meio, provocando diferenças na absorção de luz e, consequentemente, na cor observada. Assim, o extrato de repolho roxo funciona como um indicador de amplo espectro para demonstrar pH de forma visual.</p>
<div class="observacao">
<i class="fas fa-eye"></i> Faça um quadro de cores com as soluções testadas para que os alunos possam comparar e estimar o pH relativo.
</div>
<!-- VÍDEO DO PH NO REPOLHO ROXO -->
<div class="video-container">
    <iframe src="https://www.youtube.com/embed/Z9y91PAbnbQ" title="Vídeo do pH no Repolho Roxo" frameborder="0" allowfullscreen></iframe>
</div>
</section>

<section id="conclusao">
<h2><i class="fas fa-check-circle"></i> Conclusão</h2>
<p>As práticas pedagógicas de experimentação em química — Relógio de Iodo, Sangue do Diabo e pH no Repolho Roxo — permitem aos alunos compreender conceitos fundamentais da química de forma visual, interativa e significativa. Além de estimular a curiosidade científica, essas atividades reforçam o aprendizado teórico, aproximando a ciência do cotidiano.</p>
<div class="observacao">
<i class="fas fa-flask"></i> <strong>Conclusão geral:</strong> A experimentação é uma ferramenta essencial no ensino de química, pois transforma o aprendizado em uma experiência viva, envolvente e inesquecível.
</div>

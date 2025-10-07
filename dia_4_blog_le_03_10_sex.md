/* ===================== RESET BÁSICO ===================== */
* {
  margin: 0; /* Remove margens padrão */
  padding: 0; /* Remove preenchimento padrão */
  box-sizing: border-box; /* Inclui padding e borda no cálculo de largura/altura */
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; /* Fonte limpa e moderna */
  line-height: 1.6; /* Espaçamento entre linhas para melhor leitura */
  background-color: #f9f9f9; /* Fundo claro e neutro */
  color: #333; /* Cor padrão do texto */
}

/* ===================== BANNER (mantido) ===================== */
#banner {
  height: 250px; /* Altura fixa para o banner */
  background-image: url("imagens_front_blog_le/so_logo_blog_le.png"); /* Imagem de topo */
  background-position: center; /* Centraliza a imagem */
  background-size: 100% 100%; /* Preenche sem distorcer */
  background-repeat: no-repeat; /* Evita repetição da imagem */
}

/* ===================== PARTE 1: TÍTULO EM FLEXBOX ===================== */
.titulo-flex {
  display: flex; /* Ativa Flexbox */
  justify-content: center; /* Centraliza horizontalmente */
  align-items: center; /* Centraliza verticalmente */
  padding: 2rem; /* Espaço interno */
  background-color: #eaeaea; /* Fundo neutro */
  width: 100%; /* Ocupa toda a largura */
  box-sizing: border-box; /* Inclui padding na largura */
}

.titulo-flex h1 {
  font-size: 2rem; /* Tamanho do título */
  color: #222; /* Cor escura para contraste */
  text-align: center; /* Centraliza o texto */
}

/* ===================== GRID PRINCIPAL ===================== */
.conteudo-grid {
  display: grid; /* Ativa Grid Layout */
  grid-template-columns: 1fr 6fr 4fr; /* Coluna esquerda, centro e direita com proporções */
  column-gap: 2rem; /* Espaço horizontal entre colunas */
  row-gap: 1rem; /* Espaço vertical entre linhas, se houver */
  padding: 2rem; /* Espaço interno geral */
  width: 100vw; /* Ocupa toda a largura da tela */
  box-sizing: border-box; /* Inclui padding no cálculo da largura */
  align-items: stretch; /* Estica os filhos para altura igual */
}

/* ===================== COLUNAS DO GRID COM ALTURA IGUAL ===================== */
.perfil-container,
.conteudo-principal,
.lei-container {
  height: 100%; /* Ocupa toda a altura da célula do grid */
  display: flex; /* Ativa Flexbox para controle interno */
  flex-direction: column; /* Empilha conteúdo verticalmente */
  justify-content: space-between; /* Distribui conteúdo com equilíbrio */
}

/* ===================== BORDAS VERTICAIS ENTRE AS COLUNAS (OPCIONAL) ===================== */
.perfil-container {
  border-right: 1px solid #ddd; /* Linha divisória à direita */
}

/* ===================== SUBSTITUIÇÃO DA PUBLICIDADE DIREITA PELO BLOCO DA LEI USADA ===================== */
.lei-container {
  width: 100%;
  max-width: 1000px;
  margin: 2rem auto;
  padding: 1.5rem;
  background-color: #ffffff;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  border-radius: 8px;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

/* Mantém borda lateral como a antiga publicidade */
.lei-container {
  border-left: 1px solid #ddd;
}

/* ===================== ARTICLE PRINCIPAL SOBRE A LEI ===================== */
.qual_foi_lei_usada {
  display: block;
  width: 100%;
}

/* ===================== SEÇÃO INTERNA DO ARTICLE ===================== */
.secao-lei-usada {
  padding: 1rem 0;
}

/* ===================== CONTAINER INTERNO DO TEXTO ===================== */
.container-lei-usada {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

/* ===================== BLOCO DE TEXTO JURÍDICO ===================== */
.mensagem-lei {
  color: #333;
  line-height: 1.6;
}

/* ===================== TÍTULOS E DESTAQUES ===================== */
.mensagem-lei h2 {
  font-size: 1.4rem;
  color: #0055aa;
  margin-bottom: 0.5rem;
}

.mensagem-lei h3 {
  font-size: 1.2rem;
  color: #0077cc;
  margin-top: 1.5rem;
}

.mensagem-lei h4 {
  font-size: 1.1rem;
  color: #444;
  margin-top: 1rem;
}

.destaque {
  background-color: #e0f0ff;
  padding: 0.2rem 0.5rem;
  border-radius: 4px;
  font-weight: bold;
}

/* ===================== LISTAS E LINKS ===================== */
.mensagem-lei ul {
  padding-left: 1.5rem;
}

.mensagem-lei li {
  margin-bottom: 0.5rem;
}

.mensagem-lei a {
  color: #0066cc;
  text-decoration: underline;
}

.mensagem-lei a:hover {
  text-decoration: none;
}

/* ===================== RESPONSIVO PARA TELAS MENORES ===================== */
@media screen and (max-width: 768px) {
  .lei-container {
    padding: 1rem;
    margin: 1rem auto;
  }

  .mensagem-lei h2 {
    font-size: 1.2rem;
  }

  .mensagem-lei h3 {
    font-size: 1rem;
  }

  .mensagem-lei h4 {
    font-size: 0.95rem;
  }
}


/* ===================== CONTEÚDO CENTRAL COM CRESCIMENTO VERTICAL (OPCIONAL) ===================== */
.conteudo-principal > * {
  flex-grow: 1; /* Faz o conteúdo crescer para ocupar espaço vertical */
}

/* ===================== PERFIL INSTITUCIONAL: CONTAINER GERAL quem sou ===================== */
.perfil-container {
  margin: 2rem auto; /* Espaço externo acima e abaixo, centraliza horizontalmente */
  padding: 1rem; /* Espaço interno geral */
  width: 100%; /* Ocupa toda a largura disponível */
  max-width: 1000px; /* Limita a largura máxima para manter legibilidade */
  box-sizing: border-box; /* Inclui padding no cálculo da largura */
}

/* ===================== ARTICLE: BLOCO DE CONTEÚDO INDEPENDENTE quem sou===================== */
.quem-sou {
  background-color: #fff; /* Fundo branco para destaque */
  border-radius: 8px; /* Cantos arredondados */
  box-shadow: 0 0 10px rgba(0,0,0,0.05); /* Sombra leve para profundidade */
  padding: 1rem; /* Espaço interno */
}

/* ===================== SECTION: AGRUPAMENTO INTERNO ===================== */
.secao-quem {
  padding: 2rem; /* Espaço interno para separar do container externo */
}

/* ===================== CONTAINER INTERNO DO PERFIL ===================== */
.container-quem-sou {
  display: flex; /* Ativa Flexbox */
  justify-content: center; /* Centraliza horizontalmente */
  align-items: center; /* Centraliza verticalmente */
  flex-direction: column; /* Empilha os elementos verticalmente */
}

/* ===================== BLOCO DO PERFIL DO DR. LEANDRO ===================== */
.perfil-dr-leandro {
  text-align: center; /* Centraliza o texto */
  background-color: #fdf6e3; /* Fundo claro estilo institucional */
  padding: 2rem; /* Espaço interno */
  border-radius: 12px; /* Cantos mais arredondados para destaque */
  box-shadow: 0 0 8px rgba(0,0,0,0.05); /* Sombra leve */
}

/* ===================== IMAGEM DO PERFIL ===================== */
.perfil-dr-leandro img {
  width: 160px; /* Aumenta levemente o tamanho da imagem */
  height: auto; /* Mantém proporção original */
  border-radius: 50%; /* Formato circular */
  margin-bottom: 1rem; /* Espaço abaixo da imagem */
  box-shadow: 0 0 6px rgba(0,0,0,0.1); /* Sombra suave para destaque */
}

/* ===================== BLOCO DE TEXTO INSTITUCIONAL ===================== */
.mensagem h2 {
  font-size: 1.4rem; /* Tamanho do título principal */
  margin-bottom: 0.5rem; /* Espaço abaixo do título */
  color: #222; /* Cor escura para contraste */
}

.mensagem h3 {
  margin-top: 1rem; /* Espaço acima do subtítulo */
  font-size: 1.1rem; /* Tamanho do subtítulo */
  color: #444; /* Cor intermediária */
}

.mensagem p {
  font-size: 0.95rem; /* Tamanho do texto institucional */
  line-height: 1.6; /* Altura da linha para melhor leitura */
  color: #555; /* Cor suave para leitura prolongada */
}

/* ===================== DESTAQUE NO SUBTÍTULO ===================== */
.destaque {
  color: #b22222; /* Vermelho escuro para chamar atenção */
  font-weight: bold; /* Negrito para reforçar o destaque */
}

/* ===================== GRID CENTRAL: NARRATIVA DO CASO ===================== */
/* ===================== CONTEÚDO PRINCIPAL: NARRATIVA DO CASO ===================== */
.conteudo-principal {
  background-color: #ffffff; /* Fundo branco para destaque */
  padding: 2rem; /* Espaço interno generoso */
  border-radius: 8px; /* Cantos arredondados */
  box-shadow: 0 0 12px rgba(0,0,0,0.08); /* Sombra suave para profundidade */
  box-sizing: border-box; /* Inclui padding na largura */
  line-height: 1.7; /* Altura de linha para leitura confortável */
  font-size: 1rem; /* Tamanho padrão do texto */
  color: #333; /* Cor escura para contraste */
}

/* Títulos principais e intermediários */
.conteudo-principal h2 {
  font-size: 1.8rem;
  color: #0055aa;
  margin-bottom: 1rem;
}

.conteudo-principal h3 {
  font-size: 1.4rem;
  color: #0077cc;
  margin-top: 2rem;
  margin-bottom: 0.5rem;
}

/* Parágrafos */
.conteudo-principal p {
  margin-bottom: 1rem;
}

/* Listas */
.conteudo-principal ul {
  padding-left: 1.5rem;
  margin-bottom: 1rem;
}

.conteudo-principal li {
  margin-bottom: 0.5rem;
}

/* Ênfase e destaque */
.conteudo-principal em {
  font-style: italic;
  color: #444;
}

.conteudo-principal strong {
  font-weight: bold;
  color: #222;
}

/* Links internos ou externos (se houver) */
.conteudo-principal a {
  color: #0066cc;
  text-decoration: underline;
}

.conteudo-principal a:hover {
  text-decoration: none;
}



/* ===================== BLOCO DE ANÚNCIOS NA COLUNA ESQUERDA NA COLUNA DO PERFIL ===================== */
#anuncios-perfil-container {
  margin-top: 2rem; /* Espaço acima do bloco de anúncios */
  display: flex; /* Ativa Flexbox para empilhar os anúncios */
  flex-direction: column; /* Empilha verticalmente */
  gap: 1.5rem; /* Espaço entre os blocos de anúncio */
  flex-grow: 1; /* Permite ocupar o restante da altura da coluna */
  justify-content: flex-start; /* Alinha os anúncios ao topo */
}

/* Bloco visual de cada anúncio */
.anuncio-bloco-perfil {
  height: 1px; /* Elemento auxiliar para espaçamento ou separação */
  background-color: transparent; /* Invisível, pode ser usado como marcador */
}

/* Seção que agrupa os anúncios */
.secao-publicidade {
  padding: 1rem; /* Espaço interno da seção */
  background-color: #fff; /* Fundo branco para destaque */
  border-radius: 8px; /* Cantos arredondados */
  box-shadow: 0 0 10px rgba(0,0,0,0.05); /* Sombra leve */
}

/* Título da seção de publicidade */
.titulo-publicidade {
  font-size: 1.2rem; /* Tamanho do título */
  color: #333; /* Cor escura para contraste */
  margin-bottom: 1rem; /* Espaço abaixo do título */
}

/* Container que organiza os anúncios */
.container-publicidade {
  display: flex; /* Ativa Flexbox */
  flex-direction: column; /* Empilha os anúncios verticalmente */
  gap: 1rem; /* Espaço entre os anúncios */
}

/* Estilo de cada bloco de publicidade */
.publicidade {
  background-color: #f0f0f0; /* Fundo neutro */
  padding: 1rem; /* Espaço interno */
  border-radius: 6px; /* Cantos arredondados */
  box-shadow: 0 0 6px rgba(0,0,0,0.05); /* Sombra leve */
  text-align: center; /* Centraliza o conteúdo */
  font-size: 0.9rem; /* Tamanho do texto */
  color: #444; /* Cor suave para leitura */
}

/* Estilo da logo suave */

.logo-suave {
  width: 100%; /* Ocupa toda a largura do container */
  max-width: 280px; /* Limita o tamanho para não estourar o layout */
  height: auto; /* Mantém proporção original */
  border-radius: 8px; /* Cantos arredondados para suavidade */
  box-shadow: 0 4px 10px rgba(0,0,0,0.1); /* Sombra leve para destaque */
  margin: 0 auto 1rem auto; /* Centraliza e dá espaço abaixo */
  display: block; /* Garante que seja tratado como bloco */
  object-fit: cover; /* Preenche o espaço sem distorcer */
  opacity: 0.85; /* Visual suave */
  transition: opacity 0.3s ease; /* Transição suave ao interagir */
}

.logo-suave:hover {
  opacity: 1; /* Destaca ao passar o mouse */
}


/* Botões de redes sociais */
.botao-instagram,
.botao-whatsapp {
  display: inline-block; /* Permite padding e margem */
  margin-top: 0.5rem; /* Espaço acima do botão */
  color: #0066cc; /* Azul padrão */
  text-decoration: underline; /* Sublinhado */
}

.botao-instagram:hover,
.botao-whatsapp:hover {
  text-decoration: none; /* Remove sublinhado ao passar o mouse */
}


/* ===================== PARTE 3: IMAGEM EM FLEXBOX ===================== */
.imagem-flex {
  display: flex; /* Ativa Flexbox */
  justify-content: center; /* Centraliza horizontalmente */
  align-items: center; /* Centraliza verticalmente */
  padding: 2.5rem; /* Espaço interno */
  background-color: #eaeaea; /* Fundo neutro */
  width: 100%; /* Ocupa toda a largura */
  box-sizing: border-box; /* Inclui padding na largura */
}

.imagem-flex img {
  width: 100%; /* Responsivo */
  height: auto; /* Mantém proporção */
  max-height: 800px; /* Limita altura máxima */
  object-fit: fill; /* Preenche sem distorcer */
  border-radius: 10px; /* Cantos arredondados */
  box-shadow: 0 4px 12px rgba(0,0,0,0.1); /* Sombra suave */
}

/* ===================== ESPAÇAMENTO ENTRE SEÇÕES ===================== */
main > section {
  margin-bottom: 2rem; /* Espaço entre seções do main */
}

/* ===================== RODAPÉ (mantido) ===================== */
.footer {
  text-align: center; /* Centraliza o conteúdo do rodapé */
  padding: 20px; /* Espaçamento interno */
  background-color: #3e3d3d; /* Fundo cinza escuro */
  font-size: 14px; /* Texto menor */
  color: #eceef3; /* Texto em tom claro para contraste */
}

/* Container "Powered by" */
.powered-by {
  display: flex; /* Layout flexível */
  align-items: center; /* Alinha verticalmente ao centro */
  justify-content: center; /* Centraliza horizontalmente */
  gap: 10px; /* Espaço entre os elementos */
  margin-top: 10px; /* Espaço acima do bloco */
}

/* Logo suave */
.logo-suave {
  height: 24px; /* Altura fixa do logo */
  opacity: 0.6; /* Deixa o logo mais suave/menos chamativo */
  transition: opacity 0.3s ease; /* Transição suave ao mudar opacidade */
}

/* Efeito hover no logo */
.logo-suave:hover {
  opacity: 1; /* Destaca o logo ao passar o mouse */
}
/* ===================== ALINHAMENTO FINAL DAS COLUNAS DO GRID ===================== */
.perfil-container,
.conteudo-principal,
.lei-container {
  height: 100%;
  display: flex;
  flex-direction: column;
}

/* ===================== AJUSTES FINAIS PARA ALINHAMENTO E VISIBILIDADE ===================== */

/* Garante que as colunas do grid cresçam igualmente */
.perfil-container,
.conteudo-principal,
.lei-container {
  display: flex;
  flex-direction: column;
  height: 100%;
  flex-grow: 1;
  min-height: 100%;
}

/* Evita corte de conteúdo nos anúncios */
#anuncios-perfil-container {
  flex-grow: 1;
  flex-shrink: 0;
  flex-basis: auto;
  overflow: visible;
}
/* ==================================================
   AJUSTES FINAIS: ALINHAMENTO DE COLUNAS E ANÚNCIOS
   ================================================== */

/* 1) Força o mesmo comportamento flex nas 3 colunas do grid */
.perfil-container,
.conteudo-principal,
.lei-container {
  display: flex;
  flex-direction: column;
  height: 100%;       /* Ocupa toda a célula do grid */
  flex-grow: 1;       /* Cresce igualmente */
}

/* 2) Divide o espaço da coluna esquerda: perfil fixa + anúncios flex */
.perfil-container > .quem-sou {
  flex: 0 0 auto;     /* Perfil mantém seu tamanho natural */
}

#anuncios-perfil-container {
  flex: 1 1 auto;     /* Anúncios ocupam o resto */
  overflow-y: auto;   /* Scroll se passar da altura */
}

/* ==================================================
   BLOCO DE ANÚNCIOS (COLUNA ESQUERDA)
   ================================================== */

/* Container de anúncios */
#anuncios-perfil-container {
  margin-top: 2rem;
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

/* Card de publicidade */
.publicidade {
  background-color: #f0f0f0;
  padding: 1rem;
  border-radius: 6px;
  box-shadow: 0 0 6px rgba(0,0,0,0.05);
  text-align: center;
  font-size: 0.9rem;
  color: #444;
}

/* Logo / foto da equipe dentro do anúncio */
.secao-publicidade .logo-suave {
  width: 100%;
  max-width: 250px;   /* Limita largura para não estourar o card */
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  margin: 0 auto 1rem;
  display: block;
  object-fit: cover;
  opacity: 0.85;
  transition: opacity 0.3s ease;
}

.secao-publicidade .logo-suave:hover {
  opacity: 1;
}

/* Botões de redes sociais */
.botao-instagram,
.botao-whatsapp {
  display: inline-block;
  margin-top: 0.5rem;
  color: #0066cc;
  text-decoration: underline;
}

.botao-instagram:hover,
.botao-whatsapp:hover {
  text-decoration: none;
}

/* ==================================================
   POWERED-BY (FOOTER)
   ================================================== */

/* Logo no “© Equipe Powered By” */
.powered-by .logo-suave {
  height: 24px;        /* Pequena no rodapé */
  width: auto;
  opacity: 0.6;
  transition: opacity 0.3s ease;
}

.powered-by .logo-suave:hover {
  opacity: 1;
}

.conteudo-principal {
  font-size: 1.2rem; /* ou até 1.2rem se quiser mais impacto */
  line-height: 1.8;
}

.citacao-precedente {
  background-color: #f9f9f9;
  border-left: 4px solid #8b0000;
  padding: 1.5rem;
  margin-top: 2rem;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  font-family: 'Georgia', serif;
  color: #333;
}

.citacao-precedente h4 {
  font-size: 1.2rem;
  color: #8b0000;
  margin-bottom: 1rem;
  font-weight: bold;
}

.citacao-precedente blockquote {
  margin: 0;
  padding-left: 1rem;
  border-left: 3px solid #ccc;
  font-style: italic;
  color: #444;
}

.citacao-precedente blockquote p {
  font-size: 1.1rem;
  line-height: 1.6;
}

.citacao-precedente footer {
  margin-top: 0.5rem;
  font-size: 0.95rem;
  color: #666;
}

.citacao-precedente p {
  margin-top: 1rem;
  font-size: 0.95rem;
  line-height: 1.6;
}

.citacao-precedente a {
  color: #8b0000;
  text-decoration: underline;
  font-weight: bold;
}
/* ===================== CONTAINER GERAL DA LEI ===================== */
.lei-container {
  width: 100%;
  max-width: 1000px;
  margin: 2rem auto;
  padding: 1.5rem;
  background-color: #fff;
  border-left: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

/* ===================== ARTICLE E SEÇÃO ===================== */
.qual_foi_lei_usada,
.secao-lei-usada {
  width: 100%;
}

.container-lei-usada {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

/* ===================== TEXTO JURÍDICO ===================== */
.mensagem-lei {
  color: #333;
  line-height: 1.6;
}

.mensagem-lei h2,
.mensagem-lei h3,
.mensagem-lei h4 {
  margin-bottom: 0.5rem;
  font-weight: bold;
}

.mensagem-lei h2 {
  font-size: 1.4rem;
  color: #0055aa;
}

.mensagem-lei h3 {
  font-size: 1.2rem;
  color: #0077cc;
  margin-top: 1.5rem;
}

.mensagem-lei h4 {
  font-size: 1.1rem;
  color: #444;
  margin-top: 1rem;
}

.destaque {
  background-color: #e0f0ff;
  padding: 0.2rem 0.5rem;
  border-radius: 4px;
  font-weight: bold;
  color: #b22222;
}

/* ===================== LISTAS E LINKS ===================== */
.mensagem-lei ul {
  padding-left: 1.5rem;
}

.mensagem-lei li {
  margin-bottom: 0.5rem;
}

.mensagem-lei a {
  color: #0066cc;
  text-decoration: underline;
}

.mensagem-lei a:hover {
  text-decoration: none;
}

/* ===================== ASIDE: CITAÇÃO E IMAGEM ===================== */
.citacao-precedente {
  background-color: #f9f9f9;
  border-left: 4px solid #8b0000;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  font-family: 'Georgia', serif;
  color: #333;
}

.citacao-precedente h4 {
  font-size: 1.2rem;
  color: #8b0000;
  margin-bottom: 1rem;
}

.citacao-precedente blockquote {
  margin: 0;
  padding-left: 1rem;
  border-left: 3px solid #ccc;
  font-style: italic;
  color: #444;
}

.citacao-precedente blockquote p {
  font-size: 1.1rem;
  line-height: 1.6;
}

.citacao-precedente footer {
  margin-top: 0.5rem;
  font-size: 0.95rem;
  color: #666;
}

.citacao-precedente p {
  margin-top: 1rem;
  font-size: 0.95rem;
  line-height: 1.6;
}

.citacao-precedente a {
  color: #8b0000;
  text-decoration: underline;
  font-weight: bold;
}

/* ===================== IMAGEM E LEGENDA ===================== */
.representacao-hopeup {
  margin-top: 1.5rem;
  text-align: center;
}

.representacao-hopeup img {
  width: 100%;
  max-width: 600px;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.representacao-hopeup figcaption {
  margin-top: 0.5rem;
  font-style: italic;
  font-size: 0.9rem;
  color: #555;
}

/* ===================== LINK FINAL SUTIL ===================== */
.link-sutil {
  text-align: center;
  margin-top: 1rem;
}

.link-sutil a {
  color: #0066cc;
  font-weight: bold;
  text-decoration: none;
}

.link-sutil a:hover {
  text-decoration: underline;
}

html:
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blog Dr. Leandro Alves de Souza</title>
  <link rel="stylesheet" href="blog_le_front\blog_le_styles.css">
</head>
<body>

  <header>
    <div id="banner"></div>
    <!--<nav>
         Menu futuro 
    </nav> -->
  </header>


  <!-- Main -->
  <main>

    <!-- Parte 1: Título em Flexbox -->
    <section class="titulo-flex">
      <h1>Descrição do Caso</h1>
    </section>

    <!-- Parte 2: Conteúdo em CSS Grid -->
    <section class="conteudo-grid">

      <!-- Article ► Sobre o Dr. Leandro -->
      <div class="perfil-container"> <!-- Container geral da seção institucional -->

        <article class="quem-sou"> <!-- Bloco semântico informativo -->
          <section class="secao-quem"> <!-- Seção interna -->
            <div class="container-quem-sou"> <!-- Container interno -->

              <!-- Perfil Institucional -->
              <div class="perfil-dr-leandro">
                <img src="blog_le_front/imagens_front_blog_le/foto_le.webp" alt="Dr. Leandro Alves de Souza" loading="lazy">

                <div class="mensagem">
                  <h2><strong>Dr. Leandro Alves de Souza</strong></h2>
                  <p><em>Sócio-fundador do escritório LAS Advocacia e Consultoria Jurídica</em>, com atuação em mais de 2.000 processos em São Paulo, Rio de Janeiro e Distrito Federal.</p>

                  <h3><span class="destaque">Missão e Atuação</span></h3>
                  <p>
                    Nossa missão é defender os direitos dos trabalhadores com excelência, comprometimento e responsabilidade.<br>
                    Atuamos de forma especializada em <strong>Direito do Trabalho</strong>, com foco exclusivo na proteção jurídica de empregados que enfrentam situações de injustiça, abusos ou irregularidades nas relações de trabalho.<br>
                    Nossa equipe está preparada para garantir que você tenha o suporte necessário para enfrentar esse momento com segurança jurídica.
                  </p>
                </div> <!-- Fim da div .mensagem -->
              </div> <!-- Fim da div .perfil-dr-leandro -->

            </div> <!-- Fim da div .container-quem-sou -->
          </section> <!-- Fim da section .secao-quem -->
        </article> <!-- Fim do article .quem-sou -->

        <!-- Bloco de anúncios lateral -->
        <aside id="anuncios-perfil-container" aria-label="Seção de anúncios publicitários no Grid do perfil">
          <div class="anuncio-bloco-perfil"></div>

          <section class="secao-publicidade">
            <h2 class="titulo-publicidade">📢 Publicidades</h2>
            <div class="container-publicidade">

              <!-- ANÚNCIO 1 -->
              <div class="publicidade Powered by HopeUp 7.DEV">
                <img src="blog_le_front/imagens_front_blog_le/icone_hopeup.png" alt="Logo HopeUp 7.DEV" class="logo-suave" loading="lazy">
                <div class="mensagem">
                  <p><strong>Hope Up 7.DEV</strong> 💥</p>
                  <p>
                    Desenvolvido com <strong>dedicação autodidata</strong>, <strong>capricho técnico</strong> e uma <strong>resiliência silenciosa</strong>, o sistema da equipe <em>Powered by Hope Up 7.DEV</em> reflete a jornada de quem constrói com propósito. Cada linha de código escrita por <strong>HopeUp 7.DEV</strong> carrega não apenas técnica refinada — como modularização por contexto, rastreio semântico e arquitetura responsiva — mas também uma sensibilidade sutil, capaz de perceber o que não está dito. A proposta de <strong>registro único por caso</strong> permite que cada situação, seja ela jurídica, médica, educacional ou administrativa, seja tratada com exclusividade e profundidade. Essa abordagem pode ser aplicada em ramos como <em>consultoria jurídica</em>, <em>catálogo de históricos médico-cirúrgicos por caso individual e personalizado</em>, <em>gestão de prontuários clínicos</em>, <em>acompanhamento pedagógico</em> e até <em>suporte técnico personalizado</em>, sempre respeitando a individualidade de cada história.<br>Entre em contato e descubra como podemos transformar sua ideia em realidade em books de mostruários físicos e digitais!
                  </p>
                  <h3><span class="destaque">Localização e Contato</span></h3>
                  <p>Santana, São Paulo – SP<br>
                    <strong>Instagram:</strong>  
                    <a href="https://www.instagram.com/hopeup47/" target="_blank" class="botao-instagram">📷 Siga-nos</a><br>
                    <strong>WhatsApp:</strong> 
                    <a href="https://wa.me/5511953339198" target="_blank" class="botao-whatsapp">📲 HopeUp 7.DEV</a>
                  </p>
                </div>
              </div>

              <!-- Adicione mais blocos conforme necessário -->

            </div> <!-- Fim da div .container-publicidade -->
          </section> <!-- Fim da section .secao-publicidade -->
        </aside> <!-- Fim do aside .anuncios-perfil-container -->

      </div> <!-- Fim da div .perfil-container -->



       <article class="conteudo-principal">

        <h2><strong><em>Madame Anônima e a Reviravolta Jurídica</em></strong></h2>

        <p>
          <em>Ela chegou aflita.</em> Os olhos de <strong>'Madame Anônima'</strong> carregavam o peso de quem não dormia há dias. A sentença imposta pelo <strong>'órgão de execução penal'</strong> determinava a <strong>prestação de serviços à comunidade</strong> — uma pena legítima, mas impraticável diante da sua realidade.
        </p>

        <p>
          Mãe solo, trabalhadora autônoma, sustentava dois filhos com o que arrecadava diariamente. Cumprir a pena significava abrir mão do trabalho. E abrir mão do trabalho significava não alimentar sua família.
        </p>

        <p>
          Sentada diante da mesa de atendimento, ela hesitou. <em>“Eu não quero fugir da lei... só não sei como cumprir sem perder tudo.”</em> — disse com a voz embargada. <strong>'Dr. Leandro Alves de Souza'</strong> a escutava com atenção, sem interromper. Ele sabia que ali não havia apenas um caso jurídico — havia uma vida em risco.
        </p>

        <p>
          <em>“Será que posso pagar em dinheiro ao invés de prestar serviço?”</em> — ela perguntou, quase como quem pede licença para continuar existindo.
        </p>

        <h3><strong><em>O Obstáculo: A Lei e o Juiz</em></strong></h3>

        <p>
          <strong>'Dr. Leandro'</strong> sabia que a legislação brasileira não previa, como regra, a substituição da prestação de serviços por prestação pecuniária após o trânsito em julgado. O <strong>'juiz de execução penal'</strong> não poderia simplesmente converter a pena.
        </p>

        <p>
          O escritório se encheu de códigos e jurisprudências. Ele revisava cada artigo, cada precedente, cada brecha possível. A tensão era técnica — mas também humana.
        </p>

        <ul>
          <li><strong>Código Penal – Art. 44, §2º:</strong> permite a substituição da pena privativa de liberdade por:
            <ul>
              <li>Prestação pecuniária</li>
              <li>Prestação de serviços à comunidade</li>
              <li>Interdição de direitos</li>
            </ul>
            <em>Mas não autoriza a troca entre elas após a sentença.</em>
          </li>
          <li><strong>Lei de Execução Penal – Art. 148:</strong> permite ajustes na forma de cumprimento, mas não a substituição por outra modalidade.</li>
        </ul>

        <h3><strong><em>A Estratégia: A Lei Viva</em></strong></h3>

        <p>
          <strong>'Dr. Leandro'</strong> mergulhou nos precedentes. Encontrou decisões do <strong>'Superior Tribunal de Justiça'</strong> que admitiam exceções — casos em que a prestação de serviços se tornava inviável por motivos físicos, profissionais ou sociais.
        </p>

        <p>
          Com base no <strong>Art. 149, inciso III, da LEP</strong>, construiu sua tese:
          <br><em>“Para 'Madame Anônima', a impossibilidade é concreta. Não há como conciliar a pena com a sobrevivência.”</em>
        </p>

        <p>
          A <strong>prestação pecuniária</strong>, nesse contexto, não era um privilégio — era uma <strong>necessidade</strong>. Ele redigiu a petição com precisão e empatia, como quem escreve não apenas para convencer, mas para proteger.
        </p>

        <h3><strong><em>O Desfecho: Justiça com Humanidade</em></strong></h3>

        <p>
          O dia da audiência chegou. A sala era fria, silenciosa, marcada por olhares atentos e papéis empilhados. <strong>'Madame Anônima'</strong> sentou-se com as mãos trêmulas. <strong>'Dr. Leandro'</strong> estava ao seu lado, firme.
        </p>

        <p>
          Diante do <strong>'juiz de execução penal'</strong>, a defesa foi clara: não se tratava de escapar da pena, mas de compatibilizar a punição com a realidade. A alternativa financeira permitiria que ela mantivesse sua rotina, continuasse trabalhando, estudando, contribuindo com a sociedade.
        </p>

        <p>
          A sala fez silêncio. O <strong>'juiz'</strong> folheou os autos, releu os fundamentos, ponderou os elementos do caso concreto. E então, reconhecendo a excepcionalidade, <strong>autorizou a conversão</strong>.
        </p>

        <p>
          <em>A reviravolta trouxe alívio.</em> A lei, vista e aplicada com humanidade, havia permitido que justiça fosse feita sem sacrificar a dignidade.
        </p>

      </article>



        <!-- Article ► Sobre a Lei usada no conteúdo principal -->
    <div class="lei-container">

      <article class="qual_foi_lei_usada">
        <section class="secao-lei-usada">
          <div class="container-lei-usada">
            <div class="mensagem-lei">

              <h2><strong>Dr. Leandro Alves de Souza</strong></h2>
              <p><em>Sócio-fundador do escritório LAS Advocacia e Consultoria Jurídica</em>, com atuação em mais de 2.000 processos em São Paulo, Rio de Janeiro e Distrito Federal. Reconhecido por sua capacidade de unir técnica jurídica com sensibilidade social, Dr. Leandro atua em causas que exigem mais do que conhecimento: exigem escuta, estratégia e coragem.</p>

              <h3><span class="destaque">Aplicação Jurídica com Responsabilidade</span></h3>
              <p>
                Em casos como o de <strong>'Madame Anônima'</strong>, a pena imposta — prestação de serviços à comunidade — colocava em risco a subsistência da condenada. A atuação jurídica não se limitou à defesa formal: foi construída com base em uma leitura profunda da realidade, da legislação e da jurisprudência. <strong>Dr. Leandro</strong> compreendeu que o papel do advogado é também o de mediador entre o texto da lei e a vida concreta.
              </p>

              <h4>⚖️ O que diz a Lei Brasileira?</h4>
              <p>
                A prestação de serviços à comunidade é uma das penas restritivas de direitos previstas no <strong>Código Penal Brasileiro</strong>, conforme o <strong>Art. 44</strong>. Ela pode ser aplicada como substituição à pena privativa de liberdade em casos de menor gravidade.
              </p>
              <p>
                No entanto, a substituição dessa pena por prestação pecuniária (pagamento em dinheiro) <strong>não está prevista como regra legal após o trânsito em julgado</strong>. Ou seja, não é permitido ao juiz da execução penal trocar a prestação de serviços por pagamento, <strong>salvo em situações excepcionais</strong>, quando há comprovação de impossibilidade real de cumprimento da pena.
              </p>

              <h4>📘 Base Legal</h4>
              <ul>
                <li><strong>Código Penal – Art. 44, §2º</strong><br>
                  Estabelece que a pena privativa de liberdade pode ser substituída por:
                  <ul>
                    <li>Prestação pecuniária</li>
                    <li>Prestação de serviços à comunidade</li>
                    <li>Interdição de direitos</li>
                  </ul>
                  Mas não permite a troca entre elas após a sentença.
                </li>
                <li><strong>Lei de Execução Penal (LEP) – Art. 148</strong><br>
                  Permite ao juiz ajustar a forma de cumprimento da pena de prestação de serviços à comunidade às condições pessoais do condenado, mas não autoriza a substituição por outra modalidade.
                  <br>
                  🔗 <a href="https://www.planalto.gov.br/ccivil_03/leis/l7210.htm" target="_blank">Texto oficial da LEP no site do Planalto</a>
                </li>
              </ul>

              <h4>🧠 Jurisprudência e Exceções Estratégicas</h4>
              <p>
                O <strong>Superior Tribunal de Justiça (STJ)</strong> tem reafirmado que a conversão da prestação de serviços em pagamento não é regra. Contudo, em casos excepcionais — como incapacidade física, incompatibilidade profissional ou risco social — alguns tribunais têm autorizado a mudança, com base no <strong>Art. 149, inciso III, da LEP</strong>.
              </p>
              <p>
                📌 Exemplo:<br>
                “A conversão da pena de prestação de serviços à comunidade em prestação pecuniária pode ser admitida em situações excepcionais, desde que devidamente fundamentada e ajustada às condições pessoais do condenado.” — TJ-DF, Agravo em Execução Penal
              </p>

              <h4>✅ Conclusão</h4>
              <p>
                A substituição da prestação de serviços por pagamento <strong>não é prevista como direito automático</strong>, mas pode ser solicitada ao juiz da execução penal, com base em <strong>provas concretas de impossibilidade de cumprimento</strong>. O juiz pode então decidir, com base na LEP, se há justificativa legal e social para essa conversão.
              </p>
              <p>
                <strong>Dr. Leandro</strong> atua com firmeza e humanidade, defendendo que o direito deve ser aplicado com técnica, mas também com respeito à realidade de cada pessoa. Sua prática jurídica é marcada pela busca de soluções que não apenas resolvam o processo — mas que preservem a dignidade.
              </p>

            </div>
          </div>
        </section>

        <aside class="citacao-precedente">
          <h4>📜 Vozes da Advocacia</h4>
          <blockquote>
            <p><em>“A justiça atrasada não é justiça; é injustiça qualificada e manifesta.”</em></p>
            <footer>— <strong>Ruy Barbosa</strong>, jurista, advogado e defensor das liberdades civis</footer>
          </blockquote>
          <p>
            Essa frase ecoa com força nos corredores da execução penal. Quando o sistema demora a reconhecer a excepcionalidade de um caso, como no de <strong>'Madame Anônima'</strong>, o conflito gerado pela falta de harmonização entre família/trabalho e prestação de serviços à comunidade se torna evidente e prejudicial, pois no cumprimento da Lei, tem de haver reflexão que parte do réu <em>- reflexão esta que gera amadurecimento -</em>, mas quando o princípio do bem estar da família é desconsiderado, a situação se agrava e o ensinamento que tem de brotar do cumprir a Lei, se torna raso e superficial. A atuação jurídica precisa ser ágil, sensível e fundamentada. É isso que move profissionais como <strong>Dr. Leandro Alves de Souza</strong>, que não apenas interpretam a lei, mas a aplicam com responsabilidade e humanidade.
          </p>
          <p>
            🔗 <a href="https://www.casaruibarbosa.gov.br/frases-e-pensamentos" target="_blank">Fonte: Fundação Casa de Rui Barbosa</a>
          </p>

          <figure class="representacao-hopeup">
            <img src="blog_le_front/imagens_front_blog_le/le_ruy.png" alt="Representação de Dr. Leandro e Ruy Barbosa" class="le_ruy_barb" loading="lazy">
            <figcaption><em>Representação criada pela equipe HopeUp 7.DEV:<br> Dr. Leandro em meditação jurídica diante do legado de Ruy Barbosa.</em></figcaption>
          </figure>

          <p class="link-sutil">
            <a href="https://advlasadvocacia.com.br" target="_blank">🔗 LAS Advocacia</a>
          </p>
        </aside>
      </article>

    </div> <!-- Fim da div .lei-container -->


    </section> <!-- Fim da section .conteudo-grid -->

    <section class="imagem-flex">
      <img src="blog_le_front\imagens_front_blog_le\retrato_atemporal_le.png" alt="Dr. Leandro em ação" loading="lazy">
    </section>

  </main>

  <!-- Rodapé -->
    <footer class="footer">
    <p>© 2025 Blog Dr. Leandro Alves de Souza - Todos os direitos reservados</p>
    <div class="powered-by">
        <img src="blog_le_front/imagens_front_blog_le/icone_hopeup.png" alt="Logo HopeUp 7.DEV" class="logo-suave" loading="lazy">
        <span>© Equipe Powered By HopeUp 7.DEV</span>
    </div>
    </footer>

</body>
</html>

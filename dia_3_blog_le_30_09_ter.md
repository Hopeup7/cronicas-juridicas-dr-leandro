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
                <img src="blog_le_front/imagens_front_blog_le/foto_le.webp" alt="Dr. Leandro Alves de Souza">

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
                <img src="blog_le_front/imagens_front_blog_le/icone_hopeup.png" alt="Logo HopeUp 7.DEV" class="logo-suave">
                <div class="mensagem">
                  <p><strong>Hope Up 7.DEV</strong> 💥</p>
                  <h3><span class="destaque">Localização e Contato</span></h3>
                  <p>
                    Travessa José Sancho, 40<br>
                    Santana, São Paulo – SP<br>
                    <strong>Instagram:</strong>  
                    <a href="https://www.instagram.com/hopeup47/" target="_blank" class="botao-instagram">📷 Siga-nos</a><br>
                    <strong>WhatsApp:</strong> 
                    <a href="https://wa.me/5511953339198" target="_blank" class="botao-whatsapp">📲 Du</a>
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
          Foi por isso que ela procurou <strong>'Dr. Leandro Alves de Souza'</strong>. Através de amigos e redes sociais, chegou até ele com uma pergunta carregada de desespero:
          <br><em>“Será que posso pagar em dinheiro ao invés de prestar serviço?”</em>
        </p>

        <h3><strong><em>O Obstáculo: A Lei e o Juiz</em></strong></h3>

        <p>
          <strong>'Dr. Leandro'</strong> sabia que a legislação brasileira não previa, como regra, a substituição da prestação de serviços por prestação pecuniária após o trânsito em julgado. O <strong>'juiz de execução penal'</strong> não poderia simplesmente converter a pena.
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
          A <strong>prestação pecuniária</strong>, nesse contexto, não era um privilégio — era uma <strong>necessidade</strong>.
        </p>

        <h3><strong><em>O Desfecho: Justiça com Humanidade</em></strong></h3>

        <p>
          Diante do <strong>'juiz de execução penal'</strong>, a defesa foi firme. Não se tratava de escapar da pena, mas de cumpri-la de forma compatível com a realidade.
        </p>

        <p>
          A alternativa financeira permitiria que <strong>'Madame Anônima'</strong> mantivesse seu trabalho, sustentasse seus filhos e ainda cumprisse sua obrigação legal.
        </p>

        <p>
          A sala ficou em silêncio. O <strong>'juiz'</strong> folheou os autos, releu os fundamentos, ponderou os riscos. E então, reconhecendo a excepcionalidade do caso, <strong>autorizou a conversão</strong>.
        </p>

        <p>
          <em>A reviravolta estava feita.</em> A lei, viva e aplicada com humanidade, havia permitido que justiça fosse feita sem sacrificar a dignidade.
        </p>

      </article>


        <!-- Article ► Sobre a Lei usada no conteúdo principal -->
    <div class="lei-container"> <!-- Container geral da seção institucional -->

        <article class="qual_foi_lei_usada"> <!-- Bloco semântico informativo -->

          <section class="secao-lei-usada"> <!-- Seção interna -->

            <div class="container-lei-usada"> <!-- Container para layout interno -->

              <div class="mensagem-lei"> <!-- Bloco de texto jurídico -->

                <h2><strong>Dr. Leandro Alves de Souza</strong></h2>
                <p><em>Sócio-fundador do escritório LAS Advocacia e Consultoria Jurídica</em>, com atuação em mais de 2.000 processos em São Paulo, Rio de Janeiro e Distrito Federal.</p>

                <h3><span class="destaque">Reviravolta Jurídica: A Lei Viva</span></h3>
                <p>
                  Du, aqui está o que a legislação brasileira diz sobre a possibilidade de substituir a <strong>prestação de serviços à comunidade</strong> por <strong>pagamento de indenização (prestação pecuniária)</strong>:
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

                <h4>🧠 Jurisprudência e Exceções</h4>
                <p>
                  O <strong>Superior Tribunal de Justiça (STJ)</strong> tem decidido que não é possível substituir a prestação de serviços por pagamento após a condenação. No entanto, <strong>em casos excepcionais</strong>, como quando há comprovação de incapacidade física, incompatibilidade profissional ou risco social, alguns tribunais têm autorizado a conversão, com base no <strong>Art. 149, inciso III, da LEP</strong>, que permite ajustes na execução da pena.
                </p>
                <p>
                  📌 Exemplo:<br>
                  “A conversão da pena de prestação de serviços à comunidade em prestação pecuniária pode ser admitida em situações excepcionais, desde que devidamente fundamentada e ajustada às condições pessoais do condenado.” — TJ-DF, Agravo em Execução Penal
                </p>

                <h4>✅ Conclusão</h4>
                <p>
                  A substituição da prestação de serviços por pagamento <strong>não é prevista como direito automático</strong>, mas pode ser solicitada ao juiz da execução penal, com base em <strong>provas concretas de impossibilidade de cumprimento</strong>. O juiz pode então decidir, com base na LEP, se há justificativa legal e social para essa conversão.
                </p>

              </div> <!-- Fim da div .mensagem-lei -->

            </div> <!-- Fim da div .container-lei-usada -->

          </section> <!-- Fim da section .secao-lei-usada -->

        </article> <!-- Fim do article .qual_foi_lei_usada -->

      </div> <!-- Fim da div .lei-container -->
    </section> <!-- Fim da section .conteudo-grid -->

    <section class="imagem-flex">
      <img src="blog_le_front\imagens_front_blog_le\retrato_atemporal_le.png" alt="Dr. Leandro em ação">
    </section>

  </main>

  <!-- Rodapé -->
    <footer class="footer">
    <p>© 2025 Blog Dr. Leandro Alves de Souza - Todos os direitos reservados</p>
    <div class="powered-by">
        <img src="blog_le_front/imagens_front_blog_le/icone_hopeup.png" alt="Logo HopeUp 7.DEV" class="logo-suave">
        <span>© Equipe Powered By HopeUp 7.DEV</span>
    </div>
    </footer>

</body>
</html>

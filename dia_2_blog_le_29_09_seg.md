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

       <!-- 2. PUBLICIDADES -->
      <div class="publicidade-container">
        <aside id="publicidade-esquerda" aria-label="Seção de anúncios publicitários">
          <section class="secao-publicidade">
            <h2 class="titulo-publicidade">📢 Publicidades</h2>
              <div class="container-publicidade">
                <!-- ANÚNCIO 1 -->
                  <div class="publicidade corte">
                      <img src="temp_front/imagens/corte_public.webp" alt="Corte de cabelo Santana">
                        <div class="mensagem">
                          <p><strong>Junior - O Natural dos Cortes de Cabelo</strong> 💥</p>
                            <h3><span class="destaque">Localização e Contato</span></h3>
                            <p>
                            Rua Alfredo Pujol, em frente ao Colégio Barão Homem de Mello<br>
                            Santana, São Paulo – SP<br>
                            <strong>Instagram:</strong>  
                            <a href="https://www.instagram.com/saravaleriohair/" target="_blank" class="botao-instagram">📷 Siga-nos</a><br>
                            <strong>WhatsApp:</strong> 
                            <a href="https://wa.me/5511988243521" target="_blank" class="botao-whatsapp">📲 Junior</a>
                            <a href="https://wa.me/5511952395540" target="_blank" class="botao-whatsapp">📲 Sara Valerio Hair</a>
                          </p>
                        </div>
                  </div>
              </div>
          </section>
        </aside>
      </div>

        <article class="conteudo-principal">
          <p>Conteúdo principal do caso, narrado com leveza, suspense e técnica.</p>
          <!-- Aqui virão os links individuais para cada caso -->
        </article>

        <aside id="publicidade-direita" aria-label="Seção de anúncios publicitários">
          <section class="secao-publicidade">
            <h2 class="titulo-publicidade">📢 Publicidades</h2>
              <div class="publicidade funilaria">
                <img src="temp_front/imagens/public_fun_dan.jpg" alt="Serviço de funilaria">
                  <div class="mensagem">
                    <p><strong>Excelência em reparos automotivos na Zona Norte de SP</strong> 💥</p>
                    <h3><span class="destaque">Localização e Contato</span></h3>
                    <p>
                      Rua Padre João Gualberto, 440A – Imirim, São Paulo – SP<br>
                      <strong>Instagram:</strong>  
                      <a href="https://instagram.com/_OFICINA3D" target="_blank" class="botao-instagram">📷 Siga-nos</a><br>
                      <strong>WhatsApp:</strong> 
                      <a href="https://wa.me/5511974026145" target="_blank" class="botao-whatsapp">📲 Fale conosco</a>
                    </p>
                  </div>
                </div>
              </div>
          </section>
        </aside>

    </section>

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

css:
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

/* ===================== PARTE 2: GRID COM PUBLICIDADE E CONTEÚDO ===================== */
.conteudo-grid {
  display: grid; /* Ativa Grid Layout */
  grid-template-columns: 0.7fr 3.3fr 1fr; /* Coluna esquerda fina, centro amplo, direita média */
  column-gap: 2rem; /* Aumenta o espaço horizontal entre as colunas */
  row-gap: 1rem; /* Espaço vertical entre linhas, se houver */
  /*gap: 1rem;  Espaço entre colunas */
  padding: 2rem; /* Espaço interno */
  width: 100%; /* Ocupa toda a largura */
  max-width: 1200px; /* Limita largura máxima */
  margin: 0 auto; /* Centraliza horizontalmente */
  box-sizing: border-box; /* Inclui padding na largura */
}

/* Coluna esquerda: publicidade fina */
.publicidade-esquerda {
  background-color: #fdf6e3; /* Tom claro estilo anúncio */
  padding-right: -1rem; /* Espaço interno */
  font-size: 0.85rem; /* Texto menor e discreto */
  color: #444; /* Cor suave para leitura */
  border-radius: 6px; /* Cantos arredondados */
  box-shadow: 0 0 8px rgba(0,0,0,0.05); /* Sombra leve */
  display: flex; /* Flexbox para centralizar conteúdo */
  flex-direction: column; /* Empilha verticalmente */
  justify-content: center; /* Centraliza verticalmente */
  align-items: center; /* Centraliza horizontalmente */
  text-align: center; /* Centraliza texto */
}
/* Imagem pequena dentro da publicidade (se usada) */
.publicidade-esquerda img {
  width: 60px; /* Tamanho fixo da imagem */
  margin-bottom: 0.5rem; /* Espaço abaixo da imagem */
}

/* Coluna central: conteúdo principal */
.conteudo-principal {
  background-color: #fff; /* Fundo branco para destaque */
  padding: 2rem; /* Espaço interno */
  border-radius: 8px; /* Cantos arredondados */
  box-shadow: 0 0 10px rgba(0,0,0,0.05); /* Sombra leve */
  box-sizing: border-box; /* Inclui padding na largura */
}

/* Coluna direita: descrição ou parcerias */
.publicidade-direita {
  background-color: #f0f0f0; /* Fundo claro */
  padding-left: 1rem; /* Espaço interno */
  font-size: 0.9rem; /* Tamanho de texto leve */
  color: #777; /* Cor suave para texto */
  border-radius: 8px; /* Cantos arredondados */
  box-shadow: 0 0 10px rgba(0,0,0,0.05); /* Sombra leve */
  box-sizing: border-box; /* Inclui padding na largura */
}
/* Imagem pequena dentro da publicidade (se usada) */
.publicidade-direita img {
  width: 60px; /* Tamanho fixo da imagem */
  margin-bottom: 0.5rem; /* Espaço abaixo da imagem */
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
  height: 800px; /* Mantém proporção */
  max-height: 800px; /* Limita altura máxima */
  object-fit: fill; /* Preenche sem distorcer */
  border-radius: 10px; /* Cantos arredondados */
  box-shadow: 0 4px 12px rgba(0,0,0,0.1); /* Sombra suave */
}

/* ===================== ESPAÇAMENTO ENTRE SEÇÕES ===================== */
main > section {
  margin-bottom: 2rem; /* Espaço entre seções do main */
}


/* ======== Rodapé ======== */
.footer {
  text-align: center; /* Centraliza o conteúdo do rodapé */
  padding: 20px; /* Espaçamento interno */
  background-color: #3e3d3d; /* Fundo cinza escuro */
  font-size: 14px; /* Texto menor */
  color: #eceef3; /* Texto em tom claro para contraste */
}

/* ======== Container "Powered by" ======== */
.powered-by {
  display: flex; /* Layout flexível */
  align-items: center; /* Alinha verticalmente ao centro */
  justify-content: center; /* Centraliza horizontalmente */
  gap: 10px; /* Espaço entre os elementos */
  margin-top: 10px; /* Espaço acima do bloco */
}

/* ======== Logo suave ======== */
.logo-suave {
  height: 24px; /* Altura fixa do logo */
  opacity: 0.6; /* Deixa o logo mais suave/menos chamativo */
  transition: opacity 0.3s ease; /* Transição suave ao mudar opacidade */
}

/* ======== Efeito hover no logo ======== */
.logo-suave:hover {
  opacity: 1; /* Destaca o logo ao passar o mouse */
}


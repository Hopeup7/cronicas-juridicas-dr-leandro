/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/*← CSS pai que importa todos os módulos*/
/*Arquivo principal que importa todos os módulos acima*/

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ===================== RESET E BASE ===================== */
@import url('reset.css');
@import url('base.css');
@import url('header.css');
/* ===================== COMPONENTES REUTILIZÁVEIS ===================== */
@import url('componentes.css');

/* ===================== SEÇÃO 1 EM FLEXBOX ===================== */

@import url('main_parte_1_flex.css');


/* ===================== ESTRUTURA PRINCIPAL DO GRID ===================== */
@import url('main_pai_conteudo_grid.css');

/* ===================== BLOCOS DA COLUNA ESQUERDA ===================== */
@import url('main_grid_qual_foi_lei_usada.css');
@import url('main_grid_citacao_precedente.css');

/* ===================== COLUNA CENTRAL: CRÔNICA ===================== */
@import url('main_grid_conteudo_principal.css');

/* ===================== COLUNA DIREITA: LEI E CITAÇÃO ===================== */
@import url('article_quem_sou.css');
@import url('aside_perfil_ajuda.css');
@import url('aside_anuncios_perfil_container.css');
@import url('aside_perfil_anuncie_aqui.css');

/* ===================== SEÇÃO FINAL DE IMAGEM ===================== */
@import url('main_parte_3_imagem_flex.css');

/* ===================== RODAPÉ ===================== */
@import url('footer.css');

/* ===================== RESPONSIVIDADE ===================== */
@import url('media-queries.css');

/*← Reset universal de estilos*/
/*Resetar estilos padrão dos navegadores*/

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

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
  font-size: 18px; /* ou 1.125rem */
}

/* ← Tipografia, cores e elementos genéricos*/
/*Estilos básicos globais (fonte, cor, espaçamento)*/

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

main > section {
  margin-bottom: 3rem; /* Espaço entre seções do main */
}
html, body {
  overflow-x: hidden; /* Evita scroll horizontal */
  max-width: 100%;
}
*, *::before, *::after {
  box-sizing: border-box;
}

/*← Estilos do banner e topo do site*/
/*Cabeçalho do site (banner, logo, topo)*/

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ===================== BANNER (mantido) ===================== */
#banner {
  height: 550px; /* Altura fixa para o banner */
  background-image: url("blog_le_front/imagens_front_blog_le/banner.png"); /* Imagem de topo */
  background-position: center; /* Centraliza a imagem */
  background-size: 100% 100%; /* Preenche sem distorcer */
  background-repeat: no-repeat; /* Evita repetição da imagem */
}

/*Aqui eu colcoarei todas as classes que se repetem*/

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/


.destaque {
  background-color: #e0f0ff; /* Fundo azul claro para chamar atenção sem agressividade */
  padding: 0.2rem 0.5rem;     /* Espaço interno leve para destacar o texto */
  border-radius: 4px;         /* Cantos suavemente arredondados para estética moderna */
  font-weight: bold;          /* Negrito para reforçar a importância do conteúdo */
}

.destaque {
  color: #b22222; /* Vermelho escuro para chamar atenção */
  font-weight: bold; /* Negrito para reforçar o destaque */
}

.destaque {
  background-color: #e0f0ff;     /* Fundo azul claro — chama atenção sem agressividade */
  padding: 0.2rem 0.5rem;        /* Espaço interno para respiro visual */
  border-radius: 4px;            /* Cantos suavemente arredondados para estética moderna */
  font-weight: bold;            /* Negrito para reforçar a importância do trecho destacado */
  color: #b22222;               /* Vermelho escuro — forte contraste para chamar atenção ao conteúdo */
}

.destaque p
.destaque p {
  font-size: 1.5rem;
}

.destaque {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}

ul li {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}

.destaque {
  background-color: #e0f0ff; /* Fundo azul claro para chamar atenção sem agressividade */
  padding: 0.2rem 0.5rem;     /* Espaço interno leve para destacar o texto */
  border-radius: 4px;         /* Cantos suavemente arredondados para estética moderna */
  font-weight: bold;          /* Negrito para reforçar a importância do conteúdo */
}

.destaque {
  color: #b22222; /* Vermelho escuro para chamar atenção */
  font-weight: bold; /* Negrito para reforçar o destaque */
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

.botao-instagram,
.botao-whatsapp {
  display: inline-block;         /* Permite que os botões fiquem lado a lado e respeitem margens */
  margin-top: 0.5rem;            /* Espaço acima para separar do conteúdo anterior */
  color: #0066cc;                /* Azul institucional para indicar interatividade */
  text-decoration: underline;    /* Sublinha para reforçar que é clicável */
}
.botao-instagram:hover,
.botao-whatsapp:hover {
  text-decoration: none;         /* Remove sublinhado ao passar o mouse — efeito visual limpo e moderno */
}/*💡 Esses botões são simples, mas funcionais — ideais para chamadas rápidas para ação (CTA) como “Fale conosco” ou “Siga no Instagram”.*/

.destaque {
  background-color: #e0f0ff;     /* Fundo azul claro — chama atenção sem agressividade */
  padding: 0.2rem 0.5rem;        /* Espaço interno para respiro visual */
  border-radius: 4px;            /* Cantos suavemente arredondados para estética moderna */
  font-weight: bold;            /* Negrito para reforçar a importância do trecho destacado */
  color: #b22222;               /* Vermelho escuro — forte contraste para chamar atenção ao conteúdo */
}

.destaque {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}

.botao-instagram {
  display: inline-block;
  margin: 0.4rem 0;
  padding: 0.5rem 1rem;
  background-color: #E1306C;
  color: #fff;
  font-weight: 500;
  font-size: 1rem;
  border-radius: 6px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.botao-instagram i {
  margin-right: 6px;
}

.botao-instagram:hover {
  background-color: #c1275b;
}

/* WhatsApp */
.botao-whatsapp {
  display: inline-block;
  margin: 0.4rem 0;
  padding: 0.5rem 1rem;
  background-color: #25D366;
  color: #fff;
  font-weight: 500;
  font-size: 1rem;
  border-radius: 6px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.botao-whatsapp i {
  margin-right: 6px;
}

.botao-whatsapp:hover {
  background-color: #1da851;
}


ul li {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}


.destaque {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}



.bloco-contato {
  margin-top: 1.5rem;
  padding: 1rem;
  background-color: #f9f9f9;
  border-radius: 10px;
  box-shadow: 0 0 8px rgba(0,0,0,0.05);
  text-align: center;
}

.bloco-contato p {
  margin: 0.5rem 0;
  font-size: 1rem;
  line-height: 1.6;
}

/* Instagram */
.botao-instagram {
  display: inline-block;
  margin: 0.4rem 0;
  padding: 0.5rem 1rem;
  background-color: #E1306C;
  color: #fff;
  font-weight: 500;
  font-size: 1rem;
  border-radius: 6px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.botao-instagram i {
  margin-right: 6px;
}

.botao-instagram:hover {
  background-color: #c1275b;
}

/* WhatsApp */
.botao-whatsapp {
  display: inline-block;
  margin: 0.4rem 0;
  padding: 0.5rem 1rem;
  background-color: #25D366;
  color: #fff;
  font-weight: 500;
  font-size: 1rem;
  border-radius: 6px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.botao-whatsapp i {
  margin-right: 6px;
}

.botao-whatsapp:hover {
  background-color: #1da851;
}

.destaque {
  background-color: #e0f0ff;     /* Fundo azul claro — chama atenção sem agressividade */
  padding: 0.2rem 0.5rem;        /* Espaço interno para respiro visual */
  border-radius: 4px;            /* Cantos suavemente arredondados para estética moderna */
  font-weight: bold;            /* Negrito para reforçar a importância do trecho destacado */
  color: #b22222;               /* Vermelho escuro — forte contraste para chamar atenção ao conteúdo */
}

.destaque {
  background-color: #e0f0ff; /* Fundo azul claro para chamar atenção sem agressividade */
  padding: 0.2rem 0.5rem;     /* Espaço interno leve para destacar o texto */
  border-radius: 4px;         /* Cantos suavemente arredondados para estética moderna */
  font-weight: bold;          /* Negrito para reforçar a importância do conteúdo */
}

.destaque {
  color: #b22222; /* Vermelho escuro para chamar atenção */
  font-weight: bold; /* Negrito para reforçar o destaque */
}

.logo-suave-anuncie {
  max-width: 180px;               /* Limita a largura — evita distorções em telas grandes */
  height: auto;                   /* Mantém proporção original da imagem */
  border-radius: 8px;             /* Cantos arredondados — estética moderna e amigável */
  box-shadow: 0 4px 10px rgba(0,0,0,0.1); /* Sombra leve — destaca visualmente a imagem */
  opacity: 0.85;                  /* Leve transparência — efeito suave e elegante */
  transition: opacity 0.3s ease; /* Suaviza a transição ao passar o mouse */
}

.logo-suave-anuncie:hover {
  opacity: 1; /* Ao passar o mouse, a imagem fica totalmente visível — reforça interatividade */
}

.logo-suave-anuncie {
  width: 100%;
  max-width: 280px;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  margin: 0 auto 1rem auto;
  display: block;
  object-fit: cover;
  opacity: 0.85;
  transition: opacity 0.3s ease;
}

.logo-suave-anuncie:hover {
  opacity: 1;
}

/* ← Parte 1 do <main> (título e aviso) */

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ===================== CONTAINER DO TÍTULO ===================== */
.titulo-flex {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 2.5rem 1rem;
  background-color: #eaeaea;
  text-align: center;
  gap: 1rem;
}

.titulo-flex h1 {
  font-size: 2.8rem;
  color: #222;
  margin: 0 0 1.3rem 0;
  line-height: 1.3;
}

.titulo-flex h2 {
  font-size: 2.2rem;
  font-family: 'Playfair Display', serif;
  color: #2c2c2c;
  font-weight: 600;
  margin: 0;
  line-height: 1.4;
  letter-spacing: 0.5px;
}

.titulo-flex {
  font-size: 1.3rem;
  color: #555;
  font-style: italic;
  max-width: 800px;
  line-height: 1.6;
  margin-top: 1rem;
}

#aviso-narrativa {
  background-color: #fff3cd;
  border-radius: 8px;
  padding: 1rem;
  margin-top: 1rem;
}

#aviso-narrativa h5 {
  font-size: 1rem;
  font-style: italic;
  line-height: 1.6;
  color: #333;
  text-align: justify;
  margin: 0;
}
► aqui estamos com dificulaadade para ativar esta parte 1 que esat acima
***
/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

.conteudo-grid {
  display: grid; /* Ativa Grid Layout */
  grid-template-columns: 1fr 6fr 3fr; /* Coluna esquerda, centro e direita */
  column-gap: 2rem; /* Espaço horizontal entre colunas */
  row-gap: 1rem; /* Espaço vertical entre linhas, se houver */
  width: 100%;
  max-width: 1400px;
  margin: 0 auto;
  padding: 2rem;
  overflow-x: hidden;
}


/* ← Coluna esquerda: Lei aplicada no caso jurídico */

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* =============== CONTAINER DA LEI ================== */
.qual_foi_lei_usada {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.container-lei-usada {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

/* ==== BLOCO DE MENSAGEM EM LAYOUT HORIZONTAL ========= */
.mensagem-lei.layout-horizontal {
  display: flex;
  flex-direction: row;
  gap: 2rem;
  align-items: flex-start;
  flex-wrap: wrap; /* Permite quebra se não couber */
}

/* ===== PERFIL DO DR. LEANDRO (COLUNA ESQUERDA) ========== */
.perfil-dr-leandro-2 {
  flex: 0 0 auto; /* Aumenta a largura mínima */
  width: 100%; /* Ocupa toda a largura disponível */
  max-width: 500px; /* Permite imagem maior */
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #fdf6e3;
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 0 8px rgba(0,0,0,0.05);
}

.perfil-dr-leandro-2 img {
  width: 100%;
  max-width: 500px;
  border-radius: 8px;
  box-shadow: 0 0 8px rgba(0,0,0,0.1);
}

/*===TEXTO INSTITUCIONAL (COLUNA ESQUERDA) ========== */

.texto-dr-leandro {
  flex: 1;
  display: flex;
  flex-direction: column;
  gap: 1rem;
  font-size: 1.125rem;
  line-height: 1.6;
  color: #333;
}

.texto-dr-leandro h2,
.texto-dr-leandro h3,
.texto-dr-leandro h4 {
  margin-top: 1.5rem;
  margin-bottom: 0.8rem;
  font-family: 'Playfair Display', serif;
  font-weight: 600;
  color: #2c2c2c;
}

.texto-dr-leandro p {
  font-size: 1.0rem;
  line-height: 1.6;
  margin-bottom: 0.5rem;
}

.texto-dr-leandro ul {
  font-size: 0.8rem;
  padding-left: 1.5rem;
  margin-bottom: 1rem;
}

.texto-dr-leandro li {
  font-size: 0.8rem;
  margin-bottom: 0.5rem;
}

/* ===================== LINKS ===================== */
.texto-dr-leandro a {
  color: #0066cc;
  text-decoration: underline;
}

.texto-dr-leandro a:hover {
  text-decoration: none;
}

/* ← Citação de Ruy Barbosa e reflexão final */
/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ===================== CONTAINER PRINCIPAL ===================== */
.citacao-precedente {
  margin-top: 3rem;
  padding: 2rem;
  background-color: #f9f9f9;
  border-left: 4px solid #8b0000;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  font-family: 'Georgia', serif;
  font-size: 1rem;
  line-height: 1.6;
  color: #333;
}

/* ===================== TÍTULO ===================== */
.citacao-precedente h4 {
  font-size: 1.3rem;
  margin-bottom: 1rem;
  color: #8b0000;
  font-weight: bold;
}

/* ===================== BLOCO DE CITAÇÃO ===================== */
.citacao-precedente blockquote {
  margin: 1rem 0;
  padding-left: 1rem;
  border-left: 3px solid #ccc;
  font-style: italic;
  color: #444;
}

.citacao-precedente blockquote p {
  font-size: 1rem;
  line-height: 1.6;
}

.citacao-precedente blockquote footer {
  margin-top: 0.5rem;
  font-size: 0.8rem;
  font-weight: bold;
  color: #666;
}

/* ===================== TEXTO EXPLICATIVO ===================== */
.citacao-precedente p {
  margin-top: 1rem;
  font-size: 1rem;
  line-height: 1.6;
  color: #444;
}

/* ===================== LINKS ===================== */
.citacao-precedente a {
  color: #8b0000;
  text-decoration: underline;
  font-weight: bold;
}

/* ===================== FIGURA FINAL ===================== */
.le_ruy_barbosa em {
  font-size: 0.8rem;
}

/* ===================== REPRESENTAÇÃO FINAL: DR. LEANDRO E RUY BARBOSA ===================== */
.representacao-hopeup {
  margin-top: 2rem;
  text-align: center;
}

.representacao-hopeup img {
  max-width: 500px;
  width: 100%;
  border-radius: 6px;
  box-shadow: 0 0 6px rgba(0,0,0,0.1);
  margin-bottom: 0.5rem;
}

.representacao-hopeup figcaption {
  font-size: 0.9rem;
  color: #555;              /* Tom suave para leitura confortável */
  font-style: italic;
   margin-top: 0.5rem;       /* Espaço acima para separar da imagem */
}

/* ===================== LINK SUTIL ===================== */

.link-sutil {
  text-align: center;     /* Centraliza o link — ideal para fechamento visual ou CTA discreto */
  margin-top: 1rem;       /* Espaço acima para separar do conteúdo anterior */
}

.link-sutil a {
  color: #0066cc;         /* Azul institucional — reforça interatividade */
  font-weight: bold;      /* Negrito para dar leve destaque sem exagero */
  text-decoration: none;  /* Remove sublinhado padrão — visual mais limpo */
}

.link-sutil a:hover {
  text-decoration: underline; /* Reativa sublinhado no hover — reforça que é clicável */
}/*💡 Ideal para links como “Voltar ao topo”, “Ver mais detalhes” ou “Acesse o documento completo”.*/


/* ← Parte 2 do `<main>` (perfil, conteúdo, lei)*/
/*Parte central do conteúdo com layout em Grid*/

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/
/* ← Parte 2 do <main> (perfil, conteúdo, lei) */
/* Conteúdo central da narrativa jurídica */

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ============== CONTAINER PRINCIPAL ===================== */
.conteudo-principal {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  flex-grow: 1;
  min-height: 100%;
  height: 100%;
  background-color: #ffffff;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 0 12px rgba(0,0,0,0.08);
  box-sizing: border-box;
  color: #333;
  font-size: 1.3rem;
  line-height: 1.5;
}

/* ============== ELEMENTOS INTERNOS ===================== */

/* Crescimento vertical dos filhos */
.conteudo-principal > * {
  flex-grow: 1;
}

/* Títulos */
.conteudo-principal h2,
.conteudo-principal h3,
.conteudo-principal h4 {
  text-align: center;
  font-family: 'Playfair Display', serif;
  font-weight: 600;
  line-height: 1.4;
  color: #2c2c2c;
}

.conteudo-principal h2 {
  font-size: 1.8rem;
  margin: 0.25rem 0 0.5rem 0;
  letter-spacing: 0.5px;
}

.conteudo-principal h3 {
  font-size: 1.6rem;
  margin: 0.25rem 0 0.5rem 0;
  letter-spacing: 0.2px;
}

.conteudo-principal h4 {
  font-size: 1.4rem;
  margin: 1.5rem auto;
  letter-spacing: 0.5px;
}

/* Parágrafos */
.conteudo-principal p {
  font-size: 1.0rem;
  line-height: 1.6;
  margin-bottom: 0.5rem;
}

/* Listas */
.conteudo-principal ul {
  font-size: 0.8rem;
  padding-left: 1.5rem;
  margin-bottom: 1rem;
}

.conteudo-principal li {
  font-size: 0.8rem;
  margin-bottom: 0.5rem;
}

/* Ênfase */
.conteudo-principal em {
  font-style: italic;
  color: #444;
}

.conteudo-principal strong {
  font-weight: bold;
  color: #222;
}

/* Links */
.conteudo-principal a {
  color: #0066cc;
  text-decoration: underline;
}

.conteudo-principal a:hover {
  text-decoration: none;
}


/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

.conteudo-grid {
  display: grid; /* Ativa Grid Layout */
  grid-template-columns: 1fr 6fr 3fr; /* Coluna esquerda, centro e direita */
  column-gap: 2rem; /* Espaço horizontal entre colunas */
  row-gap: 1rem; /* Espaço vertical entre linhas, se houver */
  width: 100%;
  max-width: 1400px;
  margin: 0 auto;
  padding: 2rem;
  overflow-x: hidden;
}

/* ← Perfil institucional: Dr. Leandro Alves de Souza */
/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* =========== CONTAINER DO ARTICLE ========= */
.quem-sou {
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  padding: 1rem;
}

/* ========== SECTION INTERNA =============== */
.secao-quem {
  padding: 2rem;
}

/* ====== CONTAINER INTERNO DO PERFIL ======== */
.container-quem-sou {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

/* ========== BLOCO DO PERFIL ============= */
.perfil-dr-leandro {
  text-align: center;
  background-color: #fdf6e3;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 0 8px rgba(0,0,0,0.05);
}

/* ========= IMAGEM DO PERFIL ================ */
.perfil-dr-leandro img {
  width: 100%;
  max-width: 500px;
  height: auto;
  border-radius: 50%;
  margin-bottom: 1rem;
  box-shadow: 0 0 8px rgba(0,0,0,0.1);
}

/* ========= TEXTO INSTITUCIONAL =============== */
.mensagem h2 {
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
  color: #222;
  font-family: 'Playfair Display', serif;
  font-weight: 600;
}

.mensagem h3 {
  margin-top: 1.6rem;
  font-size: 1.2rem;
  color: #444;
}

.mensagem p {
  font-size: 1.125rem; /* Mantém versão maior para leitura em telas amplas */
  line-height: 1.6;
  color: #555;
}

/* ======== CONTAINER GERAL DO PERFIL ============ */
.perfil-container {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  flex-grow: 1;
  min-height: 100%;
  height: 100%;
}

.perfil-container > * {
  flex: 0 0 auto;
}

/* ← Bloco de ajuda jurídica lateral */
/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ============ CONTAINER PRINCIPAL ================ */
.perfil-ajuda {
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  padding: 1.5rem;
  margin-top: 2rem;
  font-size: 0.95rem;
  color: #444;
  flex-grow: 1;
}

/* =========== SECTION INTERNA =============== */
.secao-ajuda {
  padding: 1.5rem;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  margin: 2rem auto;
  box-sizing: border-box;
}

/* ============ CONTAINER DE TEXTO ============= */
.container-ajuda {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.container-ajuda p {
  font-size: 1.0rem;
  line-height: 1.6;
  margin-bottom: 0.5rem;
}

/* ============= TÍTULO ======== */
.perfil-ajuda h3 {
  margin-top: 1.6rem;
  font-size: 1.2rem;
  color: #444;
}

/* =============== LISTA DE AJUDA ============ */
.perfil-ajuda ul {
  font-size: 0.8rem;
  margin-bottom: 1rem;
  padding-left: 1.5rem;
  list-style-type: disc;
}

.perfil-ajuda li {
  font-size: 0.8rem;
  margin-bottom: 0.5rem;
  line-height: 1.6;
}

/* ← Bloco de publicidade institucional */
/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ===================== CONTAINER GERAL DOS ANÚNCIOS ===================== */

#anuncios-perfil-container {
  margin-top: 2rem;
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
  flex-grow: 1;
  flex-shrink: 0;
  flex-basis: auto;
  justify-content: flex-start;
  overflow: visible;
}

/* Elemento auxiliar para separação */
.anuncio-bloco-perfil {
  height: 1px;
  background-color: transparent;
}

/* ===================== SEÇÃO DE PUBLICIDADE ===================== */
.secao-publicidade {
  padding: 1.5rem;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  margin: 2rem auto;
  box-sizing: border-box;
}

/* Título da seção */
.titulo-publicidade {
  font-size: 1.4rem;
  color: #333;
  margin-bottom: 1rem;
  text-align: center;
}

/* ===================== CONTAINER DOS CARDS ===================== */
.container-publicidade {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

/* ===================== CARD INDIVIDUAL DE PUBLICIDADE ===================== */
.publicidade {
  background-color: #f0f0f0;
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 0 6px rgba(0,0,0,0.05);
  text-align: center;
  font-size: 0.95rem;
  color: #444;
}

/* ===================== LOGO SUAVE DO CARD ===================== */
.logo-suave-perfil,
.secao-publicidade .logo-suave {
  width: 100%;
  max-width: 280px;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  margin: 0 auto 1rem auto;
  display: block;
  object-fit: cover;
  opacity: 0.85;
  transition: opacity 0.3s ease;
}

/* ← Estilos textuais para o bloco de anúncios institucional */
/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ===================== TÍTULOS ===================== */
.titulo-publicidade {
  font-size: 1.4rem;
  font-family: 'Playfair Display', serif;
  font-weight: 600;
  color: #333;
  margin-bottom: 1rem;
  text-align: center;
}

.publicidade h1,
.publicidade h2,
.publicidade h3,
.publicidade h4,
.publicidade h5 {
  font-family: 'Playfair Display', serif;
  font-weight: 600;
  color: #2c2c2c;
  margin: 1rem 0 0.5rem;
  line-height: 1.4;
}

.publicidade h3 {
  font-size: 1.6rem; 
}

/* ===================== PARÁGRAFOS ===================== */
.publicidade p {
  font-size: 1rem;
  line-height: 1.6;
  color: #444;
  margin-bottom: 1rem;
}

/* ===================== ÊNFASE ===================== */
.publicidade em {
  font-style: italic;
  color: #555;
}

.publicidade strong {
  font-weight: bold;
  color: #222;
}

/* ===================== LINKS ===================== */
.publicidade a {
  color: #f7f7f7;
  text-decoration: underline;
  font-weight: bold;
}

.publicidade a:hover {
  text-decoration: none;
}


.logo-suave-perfil:hover,
.secao-publicidade .logo-suave:hover {
  opacity: 1;
}

/* ← Bloco “Anuncie Aqui” */
/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ===================== CONTAINER PRINCIPAL ===================== */
.perfil-anuncie-aqui {
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  padding: 1.5rem;
  margin-top: 2rem;
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: 0.95rem;
  color: #444;
  flex-grow: 1;
}

/* ===================== SEÇÃO INTERNA ===================== */
.secao-anuncie-aqui {
  width: 100%;
  padding: 1.5rem;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  margin: 2rem auto;
  box-sizing: border-box;
}

/* ===================== CONTAINER DE CONTEÚDO ===================== */
.container-anuncie-aqui {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 1rem;
  text-align: center;
}

.container-anuncie-aqui p {
  font-size: 1rem;
  line-height: 1.6;
  color: #444;
}

/*← Parte 3 do `<main>` (imagem final)*/
/*Parte inferior do conteúdo com Flexbox*/

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

/* ===================== PARTE 3: IMAGEM EM FLEXBOX ===================== */
.imagem-flex {
  display: flex; /* Ativa Flexbox para organizar os elementos filhos */
  flex-direction: column; /* Empilha verticalmente: imagem + legenda */
  justify-content: center; /* Centraliza verticalmente dentro do container */
  align-items: center; /* Centraliza horizontalmente os elementos */
  padding: 0; /* Remove espaçamento interno para permitir que a imagem ocupe toda a área */
  background-color: #eaeaea; /* Fundo neutro para destacar a imagem */
  width: 100%; /* Ocupa toda a largura disponível */
  box-sizing: border-box; /* Inclui padding e borda no cálculo da largura */
}
.representacao-Dr\.Leandro {
  width: 100%; /* Garante que o container da imagem ocupe toda a largura */
  text-align: center; /* Centraliza o texto da legenda */
}/*Observação: o caractere \. é necessário para escapar o ponto na classe .representacao-Dr.Leandro, já que CSS interpreta ponto como seletor de classe.*/

.representacao-Dr\.Leandro img {
  width: 100%; /* Faz a imagem ocupar toda a largura do container */
  height: 100%; /* Preenche toda a altura disponível — cuidado com distorções se o container não tiver altura definida */
  object-fit: cover; /* Corta a imagem inteligentemente para preencher o espaço sem distorcer */
  border-radius: 0; /* Remove cantos arredondados para visual institucional e de impacto */
  box-shadow: none; /* Remove sombra para manter estética limpa e direta */
  display: block; /* Garante que a imagem se comporte como bloco e não inline */
}

.representacao-Dr\.Leandro figcaption {
  font-size: 1rem; /* Tamanho padrão para leitura confortável */
  color: #555; /* Tom suave para leitura prolongada */
  font-style: italic; /* Estilo editorial para reforçar o tom narrativo */
  line-height: 1.6; /* Espaçamento entre linhas para fluidez visual */
  padding: 1rem; /* Espaço interno para respiro da legenda */
  max-width: 100%; /* Garante que a legenda não ultrapasse os limites do container */
  background-color: #f9f9f9; /* Fundo claro para destacar a legenda sem competir com a imagem */
}

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

.representacao-Dr\.Leandro em {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}

/*← Rodapé e créditos finais*/
/*Rodapé do site com créditos e logo*/

/*Deus, Tu és Senhor e Rei e integrante da Equipe HopeUp 7.DEV, por isso se faça presente aqui nestes nossos estudos, por favor, Senhor.*/

.footer {
  text-align: center; /* Centraliza o conteúdo do rodapé */
  padding: 30px; /* Espaçamento interno */
  background-color: #3e3d3d; /* Fundo cinza escuro */
  font-size: 14px; /* Texto menor */
  color: #eceef3; /* Texto em tom claro para contraste */
}
.powered-by {
  display: flex; /* Ativa Flexbox para organizar os elementos horizontalmente */
  align-items: center; /* Alinha verticalmente os itens ao centro (útil para ícones + texto) */
  justify-content: center; /* Centraliza horizontalmente todo o conteúdo dentro do container */
  gap: 12px; /* Espaço entre os elementos (ex: logo + texto) para evitar que fiquem colados */
  margin-top: 12px; /* Espaço acima para separar do conteúdo anterior (ex: linha final do site) */
  flex-wrap: wrap; /* permite quebrar linha se necessário — essencial para responsividade em telas pequenas */
  color: #eceef3; /* Cor clara para texto — ideal se o fundo for escuro, garantindo contraste e legibilidade */
  font-size: 1.1rem; /* aumenta o texto da equipe */

}
/* Logo suave */
.logo-suave {
  height: 42px; /* Altura fixa do logo */
  opacity: 0.6; /* Deixa o logo mais suave/menos chamativo */
  transition: opacity 0.3s ease; /* Transição suave ao mudar opacidade */
  vertical-align: middle; /* Alinha verticalmente com o texto ao lado */
}

/* Efeito hover no logo */
.logo-suave:hover {
  opacity: 1; /* Destaca o logo ao passar o mouse */
}
.footer p {
  margin-bottom: 1rem; /* Espaço entre o texto institucional e o bloco da equipe */
  font-size: 1.1rem; /* aumenta o texto da equipe */
}

/* Logo no “© Equipe Powered By” */
.powered-by .logo-suave {
  height: 32px;                   /* Tamanho pequeno para se encaixar discretamente no rodapé */
  width: auto;                    /* Mantém proporção original da imagem */
  opacity: 0.6;                   /* Aplica leve transparência para visual suave e não competitivo */
  transition: opacity 0.3s ease; /* Suaviza a transição ao passar o mouse — efeito elegante */
  font-size: 1.1rem; /* aumenta o texto da equipe */
}

.powered-by .logo-suave:hover {
  opacity: 1; /* Ao passar o mouse, a logo fica totalmente visível — reforça interatividade sutil */
}

.powered-by {
  flex-wrap: wrap;        /* Permite que os elementos internos quebrem linha — útil em rodapés com múltiplos logos ou links */
  color: #eceef3;         /* Tom claro — combina com fundo escuro típico de rodapés */
}


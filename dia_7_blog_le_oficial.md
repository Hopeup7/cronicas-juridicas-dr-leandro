<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blog Dr. Leandro Alves de Souza</title>
  <link rel="stylesheet" href="blog_le_front\blog_le_styles.css">
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">


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
      <h1>Crônicas Jurídicas — Dr. Leandro Alves de Souza</h1>
      <h2><span class="nome-cronica">Madame Anônima</span><br>A sentença que virou esperança</h2>


      <div id="aviso-narrativa" class="aviso-flex" role="note">
        <h5>
          Esta é uma <strong>Crônica jurídica</strong> — mais literária, reflexiva, focada na experiência, no sentimento e na ética por trás do caso.  
          Criada pela <strong>Equipe HopeUP 7.DEV</strong>, a narrativa é baseada em um caso real, com fundamentos legais autênticos e referências verídicas.  
          O conteúdo foi adaptado editorialmente para facilitar a compreensão de termos técnicos e jargões jurídicos, mantendo a integridade dos fatos e da atuação profissional.  
          A história de <em>'Madame Anônima'</em> é contada com sensibilidade e clareza, para que qualquer pessoa — mesmo sem formação em Direito — possa entender o impacto humano por trás da sentença.  
          A <strong>lei utilizada como base na defesa</strong> encontra-se na coluna esquerda e também está disponível para consulta direta na narrativa:  
          <a href="https://www.planalto.gov.br/ccivil_03/leis/l7210.htm" target="_blank">Lei de Execução Penal – nº 7.210/1984</a>.
        </h5>
      </div>
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
                  <p><em>Sócio-fundador do escritório LAS Advocacia e Consultoria Jurídica</em>, com atuação em processos em São Paulo, Rio de Janeiro e Distrito Federal.</p>

                  <h3><span class="destaque">Missão e Atuação</span></h3>
                  <p>
                    Nossa missão é defender os direitos dos trabalhadores com excelência, comprometimento e responsabilidade.<br>
                    Atuamos de forma especializada em <strong>Direito do Trabalho</strong>, com foco exclusivo na proteção jurídica de empregados que enfrentam situações de injustiça, abusos ou irregularidades nas relações de trabalho.<br>
                    Nossa equipe está preparada para garantir que você tenha o suporte necessário para enfrentar esse momento com segurança jurídica.
                  </p>
                  <h3><span class="destaque">Localização e Contato</span></h3>

                  <div class="bloco-contato">
                  <p>Santana, São Paulo – SP</p>
                  <p>
                    <strong>Instagram:</strong>
                    <a href="https://www.instagram.com/advogado_leandro/" target="_blank" class="botao-instagram">
                      <i class="fab fa-instagram"></i> Siga-nos
                    </a><br>
                    <strong>WhatsApp:</strong>
                    <a href="https://wa.me/5511971949198" target="_blank" class="botao-whatsapp">
                      <i class="fab fa-whatsapp"></i> Fale conosco
                    </a>
                  </p>
                </div>


                </div> <!-- Fim da div .mensagem -->
              </div> <!-- Fim da div .perfil-dr-leandro -->

            </div> <!-- Fim da div .container-quem-sou -->
          </section> <!-- Fim da section .secao-quem -->
        </article> <!-- Fim do article .quem-sou -->

        <aside class="perfil-ajuda">
        <section class="secao-ajuda">
          <div class="container-ajuda">
            <h3><span class="destaque">🛡️ Saiba como podemos te ajudar</span></h3>
            <p>Se você está passando por algum desses problemas, faça uma análise com um advogado especialista e saiba como garantir seus direitos:</p>
            <ul>
              <li>Rescisão indireta</li>
              <li>Reclamações trabalhistas</li>
              <li>Verbas rescisórias não pagas</li>
              <li>Assédio moral e sexual no trabalho</li>
              <li>Acidente de trabalho e doenças ocupacionais</li>
              <li>Estabilidade provisória (acidente, gestante, CIPA, etc.)</li>
              <li>Reconhecimento de vínculo empregatício</li>
              <li>Horas extras e adicionais não pagos</li>
              <li>Desvio de função e acúmulo de tarefas</li>
              <li>Trabalho em condições irregulares</li>
              <li>Consultoria preventiva antes de acordos ou rescisão</li>
            </ul>
            <p>Na <strong>LAS Advocacia</strong>, cada caso é tratado com escuta ativa, linguagem clara e estratégias personalizadas. Atuamos com foco exclusivo na defesa dos trabalhadores, oferecendo suporte jurídico imediato e humanizado para quem enfrenta situações de injustiça, abusos ou irregularidades nas relações de trabalho.</p>
            <p>Nossa missão é garantir que você tenha segurança jurídica em cada etapa — desde a análise inicial até a resolução definitiva. Com mais de <strong>2.000 processos sendo conduzidos com excelência</strong>, o Dr. Leandro Alves de Souza e sua equipe estão preparados para transformar sua preocupação em solução. Se você busca orientação confiável, transparência e resultados concretos, fale conosco. Estamos aqui para você, a qualquer momento.</p>
          </div>
        </section>
      </aside>



        <!-- Bloco de anúncios lateral -->
        <aside id="anuncios-perfil-container" aria-label="Seção de anúncios publicitários no Grid do perfil">
          <div class="anuncio-bloco-perfil"></div>

          <section class="secao-publicidade">
            <h2 class="titulo-publicidade">📢 Publicidades</h2>
            <div class="container-publicidade">

              <!-- ANÚNCIO 1 -->
              <div class="publicidade Powered by HopeUp 7.DEV">
                <img src="blog_le_front/imagens_front_blog_le/icone_hopeup.png" alt="Logo HopeUp 7.DEV" class="logo-suave-perfil" loading="lazy">
                <div class="mensagem">
                  <p><strong>Hope Up 7.DEV</strong> 💥</p>
                  <p>
                    Desenvolvido com <strong>dedicação autodidata</strong>, <strong>capricho técnico</strong> e uma <strong>resiliência silenciosa</strong>, o sistema da equipe <em>Powered by Hope Up 7.DEV</em> reflete a jornada de quem constrói com propósito. Cada linha de código escrita por <strong>HopeUp 7.DEV</strong> carrega não apenas técnica refinada — como modularização por contexto, rastreio semântico e arquitetura responsiva — mas também uma sensibilidade sutil, capaz de perceber o que não está dito. A proposta de <strong>registro único por caso</strong> permite que cada situação, seja ela jurídica, médica, educacional ou administrativa, seja tratada com exclusividade e profundidade. Essa abordagem pode ser aplicada em ramos como <em>consultoria jurídica</em>, <em>catálogo de históricos médico-cirúrgicos por caso individual e personalizado</em>, <em>gestão de prontuários clínicos</em>, <em>acompanhamento pedagógico</em> e até <em>suporte técnico personalizado</em>, sempre respeitando a individualidade de cada história.<br>Entre em contato e descubra como podemos transformar sua ideia em realidade em books de mostruários físicos e digitais!
                  </p>
                  <h3><span class="destaque">Localização e Contato</span></h3>
                  <div class="bloco-contato">
                  <p>Santana, São Paulo – SP</p>
                  <p>
                    <strong>Instagram:</strong>
                    <a href="https://www.instagram.com/advogado_leandro/" target="_blank" class="botao-instagram">
                      <i class="fab fa-instagram"></i> Siga-nos
                    </a><br>
                    <strong>WhatsApp:</strong>
                    <a href="https://wa.me/5511971949198" target="_blank" class="botao-whatsapp">
                      <i class="fab fa-whatsapp"></i> Fale conosco
                    </a>
                  </p>
                </div>

                  
                </div>
              </div>

              <!-- Adicione mais blocos conforme necessário -->

            </div> <!-- Fim da div .container-publicidade -->
          </section> <!-- Fim da section .secao-publicidade -->
        </aside> <!-- Fim do aside .anuncios-perfil-container -->
        <aside class="perfil-anuncie-aqui">
          <section class="secao-anuncie-aqui">
            <div class="container-anuncie-aqui">
              <img src="blog_le_front/imagens_front_blog_le/temp_anuncie_aqui.PNG" alt="Anuncie Aqui" class="logo-suave-anuncie" loading="lazy">
              <p>
                <strong>📣 Anuncie aqui com propósito.</strong><br>
                Este espaço é reservado para marcas, serviços ou projetos que compartilham dos mesmos valores que este blog: justiça, dignidade e transformação. Ao lado de histórias reais e decisões jurídicas que impactam vidas, seu anúncio ganha relevância, empatia e atenção genuína. Alcance pessoas que buscam soluções sérias e humanas — anuncie com quem inspira confiança.
              </p>
            </div>
          </section>
        </aside>

      </div> <!-- Fim da div .perfil-container -->

      

       <article class="conteudo-principal">

        <h2><strong><em>'Madame Anônima'<br>'A Reviravolta Jurídica'</em></strong></h2>

        <p><em>Ela chegou aflita.</em> Os olhos de <strong>'Madame Anônima'</strong> carregavam o peso de quem não dormia há dias. Olheiras profundas, rosto abatido. A sentença imposta pelo <strong>'Órgão de Execução Penal'</strong> determinava a <strong>prestação de serviços à comunidade</strong> — uma pena legítima, mas impraticável diante da sua realidade.</p>

        <p>Esse era o dilema: <strong>Dor</strong>. A inviabilidade de cumprir a pena se tornava uma fonte de sofrimento. Simplesmente a dor emocional e psicológica que passou a consumir e afetar também sua saúde física e mental, estava fazendo com que 'Madame Anônima' se sentisse cada vez mais perdida e desorientada. A necessidade de voltar a viver, sorrir e enfim dormir em paz foi o que a levou ao escritório de <strong>'Dr. Leandro Alves de Souza'</strong>.</p>

        <p>Mãe solo, trabalhadora autônoma, sustentava dois filhos com o que arrecadava diariamente. Cumprir a pena significava abrir mão do trabalho. E abrir mão do trabalho significava não alimentar sua família.</p>

        <p>A possibilidade de ver seus filhos na corda bamba da <strong>falta de recursos</strong> a deixava em desespero.</p>

        <p>Sentada diante da mesa de Dr. Leandro, ela hesitou...mas enfim, como quem se entrega a um último recurso e lampejo de esperança, disse:</p>

        <p><em>“Eu não quero fugir da lei... só não sei como cumprir sem perder tudo... Meus filhos precisam de mim, Dr. Leandro. Por favor, me ajude... me ajude.”</em></p>

        <p>Disse 'Madame Anônima' com a voz embargada, olhos marejados e lágrimas escorrendo pelo rosto. <strong>'Dr. Leandro Alves de Souza'</strong> a escutava com atenção, sem interromper. Ele sabia que ali não havia apenas um caso jurídico — havia uma vida em risco.</p>

        <p>Dr. Leandro a observava com extrema preocupação, pois pessoas acuadas e desesperadas podem simplesmente perder o desejo de viver. Ele buscava entender a profundidade de seu desespero, mas não conseguia, uma vez que a cena e dor a ele transmitidas eram intensas e angustiantes. Diante do que acabara de presenciar, Dr. Leandro sentiu a urgência de encontrar uma solução.</p>

        <p>'Madame Anônima' desabafou:</p>

        <p><em>“Será que posso pagar em dinheiro ao invés de prestar serviço, Dr. Leandro?”</em> — perguntou, quase como quem pede licença para continuar existindo.</p>

        <p>Diante desse cenário de sólida tristeza e preocupação, Dr. Leandro sentiu a pressão aumentar. Ele precisava encontrar uma solução que respeitasse a lei, mas que também atendesse às necessidades de sua cliente.</p>

        <h3><strong><em>O Obstáculo: A Lei e o Juiz</em></strong></h3>

        <p><strong>'Dr. Leandro'</strong> sabia que a legislação brasileira não previa, como regra, a substituição da prestação de serviços por prestação pecuniária após o trânsito em julgado. O <strong>'Digníssimo Juiz de Execução Penal'</strong> não poderia simplesmente converter a pena.</p>

        <p>O escritório se encheu de pastas e mais pastas, de volumosos e gastos livros de Direito e Jurisprudências. Dr. Leandro revisava cada artigo, cada precedente, cada brecha possível. A tensão era técnica — mas também humana.</p>

        <ul>
          <li><strong>O Código Penal da Constituição Brasileira – Art. 44, §2º:</strong> permite a substituição da pena privativa de liberdade por:<br>
            <strong><ul>
              <li>Prestação pecuniária</li>
              <li>Prestação de serviços à comunidade</li>
              <li>Interdição de direitos</li>
            </ul></strong><br>
            <em>Mas não autoriza a troca entre elas após a sentença.</em>
          </li>
          <li><strong>Lei de Execução Penal – Art. 148:</strong> permite ajustes na forma de cumprimento, mas não a substituição por outra modalidade.</li>
        </ul>

        <h3><strong><em>A Estratégia: A Lei Viva</em></strong></h3>

        <p><strong>'Dr. Leandro'</strong> mergulhou nos precedentes...e ao passar de penosos e longos dias de muitas pesquisas, leituras, reflexões, meditações, e extensas anotações, uma luz se acendeu. Enfim, longas e minuciosas horas de trabalho árduo fizeram com que seu esforço fosse iluminado. Num dia em que tudo parecia perdido, ele encontrou decisões do <strong>'Superior Tribunal de Justiça'</strong> que admitiam exceções — casos em que a prestação de serviços se tornava inviável por motivos físicos, profissionais ou sociais.</p>

        <p><strong>O alvorecer estava próximo.</strong></p>

        <p>Com base no <strong>Art. 149, inciso III, da LEP</strong>, Dr. Leandro construiu sua tese com afinco:</p>

        <p><em>“Para 'Madame Anônima', a impossibilidade é concreta. Não há como conciliar a pena com a sobrevivência.”</em></p>

        <p>A <strong>prestação pecuniária</strong>, nesse contexto, não era um privilégio — era uma <strong>necessidade</strong>. Dr. Leandro redigiu a petição com precisão e empatia, como quem escreve não apenas para convencer, mas para proteger, cuidar e garantir a dignidade de sua cliente.</p>

        <h3><strong><em>O Desfecho: Justiça com Humanidade</em></strong></h3>

        <p>O dia da audiência chegou.</p>

        <p>A sala era fria, silenciosa, marcada por olhares atentos e papéis empilhados, o que aumentava ainda mais a tensão no ambiente. <strong>'Madame Anônima'</strong> sentou-se com as mãos trêmulas. <strong>'Dr. Leandro'</strong> estava ao seu lado, firme.</p>

        <p>Diante do <strong>'Honorável Juiz de Execução Penal'</strong>, a defesa feita por Dr. Leandro foi clara: não se tratava de escapar da pena, mas de compatibilizar a punição com a realidade. A alternativa financeira permitiria que ela mantivesse sua rotina, continuasse trabalhando, cuidando de seu lar e contribuindo com a sociedade.</p>

        <p>A sala fez silêncio. O <strong>Excelentíssimo Juiz</strong> folheou os autos, releu os fundamentos, ponderou os elementos do caso concreto. E então, reconhecendo a excepcionalidade, <strong>autorizou a conversão</strong>.</p>

        <h4>
          <strong><em>A reviravolta trouxe alívio.</em><br><br>
          A lei, vista e revista, ao ser aplicada com humanidade, permitiu que a justiça fosse potencializada e feita sem sacrificar a dignidade.<em></em><br>
          Sim, e as recorrentes lágrimas de dor e desespero de 'Madame Anônima' se transformaram num sorrir carregado de lágrimas intensas de alívio e alegria e gratidão ao Dr. Leandro. E a sensação de ter seu choro contido por esta conquista foi indescritível.</em></strong>
        </h4>

        <p>Hoje 'Madame Anônima' é uma mulher livre. Ela conseguiu cumprir o novo acordo e consequentemente retomar sua vida, seus sonhos e sua dignidade.<br> A justiça, quando aplicada com humanidade, pode transformar realidades e oferecer novas oportunidades.</p>

        <h3><strong><em>Reflexões Finais</em></strong></h3>

        <p><em>Este é um caso real.</em> A história foi retratada em forma de crônica jurídica para que qualquer pessoa — inclusive aquelas como <strong>'Madame Anônima'</strong> — possa compreender o impacto humano por trás de uma sentença.</p>

        <p>A defesa construída por <strong>Dr. Leandro Alves de Souza</strong>, com base legal autêntica, está disponível na <strong>coluna ao lado</strong>, com conteúdo jurídico real e fundamentado.</p>

      </article>



        <!-- Article ► Sobre a Lei usada no conteúdo principal -->
    <!-- Seção Principal: Lei Aplicada no Caso -->
      <div class="lei-container">

        <article class="qual_foi_lei_usada">
          <section class="secao-lei-usada">
            <div class="container-lei-usada">
              <div class="mensagem-lei layout-horizontal">

                <!-- Perfil do Dr. Leandro -->
                <div class="perfil-dr-leandro-2">
                  <img src="blog_le_front/imagens_front_blog_le/foto_le_2_blog_le.jpg" alt="Dr. Leandro Alves de Souza" loading="lazy">
                </div>

                <!-- Texto Institucional -->
                <div class="texto-dr-leandro">
                  <h2><strong>Dr. Leandro Alves de Souza</strong></h2>
                  <p><em>Sócio-fundador do escritório LAS Advocacia e Consultoria Jurídica</em>, com atuação em mais de 2.000 processos em São Paulo, Rio de Janeiro e Distrito Federal. Reconhecido por sua capacidade de unir técnica jurídica com sensibilidade social, Dr. Leandro atua em causas que exigem mais do que conhecimento: exigem escuta, estratégia e coragem.</p>

                  <h3><span class="destaque">Aplicação Jurídica com Responsabilidade</span></h3>
                  <p>Em casos como o de <strong>'Madame Anônima'</strong>, a pena imposta — prestação de serviços à comunidade — colocava em risco a subsistência da condenada. A atuação jurídica não se limitou à defesa formal: foi construída com base em uma leitura profunda da realidade, da legislação e da jurisprudência. <strong>Dr. Leandro</strong> compreendeu que o papel do advogado é também o de mediador entre o texto da lei e a vida concreta.</p>

                  <h4>⚖️ O que diz a Lei Brasileira?</h4>
                  <p>A prestação de serviços à comunidade é uma das penas restritivas de direitos previstas no <strong>Código Penal Brasileiro</strong>, conforme o <strong>Art. 44</strong>. Ela pode ser aplicada como substituição à pena privativa de liberdade em casos de menor gravidade.</p>
                  <p>No entanto, a substituição dessa pena por prestação pecuniária (pagamento em dinheiro) <strong>não está prevista como regra legal após o trânsito em julgado</strong>. Ou seja, não é permitido ao juiz da execução penal trocar a prestação de serviços por pagamento, <strong>salvo em situações excepcionais</strong>, quando há comprovação de impossibilidade real de cumprimento da pena.</p>

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
                  <p>O <strong>Superior Tribunal de Justiça (STJ)</strong> tem reafirmado que a conversão da prestação de serviços em pagamento não é regra. Contudo, em casos excepcionais — como incapacidade física, incompatibilidade profissional ou risco social — alguns tribunais têm autorizado a mudança, com base no <strong>Art. 149, inciso III, da LEP</strong>.</p>
                  <p>📌 Exemplo:<br>
                    “A conversão da pena de prestação de serviços à comunidade em prestação pecuniária pode ser admitida em situações excepcionais, desde que devidamente fundamentada e ajustada às condições pessoais do condenado.” — TJ-DF, Agravo em Execução Penal
                  </p>

                  <h4>✅ Conclusão</h4>
                  <p>A substituição da prestação de serviços por pagamento <strong>não é prevista como direito automático</strong>, mas pode ser solicitada ao juiz da execução penal, com base em <strong>provas concretas de impossibilidade de cumprimento</strong>. O juiz pode então decidir, com base na LEP, se há justificativa legal e social para essa conversão.</p>
                  <p><strong>Dr. Leandro</strong> atua com firmeza e humanidade, defendendo que o direito deve ser aplicado com técnica, mas também com respeito à realidade de cada pessoa. Sua prática jurídica é marcada pela busca de soluções que não apenas resolvam o processo — mas que preservem a dignidade.</p>
                </div>
              </div>
            </div>
          </section>

          <!-- Aside: Citação e Reflexão -->
          <aside class="citacao-precedente">
            <h4>📜 Vozes da Advocacia</h4>
            <blockquote>
              <p><em>“A justiça atrasada não é justiça; é injustiça qualificada e manifesta.”</em></p>
              <footer>— <strong>Ruy Barbosa</strong>, jurista, advogado e defensor das liberdades civis</footer>
            </blockquote>
            <p>Essa frase ecoa com força nos corredores da execução penal. Quando o sistema demora a reconhecer a excepcionalidade de um caso, como no de <strong>'Madame Anônima'</strong>, o conflito gerado pela falta de harmonização entre família/trabalho e prestação de serviços à comunidade se torna evidente e prejudicial. No cumprimento da Lei, tem de haver reflexão que parte do réu <em>— reflexão esta que gera amadurecimento —</em>, mas quando o princípio do bem-estar da família é desconsiderado, a situação se agrava e o ensinamento que tem de brotar do cumprir a Lei se torna raso e superficial. A atuação jurídica precisa ser ágil, sensível e fundamentada. É isso que move profissionais como <strong>Dr. Leandro Alves de Souza</strong>, que não apenas interpretam a lei, mas a aplicam com responsabilidade e humanidade.</p>
            <p>🔗 <a href="https://www.casaruibarbosa.gov.br/frases-e-pensamentos" target="_blank">Fonte: Fundação Casa de Rui Barbosa</a></p>

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

    
      
    </section>

    <section class="imagem-flex">
      <figure class="representacao-Dr.Leandro">
        <img src="blog_le_front/imagens_front_blog_le/retrato_atemporal_le.png" alt="Representação artística de Dr. Leandro em audiência jurídica" loading="lazy">
        <figcaption>
          <em>
            Representação criada pela equipe HopeUp 7.DEV:<br>
            Dr. Leandro apresenta sua tese jurídica diante de um juiz honorável, em um cenário que evoca os grandes debates da história — onde a palavra, a técnica e a dignidade se encontram.
          </em>
        </figcaption>
      </figure>
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

***
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
  font-size: 18px; /* ou 1.125rem */
}

/* ===================== BANNER (mantido) ===================== */
#banner {
  height: 550px; /* Altura fixa para o banner */
  background-image: url("imagens_front_blog_le/so_logo_blog_le.png"); /* Imagem de topo */
  background-position: center; /* Centraliza a imagem */
  background-size: 100% 100%; /* Preenche sem distorcer */
  background-repeat: no-repeat; /* Evita repetição da imagem */
}

/* ===================== PARTE 1: TÍTULO EM FLEXBOX ===================== */
.titulo-flex {
  display: flex; /* Ativa o Flexbox para organizar os elementos filhos */
  flex-direction: column; /* Empilha os elementos verticalmente (h1, h2, subtítulo) */
  justify-content: center; /* Centraliza verticalmente dentro do container */
  align-items: center; /* Centraliza horizontalmente os elementos */
  padding: 2.5rem 1rem; /* Espaço interno: vertical generoso, horizontal mais contido */
  background-color: #eaeaea; /* Fundo neutro e claro para destacar o título */
  width: 100%; /* Ocupa toda a largura disponível */
  box-sizing: border-box; /* Inclui padding e borda no cálculo da largura */
  text-align: center; /* Centraliza o texto dos elementos filhos */
  gap: 1rem; /* Espaço automático entre os elementos filhos (h1, h2, subtítulo) */
}


.titulo-flex h1 {
  font-size: 2.4rem; /* Tamanho grande para destaque principal */
  color: #222; /* Cor escura para contraste e legibilidade */
  margin: 0 0 1.3rem 0; /* Remove margens padrão do navegador */
  line-height: 1.3; /* Altura de linha equilibrada para o título */
}

.titulo-flex h2 {
  font-family: 'Playfair Display', serif; /* Fonte com curvas e presença */
  font-size: 2rem;                        /* Levemente maior para impacto */
  color: #2c2c2c;                         /* Tom mais profundo e editorial */
  margin: 0;
  line-height: 1.4;
  font-weight: 600;                       /* Peso elegante, sem exagero */
  text-align: center;                    /* Centraliza para efeito de título */
  letter-spacing: 0.5px;                 /* Espaçamento sutil entre letras */
}


.titulo-flex .subtitulo {
  font-size: 1.2rem; /* Tamanho menor para texto de apoio */
  color: #555; /* Tom suave para leitura prolongada */
  font-style: italic; /* Estilo editorial para reforçar o tom narrativo */
  max-width: 800px; /* Limita a largura para evitar linhas muito longas */
  line-height: 1.6; /* Altura de linha confortável para leitura */
  margin-top: 1rem; /* Espaço acima para separar do h2 */
}

/* Responsivo para telas menores */
@media (max-width: 768px) {
  .titulo-flex h1 {
    font-size: 1.8rem; /* Reduz o título principal para caber melhor em telas pequenas */
  }

  .titulo-flex h2 {
    font-size: 1.4rem; /* Ajusta o subtítulo para manter hierarquia visual */
  }

  .titulo-flex .subtitulo {
    font-size: 1rem; /* Torna o texto de apoio mais leve e legível em dispositivos móveis */
  }
}

@media (max-width: 768px) {
  /* Em telas menores (até 768px de largura), ajusta a largura máxima do subtítulo */
  .titulo-flex .subtitulo {
    max-width: 90%; /* Permite que o texto se expanda até 90% da largura do container, evitando que fique estreito demais */
  }
}

/* ===================== GRID PRINCIPAL do meio===================== */
.conteudo-grid {
  display: grid; /* Ativa Grid Layout */
  grid-template-columns: 1fr 6fr 3fr; /* Coluna esquerda, centro e direita com proporções */
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

/* ===================== COLUNA DIREITA BLOCO DA LEI USADA ===================== */

.lei-container {
  width: 100%; /* Ocupa toda a largura disponível do grid */
  max-width: 1000px; /* Limita a largura para manter legibilidade em telas grandes */
  margin: 2rem auto; /* Espaço vertical e centralização horizontal */
  padding: 1.5rem; /* Espaço interno para respiro do conteúdo */
  background-color: #ffffff; /* Fundo branco para destaque e contraste */
  box-shadow: 0 0 10px rgba(0,0,0,0.05); /* Sombra leve para profundidade visual */
  border-radius: 8px; /* Cantos arredondados para suavidade estética */
  box-sizing: border-box; /* Inclui padding e borda no cálculo da largura */
  display: flex; /* Ativa Flexbox para organizar o conteúdo interno */
  flex-direction: column; /* Empilha os elementos verticalmente */
  justify-content: space-between; /* Distribui os elementos com espaçamento equilibrado */
  border-left: 1px solid #ddd; /* Linha sutil à esquerda para separar visualmente do conteúdo central */
}

.perfil-dr-leandro-2 {
  text-align: center; /* Centraliza o texto */
  background-color: #fdf6e3; /* Fundo claro estilo institucional */
  padding: 2rem; /* Espaço interno */
  border-radius: 5px; /* Cantos mais arredondados para destaque */
  box-shadow: 0 0 8px rgba(0,0,0,0.05); /* Sombra leve */
}
/* ===================== IMAGEM DO PERFIL ===================== */
.perfil-dr-leandro-2 img {
  width: 250px; /* Aumenta levemente o tamanho da imagem */
  height: 100; /* Mantém proporção original */
  border-radius: 50%; /* Formato circular */
  margin-bottom: 1rem; /* Espaço abaixo da imagem */
  box-shadow: 0 0 6px rgba(0,0,0,0.1); /* Sombra suave para destaque */
}
/* ===================== ARTICLE PRINCIPAL SOBRE A LEI ===================== */
.qual_foi_lei_usada {
  display: block; /* Garante que o elemento se comporte como bloco */
  width: 100%; /* Ocupa toda a largura do container pai */
}


/* ===================== SEÇÃO INTERNA DO ARTICLE ===================== */
.secao-lei-usada {
  padding: 1rem 0; /* Espaço vertical para separar do conteúdo acima e abaixo */
}


/* ===================== CONTAINER INTERNO DO TEXTO ===================== */
.container-lei-usada {
  display: flex; /* Ativa Flexbox para organizar os blocos de texto */
  flex-direction: column; /* Empilha os elementos verticalmente */
  gap: 1.5rem; /* Espaço entre os blocos de texto para leitura confortável */
}
@media (max-width: 768px) {
  /* Aplica estilos específicos para telas pequenas, como celulares e tablets */
  
  .lei-container {
    padding: 1rem;       /* Reduz o espaçamento interno para acomodar melhor em telas menores */
    margin: 1rem auto;   /* Diminui o espaço externo e mantém o bloco centralizado */
  }

  .container-lei-usada {
    gap: 1rem;           /* Reduz o espaçamento entre os elementos internos para compactar o layout */
  }
}


/* ===================== BLOCO DE TEXTO JURÍDICO ===================== */
.mensagem-lei {
  color: #333;            /* Define uma cor escura e neutra para o texto, garantindo boa legibilidade */
  line-height: 1.6;       /* Aumenta o espaçamento entre linhas para leitura confortável, especialmente em textos densos como jurídicos */
}


/* ===================== TÍTULOS E DESTAQUES ===================== */
.mensagem-lei h2 {
  font-size: 1.4rem;         /* Título principal da seção jurídica — destaque moderado */
  color: #0055aa;            /* Azul institucional para reforçar autoridade e seriedade */
  margin-bottom: 0.5rem;     /* Espaço abaixo para separar do conteúdo seguinte */
}

.mensagem-lei h3 {
  font-size: 1.2rem;         /* Subtítulo intermediário — hierarquia abaixo do h2 */
  color: #0077cc;            /* Azul mais claro para diferenciar visualmente do h2 */
  margin-top: 1.5rem;        /* Espaço acima para separar do bloco anterior */
}

.mensagem-lei h4 {
  font-size: 1.1rem;         /* Subtítulo menor — usado para tópicos ou divisões internas */
  color: #444;               /* Tom neutro para não competir com os títulos principais */
  margin-top: 1rem;          /* Espaço acima para respiro visual */
}

.destaque {
  background-color: #e0f0ff; /* Fundo azul claro para chamar atenção sem agressividade */
  padding: 0.2rem 0.5rem;     /* Espaço interno leve para destacar o texto */
  border-radius: 4px;         /* Cantos suavemente arredondados para estética moderna */
  font-weight: bold;          /* Negrito para reforçar a importância do conteúdo */
}
@media (max-width: 768px) {
  /* Aplica estilos específicos para telas pequenas, como celulares e tablets */

  .destaque {
    font-size: 0.95rem;     /* Reduz levemente o tamanho da fonte para se adaptar à tela menor sem perder destaque */
    padding: 0.2rem 0.4rem; /* Ajusta o espaçamento interno para manter proporção visual e evitar que o destaque fique "inchado" em telas pequenas */
  }
}


/* ===================== LISTAS E LINKS ===================== */
.mensagem-lei ul {
  padding-left: 1.5rem; /* Adiciona recuo à esquerda para destacar os itens da lista e evitar que fiquem colados à margem */
}
.mensagem-lei li {
  margin-bottom: 0.5rem; /* Espaço entre os itens da lista para melhorar a leitura e evitar visual "amontoado" */
}
.mensagem-lei a {
  color: #0066cc; /* Azul institucional para links, reforça confiabilidade e visibilidade */
  text-decoration: underline; /* Sublinha os links para indicar claramente que são clicáveis */
}
.mensagem-lei a:hover {
  text-decoration: none; /* Remove o sublinhado ao passar o mouse, criando um efeito visual sutil e moderno */
}
/* ===================== RESPONSIVO PARA TELAS MENORES ===================== */
@media screen and (max-width: 768px) {
  /* Aplica estilos específicos para dispositivos com largura de tela até 768px — celulares e tablets */

  .lei-container {
    padding: 1rem;         /* Reduz o espaçamento interno para acomodar melhor o conteúdo em telas pequenas */
    margin: 1rem auto;     /* Diminui o espaço externo e mantém o bloco centralizado */
  }

  .mensagem-lei h2 {
    font-size: 1.2rem;     /* Reduz o tamanho do título principal para manter legibilidade sem ocupar espaço excessivo */
  }

  .mensagem-lei h3 {
    font-size: 1rem;       /* Ajusta o subtítulo intermediário para caber melhor em telas menores */
  }

  .mensagem-lei h4 {
    font-size: 0.95rem;    /* Reduz o subtítulo menor para manter proporção e fluidez visual */
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
  width: 250px; /* Aumenta levemente o tamanho da imagem */
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
  margin-top: 1.1rem; /* Espaço acima do subtítulo */
  font-size: 1.2rem; /* Tamanho do subtítulo */
  color: #444; /* Cor intermediária */
}
.mensagem p {
  font-size: 1rem; /* Tamanho do texto institucional */
  line-height: 1.6; /* Altura da linha para melhor leitura */
  color: #555; /* Cor suave para leitura prolongada */
}
/* ===================== DESTAQUE NO SUBTÍTULO ===================== */
.destaque {
  color: #b22222; /* Vermelho escuro para chamar atenção */
  font-weight: bold; /* Negrito para reforçar o destaque */
}
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
@media (max-width: 768px) {
  .representacao-Dr\.Leandro figcaption {
    font-size: 0.95rem; /* Reduz levemente o tamanho da fonte para se adaptar a telas menores */
    padding: 0.75rem;   /* Ajusta o espaçamento interno para manter proporção visual */
  }
}

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
  text-align: center;
  margin: 1.5rem auto;
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  font-weight: 600;
  line-height: 1.4;
  color: #2c2c2c;
  letter-spacing: 0.5px;
}


.conteudo-principal h3 {
  text-align: center;
  margin: 1.0rem auto;
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  font-weight: 600;
  line-height: 1.4;
  color: #2c2c2c;
  letter-spacing: 0.2px;
}
.conteudo-principal h4 {
  text-align: center;
  margin: 1.5rem auto;
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  font-weight: 600;
  line-height: 1.4;
  color: #2c2c2c;
  letter-spacing: 0.5px;
}

/* Parágrafos */
.conteudo-principal p {
  margin-bottom: 0em;   /* Espaço entre parágrafos para leitura fluida e respiro visual */
}/*💡 Dica: O espaçamento entre parágrafos é uma técnica editorial que melhora a escaneabilidade e o ritmo da leitura — especialmente em narrativas jurídicas ou humanas.*/
/* Listas */
.conteudo-principal ul {
  padding-left: 1.5rem;    /* Recuo à esquerda para destacar os itens da lista e evitar que fiquem colados à margem */
  margin-bottom: 1rem;     /* Espaço abaixo da lista para separar do próximo bloco de texto */
}

.conteudo-principal li {
  margin-bottom: 0.5rem;   /* Espaço entre os itens da lista para evitar visual "amontoado" */
}
/* Ênfase e destaque */
.conteudo-principal em {
  font-style: italic; /* Aplica itálico para indicar ênfase leve, como termos jurídicos, expressões ou reflexões */
  color: #444;         /* Tom neutro e suave para manter legibilidade sem chamar atenção excessiva */
}/*💡 O uso de <em> é ideal para trechos que precisam de atenção sutil — como citações indiretas, termos técnicos ou nuances emocionais.*/
.conteudo-principal strong {
  font-weight: bold; /* Aplica negrito para destacar trechos importantes, como nomes, datas ou argumentos centrais */
  color: #222;        /* Tom escuro para reforçar contraste e autoridade visual */
}/*💡 O <strong> é perfeito para reforçar pontos-chave da narrativa, como decisões jurídicas, frases impactantes ou viradas de contexto.*/
/* Links internos ou externos (se houver) */
.conteudo-principal a {
  color: #0066cc;              /* Azul institucional para indicar claramente que é um link clicável */
  text-decoration: underline;  /* Sublinha o link para reforçar a interatividade e acessibilidade */
}/*💡 Esse estilo é clássico e funcional — o azul com sublinhado é reconhecido universalmente como link, o que melhora a usabilidade.*/
.conteudo-principal a:hover {
  text-decoration: none;       /* Remove o sublinhado ao passar o mouse, criando um efeito visual sutil e moderno */
}/*💡 Esse hover dá um toque de refinamento visual sem comprometer a clareza. O link continua azul, mas com uma leve suavização na interação.*/


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

.logo-suave-perfil {
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
.logo-suave-perfil:hover {
  opacity: 1; /* Destaca ao passar o mouse: garante que a imagem fique totalmente visível, caso tenha sido estilizada com opacidade reduzida inicialmente */
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


/* ===================== ALINHAMENTO FINAL DAS COLUNAS DO GRID ===================== */
.perfil-container,
.conteudo-principal,
.lei-container {
  height: 100%;           /* Faz com que cada coluna ocupe toda a altura disponível do grid pai */
  display: flex;          /* Ativa Flexbox para organizar os elementos internos */
  flex-direction: column; /* Empilha os elementos verticalmente dentro de cada coluna */
}

/* ===================== AJUSTES FINAIS PARA ALINHAMENTO E VISIBILIDADE ===================== */

/* Garante que as colunas do grid cresçam igualmente */
.perfil-container,
.conteudo-principal,
.lei-container {
  display: flex;             /* Ativa Flexbox para organizar os elementos internos */
  flex-direction: column;    /* Empilha os elementos verticalmente dentro de cada coluna */
  height: 100%;              /* Faz com que cada coluna ocupe toda a altura disponível do grid pai */
  flex-grow: 1;              /* Permite que cada coluna cresça proporcionalmente dentro do grid, ocupando o espaço restante */
  min-height: 100%;          /* Garante que a altura mínima seja igual à do grid pai, evitando colapsos em layouts dinâmicos */
}

/* Evita corte de conteúdo nos anúncios */
#anuncios-perfil-container {
  flex-grow: 1;         /* Permite que o container dos anúncios cresça e ocupe o espaço disponível dentro do layout flexível */
  flex-shrink: 0;       /* Impede que o container encolha quando o espaço for reduzido — preserva a área mínima necessária */
  flex-basis: auto;     /* Define a base de tamanho como automática, respeitando o conteúdo interno */
  overflow: visible;    /* Garante que nenhum conteúdo interno seja cortado — mesmo que ultrapasse os limites do container */
}

/* ==================================================
   AJUSTES FINAIS: ALINHAMENTO DE COLUNAS E ANÚNCIOS
   ================================================== */

/* 1) Força o mesmo comportamento flex nas 3 colunas do grid */
.perfil-container,
.conteudo-principal,
.lei-container {
  display: flex;             /* Ativa Flexbox para organizar os elementos internos */
  flex-direction: column;    /* Empilha os elementos verticalmente dentro de cada coluna */
  height: 100%;              /* Faz com que cada coluna ocupe toda a altura da célula do grid pai */
  flex-grow: 1;              /* Permite que cada coluna cresça proporcionalmente, ocupando o espaço restante */
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
  margin-top: 2rem;         /* Cria espaçamento acima do bloco para separá-lo do conteúdo anterior */
  display: flex;            /* Ativa Flexbox para organizar os anúncios verticalmente */
  flex-direction: column;   /* Empilha os anúncios um abaixo do outro */
  gap: 1.5rem;              /* Espaço entre os anúncios para evitar visual "amontoado" e melhorar a leitura */
}


/* Card de publicidade */
.publicidade {
  background-color: #f0f0f0;       /* Fundo cinza claro para destacar o card sem competir com o conteúdo principal */
  padding: 1rem;                   /* Espaço interno para respiro visual e conforto na leitura */
  border-radius: 6px;              /* Cantos suavemente arredondados para estética moderna e amigável */
  box-shadow: 0 0 6px rgba(0,0,0,0.05); /* Sombra leve para dar profundidade e separar do fundo da página */
  text-align: center;              /* Centraliza o texto e elementos internos — ideal para chamadas ou logos */
  font-size: 0.9rem;               /* Tamanho de fonte discreto, mas legível — não rouba atenção do conteúdo principal */
  color: #444;                     /* Tom escuro suave para garantir contraste e leitura confortável */
}
.secao-publicidade .logo-suave {
  width: 100%;                    /* Ocupa toda a largura disponível do container pai */
  max-width: 250px;               /* Limita a largura para evitar que a imagem estoure o card */
  height: auto;                   /* Mantém a proporção original da imagem */
  border-radius: 8px;             /* Cantos arredondados para visual moderno e amigável */
  box-shadow: 0 4px 10px rgba(0,0,0,0.1); /* Sombra leve para destacar a imagem sem exagero */
  margin: 0 auto 1rem;            /* Centraliza horizontalmente e adiciona espaço abaixo */
  display: block;                 /* Garante que a imagem se comporte como bloco */
  object-fit: cover;              /* Preenche o espaço cortando inteligentemente sem distorcer */
  opacity: 0.85;                  /* Aplica leve transparência para efeito suave */
  transition: opacity 0.3s ease; /* Suaviza a transição ao passar o mouse */
}
.secao-publicidade .logo-suave:hover {
  opacity: 1; /* Ao passar o mouse, a imagem fica totalmente visível — reforça interatividade */
}/*💡 Esse efeito de hover é sutil e elegante, ideal para logos institucionais ou fotos de equipe.*/

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


/* ==================================================
   POWERED-BY (FOOTER)
   ================================================== */
/* ===================== RODAPÉ (mantido) ===================== */
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

.citacao-precedente {
  background-color: #f9f9f9;           /* Fundo claro para destacar o bloco sem competir com o conteúdo principal */
  border-left: 4px solid #8b0000;      /* Faixa vermelha à esquerda — remete à seriedade e autoridade jurídica */
  padding: 1.5rem;                     /* Espaço interno generoso para respiro visual */
  margin-top: 2rem;                    /* Espaço acima para separar do conteúdo anterior */
  border-radius: 8px;                  /* Cantos arredondados para suavidade estética */
  box-shadow: 0 2px 10px rgba(0,0,0,0.05); /* Sombra leve para profundidade e destaque */
  font-family: 'Georgia', serif;       /* Fonte clássica e editorial — reforça tom jurídico e institucional */
  color: #333;                         /* Tom escuro neutro para leitura confortável */
}
.citacao-precedente h4 {
  font-size: 1.2rem;       /* Tamanho equilibrado para título interno */
  color: #8b0000;          /* Vermelho institucional — reforça autoridade e destaque */
  margin-bottom: 1rem;     /* Espaço abaixo para separar do conteúdo seguinte */
  font-weight: bold;       /* Negrito para reforçar hierarquia visual */
}
.citacao-precedente blockquote {
  margin: 0;                      /* Remove margens padrão para controle total do layout */
  padding-left: 1rem;            /* Recuo interno para separar do traço lateral */
  border-left: 3px solid #ccc;   /* Faixa cinza clara para reforçar visual de citação */
  font-style: italic;            /* Itálico para tom editorial e reflexivo */
  color: #444;                   /* Tom suave para leitura prolongada */
}
.citacao-precedente blockquote p {
  font-size: 1.1rem;             /* Tamanho levemente maior para dar destaque à fala citada */
  line-height: 1.6;              /* Espaçamento confortável para leitura fluida */
}
.citacao-precedente footer {
  margin-top: 0.5rem;            /* Espaço acima para separar da citação principal */
  font-size: 0.95rem;            /* Tamanho menor para indicar fonte ou referência */
  color: #666;                   /* Tom discreto para não competir com o conteúdo principal */
}
.citacao-precedente p {
  margin-top: 1rem;              /* Espaço acima para separar do bloco anterior */
  font-size: 0.95rem;            /* Tamanho menor para conteúdo explicativo ou contextual */
  line-height: 1.6;              /* Espaçamento confortável para leitura fluida */
}
.citacao-precedente a {
  color: #8b0000;                /* Vermelho institucional para manter consistência com o destaque do bloco */
  text-decoration: underline;    /* Sublinha para indicar interatividade */
  font-weight: bold;             /* Negrito para reforçar importância do link */
}

/* ===================== CONTAINER GERAL DA LEI ===================== */
.lei-container {
  width: 100%;                   /* Ocupa toda a largura disponível do grid pai */
  max-width: 1000px;             /* Limita a largura para manter legibilidade em telas grandes */
  margin: 2rem auto;             /* Espaço vertical e centralização horizontal */
  padding: 1.5rem;               /* Espaço interno para respiro do conteúdo */
  background-color: #fff;        /* Fundo branco para contraste e destaque institucional */
  border-left: 1px solid #ddd;   /* Linha sutil à esquerda — remete à separação visual como em colunas jurídicas */
  border-radius: 8px;            /* Cantos suavemente arredondados para estética moderna */
  box-shadow: 0 0 10px rgba(0,0,0,0.05); /* Sombra leve para profundidade e destaque sem exagero */
  box-sizing: border-box;       /* Inclui padding e borda no cálculo da largura — evita quebra de layout */
  display: flex;                 /* Ativa Flexbox para organizar os elementos internos */
  flex-direction: column;       /* Empilha os elementos verticalmente */
  gap: 2rem;                     /* Espaço entre os blocos internos — ideal para separar seções jurídicas ou narrativas */
}

/* ===================== ARTICLE E SEÇÃO ===================== */
.qual_foi_lei_usada,
.secao-lei-usada {
  width: 100%; /* Garante que os elementos ocupem toda a largura disponível do container pai */
}/*💡 Ideal para títulos, subtítulos ou blocos explicativos que precisam se alinhar com o restante do conteúdo jurídico.*/
.container-lei-usada {
  display: flex;             /* Ativa Flexbox para organizar os elementos internos */
  flex-direction: column;    /* Empilha os elementos verticalmente — ótimo para artigos, incisos e parágrafos */
  gap: 1.5rem;               /* Espaço entre os elementos para evitar visual "amontoado" e facilitar leitura */
}/*💡 Esse gap é excelente para separar trechos legais, como artigos e incisos, mantendo clareza e ritmo visual.*/


/* ===================== TEXTO JURÍDICO ===================== */
.mensagem-lei {
  color: #333;           /* Tom escuro neutro — ideal para leitura prolongada e compatível com fundo claro */
  line-height: 1.6;      /* Espaçamento entre linhas confortável — evita cansaço visual em textos densos como leis e pareceres */
}

.mensagem-lei h2,
.mensagem-lei h3,
.mensagem-lei h4 {
  margin-bottom: 0.5rem;  /* Espaço abaixo de cada título para separar do conteúdo seguinte — evita visual colado */
  font-weight: bold;      /* Negrito para reforçar a hierarquia e dar destaque ao título jurídico */
}
.mensagem-lei h2 {
  font-size: 1.4rem;     /* Título principal da seção jurídica — destaque visual forte */
  color: #0055aa;        /* Azul institucional para reforçar autoridade e seriedade */
}
.mensagem-lei h3 {
  font-size: 1.2rem;     /* Subtítulo intermediário — hierarquia abaixo do h2 */
  color: #0077cc;        /* Azul mais claro para diferenciar visualmente do h2 */
  margin-top: 1.5rem;    /* Espaço acima para separar do bloco anterior */
}
.mensagem-lei h4 {
  font-size: 1.1rem;     /* Título de menor hierarquia — ideal para incisos ou parágrafos específicos */
  color: #444;           /* Tom neutro para manter sobriedade sem perder contraste */
  margin-top: 1rem;      /* Espaço acima para separar do conteúdo anterior */
}/*💡 Essa hierarquia de cores e tamanhos cria uma estrutura visual clara e respeita o tom jurídico do conteúdo.*/
.destaque {
  background-color: #e0f0ff;     /* Fundo azul claro — chama atenção sem agressividade */
  padding: 0.2rem 0.5rem;        /* Espaço interno para respiro visual */
  border-radius: 4px;            /* Cantos suavemente arredondados para estética moderna */
  font-weight: bold;            /* Negrito para reforçar a importância do trecho destacado */
  color: #b22222;               /* Vermelho escuro — forte contraste para chamar atenção ao conteúdo */
}

/* ===================== LISTAS E LINKS ===================== */
.mensagem-lei ul {
  padding-left: 1.5rem; /* Recuo à esquerda para destacar os itens da lista — evita que fiquem colados à margem */
}

.mensagem-lei li {
  margin-bottom: 0.5rem; /* Espaço abaixo de cada item da lista — evita visual colado */
}

.mensagem-lei a {
  color: #0066cc;
  text-decoration: underline;
}/* Estilo clássico de link: azul com sublinhado para indicar interatividade */

.mensagem-lei a:hover {
  text-decoration: none;
}/* Efeito hover: remove sublinhado para um visual mais limpo ao interagir */

/* ===================== ASIDE: CITAÇÃO E IMAGEM ===================== */
.citacao-precedente {
  background-color: #f9f9f9;           /* Fundo cinza claro — destaca o bloco sem competir com o conteúdo principal */
  border-left: 4px solid #8b0000;      /* Faixa vermelha à esquerda — remete à seriedade e autoridade jurídica */
  padding: 1.5rem;                     /* Espaço interno generoso para conforto na leitura */
  border-radius: 8px;                  /* Cantos suavemente arredondados — estética moderna e amigável */
  box-shadow: 0 2px 10px rgba(0,0,0,0.05); /* Sombra leve para profundidade e separação visual */
  font-family: 'Georgia', serif;       /* Fonte clássica e editorial — reforça tom jurídico e institucional */
  color: #333;                         /* Tom escuro neutro — ideal para leitura prolongada */
}
.citacao-precedente h4 {
  font-size: 1.2rem;     /* Tamanho equilibrado para título interno — destaque sem exagero */
  color: #8b0000;        /* Vermelho institucional — reforça autoridade jurídica */
  margin-bottom: 1rem;   /* Espaço abaixo para separar do conteúdo seguinte */
}
.citacao-precedente blockquote {
  margin: 0;                      /* Remove margens padrão — controle total do layout */
  padding-left: 1rem;            /* Recuo interno para separar do traço lateral */
  border-left: 3px solid #ccc;   /* Faixa cinza clara — reforça visual de citação */
  font-style: italic;            /* Itálico para tom editorial e reflexivo */
  color: #444;                   /* Tom suave para leitura prolongada */
}
.citacao-precedente blockquote p {
  font-size: 1.1rem;             /* Tamanho levemente maior — dá destaque à fala citada */
  line-height: 1.6;              /* Espaçamento confortável para leitura fluida */
}
.citacao-precedente footer {
  margin-top: 0.5rem;            /* Espaço acima para separar da citação principal */
  font-size: 0.95rem;            /* Tamanho menor — ideal para fonte ou referência */
  color: #666;                   /* Tom discreto — não compete com o conteúdo principal */
}
.citacao-precedente p {
  margin-top: 1rem;              /* Espaço acima — separa do bloco anterior */
  font-size: 0.95rem;            /* Tamanho menor — ideal para explicações ou contexto */
  line-height: 1.6;              /* Espaçamento confortável para leitura fluida */
}
.citacao-precedente a {
  color: #8b0000;                /* Vermelho institucional — mantém consistência com o destaque do bloco */
  text-decoration: underline;    /* Sublinha — reforça interatividade e acessibilidade */
  font-weight: bold;             /* Negrito — destaca links importantes como fontes ou decisões */
}

/* ===================== IMAGEM E LEGENDA ===================== */
.representacao-hopeup {
  margin-top: 1.5rem;       /* Espaço acima para separar do conteúdo anterior */
  text-align: center;       /* Centraliza imagem e legenda — ótimo para destaque visual */
}
.representacao-hopeup img {
  width: 100%;              /* Ocupa toda a largura disponível do container */
  max-width: 600px;         /* Limita a largura para manter legibilidade e evitar distorções */
  height: auto;             /* Mantém proporção original da imagem */
  border-radius: 8px;       /* Cantos suavemente arredondados — estética moderna e amigável */
  box-shadow: 0 4px 12px rgba(0,0,0,0.1); /* Sombra leve para profundidade e destaque visual */
}/*💡 Ideal para imagens institucionais, retratos, gráficos ou ilustrações jurídicas.*/
.representacao-hopeup figcaption {
  margin-top: 0.5rem;       /* Espaço acima para separar da imagem */
  font-style: italic;       /* Itálico para tom editorial e explicativo */
  font-size: 0.9rem;        /* Tamanho discreto — não compete com o conteúdo principal */
  color: #555;              /* Tom suave para leitura confortável */
}

/* ===================== LINK FINAL SUTIL ===================== */
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
.powered-by {
  flex-wrap: wrap;        /* Permite que os elementos internos quebrem linha — útil em rodapés com múltiplos logos ou links */
  color: #eceef3;         /* Tom claro — combina com fundo escuro típico de rodapés */
}
.perfil-ajuda {
  background-color: #fff;       /* Fundo branco — mantém consistência com o layout principal */
  border-radius: 8px;           /* Cantos arredondados — visual moderno e acolhedor */
  box-shadow: 0 0 10px rgba(0,0,0,0.05); /* Sombra leve — destaca o bloco sem exagero */
  padding: 1.5rem;              /* Espaço interno generoso — conforto na leitura */
  margin-top: 2rem;             /* Espaço acima — separa do conteúdo anterior */
  font-size: 0.95rem;           /* Tamanho discreto — ideal para instruções ou orientações */
  color: #444;                  /* Tom escuro suave — leitura confortável */
}
.secao-ajuda {
  padding: 1rem 0;              /* Espaço vertical — separa seções internas */
}
.container-ajuda {
  display: flex;                /* Ativa Flexbox para organizar os elementos internos */
  flex-direction: column;      /* Empilha os elementos verticalmente */
  gap: 1rem;                    /* Espaço entre os elementos — evita visual amontoado */
}
.perfil-ajuda h3 {
  font-size: 1.1rem;            /* Tamanho equilibrado — destaque sem exagero */
  color: #0077cc;               /* Azul institucional — reforça tom informativo */
  margin-bottom: 0.5rem;        /* Espaço abaixo — separa do conteúdo seguinte */
}
.perfil-ajuda ul {
  padding-left: 1.5rem;       /* Recuo à esquerda — separa os itens da margem e melhora a escaneabilidade */
  list-style-type: disc;      /* Marcadores em bolinha — visual clássico e limpo para listas de ajuda ou instruções */
}
.perfil-ajuda li {
  margin-bottom: 0.5rem;      /* Espaço entre os itens — evita visual amontoado */
  line-height: 1.6;           /* Espaçamento entre linhas — leitura confortável mesmo em itens com mais de uma linha */
}
.perfil-container,
.conteudo-principal,
.lei-container {
  display: flex;                  /* Ativa Flexbox — controle total sobre o layout interno */
  flex-direction: column;        /* Empilha os elementos verticalmente */
  justify-content: space-between;/* Distribui espaço entre os elementos — útil para rodapés fixos ou conteúdo fluido */
  flex-grow: 1;                  /* Permite que o container cresça para ocupar o espaço disponível */
  min-height: 100%;              /* Garante que o container ocupe toda a altura da viewport — essencial para layout de página inteira */
}/*💡 Esse bloco é poderoso para criar layouts responsivos e estruturados, especialmente em páginas com rodapé fixo ou conteúdo dinâmico.*/
.perfil-container > * {
  flex: 0 0 auto;                /* Impede que os filhos cresçam ou encolham — mantém tamanho natural dos elementos */
}/*💡 Isso garante que cada elemento dentro de .perfil-container mantenha seu tamanho original, sem distorções causadas pelo Flexbox.*/


#anuncios-perfil-container,
.perfil-ajuda,
.perfil-anuncie-aqui {
  flex-grow: 1; /* Permite que esses blocos ocupem o espaço disponível na coluna — ideal para layout fluido */
}

.perfil-anuncie-aqui {
  background-color: #fff;       /* Fundo branco — mantém consistência com o layout principal */
  border-radius: 8px;           /* Cantos arredondados — visual moderno e acolhedor */
  box-shadow: 0 0 10px rgba(0,0,0,0.05); /* Sombra leve — destaca o card sem exagero */
  padding: 1.5rem;              /* Espaço interno generoso — conforto na leitura */
  margin-top: 2rem;             /* Espaço acima — separa do conteúdo anterior */
  display: flex;                /* Ativa Flexbox para organizar os elementos internos */
  flex-direction: column;      /* Empilha os elementos verticalmente */
  align-items: center;         /* Centraliza os elementos — ideal para imagem e texto alinhados */
  font-size: 0.95rem;           /* Tamanho discreto — ideal para texto explicativo ou promocional */
  color: #444;                  /* Tom escuro suave — leitura confortável */
  flex-grow: 1;                 /* Permite que o card ocupe espaço proporcional na coluna */
}
.secao-anuncie-aqui {
  width: 100%; /* Garante que a seção ocupe toda a largura disponível do card */
}
.container-anuncie-aqui {
  display: flex;             /* Ativa Flexbox para organizar os elementos internos */
  flex-direction: column;    /* Empilha os elementos verticalmente */
  align-items: center;       /* Centraliza os elementos — ideal para imagem e texto alinhados */
  gap: 1rem;                 /* Espaço entre os elementos — evita visual amontoado */
  text-align: center;        /* Centraliza o texto — reforça o foco institucional ou promocional */
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
.perfil-anuncie-aqui p {
  line-height: 1.6; /* Espaçamento entre linhas — leitura confortável para textos explicativos ou promocionais */
}


/* ========== TELAS MUITO PEQUENAS (até 480px) ========== */
@media screen and (max-width: 480px) {
  body {
    font-size: 0.9rem; /* Reduz o tamanho base da fonte para melhor adaptação em telas pequenas */
  }



  .titulo-flex h1,
  .mensagem h2,
  .conteudo-principal h2 {
    font-size: 1.4rem; /* Reduz os títulos principais para evitar quebra de linha ou sobrecarga visual */
  }

  .titulo-flex h2,
  .mensagem h3,
  .conteudo-principal h3 {
    font-size: 1.1rem; /* Ajusta subtítulos para manter hierarquia sem ocupar espaço excessivo */
  }

  .subtitulo,
  .mensagem p,
  .conteudo-principal p,
  .mensagem-lei p,
  .perfil-ajuda p {
    font-size: 0.9rem; /* Uniformiza o tamanho dos parágrafos — leitura confortável em telas pequenas */
  }

  .perfil-dr-leandro img,
  .logo-suave-perfil,
  .logo-suave-anuncie {
    max-width: 180px; /* Limita a largura das imagens — evita distorções ou quebra de layout */
  }


    .conteudo-grid {
    grid-template-columns: 1fr; /* Converte o layout para uma única coluna — ideal para mobile */
    padding: 1rem;              /* Reduz o espaçamento interno para melhor aproveitamento da tela */
  }


  .lei-container,
  .perfil-container,
  .conteudo-principal {
    padding: 1rem;              /* Reduz o espaçamento interno — mais compacto e funcional */
    margin: 1rem 0;             /* Margem vertical equilibrada — evita excesso de espaço em telas pequenas */
  }


  .imagem-flex img {
    max-height: 400px; /* Limita a altura da imagem — evita que ultrapasse a viewport vertical */
  }
}



/* ========== TELAS PEQUENAS (481px a 768px) ========== */
@media screen and (min-width: 481px) and (max-width: 768px) {
  .titulo-flex h1 {
    font-size: 1.8rem; /* Reduz o título principal para se adaptar ao espaço sem perder impacto */
  }

  .titulo-flex h2 {
    font-size: 1.4rem; /* Subtítulo com destaque moderado — mantém hierarquia visual */
  }

  .subtitulo {
    font-size: 1rem;   /* Tamanho equilibrado para subtítulos explicativos */
  }


  .mensagem h2,
  .conteudo-principal h2 {
    font-size: 1.6rem; /* Título de seção — destaque sem exagero */
  }

  .mensagem h3,
  .conteudo-principal h3 {
    font-size: 1.2rem; /* Subtítulo de seção — mantém estrutura clara */
  }


  .mensagem p,
  .conteudo-principal p,
  .mensagem-lei p {
    font-size: 0.95rem; /* Leitura confortável — nem grande demais, nem apertado */
  }


  .conteudo-grid {
    grid-template-columns: 1fr 2fr; /* Layout com coluna lateral menor — ideal para anúncios ou navegação */
    column-gap: 1rem;               /* Espaço entre colunas — evita visual colado */
    padding: 1.5rem;                /* Espaço interno equilibrado para tablets */
  }


  .imagem-flex img {
    max-height: 600px; /* Limita a altura da imagem — evita que ultrapasse a viewport vertical */
  }
}


/* ========== TELAS MÉDIAS (769px a 1200px) ========== */
@media screen and (min-width: 769px) and (max-width: 1200px) {
  .titulo-flex h1 {
    font-size: 2rem;
  }

  .titulo-flex h2 {
    font-size: 1.6rem;
  }

  .subtitulo {
    font-size: 1.1rem;
  }

  .mensagem h2,
  .conteudo-principal h2 {
    font-size: 1.8rem;
  }

  .mensagem h3,
  .conteudo-principal h3 {
    font-size: 1.4rem;
  }

  .mensagem p,
  .conteudo-principal p,
  .mensagem-lei p {
    font-size: 1rem;
  }

  .conteudo-grid {
    grid-template-columns: 1fr 4fr 2fr;
    column-gap: 2rem;
    padding: 2rem;
  }

  .imagem-flex img {
    max-height: 700px;
  }
}

/* ========== TELAS GRANDES (1201px a 1920px) ========== */
@media screen and (min-width: 1201px) and (max-width: 1920px)/*💡 Abrange dispositivos intermediários — garante que o layout fique fluido e legível em resoluções médias.*/ {
  .titulo-flex h1 {
    font-size: 2rem; /* Título principal — mantém destaque sem exagero */
  }

  .titulo-flex h2 {
    font-size: 1.6rem; /* Subtítulo — hierarquia clara e proporcional à tela */
  }

  .subtitulo {
    font-size: 1.1rem; /* Texto explicativo — leitura confortável */
  }


  .mensagem h2,
  .conteudo-principal h2 {
    font-size: 1.8rem; /* Título de seção — destaque equilibrado */
  }

  .mensagem h3,
  .conteudo-principal h3 {
    font-size: 1.4rem; /* Subtítulo de seção — mantém estrutura clara */
  }


  .mensagem p,
  .conteudo-principal p,
  .mensagem-lei p {
    font-size: 1rem; /* Leitura confortável — ideal para textos jurídicos e explicativos */
  }


    .conteudo-grid {
    grid-template-columns: 1fr 4fr 2fr; /* Layout com coluna lateral, conteúdo principal e apoio — bem distribuído */
    column-gap: 2rem;                   /* Espaço entre colunas — evita visual colado */
    padding: 2rem;                      /* Espaço interno generoso — ideal para telas médias */
  }


    .imagem-flex img {
    max-height: 700px; /* Limita a altura da imagem — evita que ultrapasse a viewport vertical */
  }
}


/* ========== TELAS EXTRA GRANDES (acima de 1921px até 3840px) ========== */
@media screen and (min-width: 1921px)/*💡 Abrange resoluções acima de Full HD — garante que o layout se expanda com elegância sem parecer vazio ou desproporcional.*/ {
    body {
    font-size: 1.2rem; /* Aumenta a base da fonte — leitura confortável em telas grandes */
  }

  .titulo-flex h1 {
    font-size: 3rem; /* Título principal — presença forte e proporcional à tela */
  }

  .titulo-flex h2 {
    font-size: 2.2rem; /* Subtítulo — destaque visual sem exagero */
  }

  .subtitulo {
    font-size: 1.4rem; /* Texto explicativo — leitura fluida e elegante */
  }

  .mensagem h2,
  .conteudo-principal h2 {
    font-size: 2.4rem; /* Título de seção — reforça hierarquia visual */
  }

  .mensagem h3,
  .conteudo-principal h3 {
    font-size: 1.8rem; /* Subtítulo de seção — mantém estrutura clara */
  }

  .mensagem p,
  .conteudo-principal p,
  .mensagem-lei p {
    font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
  }


    .conteudo-grid {
    grid-template-columns: 1fr 6fr 3fr; /* Layout com coluna lateral, conteúdo principal e apoio — bem distribuído para telas largas */
    column-gap: 3rem;                   /* Espaço generoso entre colunas — evita visual comprimido */
    padding: 3rem;                      /* Espaço interno proporcional à resolução */
  }


    .imagem-flex img {
    max-height: 1000px; /* Permite imagens maiores — ideal para gráficos, retratos ou ilustrações em alta resolução */
  }
}
#aviso-narrativa {
  display: flex;
  flex-direction: column;
  width: 100%;
  box-sizing: border-box;
   background-color: #fff3cd; /* tom de aviso mais evidente */
   border-radius: 8px;        /* cantos suavemente arredondados */
}
#aviso-narrativa h5 {
  font-size: inherit;
  font-style: inherit;
  line-height: inherit;
  color: inherit;
  margin: 0;
  padding: 0;
  width: 100%;
  text-align: justify;
  box-sizing: border-box;
}
@media screen and (max-width: 768px) {
  #aviso-narrativa {
    padding: 1rem 1.5rem; /* reduz o espaçamento lateral */
    border-radius: 6px;   /* cantos levemente mais compactos */
  }

  #aviso-narrativa h5 {
    font-size: 1rem;      /* reduz o tamanho da fonte */
    line-height: 1.5;     /* ajusta a altura da linha */
  }
}

@media screen and (max-width: 480px) {
  #aviso-narrativa {
    padding: 0.75rem 1rem; /* ainda mais compacto */
    border-radius: 4px;
  }

  #aviso-narrativa h5 {
    font-size: 0.95rem;
    line-height: 1.4;
  }
}
@media screen and (min-width: 1200px) {
  #aviso-narrativa {
    padding: 2rem 3rem;     /* mais respiro lateral */
    border-radius: 10px;    /* cantos mais suaves */
  }

  #aviso-narrativa h5 {
    font-size: 1.2rem;      /* texto mais confortável para leitura ampla */
    line-height: 1.7;
  }
}

@media screen and (min-width: 1920px) {
  #aviso-narrativa {
    padding: 2.5rem 4rem;   /* ainda mais espaçamento para telas ultrawide */
    border-radius: 12px;    /* estética editorial mais refinada */
  }

  #aviso-narrativa h5 {
    font-size: 1.3rem;      /* texto editorial com presença */
    line-height: 1.8;
  }
}

/*testes zoom*/

.titulo-flex h1 {
  font-size: 2.8rem;
}

.titulo-flex h2 {
  font-size: 2.2rem;
}

.titulo-flex .subtitulo {
  font-size: 1.3rem;
}
.conteudo-principal {
  font-size: 1.125rem; /* equivalente a 18px */
  line-height: 1.8;
}
.conteudo-principal h2,
.conteudo-principal h3 {
  font-size: 2.2rem;
}
main > section {
  margin-bottom: 3rem; /* aumenta o respiro entre blocos */
}


.citacao-precedente p,
.destaque p,
.mensagem-lei p,
.conteudo-principal p,
.container-anuncie-aqui p,
.mensagem p,
.container-ajuda p,
.destaque p {
  font-size: 1.5rem;
} /* Parágrafos maiores — ideal para leitura em telas amplas */

ul li {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}
.citacao-precedente blockquote p {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}
.citacao-precedente blockquote footer {
  font-size: 1.2rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}
.representacao-hopeup figcaption {
  font-size: 1.5rem; /* Legenda maior para melhor leitura */
}
.le_ruy_barbosa em {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}
.representacao-Dr\.Leandro em {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}
.destaque {
  font-size: 1.5rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
}
.container-lei-usada h2 {
  font-size: 2.2rem;
  text-align: center;
}
.container-lei-usada .destaque {
  font-size: 1.6rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
  text-align: center;
}
.container-lei-usada h4 {
  font-size: 1.6rem; /* Parágrafos maiores — ideal para leitura em telas amplas */
  text-align: center;
  margin-bottom: 1rem;
  margin-top: 2rem;
}

.conteudo-principal {
  font-size: 1.3rem;       /* Tamanho de fonte confortável para leitura — pode ser aumentado para dar mais impacto */
  line-height: 1.3;        /* Espaçamento generoso entre linhas, ideal para textos densos como jurídicos ou narrativos */
}
.conteudo-principal p {
  margin-bottom: 0.5rem; /* Espaço leve entre parágrafos */
}
.conteudo-principal h2 {
  margin: 0.25rem 0 0.5rem 0; /* topo menor, base mais próxima do conteúdo */
}
.conteudo-principal h3 {
  margin: 0.25rem 0 0.5rem 0;
}
.conteudo-principal {
  line-height: 1.5; /* ou até 1.6 se quiser suavidade */
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
.secao-ajuda,
.secao-publicidade,
.secao-anuncie-aqui {
  padding: 1.5rem;
  background-color: #ffffff;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.05);
  margin: 2rem auto;
  box-sizing: border-box;
}

.container-ajuda,
.container-publicidade,
.container-anuncie-aqui {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.titulo-publicidade {
  font-size: 1.4rem;
  color: #333;
  margin-bottom: 1rem;
  text-align: center;
}

.publicidade {
  background-color: #f0f0f0;
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 0 6px rgba(0,0,0,0.05);
  text-align: center;
  font-size: 0.95rem;
  color: #444;
}

.logo-suave-perfil,
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

.logo-suave-perfil:hover,
.logo-suave-anuncie:hover {
  opacity: 1;
}
@media (max-width: 768px) {
  .bloco-contato {
    padding: 0.75rem;
  }

  .botao-instagram,
  .botao-whatsapp {
    font-size: 0.95rem;
    padding: 0.4rem 0.8rem;
  }

  .logo-suave-perfil,
  .logo-suave-anuncie {
    max-width: 220px;
  }
}
.perfil-dr-leandro-2 {
  flex: 1 1 350px; /* Aumenta a largura mínima */
  max-width: 440px; /* Permite imagem maior */
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
  max-width: 500px; /* Tamanho vertical maior */
  height: auto;
  border-radius: 15px; /* Retira o formato circular */
  margin-bottom: 0;
  box-shadow: 0 0 6px rgba(0,0,0,0.1);
  object-fit: cover;
}

.texto-dr-leandro {
  flex: 2 1 500px;
  font-size: 1.1rem;
  line-height: 1.7;
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

.texto-dr-leandro ul {
  padding-left: 1.5rem;
  margin-bottom: 1rem;
}

.texto-dr-leandro li {
  margin-bottom: 0.5rem;
}
.citacao-precedente {
  margin-top: 3rem;
  padding: 2rem;
  background-color: #f5f5f5;
  border-left: 6px solid #ccc;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.04);
  font-size: 1rem;
  line-height: 1.6;
  color: #444;
}

.citacao-precedente h4 {
  font-size: 1.3rem;
  margin-bottom: 1rem;
  color: #2c2c2c;
}

.citacao-precedente blockquote {
  margin: 1rem 0;
  padding-left: 1rem;
  border-left: 4px solid #999;
  font-style: italic;
  color: #555;
}

.citacao-precedente footer {
  margin-top: 0.5rem;
  font-weight: bold;
  color: #333;
}

.representacao-hopeup {
  margin-top: 2rem;
  text-align: center;
}

.representacao-hopeup img.le_ruy_barb {
  max-width: 500px;
  width: 100%;
  border-radius: 6px;
  box-shadow: 0 0 6px rgba(0,0,0,0.1);
  margin-bottom: 0.5rem;
}

.representacao-hopeup figcaption {
  font-size: 1.4rem;
  color: #666;
  font-style: italic;
}

.link-sutil {
  text-align: center;
  margin-top: 1rem;
}

.link-sutil a {
  color: #0066cc;
  text-decoration: underline;
  font-weight: 500;
}
@media (max-width: 768px) {
  .layout-horizontal {
    flex-direction: column;
    align-items: center;
  }

  .perfil-dr-leandro-2,
  .texto-dr-leandro {
    max-width: 100%;
    flex: 1 1 100%;
  }

  .citacao-precedente {
    padding: 1.5rem;
  }
}

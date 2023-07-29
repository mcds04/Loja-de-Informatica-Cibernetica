# Loja-de-Informatica-Cibernetica
<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loja de Informática Cibernética</title>
  <!-- Link para o CSS do Bootstrap -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
    /* Estilos CSS para as seções */
    section {
      background-color: hsl(261, 49%, 23%);
      padding: 40px 0;
      color: #1a1010;
      /* Nova cor do texto das seções */
      width: 100%;
    }

    section legend {
      color: #fff9f9;
      font-size: 24px;
      font-weight: bold;
      text-align: center;
      padding: 10px;
      background-color: hsl(260, 82%, 29%);
      border-radius: 10px;

    }


    section h2,
    section p,
    titulo-secao {
      color: #ebdfdf;
    }

    .quem-somos img {
      width: 100%;
      height: auto;
    }

    .time-image {


      width: 200px;


      height: 200px;
    }

    .time-image-text {


      color: #007bff;
    }

    .nossos-produtos .card {
      background-color: #179db4;
      border-radius: 10px;
      padding: 20px;
    }

    .nossos-produtos .row {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
    }

    /* Estilos CSS para o rodapé */
    footer {
      background-color: hsl(259, 82%, 9%);
      color: #e2d9d9;
      text-align: center;
      padding: 10px 0;
    }

    footer.bg-dark {
      background-color: hsl(259, 82%, 9%);
    }

    footer.bg-roda-pe {
      background-color: #444;
      color: #fff;
    }

    footer p {
      margin: 0;
    }

    .social-icons a {
      color: #fff;
      margin-right: 10px;
    }

    .social-icons a:last-child {
      margin-right: 0;
    }
  </style>
</head>

<body>
  <!-- Barra de Navegação -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <a class="navbar-brand" href="#">Tech Co. MCDS</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#quem-somos">Quem Somos</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#Nosso-Time">Nosso Time</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#nossos-produtos">Nossos Produtos</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#mindset">Tech Co. Innovating</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#template-loja">Loja Tech Co. MCDS</a>
        </li>
      </ul>
    </div>
  </nav>
  <!-- Conteúdo do Carousel (pode ser adicionado aqui) -->
  <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="./Grid.Img - Copia/CelDesign.jpg" class="d-block w-100" alt="Imagem 1">
      </div>
      <div class="carousel-item">
        <img src="./Grid.Img - Copia/Apple1.jpg" class="d-block w-100" alt="Imagem 2">
      </div>
      <div class="carousel-item">
        <img src="./Grid.Img - Copia/Figura2.jpg" class="d-block w-100" alt="Imagem 3">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Anterior</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Próximo</span>
    </a>
  </div>

  <!-- Seção "Quem Somos" -->
  <section id="quem-somos" class="container mt-5 quem-somos">
    <fieldset>
      <legend class="titulo-secao">Quem Somos</legend>
      <div class="row">
        <div class="col-lg-6">
          <p>
            Somos uma empresa apaixonada por tecnologia, dedicada a desvendar o vasto universo da informática e suas
            infinitas possibilidades. Fundada com o objetivo de oferecer soluções inovadoras e serviços de excelência,
            embarcamos em uma jornada de conhecimento e evolução constante, impulsionando a transformação digital em
            todos
            os setores da sociedade.

            Nossa equipe é composta por profissionais altamente preparados, especialistas em diversas áreas da
            informática.
            Desde programadores talentosos até especialistas em segurança cibernética, incentivados em sinergia para
            fornecer soluções personalizadas e sob medida para atender às necessidades específicas de nossos clientes.

            Alicerçada em uma cultura de inovação, mantemos um olhar atento às tendências tecnológicas e nos esforçamos
            para
            estar sempre na vanguarda do mercado. A pesquisa e o desenvolvimento fazem parte do nosso DNA, pois
            acreditamos
            que só através do conhecimento e da criatividade é possível o crescimento tecnológico.

            Nossos valores fundamentais são a transparência, a ética e a confiança. Cada projeto é tratado com máxima
            confidencialidade.
          </p>
        </div>
        <div class="col-lg-6">
          <img src="./Grid.Img - Copia/Loja Tech Co. MCDS.png" class="img-fluid rounded" alt="Imagem da Empresa">
        </div>
      </div>
    </fieldset>
  </section>

  <!-- Seção "Nosso Time" -->
  <section id="Nosso-Time" class="container mt-5">
    <fieldset>
      <legend class="titulo-secao">Nosso Time</legend>
      <div class="row">
        <div class="col-lg-4 d-flex">
          <div class="align-items-center">
            <img src="./Grid.Img/FotoQuemSomos2.jpg" class="img-fluid rounded-circle time-image" alt="Membro 1">
            <h4 class="time-image-text">Secretária Executiva Sênior</h4>
          </div>
        </div>
        <div class="col-lg-4 d-flex">
          <div class="align-items-center">
            <img src="./Grid.Img/FotosQuemSomos5.jpg" class="img-fluid rounded-circle time-image" alt="Membro 2">
            <h4 class="time-image-text">Gerente Administrativo Geral</h4>
          </div>
        </div>
        <div class="col-lg-4 d-flex">
          <div class="align-items-center">
            <img src="./Grid.Img - Copia/236x163.png" class="img-fluid rounded-circle time-image" alt="Membro 3">
            <h4 class="time-image-text">Executivo de Finanças</h4>
          </div>
        </div>
      </div>
    </fieldset>
  </section>


  <!-- Seção "Nossos Produtos" -->
  <section id="nossos-produtos" class="container mt-3 nossos-produtos">
    <fieldset>
      <legend>Nossos Produtos</legend>
      <div class="row">
        <div class="col-lg-4 col-md-6">
          <div class="card">
            <img src="./Grid.Img/NossoProduto6PcGamer.png" class="card-img-top" alt="Produto 1">
            <div class="card-body">
              <h5 class="card-title">PC GAMER ALFHA</h5>
              <p class="card-text">EMAXX GAMER</p>
              <p class="card-text">Valor: R$5.490,90</p>

              <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#modalCompras"
                onclick="adicionarAoCarrinho('PC GAMER ALFHA', 5490.9)">Adicionar ao Carrinho</button>
            </div>
          </div>
        </div>
        <!-- Repita os cards para os outros produtos -->

        <!-- Card do Produto 2 -->
        <div class="col-lg-4 col-md-6">
          <div class="card">
            <img src="./Grid.Img/NossoProduto6CadeiraGamer.png" class="card-img-top" alt="Produto 2">
            <div class="card-body">
              <h5 class="card-title">CADEIRA GAMER</h5>
              <p class="card-text">EXTREME CONFORT</p>
              <p class="card-text">Valor: R$1.299,90</p>
              <button type="button" class="btn btn-primary"
                onclick="adicionarAoCarrinho('CADEIRA GAMER', 1299.9)">Adicionar
                ao Carrinho</button>
            </div>
          </div>
        </div>

        <!-- Card do Produto 3 -->
        <div class="col-lg-4 col-md-6">
          <div class="card">
            <img src="./Grid.Img/NossoProduto6Teclado.png" class="card-img-top" alt="Produto 3">
            <div class="card-body">
              <h5 class="card-title">TECLADO DESIGN</h5>
              <p class="card-text">TECLADO MECÂNICO</p>
              <p class="card-text">Valor: R$680,90</p>
              <button type="button" class="btn btn-primary"
                onclick="adicionarAoCarrinho('TECLADO DESIGN', 680.9)">Adicionar
                ao Carrinho</button>
            </div>
          </div>
        </div>

      </div>
    </fieldset>
  </section>

  <!-- Seção "Mindset" -->
  <section id="mindset" class="container mt-5">
    <fieldset>
      <legend>Tech Co. Innovating</legend>
      <div class="row">
        <div class="col-lg-6">
          <p>
            Nossa empresa de informática é enraizado na busca incessante pela inovação e excelência. Acreditamos que a
            tecnologia é a chave para impulsionar o progresso e transformar o mundo. Nossa equipe é movida pela
            curiosidade
            e disposição em enfrentar desafios complexos, sempre buscando soluções criativas para os problemas dos
            nossos
            clientes.

            Valorizamos a mentalidade colaborativa, onde o compartilhamento de conhecimento e a troca de ideias são
            fundamentais para o crescimento coletivo. Estamos comprometidos em manter-nos atualizados com as últimas
            tendências tecnológicas, investindo em treinamento contínuo para nossa equipe.

            A agilidade é um dos pilares do nosso mindset, permitindo-nos adaptar rapidamente às mudanças do mercado e
            entregar resultados com eficiência. Encaramos os erros como oportunidades de aprendizado e buscamos
            constantemente melhorar nossos processos e produtos.

            inovações que impactam positivamente na vida das pessoas.
          </p>
        </div>
        <div class="col-lg-6">
          <img src="./Grid.Img/mindset-da-inovacao.jpg" class="img-fluid" alt="Mindset da Empresa">
        </div>
      </div>
    </fieldset>
  </section>

  <!-- Template de Loja de Informática -->
  <section id="template-loja" class="container mt-5">
    <fieldset>
      <legend>Loja Tech Co. MCDS</legend>
      <p>
        Bem-vindo à nossa loja Tech Co. MCDS! Aqui você encontrará uma grande variedade de produtos e serviços de
        alta qualidade para atender todas as suas necessidades tecnológicas. Nossa equipe de especialistas está pronta
        para ajudá-lo a encontrar o produto certo para você.

        Oferecemos uma seleção completa de computadores, laptops, periféricos, componentes e acessórios das principais
        marcas do mercado. Nossos produtos são cuidadosamente selecionados para garantir desempenho excepcional e
        confiabilidade.

        Além disso, também fornecemos serviços de assistência técnica, reparo e manutenção para garantir que seus
        dispositivos funcionem perfeitamente. Nossa equipe de técnicos altamente qualificados está pronta para resolver
        qualquer problema que você possa enfrentar.

        Na nossa loja, você encontrará um ambiente acolhedor e amigável, onde poderá explorar os produtos e receber
        atendimento personalizado. Nossa missão é oferecer a melhor experiência de compra possível, para que você possa
        aproveitar ao máximo a tecnologia.

        Venha nos visitar e descubra o que há de mais moderno em informática. Estamos ansiosos para recebê-lo!

        <!-- Adicione mais informações sobre a loja, como horário de funcionamento, localização, etc. -->
        <!-- Seção "Horário de Funcionamento" -->
      <section id="horario-funcionamento" class="container mt-5">
        <fieldset>
          <legend>Horário de Funcionamento</legend>
          <div class="row">
            <div class="col-lg-12">
              <table class="table table-bordered">
                <thead>
                  <tr>
                    <th>Dia da Semana</th>
                    <th>Horário</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td>Segunda-feira</td>
                    <td>09:00 - 18:00</td>
                  </tr>
                  <tr>
                    <td>Terça-feira</td>
                    <td>09:00 - 18:00</td>
                  </tr>
                  <tr>
                    <td>Quarta-feira</td>
                    <td>09:00 - 18:00</td>
                  </tr>
                  <tr>
                    <td>Quinta-feira</td>
                    <td>09:00 - 18:00</td>
                  </tr>
                  <tr>
                    <td>Sexta-feira</td>
                    <td>09:00 - 18:00</td>
                  </tr>
                  <tr>
                    <td>Sábado</td>
                    <td>10:00 - 15:00</td>
                  </tr>
                  <tr>
                    <td>Domingo</td>
                    <td>Fechado</td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </fieldset>
      </section>

      </p>
    </fieldset>
  </section>

  <!-- Modal Suas Compras -->
  <div class="modal fade" id="modalCompras" tabindex="-1" role="dialog" aria-labelledby="modalComprasLabel"
    aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="modalComprasLabel">Suas Compras</h5>
          <button type="button" class="close" data-dismiss="modal" aria-label="Close">
            <span aria-hidden="true">&times;</span>
          </button>
        </div>
        <div class="modal-body">
          <div class="carrinho-compras">
            <!-- Conteúdo do carrinho de compras será adicionado dinamicamente aqui -->
          </div>
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-dismiss="modal">Fechar</button>
        </div>
      </div>
    </div>
  </div>


  <!-- Scripts do Bootstrap e jQuery -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  <script>
    function adicionarAoCarrinho(produto, valor) {
      const carrinhoCompras = document.querySelector('.carrinho-compras');
      const novoItem = document.createElement('p');
      novoItem.innerText = `${produto} - Valor: R$${valor.toFixed(2)}`;
      carrinhoCompras.appendChild(novoItem);
    }


  </script>
  <!-- Rodapé -->
  <footer class="bg-dark text-white text-center py-2">
    <p>Tech Co. MCDS &copy; 2023. Todos os direitos reservados.</p>
    <footer class="bg-roda-pe text-white text-center p-3">
      <div class="container">
        <!-- Conteúdo do Rodapé -->
        <div class="row">
          <div class="col-lg-4">
            <h4>Endereço</h4>
            <p>Travessa S-4, Nº 12A, Campina de Icoaraci- BELÉM/PA</p>
          </div>
          <div class="col-lg-4">
            <h4>Telefone</h4>
            <p>(91) 99100-0003</p>
          </div>
          <div class="col-lg-4">
            <h4>Redes Sociais</h4>
            <div class="social-icons">
              <a href="#" class="facebook"><i class="https://www.facebook.com/profile.php?id=100008301706573"></i></a>
              <a href="#" class="instagram"><i class="https://www.instagram.com/cristhysol/"></i></a>
            </div>
          </div>
        </div>
      </div>
    </footer>

</body>

</html>

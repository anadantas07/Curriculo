<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <title>Ana Clara Dantas | Portfólio</title>

  <!-- Bootstrap -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />

  <!-- Bootstrap Icons -->
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css"
  />

  <style>
    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      background: linear-gradient(135deg, #ffd6e7, #ffc2dc, #ff9fc5);
      min-height: 100vh;
      color: #fff;
    }

    .navbar{
      background-color: rgba(255,255,255,0.15);
      backdrop-filter: blur(10px);
    }

    .navbar-brand{
      color: white !important;
      font-weight: bold;
      font-size: 1.5rem;
    }

    .nav-link{
      color: white !important;
      transition: 0.3s;
    }

    .nav-link:hover{
      color: #ffe6f0 !important;
    }

    .hero{
      min-height: 90vh;
      display: flex;
      align-items: center;
    }

    .hero h1{
      font-size: 4rem;
      font-weight: bold;
    }

    .hero span{
      color: #fff0f6;
    }

    .hero p{
      font-size: 1.2rem;
      margin-top: 20px;
    }

    .btn-custom{
      background-color: white;
      color: #ff4f93;
      border: none;
      padding: 12px 28px;
      border-radius: 30px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn-custom:hover{
      background-color: #ffe6f0;
      transform: scale(1.05);
    }

    .card-custom{
      background-color: rgba(255,255,255,0.15);
      border: none;
      border-radius: 20px;
      backdrop-filter: blur(10px);
      color: white;
      transition: 0.3s;
      height: 100%;
    }

    .card-custom:hover{
      transform: translateY(-8px);
    }

    .section-title{
      font-size: 2.5rem;
      font-weight: bold;
      margin-bottom: 40px;
    }

    footer{
      padding: 30px 0;
      text-align: center;
      margin-top: 60px;
      background-color: rgba(255,255,255,0.12);
    }

    .social-icons a{
      color: white;
      font-size: 1.8rem;
      margin: 0 10px;
      transition: 0.3s;
    }

    .social-icons a:hover{
      color: #ffe6f0;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="#">
        Ana Clara Dantas
      </a>

      <button
        class="navbar-toggler bg-white"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#menu"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="menu">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#sobre">Sobre</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#projetos">Projetos</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#contato">Contato</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero container">
    <div class="row align-items-center">

      <div class="col-lg-7">
        <h1>
          Olá, eu sou <span>Ana Clara</span>
        </h1>

        <p>
          Estudante de Ciência de Dados, apaixonada por tecnologia,
          análise de dados e desenvolvimento de projetos visuais
          utilizando ferramentas como Power BI.
        </p>

        <div class="mt-4">
          <a
            href="https://docs.google.com/presentation/d/1N4LJJxP-pcvNcfMqpsFzWyolyJurccGmRxTL-ERy8Xc/edit?slide=id.p1#slide=id.p1"
            target="_blank"
            class="btn btn-custom me-3"
          >
            Ver Portfólio
          </a>

          <a
            href="https://www.linkedin.com/in/ana-clara-dantas-baa9313b0/"
            target="_blank"
            class="btn btn-outline-light rounded-pill px-4"
          >
            LinkedIn
          </a>
        </div>
      </div>

      <div class="col-lg-5 text-center mt-5 mt-lg-0">
        <img
          src="https://cdn-icons-png.flaticon.com/512/4140/4140048.png"
          class="img-fluid"
          width="350"
        />
      </div>

    </div>
  </section>

  <!-- Sobre -->
  <section id="sobre" class="container py-5">
    <h2 class="section-title text-center">
      Sobre Mim
    </h2>

    <div class="card card-custom p-4">
      <p>
        Meu nome é Ana Clara Dantas, tenho 18 anos e curso
        Ciência de Dados. Meu principal objetivo é desenvolver
        projetos modernos e impactantes, focados em análise
        de dados e visualização de informações.
      </p>

      <p>
        Atualmente venho construindo meu portfólio com projetos
        utilizando Power BI e ferramentas voltadas para dados,
        buscando evoluir constantemente na área de tecnologia.
      </p>
    </div>
  </section>

  <!-- Projetos -->
  <section id="projetos" class="container py-5">
    <h2 class="section-title text-center">
      Projetos
    </h2>

    <div class="row g-4">

      <div class="col-md-6">
        <div class="card card-custom p-4">
          <h3>
            <i class="bi bi-bar-chart-fill"></i>
            Projeto Power BI
          </h3>

          <p class="mt-3">
            Dashboard desenvolvido utilizando Power BI para
            análise e visualização de dados.
          </p>

          <a
            href="https://docs.google.com/presentation/d/1N4LJJxP-pcvNcfMqpsFzWyolyJurccGmRxTL-ERy8Xc/edit?slide=id.p1#slide=id.p1"
            target="_blank"
            class="btn btn-light mt-3"
          >
            Ver Projeto
          </a>
        </div>
      </div>

      <div class="col-md-6">
        <div class="card card-custom p-4">
          <h3>
            <i class="bi bi-graph-up-arrow"></i>
            Portfólio de Dados
          </h3>

          <p class="mt-3">
            Projetos voltados para análise de dados,
            dashboards interativos e apresentação visual
            de métricas.
          </p>

          <a
            href="https://docs.google.com/presentation/d/1N4LJJxP-pcvNcfMqpsFzWyolyJurccGmRxTL-ERy8Xc/edit?slide=id.p1#slide=id.p1"
            target="_blank"
            class="btn btn-light mt-3"
          >
            Abrir Portfólio
          </a>
        </div>
      </div>

    </div>
  </section>

  <!-- Contato -->
  <section id="contato" class="container py-5">
    <h2 class="section-title text-center">
      Contato
    </h2>

    <div class="card card-custom p-5 text-center">

      <h4>
        Vamos nos conectar!
      </h4>

      <p class="mt-3">
        Entre em contato pelo LinkedIn para oportunidades,
        networking e projetos.
      </p>

      <div class="social-icons mt-4">
        <a
          href="https://www.linkedin.com/in/ana-clara-dantas-baa9313b0/"
          target="_blank"
        >
          <i class="bi bi-linkedin"></i>
        </a>
      </div>

    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>
      © 2026 Ana Clara Dantas • Portfólio de Ciência de Dados
    </p>
  </footer>

  <!-- Bootstrap JS -->
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js">
  </script>

</body>
</html>

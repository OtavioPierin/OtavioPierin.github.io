<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <!-- Meu css-->
    <link rel="stylesheet" href="css/estilo.css">
    <link rel="stylesheet" href="css/galeria.css">


    <title>Hotel Pet</title>
</head>

<body>
    <!-- Cabeçalho -->
    <header class="p-3 bg-laranja text-white d-flex">
        <img src="img/logo.png" id="logo" alt="Logo Hotel">

        <h3 class="titulo">Hotel e creche para pets!</h3>
    </header>
    <!-- Barra de navegação -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-navbar">
        <div class="container-fluid">
            <!-- Botão Hamburguer -->
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu1"
                aria-controls="menu1" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapsed navbar-collapse" id="menu1">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" href="home.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="galeria.html">Galeria</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="forms.html">Reservas</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link active" href="quemsomos.html">Quem Somos</a>
                    </li>

                </ul>
            </div>
        </div>
    </nav>
    <!-- Fim menu e navbar -->

    <div class="container mt-5">

        <div class="row">
            <!--criando coluna da esquerda com espaço de 8 col-->
            <div class="col-sm-6">
                <div class="rounded p-4 mb-5 bg-fundo-ambiente ambiente">
                    <center>
                        <h2><i> Ambiente</i></h2>
                    </center>
                    <p>
                        Aqui na Auqmiaepia contamos com um local amplo e aconchegante para seu pet brincar e se divertir
                        bastante, com conforto e segurança.
                        Com vários briquedos, jogos e atividades lúdicas faz com que o Auqmiaepia seja
                        o lugar ideal para deixar o seu amigo.
                    </p>

                    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
                        <div class="carousel-indicators">
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0"
                                class="active" aria-current="true" aria-label="Slide 1"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                                aria-label="Slide 2"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
                                aria-label="Slide 3"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3"
                                aria-label="Slide 4"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="4"
                                aria-label="Slide 5"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="5"
                                aria-label="Slide 6"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="6"
                                aria-label="Slide 7"></button>
                        </div>
                        <div class="carousel-inner">
                            <div class="carousel-item active">
                                <img src="img/local1.jpg" class="d-block w-100" alt="1">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="img/local2.jpg" class="d-block w-100" alt="2">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="img/gatos dormindo.jpg" class="d-block w-100" alt="3">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="img/gato-brincando-feliz.jpg" class="d-block w-100" alt="4">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="img/gato na casinha.jpg" class="d-block w-100" alt="5">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="img/parque cachorro.jpg" class="d-block w-100" alt="6">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="img/local brincar.png" class="d-block w-100" alt="7">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                        </div>
                        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
                            data-bs-slide="prev">
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Previous</span>
                        </button>
                        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
                            data-bs-slide="next">
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Next</span>
                        </button>
                    </div>

                </div>
                <div class="locais rounded p-4 mb-5 bg-fundo-locais">
                    <center>
                        <h2><i> Locais de Brincadeiras</i></h2>
                    </center>
                    <p>
                        Nosso hotel oferece aos pets locais ideais para o seu divertimento, de acordo com a necessidade
                        de
                        cada um. Dessa maneira, além da segurança oferecida nesses locais temos também nossa equipe de
                        funcionários que monitoriam tudo o que acontece.
                    </p>
                    <p>
                        Nosso hotel conta com:
                    </p>
                    <ul>
                        <li>
                            <p>Piscina</p>
                        </li>
                        <li>
                            <p>Piscina de bolinha</p>
                        </li>
                        <li>
                            <p>Ambiente especial para gatos</p>
                        </li>
                        <li>
                            <p>Parquinho</p>
                        </li>
                    </ul>
                    <div id="carouselExampleCaptions" class="carousel slide col-lg-8" data-bs-ride="carousel">
                        <div class="carousel-indicators">
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0"
                                class="active" aria-current="true" aria-label="Slide 1"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
                                aria-label="Slide 2"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
                                aria-label="Slide 3"></button>
                            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3"
                                aria-label="Slide 4"></button>
                        </div>
                        <div class="carousel-inner">
                            <div class="carousel-item active">
                                <img src="img/local pets 3.jpg" class="d-block w-100" alt="1">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="img/img-creche.jpg" class="d-block w-100" alt="2">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="img/local2.jpg" class="d-block w-100" alt="3">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                            <div class="carousel-item">
                                <img src="img/cão-bolinha.jpg" class="d-block w-100" alt="4">
                                <div class="carousel-caption d-none d-md-block">

                                </div>
                            </div>
                        </div>
                        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions"
                            data-bs-slide="prev">
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Previous</span>
                        </button>
                        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions"
                            data-bs-slide="next">
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Next</span>
                        </button>
                    </div>
                </div>
                
               
                <!--<div class="card-group bg-fundo-home row">
                    <div class="card">
                        <img src="img/hotel.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">HOTEL</h5>
                            <p class="card-text">
                                A diária é de 24 horas, onde seu amigo desenvolve diversas atividades como
                                brincadeiras, socialização e cuidados. Ao final do dia são recolhidos
                                para uma área diferente, protegidos do sereno e preparados para dormir. 
                            </p>
                            <p class="card-text"><small class="text-muted"></small></p>
                        </div>
                    </div>
                    <div class="card">
                        <img src="img/creche.jpg" vspace="5" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">CRECHE</h5>
                            <p class="card-text">A nossa creche tem permanência de até 12 horas, sendo das 7hs às 19hs.
                                Temos um rigor bem específico com nossos usuários para evitar algumas intercorrências
                                que são esperadas em nossos pets.

                                Nossa área tem espaço protegido para filhotes em fase de vacinação com cuidados
                                específicos para a idade e auxílio no treinamento para uso de tapete higiênico
                            </p>

                            <p class="card-text"><small class="text-muted"></small></p>
                        </div>

                    </div>

                    <div class="card">
                        <img src="img/banner-banho-e-tosa.png" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">BANHO E TOSA</h5>
                            <p class="card-text">
                                Os banhos são feitos com o uso de xampus neutro indicados para todos os tipos de pelo e
                                pele inclusive as mais sensíveis. No caso de banhos terapêuticos, basta trazerem os
                                produtos receitados pelo veterinário que realizaremos os procedimentos sem custo
                                adicional.
                            </p>
                            Segunda a sexta: 8:00 às 18:00
                            Sábados: 8:00 às 12:00
                            </p>
                            <p class="card-text"><small class="text-muted"></small></p>
                        </div>
                    </div>

                </div> -->

            </div>
             <!--Coluna Direita-->
             <div class=" informacoes col-sm-5">
                <ul class="nav nav-pills flex-column mt-3">
                    <img src="img/endereco.jpg" alt="endereco">
                </ul>
                <h2 class="mt-4"><i>Mapa</i></h2>
                <ul class="nav nav-pills flex-column mt-3">
                </ul>
                <iframe
                    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3657.825427391717!2d-46.21363658447611!3d-23.53878046664505!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce77b84ce4dd37%3A0xf62cc4be93a9a4b!2sCreche%20e%20Hotel%20para%20Cachorros%20%7C%20Au%20Que%20Mia%20e%20Pia%20%7C%20Mogi%20das%20Cruzes!5e0!3m2!1spt-BR!2sbr!4v1652298466164!5m2!1spt-BR!2sbr"
                    width="500" height="450" style="border:0;" allowfullscreen="" loading="lazy"
                    referrerpolicy="no-referrer-when-downgrade"></iframe>
                <ul class="nav nav-pills flex-column mt-2">
                    <img src="img/horario.png" alt="horario">
            </div>
        </div>
            <div class="container mt-5" id="participantes">
               
                <div class="row row-cols-1 row-cols-lg-4 ">
                  <div class="col">
                    <div class="card participantes">
                        <img src="img/hotel.jpg" class="card-img-top" alt="...">
                      <div class="card-body">
                        <h5 class="card-title">HOTEL </h5>
                        <p class="card-text">
                            A diária é de 24 horas, onde seu amigo desenvolve diversas atividades como
                            brincadeiras, socialização e cuidados. Ao final do dia são recolhidos
                            para uma área diferente, protegidos do sereno e preparados para dormir. 
                        </p>
                      </div>
                    </div>
                  </div>
                  <div class="col">
                    <div class="card participantes">
                        <img src="img/creche2.jpg" vspace="5" class="card-img-top" alt="...">
                      <div class="card-body">
                        <h5 class="card-title">CRECHE</h5>
                        <p class="card-text">A nossa creche tem permanência de até 12 horas, sendo das 7hs às 19hs.
                            Nossa área tem espaço protegido para filhotes em fase de vacinação com cuidados
                            específicos para a idade e auxílio no treinamento para uso de tapete higiênico.
                        </p>
                      </div>
                    </div>
                  </div>
                  <div class="col">
                    <div class="card participantes">
                        <img src="img/banner-banho-e-tosa.png" class="card-img-top" alt="...">
                      <div class="card-body">
                        <h5 class="card-title">BANHO E TOSA</h5>
                        <p class="card-text">
                            Os banhos são feitos com o uso de xampus neutro indicados para todos os tipos de pelo e
                            pele inclusive as mais sensíveis. No caso de banhos terapêuticos, basta trazerem os
                            produtos receitados pelo veterinário que realizaremos os procedimentos sem custo
                            adicional.
                        </p>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

           
        
    </div>

    <body>

        <!-- Footer -->
        <footer class="mt-5 p-4 bg-navbar text-white text-center">
            <p>AUQMIAEPIA - Hotel e Creche para Pets-&nbsp;|&nbsp;
                <a href="https://www.facebook.com/auqmiaepia/"><img src="img/facebook-icon.png" alt="" width="50px"
                        height="40px"></a>&nbsp;|&nbsp;<a href="https://www.instagram.com/auqmiaepia/"><img
                        src="img/instagram.png" alt="" width="50px" height="40px"></a>
                <!-- Link para o whats -->
                &nbsp;|&nbsp;<a href="https://api.whatsapp.com/send?phone=551147298902&text=Mande%20uma%20mensagem"><img
                        src="img/logowhatts.png" alt="" width="50px" height="40px"></a>
            </p>
        </footer>
    </body>
    <!--meu Script-->
    <script>
        function marcar(obj) {
            document.getElementById(obj).classList.toggle('active')
        }
    </script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>

</html>

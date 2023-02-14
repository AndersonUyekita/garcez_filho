---
layout: zero
date: 2023-02-03 12:00:00 -0300
permalink: /
featured_section: false
call_action_section: false
---

<style>
        .parallax {
          /* The image used */
          background-image: url("/01-Figure/bg.jpg");

          /* Set a specific height */
          min-height: 100vh; 

          /* Create the parallax scrolling effect */
          background-attachment: fixed;
          background-position: center;
          background-repeat: no-repeat;
          background-size: cover;
          margin: 0;
          filter: brightness(65%);
        }

        #header{
          position: absolute;
          z-index: 1000;
          top: 50vh;
          right: 5vw;
          color: white;
        }
        .text-box{
	        height: 50vh;
	        padding: 10px;
        }
        @media only screen and (max-device-width: 1024px) {
            .parallax {
                background-attachment: scroll;
            }
        }
        #header{
         position: absolute;
          top: 50vp;
          -webkit-transform: translateY(-50vp);
          -ms-transform: translateY(-50vp);
          transform: translateY(-50vp);
        }
</style>


<!-- Texto que fica sobre o Parallax. -->
<div class="parallax-hero">
    <h2 style="font-family:'Oswald'; text-align: right">Garcez Filho | Advocacia & Consultoria Jurídica</h2>
    <h1 style="font-family:'Oswald'; text-align: right; font-size: 8vw;">PROTEGENDO<br>OS SEUS DIREITOS</h1>
    <h3 style="font-family:'Oswald'; text-align: right">Civil | Trabalhista | Ambiental</h3>
</div>

<!-- Criando o Parallax -->
<div class="parallax"></div>

<!-- Seção dos Serviços -->
<section class="reveal">
    <h1 id="servicos" style="margin-top: 5vh;padding-top: 5vh;text-align: center;font-family:'Oswald';">SERVIÇOS</h1>
    <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding: 5vh; opacity:1">
    <!-- Listagem dos Serviços -->
    <div class="container" style="max-width:70vw">
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <!-- Serviços: Civil -->
            <div class="col">
                <div id="civil" class="card h-100">
                    <img src="./01-Figure/civil_law.jpg" class="card-img-top" alt="Imagem Direito Civil Card">
                    <div class="card-body">
                        <h5 class="card-title" style="text-align: center;font-family:'Book Antiqua';font-weight: bold;">Civil</h5>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding-bottom: 10px; opacity:1">
                        <ul>
                            <li>Indenizações;</li>
                            <li>Código de Proteção e Defesa do Consumidor;</li>
                            <li>Ajuizamento e defesa em ações de cobranças;</li>
                            <li>Recuperação de créditos;</li>
                            <li>Responsabilidade civil;</li>
                            <li>Casamento, Separação e Divórcio;</li>
                            <li>Inventários e testamentos;</li>
                        </ul>
                        <div class="row m-0 p-0"><a class="btn btn-primary" href="https://blog.garcezfilho.com.br/categorias/civil" role="button">Ver mais</a></div>
                    </div>
                </div>
            </div>
            <!-- Serviços: Penal -->
            <div class="col">
                <div id="criminal" class="card h-100">
                    <img src="./01-Figure/criminal_law.jpg" class="card-img-top" alt="Imagem Direito Criminal Card">
                    <div class="card-body">
                        <h5 class="card-title" style="text-align: center;font-family:'Book Antiqua';font-weight: bold;">Criminal</h5>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding-bottom: 10px; opacity:1">
                        <ul>
                            <li>Requerimento de habeas corpus;</li>
                            <li>Pedido de relaxamento ou revogação de prisão;</li>
                            <li>Defesa em ação penal e inquérito policial;</li>
                            <li>Pedido de liberdade provisória;</li>
                            <li>Entrada de recursos;</li>
                            <li>Revisão criminal;</li>
                            <li>Pedido de instauração de queixa de crime;</li>
                        </ul>
                        <div class="row m-0 p-0"><a class="btn btn-primary" href="https://blog.garcezfilho.com.br/categorias/penal" role="button">Ver mais</a></div>
                    </div>
                </div>
            </div>
            <!-- Serviços: Regularização de Armas -->
            <div class="col">
                <div id="armas" class="card h-100">
                    <img src="./01-Figure/gun_law.jpg" class="card-img-top" alt="Imagem Armas Card">
                    <div class="card-body">
                        <h5 class="card-title" style="text-align: center;font-family:'Book Antiqua';font-weight: bold;">Armas</h5>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding-bottom: 10px; opacity:1">
                        <ul>
                            <li>Aquisição de Armas de uso permitido junto à Polícia Federal (SINARM);</li>
                            <li>Aquisição de Armas de uso permitido e restrito junto ao Exército (SIGMA);</li>
                            <li>Certificado de Registro (CR);</li>
                            <li>Autorização de compra;</li>
                            <li>Emissão de CRAF;</li>
                            <li>Emissão de guia de trânsito;</li>
                        </ul>
                        <div class="row m-0 p-0"><a class="btn btn-primary" href="https://blog.garcezfilho.com.br/categorias/armas" role="button">Ver mais</a></div>
                    </div>
                </div>
            </div>
            <!-- Serviços: Ambiental -->
            <div class="col">
                <div id="ambiental" class="card h-100">
                    <img src="./01-Figure/environment_law.jpg" class="card-img-top" alt="Imagem Direito Ambiental Card">
                    <div class="card-body">
                        <h5 class="card-title" style="text-align: center;font-family:'Book Antiqua';font-weight: bold;">Ambiental</h5>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding-bottom: 10px; opacity:1">
                        <ul>
                            <li>Regularização rural;</li>
                            <li>Regularização ambiental;</li>
                            <li>Regularização urbana;</li>
                        </ul>
                        <div class="row m-0 p-0"><a class="btn btn-primary" href="https://blog.garcezfilho.com.br/categorias/ambiental" role="button">Ver mais</a></div>
                    </div>
                </div>
            </div>
            <!-- Serviços: Imobiliário -->
            <div class="col">
                <div id="imobiliario" class="card h-100">
                    <img src="./01-Figure/realstate_law.jpg" class="card-img-top" alt="Imagem Imobiliário Card">
                    <div class="card-body">
                        <h5 class="card-title" style="text-align: center;font-family:'Book Antiqua';font-weight: bold;">Imobiliário</h5>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding-bottom: 10px; opacity:1">
                        <ul>
                            <li>Assessoria jurídica;</li>
                            <li>Análise e confecção de contratos;</li>
                            <li>Cobrança de aluguéis;</li>
                            <li>Locação, Compra e Venda;</li>
                            <li>Posse e Usucapião;</li>
                            <li>Registro de Imóveis;</li>
                            <li>Regularização de Imóveis;</li>
                            <li>Desapropriação;</li>
                            <li>Reintegração de posse;</li>
                        </ul>
                        <div class="row m-0 p-0"><a class="btn btn-primary" href="https://blog.garcezfilho.com.br/categorias/imobiliario" role="button">Ver mais</a></div>
                    </div>
                </div>
            </div>
            <!-- Serviços: Trabalhista -->
            <div class="col">
                <div id="trabalhista" class="card h-100">
                    <img src="./01-Figure/labour_law.jpg" class="card-img-top" alt="Imagem Direito Trabalhista Card">
                    <div class="card-body">
                        <h5 class="card-title" style="text-align: center;font-family:'Book Antiqua';font-weight: bold;">Trabalhista</h5>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding-bottom: 10px; opacity:1">
                        <ul>
                            <li>Reconhecimento do vínculo trabalhista;</li>
                            <li>Pagamento de horas extraordinárias;</li>
                            <li>Recolhimento do FGTS;</li>
                            <li>Intervalo intrajornada;</li>
                            <li>Assédio moral;</li>
                            <li>Verbas atrasadas;</li>
                            <li>Acidente em serviço;</li>
                        </ul>
                        <div class="row m-0 p-0"><a class="btn btn-primary" href="https://blog.garcezfilho.com.br/categorias/trabalhista" role="button">Ver mais</a></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Sobre -->
<section class="reveal">
    <div class="container-fluid" style="background-color: rgba(119,80,21,.1);padding-bottom: 5vh;">
        <h1 id="sobre" style="margin-top: 5vh;padding-top: 5vh;text-align: center;font-family:'Oswald';">SOBRE</h1>
        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding: 5vh; opacity:1">
        <div class="container-fluid" style="max-width:70vw">
            <div class="container">
              <div class="row row-cols-1 row-cols-md-2 g-4">
                <div class="col" style="margin:auto;">
                    <div class="container-fluid">
                        <h5 style="font-family:'Book Antiqua';font-weight: bold;">História</h5>
                        <p>A Garcez Filho possui 11 anos de experiência, atuando em mais de 500 ações judiciais e extra judiciais,
                           envolvendo: direito penal, direito do trabalho, direito do consumidor, direito civil, direito de família e sucessões,
                           execuções fiscais, regularização rural, regularização urbana, regularização ambiental e serviços cartorários.</p>
                    </div>
                    <!-- 
                    <div class="container-fluid">
                        <h5>Missão</h5>
                        <p>To organize the world's information and make it universally accessible and useful.</p>
                    </div>
                    
                    <div class="container-fluid">
                        <h5>Visão</h5>
                        <p>To provide access to the world's information in one click</p>
                    </div>
                    <div class="container-fluid">
                        <h5>Valores</h5>
                        <p>Foco no sucesso do cliente, Transparência, Ética e Justiça.</p>
                    </div>
                    -->
                    <!-- NavBar: Missão, Visão e Valores
                    <ul class="nav nav-tabs nav-justified" id="myTab" role="tablist">
                          <li class="nav-item" role="presentation">
                            <button class="nav-link active" id="missap-tab" data-bs-toggle="tab" data-bs-target="#missao" type="button" role="tab" aria-controls="missao" aria-selected="true">Missão</button>
                          </li>
                          <li class="nav-item" role="presentation">
                            <button class="nav-link" id="visao-tab" data-bs-toggle="tab" data-bs-target="#visao" type="button" role="tab" aria-controls="visao" aria-selected="true">Visão</button>
                          </li>
                          <li class="nav-item" role="presentation">
                            <button class="nav-link" id="valores-tab" data-bs-toggle="tab" data-bs-target="#valores" type="button" role="tab" aria-controls="valores" aria-selected="true">Valores</button>
                          </li>
                    </ul>
                    <div class="tab-content" id="myTabContent">
                      <div class="tab-pane fade show active" id="missao" role="tabpanel" aria-labelledby="missao-tab">...</div>
                      <div class="tab-pane fade" id="visao" role="tabpanel" aria-labelledby="visao-tab">...</div>
                      <div class="tab-pane fade" id="valores" role="tabpanel" aria-labelledby="contact-tab">...</div>
                    </div> -->
                </div>
                <!-- Figura -->
                <div class="col">
                    <img src="./01-Figure/sobre.jpg" alt="Figura do martelo." style="max-width:100%;">
                </div>
              </div>
            </div>
        </div>
    </div>
</section>

<!-- Equipe -->
<section class="reveal">
    <h1 id="equipe" style="margin-top: 5vh;text-align: center;font-family:'Oswald';">EQUIPE</h1>
    <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding: 5vh; opacity:1">
    <div class="container" style="max-width:70vw">
        <div class="row row-cols-1 row-cols-md-2 justify-content-md-center g-5">
            <div class="col">
                <div class="card h-100" style="border-color: transparent;">
                    <!-- Carlos -->
                    <img src="./01-Figure/profile_carlos.jpg" class="card-img-top" alt="Foto do Carlos" style="border-radius: 50%;width: 50%;margin: auto;">
                    <div class="card-body">
                        <h4 class="card-title" style="text-align: center; font-family:'Book Antiqua';"><strong>José Carlos Garcez Filho</strong></h4>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto; opacity:1;padding-bottom: 2vh">
                        <h6 style="text-align: center; font-family:'Book Antiqua'; padding-bottom:5vh;"><strong>Sócio fundador</strong></h6>
                        <p class="card-text">
                            Advogado, formado em 2009 pela Universidade Braz Cubas, é conveniado a Defensoria Pública OAB/SP para prestação de
                            Assistência Judiciária suplementar. Membro da Comissão de Estudos sobre a Legislação e Regulamentação de Controle de
                            Armas – OAB/SP 17º Subseção – Mogi das Cruzes. Também é instrutor de Armamento e Tiro (IAT) formado pelo Clube de Tiro
                            Red Delta – Cascavel/PR
                        </p>
                        <!-- Colocar o Linkedin
                        <div class="container-fluid" style="text-align: center;">
                            <h1>
                                <i class="fa fa-linkedin-square" aria-hidden="true"></i>
                            </h1>
                        </div>
                        -->
                    </div>
                </div>
            </div>
	            <!-- Inserir o perfil da Fran
	            <div class="col">
	                <div class="card h-100" style="border-color: transparent;">
	                     
	                    <img src="./01-Figure/profile_fran.jpg" class="card-img-top" alt="Foto da Fran" style="border-radius: 50%;width: 50%;margin: auto;">
	                    <div class="card-body">
	                        <h4 class="card-title" style="text-align: center; font-family:'Book Antiqua';"><strong>Françoise Patriane de Souza</strong></h4>
	                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto; opacity:1;padding-bottom: 2vh">
	                        <h6 style="text-align: center; font-family:'Book Antiqua'; padding-bottom:5vh;"><strong>Sócia fundadora</strong></h6>
	                        <p class="card-text">
	                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque lacinia sodales nibh, sed fermentum sem imperdiet et. Cras sit amet ex ut tellus molestie ultricies. Donec non quam id magna congue consectetur. Quisque euismod, ligula quis lobortis venenatis, massa leo luctus tortor, eget ullamcorper leo justo id eros. Vestibulum eu justo enim. Aenean pharetra libero risus, nec sollicitudin nisi aliquam nec. Aenean sed libero in enim facilisis viverra non sed ligula. Vestibulum eu mattis lectus.
	                        </p>
	                    </div>
	                </div>
	            </div>
	            -->
		</div>
    </div>
</section>

<!-- Mapa -->
<section class="reveal m-0 p-0" style="width: 100%; height: 50vh;">
    <div id="localizacao" class="container-fluid m-0 p-0" style="margin-top: 5vh;padding-top: 5vh; padding-left: 0; padding-right: 0; width: 100%; height: 50vh;">
        <iframe title="Localização a partir do Google Maps" style="width :100%; height:50vh;" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3658.2949810449313!2d-46.19240448462983!3d-23.521890584702476!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94cdd815ff1d3353%3A0xa4d7ba69bb02ec09!2sR.%20Cel.%20Souza%20Franco%2C%20771%20-%20Centro%2C%20Mogi%20das%20Cruzes%20-%20SP%2C%2008710-025!5e0!3m2!1sen!2sbr!4v1674654236741!5m2!1sen!2sbr" frameborder="0" data-ll-status="loaded"></iframe>
    </div>
</section>

<!-- Contatos -->
<section class="reveal">
    <h1 id="contatos" style="margin-top: 5vh; padding-top: 5vh; text-align: center;font-family:'Oswald';">CONTATOS</h1>
    <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto;padding: 5vh; opacity:1">
    <div class="container-fluid" style="max-width:70vw">
        <div class="row row-cols-1 row-cols-md-2 g-5">
            <!-- Coluna da Esquerda -->
            <div class="col">
                <div class="card h-100" style="border-color: transparent;">
                    <div class="card-body">
                        <!-- Endereços -->
                        <h4 class="card-title" style="text-align: center; font-family:'Book Antiqua';"><strong>Endereço</strong></h4>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto; opacity:1;padding-bottom: 2vh">
                        <p class="card-text">
                        <i class="fa fa-map-o" aria-hidden="true"></i>
                        Rua Coronel Souza Franco, 771 - Centro, Mogi das Cruzes - SP, CEP 08710-020
                        </p><br>
                        <!-- Telefones -->
                        <h4 class="card-title" style="text-align: center; font-family:'Book Antiqua';"><strong>Telefones</strong></h4>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto; opacity:1;padding-bottom: 2vh">
                        <p class="card-text">
                            <i class="fa fa-whatsapp" aria-hidden="true"></i> +55 (11) 99977-6346
                            <br>
                            <i class="fa fa-mobile" aria-hidden="true"></i> +55 (11) 2629-2693
                        </p> 
                        <!-- Email -->
                        <h4 class="card-title" style="text-align: center; font-family:'Book Antiqua';"><strong>Email</strong></h4>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto; opacity:1;padding-bottom: 2vh">
                        <p class="card-text">
                            <i class="fa fa-envelope-o" aria-hidden="true"></i> garcez@adv.oabsp.org.br
                        </p> 
                    </div>
                </div>
            </div>
            <!-- Coluna da Direita -->
            <div class="col">
                <div class="card h-100" style="border-color: transparent;">
                    <div class="card-body">
                        <!-- Call to Action Button -->
                        <h4 class="card-title" style="text-align: center; font-family:'Book Antiqua';"><strong>Entre em contato</strong></h4>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto; opacity:1;padding-bottom: 2vh">
                        <p class="card-text">
                        Envie-me uma mensagem pelo
                        </p>
                        <div class="container-fluid" style="text-align: center;">
                            <a href="https://wa.me/5511999776346" class="btn btn-primary btn-lg" role="button" target="_blank"><i class="fa fa-whatsapp" aria-hidden="true"></i> WhatsApp</a>
                        </div>
                        <br>
                        <!-- Save o meu Contato -->
                        <h4 class="card-title" style="text-align: center; font-family:'Book Antiqua';"><strong>Save o meu Contato</strong></h4>
                        <hr style="max-width: 50px;border-width: 3px;border-color: rgba(6,42,78);text-align: center;margin: auto; opacity:1;padding-bottom: 2vh">
                        <p class="card-text">
                            <div class="row row-cols-1 row-cols-md-2 g-1">
                                  <!-- QR Code -->  
                                  <div class="col">
                                    <div class="card h-100" style="border-color: transparent;">
                                      <img src="./01-Figure/qr_code.png" class="card-img-top" alt="Código QR Code para salvar o contato" style="width:75%; margin: auto;">
                                    </div>
                                  </div>
                                  <!-- Texto sobre o QR Code --> 
                                  <div class="col" style="margin:auto;">
                                    <div class="card h-100" style="border-color: transparent;">
                                      <div class="card-body">
                                        <p class="card-text">Leia o QR code e me adicione a sua lista de contatos.</p>
                                      </div>
                                    </div>
                                  </div>
                            </div>    
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0,
    minimum-scale=1.0">

    <title>Innotica</title>

    <link rel="stylesheet" href="index/css/bootstrap.min.css">

	<link rel="shortcut icon" type="image/x-icon" href="index/img/favicon.Innotica.ico">

	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">  
	
    <link rel="stylesheet" href="index/css/estilosBaseIndex.css">
    <link rel="stylesheet" href="index/css/estilosIndex.css">
    
</head>

<body>
   
    <!-- Contenedor del header  -->
    <div class="container-fluid" id="headerDesktop" style="position: absolute; height: 98.22px; background: transparent; z-index: 1; max-width: 1700px;">

        <!-- Fila del header  -->
        <div class="row m-0 p-0" style=" position: relative; height: 100%; top: 0%; width: 100%;">
           
            <!-- Columna donde se ubica el logo de la página  -->
            <div class="col-4 m-0 p-0" style="position: relative; height: 50%; top: 25%;">
                <!-- Logo de la página -->
                <a id="navbar-brand-desktop"  href="index.html"><img src="index/img/Logo Innotica Negro y Verde.png" 
                    style="position: relative; width: 152px;; left: 32.5%; height:42.33%;top: 20%;"></a>
            </div>

            <!-- Columna donde se ubica el menú de la página  -->
            <div class="col-8 m-0 p-0 d-flex justify-content-around d-flex align-items-center" style="position: relative; height: 10px; height: 50%; top: 25%;">

            <!-- Menú Enfoques  -->
                <div  class="d-flex flex-row" id="boxMenus" style="width: 200px; height:42.33%;top: 25%;">
                    <div style="width: 90px">
                        <div id="lineaSupMenu" style="visibility: visible;">  </div>
                        <a id="txtMenu"  href="#">Enfoques</a></li>
                        <div id="lineaInfMenu" style="visibility: visible;"> </div>
                    </div>
                        <span  id="trianguloMenu" style="position: relative;top: 50%; visibility: visible;"></span>
                        <nav id="boxSubMenus" style="position: relative; width: 100%; left: -45%; top: 70%; padding-top:10px; height:100px;">
                            <a id="txtSubMenu0"  href="enfoques/enfoques.html" >Enfoques</a> <br>
                            <a id="txtSubMenu1"  href="enfoques/construcciontradicional.html">Tradicional</a><br>
                            <a id="txtSubMenu2"  href="enfoques/construccionsostenible.html">Sostenible</a> <br>
                            <a id="txtSubMenu3"  href="enfoques/construccionbim.html">Digital BIM </a> <br>
                        </nav>                   
                </div>

             <!-- Menú Servicios  -->
                <div class="d-flex flex-row" id="boxMenus" style="width: 200px; height:42.33%;top: 25%;">
                    <div style="width: 90px; ">
                        <div id="lineaSupMenu">  </div>
                        <a id="txtMenu" href="#">Servicios</a></li>
                        <div id="lineaInfMenu"> </div>
                    </div>
                    <span id="trianguloMenu" style="position: relative;top: 50%; left:5%"></span>
                    <nav id="boxSubMenus" style="position: relative; width: 100%; left: -46%; top: 70%; padding-top:10px; height:100px;">
                        <a id="txtSubMenu0"  href="servicios/servicioautomatizacion.html">Automatización</a> <br>
                        <a id="txtSubMenu1"  href="servicios/serviciosostenibilidad.html">Sostenibilidad</a> <br>
                        <a id="txtSubMenu2"  href="servicios/servicioformacion.html">Formación</a> <br>
                        <a id="txtSubMenu3"  href="servicios/productos.html">Productos</a> <br>

                    </nav>
                </div>
            <!-- SubMenú de los Servicios  -->


            <div class="d-flex flex-row" id="boxMenus" style="width: 200px; height:42.33%;top: 25%;">
                <div style="width: 95px;">
                        <div id="lineaSupMenu">  </div>
                        <a id="txtMenu" href="#">Proyectos</a></li>
                        <div id="lineaInfMenu"> </div>
                    </div>
                    <span id="trianguloMenu" style="position: relative;top: 50%;; left:5%"></span>
                    <nav id="boxSubMenus" style="position: relative; width: 100%; left: -50%; top: 70%; padding-top:10px; height:100px;">
                        <a id="txtSubMenu0"  href="proyectos/proyectos.html">Proyectos</a><br>
                        <a id="txtSubMenu1"  href="proyectos/proyectosenejecucion.html">En proceso</a><br>
                        <a id="txtSubMenu2"  href="proyectos/proyectosejecutados.html">Ejecutados</a> <br>
                    </nav>
                </div>

                <div class="d-flex flex-row" id="boxMenus" style="width: 200px; height:42.33%;top: 25%;">
                    <div style="width: 90px">
                        <div id="lineaSupMenu">  </div>
                        <a id="txtMenu" href="#">Contacto</a></li>
                        <div id="lineaInfMenu"> </div>
                    </div>
                    <span id="trianguloMenu" style="position: relative;top: 50%; left:5%"></span>
                    <nav id="boxSubMenus" style="position: relative; width: 100%; left: -46%; top: 60%; padding-top:10px; height:100px;">
                        <a id="txtSubMenu0"  href="contacto/podcastinnova2.html" >Innova2</a> <br>
                        <a id="txtSubMenu1"  href="contacto/blog.html">Blog</a> <br>
                        <a id="txtSubMenu2"  href="contacto/nosotros.html">Nosotros</a> <br>
                        <a id="txtSubMenu3"  href="contacto/contacto.html">Contacto</a> <br>
                    </nav>
                </div>

            </div>
        </div>
      </div>
                
    <!-------------------------------------------- Header para Mobile----------------------------------------------------->


        <div class="container-fluid" id="headerMobile" style="width: 100%; height:56px; background: #1C1F2A">
            <div class="row">
                <div class="col" id="navbarMobile">
                    <a id="navbar-brand-mobile" href="index.html"><img src="index/img/Logo Innotica Blanco y Verde.png" 
                        style="width: 152px; height: 21px; position: absolute; left: 5.94%; top: 16px;">
                    </a>
                    <input type="radio" name="modal" id="abrir-modal">
                    <label for="abrir-modal" id="label-abrir-modal" style="cursor:pointer;">
                        <div style="background-color: transparent; height:5px; width: 20px">  </div>
                        <div style="background-color: #64AE45; height:2px; width: 20px">  </div>
                        <div style="background-color: transparent; height:5px; width: 20px">  </div>
                        <div style="background-color: #64AE45; height:2px; width: 20px">  </div>
                        <div style="background-color: transparent; height:5px; width: 20px">  </div>
                        <div style="background-color: #64AE45; height:2px; width: 20px">  </div>
                    </label>




        <!-------------------------------------------- Modal del Mobile ----------------------------------------------------->

                    <div class="d-flex align-content flex-column" id="modal">

                        <input type="radio"  name="modal" id="cerrar-modal">
                        <label for="cerrar-modal" id="label-cerrar-modal"><a 
                            style=" color:#64AE45; 
                                    text-decoration: none;
                                    font-family: 'Montserrat';
                                    font-style: normal;
                                    font-weight: 800;
                                    font-size: 30px;">
                            X
                        </a></label>

                        <h2>
                            <a  class="btn" data-bs-toggle="collapse" href="#collapsesubMenuEnfoquesMobile" role="button" 
                                aria-expanded="false" aria-controls="collapseExample" id="txtEnfoqueMobile">
                                Enfoques
                            </a>
                        </h2>
                        <div class="collapse" id="collapsesubMenuEnfoquesMobile">
                            <div class="card card-body accordion-body align-content" id="subMenuEnfoquesMobile">
                                <a id="txtEnfoqueMobile1"  href="enfoques/enfoques.html">Enfoques</a> <br>
                                <a  id="txtEnfoqueMobile2"  href="enfoques/construcciontradicional.html">Construcción tradicional</a> <br>
                                <a  id="txtEnfoqueMobile2"  href="enfoques/construccionsostenible.html">Construcción sostenible</a> <br>
                                <a   href="enfoques/construccionbim.html">Construcción digital (BIM) </a> 
                                <div style="background:transparent; width: 100px; height: 20px"> </div>
                                <p id="lineSubMenuMobile">- - - -</p>
                            </div>
                        </div>
                        <h2>
                            <a class="btn" data-bs-toggle="collapse" href="#collapsesubMenuServiciosMobile" role="button" 
                                aria-expanded="false" aria-controls="collapseExample" id="txtServiciosMobile">
                                Servicios
                            </a>
                        </h2>
                        <div class="collapse" id="collapsesubMenuServiciosMobile">
                            <div class="card card-body accordion-body" id="subMenuServiciosMobile">
                                    <a  href="servicios/servicioautomatizacion.html">Servicios de automatización</a><br> 
                                    <a  href="servicios/serviciosostenibilidad.html">Servicios de sostenibilidad</a> <br>
                                    <a  href="servicios/servicioformacion.html">Servicios de formación</a> <br>
                                    
                                    <div style="background:transparent; width: 100px; height: 20px"> </div>
                                    <p id="lineSubMenuMobile">- - - -</p>
                                </div>
                            </div>
                            <h2>
                                <a class="btn" data-bs-toggle="collapse" href="#collapsesubMenuProyectosMobile" role="button" 
                                    aria-expanded="false" aria-controls="collapseExample" id="txtProyectosMobile">
                                    Proyectos
                                </a>
                            </h2>
                        <div class="collapse" id="collapsesubMenuProyectosMobile">
                            <div class="card card-body accordion-body" id="subMenuProyectosMobile">
                                    <a  href="proyectos/proyectos.html">Proyectos</a><br> 
                                    <a  href="proyectos/proyectosenejecucion.html">Proyectos en ejecución</a><br> 
                                    <a  href="proyectos/proyectosejecutados.html">Proyectos ejecutados</a> <br>
                                    <div style="background:transparent; width: 100px; height: 20px"> </div>
                                    <p  id="lineSubMenuMobile">- - - -</p>
                            </div>
                        </div>
                        <h2>
                            <a href="servicios/productos.html" id="txtNosotrosMobile"> Productos </a>
                        </h2>
                        <h2>
                            <a href="contacto/nosotros.html" id="txtNosotrosMobile"> Nosotros </a>
                        </h2>
                        <h2>
                            <a  href="contacto/blog.html" id="txtBlogMobile"> Blog </a>
                        </h2>
                        <h2>
                            <a href="contacto/podcastinnova2.html" id="txtPodcastMobile"> Podcast </a>
                        </h2>
                        <h2>
                            <a href="contacto/contacto.html" id="txtContactoMobile"> Contacto </a>
                        </h2>

                    </div>
                </div>
            </div>
        </div>

    <!-------------------------------------------- Hero ----------------------------------------------------->
 
    <div class="container-fluid" id="hero">

        <div class="row m-0 p-0" style="height: 100%; top: 0%; width: 100%;">
            <div class="col m-0 p-0">
                   <img  style="z-index: -10;"  id="imgHome" src="index/img/grant-lemons-jTCLppdwSEc-unsplash.svg" alt="Edificio en un lateral">
                    <div id="txtIntro"><b>Empresa de<br> automatización<br> y sostenibilidad <br>
                         aplicada al diseño,<br> construcción<br> y operación de<br>infraestructuras <br>
                         <a id="leerMasIntro" href="contacto/nosotros.html">Leer más → </a></li>                 
                    </div></b> 
            </div>
        </div>
    </div>

    <!--------------------------------------------- Servicios en el contenedor del body----------------------------------------------------->

        <div class="row d-flex justify-content-center" style="position: relative; background:white">
            <div class="col-lg-7 col-12 m-lg-3 m-3 p-lg-5 p-3" style="position: relative; height: 100%;">
                    <h4 id="txtServiciosInnotica"><b>Automatización</b></h4>
                        <ul class="justify-content-start p-lg-5 p-3" id="listaProductosServicios"> 
                            <li> Ingenierías</li>
                            <li> Suministros de Hardware y Software</li>
                            <li> Instalación, Programación, Implementación</li>
                            <li> Conserjería virtual</li>
                        </ul>
                        <br>
                    <a id="leerMasProductosServicios" href="servicios/servicioautomatizacion.html">Leer más → </a></li>
            </div>
        </div>

        <div class="container-fluid d-flex justify-content-center" style="position: relative;">
            <div class="col-lg-7 col-12 m-0 p-lg-5 p-3" style="position: relative; height: 100%;">
                    <h4 id="txtServiciosInnotica"><b>Sostenibilidad</b></h4>
                        <ul class="justify-content-start p-lg-5 p-3" id="listaProductosServicios"> 
                            <li> Asesoría para certificaciones LEED, EDGE, Sistema B</li>
							<li> Comisionamiento y modelado energético</li>
							<li> Diagnostico, definiciones y acompañamiento</li>
							<li> Energías Renovables</li>
                        </ul>
                        <br>
                    <a id="leerMasProductosServicios" href="servicios/serviciosostenibilidad.html">Leer más → </a></li>
            </div>
        </div>

        <div class="container-fluid d-flex justify-content-center" style="position: relative;">
            <div class="col-lg-7 col-12 m-0 p-lg-5 p-3" style="position: relative; height: 100%;">
                    <h4 id="txtServiciosInnotica"><b>Productos</b></h4>
                        <ul class="justify-content-start p-lg-5 p-3" id="listaProductosServicios"> 
							<li> Sirio = Controlador BACnet, Modbus, SNMP, entre otros</li>
							<li> Perseo = Gestión de sistemas de bombeo</li>
							<li> Orión = SCADA de gestión de su infraestructura</li>
							<li> Polaris = Gestión de sistemas HVAC</li>
                        </ul>
                        <br>
                    <a id="leerMasProductosServicios" href="servicios/productos.html">Leer más → </a></li>
            </div>
        </div>

        <div class="container-fluid d-flex justify-content-center" style="position: relative">
            <div class="col-lg-7 col-12 m-0 p-lg-5 p-3" style="position: relative; height: 100%;">
                    <h4 id="txtServiciosInnotica"><b>Construcción</b></h4>
                        <ul class="justify-content-start p-lg-5 p-3" id="listaProductosServicios"> 
							<li> Definición de costos para proyectos de construcción</li>
							<li> Supervisión y acompañamiento</li>
							<li> Operación y Mantenimiento (FCM) </li>
                        </ul>
                        <br>
                    <a id="leerMasProductosServicios" href="enfoques/construcciontradicional.html">Leer más → </a></li>
                        <img   id="imgBody" src="index/img/grant-lemons-jTCLppdwSEc-unsplash.svg" alt="Edificio en un lateral">
            </div>
        </div>

        <div class="container-fluid" id="contenedorBodyTres">
            <div class="m-0 m-lg-5 p-3 p-lg-5"  href="#">
                    <b>SOLUCIONES INTEGRALES</b> para proyectos alineados con el <b>ENFOQUE</b> de una construcción tradicional,
                    construcción sostenible y construcción bajo la metodología BIM <br>
                    <a id="leerMasSolucionesIntegrales" href="enfoques/enfoques.html"> Leer más → </a></li></div>
            </div>
        </div>


        <div class="container-fluid p-lg-5" id="contenedorBodyCuatro">
            <div class="col position-absolute">
                    <div id="txtUltimosProyectos"> Proyectos destacados </div>
                    <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel" 
                        style="position:relative; "> 
    
                        <button class="carousel-control-prev" id="imgVectorFlechaIzquierda" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
                            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Previous</span>
                          </button>
                          <button class="carousel-control-next" id="imgVectorFlechaDerecha" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
                            <span class="carousel-control-next-icon" aria-hidden="true"></span>
                            <span class="visually-hidden">Next</span>
                          </button>

                        <div class="carousel-inner" id="carouselProyectos" style="overflow:hidden; ">
    
                          <div class="carousel-item active" data-bs-interval="3000"  id="itemCarouselProyecto">

                            <img src="index/img/carousel1.png" class="d-block w-100" alt="..." id="imgProyectoLeft">                             
                            <div class="d-flex">
                                <img src="index/img/carousel1.png" class="d-block w-100" alt="..." id="imgProyecto"> 
                            </div>
                            <img src="index/img/carousel1.png" class="d-block w-100" alt="..." id="imgProyectoRight"  >                             

                            <div class="carousel-caption"  style="position: relative; text-align: start;">
                                <a href="proyectos/Mastercard/oficinamastercardvenezuela.html"><h5 id="txtNombreProyecto"><b>Oficina Mastercard Venezuela</b></h5></a>
                                <p id="txtDescripcionProyecto">Asesoría para la obtención de la certificación LEED v4 ID+C, diseño, suministro,
                                instalación y puesta en marcha del sistema de monitoreo y control de todos los
                                sistemas de la oficina de más de 1.500 m2...
                           </p>
                            </div>
                          </div>
    
                          <div class="carousel-item" data-bs-interval="3000" id="itemCarouselProyecto">

                            <img src="index/img/Torre_Luxor.jpg" class="d-block w-100" alt="..."  id="imgProyectoLeft"> 
                            <div class="d-flex">
                                <img src="index/img/Torre_Luxor.jpg" class="d-block w-100" alt="..." id="imgProyecto"> 
                            </div>                     
                            <img src="index/img/Torre_Luxor.jpg" class="d-block w-100" alt="..." id="imgProyectoRight"> 

                            <div class="carousel-caption" id="captionCarousel" style="position: relative; text-align: start;">
                                <a href="proyectos/Mastercard/oficinamastercardvenezuela.html"><h5 id="txtNombreProyecto"><b>Torre Luxor</b></h5></a>
                                <p id="txtDescripcionProyecto">Diseño, suministro, instalación y puesta en funcionamiento del sistema integral de monitoreo
                                                               y control de la torre, incluyendo sistemas como ventilación forzada, bombeo, 
                                                               medición del CO, entre otros...
                              </p>
                            </div>
                          </div>
    
                          <div class="carousel-item" data-bs-interval="3000" id="itemCarouselProyecto">

                            <img src="index/img/TeatroTeresaCarreño.jpg" class="d-block w-100" alt="..."  id="imgProyectoLeft"> 
                            <div class="d-flex">
                                <img src="index/img/TeatroTeresaCarreño.jpg" class="d-block w-100" alt="..." id="imgProyecto"> 
                            </div>        
                            <img src="index/img/TeatroTeresaCarreño.jpg" class="d-block w-100" alt="..." id="imgProyectoRight"> 


                            <div class="carousel-caption" id="captionCarousel" style="position: relative; text-align: start;">
                                <a href="proyectos/Mastercard/oficinamastercardvenezuela.html"><h5 id="txtNombreProyecto"><b>Teatro Teresa Carreño</b></h5></a>
                                <p id="txtDescripcionProyecto">Diseño, suministro, instalación y puesta en funcionamiento del sistema de monitoreo y control
                                                               de la planta de agua helada, un total de 4 chillers, 11 bombas y 29 UMAs, entre otras funcionalidades...
                               </p>
                            </div>
                          </div>

                        </div>
    
                        <div class="carousel-indicators" id="indicadoresCarousel" style="background: #F2F2F2;width: 100%;">
                            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
                            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
                        </div>
      
                    
                    </div>     
            </div>
        </div>

    <div class="container-fluid p-lg-5" id="contenedorBodyCinco">
        <div class="row">
            <div class="col">
                <article>
                    <div id="txtContenedorBody5"> Creamos capacidades para el diseño, contrucción y operación de infraestructuras con
                         base a la sostenibilidad y automatización, empleando para ello nuestra plataforma <b>Campus Innotica.</b><br>
                        <a id="leerMasContenedor5" href="servicios/servicioformacion.html">
                            Leer más → </a></li>
                    </div>
                </article>
            </div>
        </div>
    </div>


    <div class="container-fluid position-relative" id="lineaDivisoraFinal">  <hr> </div>
    
    <div class="container-fluid p-lg-5" id="contenedorBodySeis"> 
            <article id="txtContenedorBody6" style="padding-left: 10%; padding-right: 10%;"><b>Equipo de expertos en automatización 
                y sostenibilidad en infraestructuras</b></article>
    </div>


    <div class="container-fluid" id="contenedorBodySiete">
        <div class="col position-absolute">
                <div> <br>  <br> <br></div>
                <div id="carouselAcreditaciones" class="carousel carousel-dark carousel-fade" data-bs-ride="carousel" 
                    style="position:relative;"> 

                    <div class="carousel-inner"  id="carouselBloqueAcreditaciones">

                      <div class="carousel-item active" data-bs-interval="1500"  id="itemCarouselAcreditaciones">
                        <div class="d-flex">
                            <img src="index/img/Certificaciones1de5.png" class="d-block w-100" alt="..." id="imgAcreditaciones"> 
                        </div>
                      </div>

                      <div class="carousel-item" data-bs-interval="1500" id="itemCarouselAcreditaciones">
                        <div class="d-flex">
                            <img src="index/img/Certificaciones2de5.png" class="d-block w-100" alt="..." id="imgAcreditaciones"> 
                        </div>                     
                      </div>

                      <div class="carousel-item" data-bs-interval="1500" id="itemCarouselAcreditaciones">
                        <div class="d-flex">
                            <img src="index/img/Certificaciones3de5.png" class="d-block w-100" alt="..." id="imgAcreditaciones"> 
                        </div>        
                     </div>
                     <div class="carousel-item" data-bs-interval="1500" id="itemCarouselAcreditaciones">
                        <div class="d-flex">
                            <img src="img/Certificaciones4de5.png" class="d-block w-100" alt="..." id="imgAcreditaciones"> 
                        </div>        
                     </div>
                     <div class="carousel-item" data-bs-interval="5000" id="itemCarouselAcreditaciones">
                        <div class="d-flex">
                            <img src="index/img/Certificaciones5de5.png" class="d-block w-100" alt="..." id="imgAcreditaciones"> 
                        </div>        
                     </div>
                     <div class="carousel-item" data-bs-interval="5000" id="itemCarouselAcreditaciones">
                        <div class="d-flex">
                            <img src="index/img/Certificaciones6de5.png" class="d-block w-100" alt="..." id="imgAcreditaciones"> 
                        </div>        
                     </div>
                    </div>
                </div>
     
        </div>

   
    </div>
    <br><br>

            <div class="container-fluid" id="contenedorFooter">

				<a id="txtContenedorFooter" href="#"><b>Transformando el sector del diseño, construcción y operación de infraestructuras</b></a>
				<a id="logoFooter" href="#"><img src="index/img/Logo Innotica Blanco y Verde.png"></a>

				<a id="txtNosotros" href="contacto/nosotros.html">Nosotros</a></li>
				<a id="txtBlog" href="contacto/blog.html">Blog</a></li>
				<a id="txtPodcast" href="contacto/podcastinnova2.html">Podcast</a></li>
				<a id="txtContactoFooter" href="contacto/contacto.html">Contacto</a></li>

				<img id="imgUbicacion" src="index/img/VectorUbicacion.png" alt="">
				<img id="imgBanderaVenezuela" src="index/img/VectoBanderaVenezuela.png" alt="">
				<h5 id="txtVenezuela">VENEZUELA</h5>
				<h5 id="txtTelefonoVenezuela">+58-212-241.0510</h5>
				<img id="imgBanderaDominicana" src="index/img/VectoBanderaDominicana.png" alt="">
				<h5 id="txtDominicana">REPÚBLICA DOMINICANA</h5>
				<h5 id="txtTelefonoDominicana">+1-829-946.3986</h5>
				<img id="imgBanderaEstadosUnidos" src="index/img/VectorBanderaUSA.png" alt="">
				<h5 id="txtEstadosUnidos">ESTADOS UNIDOS</h5>
				<h5 id="txtTelefonoEstadosUnidos">+1-829-946.3986</h5>
                

                <img id="imgPhone" src="index/img/VectorPhone.png" alt="">

				<a id="txtCorreoContacto" href="mailto:info@innotica.net">info@innotica.net</a></li>
				<a href="mailto:info@innotica.net"><img id="imgCorreo" src="index/img/VectorCorreo.png" alt=""></a></li>
				<a href="https://api.whatsapp.com/message/KGHKERPKWZASH1?autoload=1&app_absent=0"><img id="imgWhatsaap" src="index/img/VectorWhatsapp.png" alt=""></a></li>
				<a href="https://www.linkedin.com/company/innotica/"><img id="imgLinkedin" src="index/img/VectorLinkedin.png" alt=""></a></li>
				<a href="https://www.instagram.com/innotica_net/"><img id="imgInstagram" src="index/img/VectorInstagram.png" alt=""></a></li>
				<a href="https://twitter.com/innotica_netlin"><img id="imgTwitter" src="index/img/VectorTwitter.png" alt=""></a></li>
				<div id="lineaDivisoraFooter">  </div>
				<div id="txtContenedorFooterDerechos">© 2013-2023. Innotica System - All Rights Reserved. Made by Innotica Dev</div>
			</div>

    <script src="index/js/bootstrap.bundle.min.js">  </script>

</body>


</html># web.innotica

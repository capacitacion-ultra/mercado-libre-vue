<template>
  <header>
    <div class="container text-center header">
      <div class="row">
        <div class="col-2 d-flex justify-content-center my-auto">
          <a class="logoML d-flex my-2" href="//www.mercadolibre.com.mx"></a>
        </div>
        <div class="col-6">
          <div class="input-group input-group-lg my-2">
            <input type="text" class="search form-control form-control-lg"
              placeholder="Buscar productos, marcas y más..." />
            <span class="input-group-text border-0" id="basic-addon2"><i class="fas fa-search"></i></span>
          </div>
        </div>
        <div class="col-4 my-auto">
          <div class="d-flex justify-content-center">
            <i class="fas fa-burn"></i>
            Hot Sale está por llegar ¡Preparate!
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-2 d-flex justify-content-center fs-3">
          <div class="my-auto">
            <i class="fas fa-map-marker-alt"></i>
          </div>
          <div class="text-start">
            <p class="my-0 fs-6 mx-2"><span style="font-size: 12px;">Ingresa tu</span> <br> Código postal</p>
          </div>
        </div>
        <div class="col-6">
          <div class="d-flex justify-content-start">
            <nav class="navbar navbar-expand-lg bg-body-tertiary py-0">
              <div class="container-fluid ps-0" style="background-color: #fff159;">
                <div class="collapse navbar-collapse">
                  <ul class="navbar-nav">
                    <li class="nav-item dropdown">
                      <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                        aria-expanded="false">
                        Categorías
                      </a>
                      <ul class="dropdown-menu expande-menu bg-black">
                        <li><a class="enlace-dropdown dropdown-item text-white" href="#">Vehículos</a></li>
                        <li><a class="enlace-dropdown dropdown-item text-white" href="#">Supermercado</a></li>
                        <li><a class="enlace-dropdown dropdown-item text-white" href="#">Tecnología</a></li>
                        <li><a class="enlace-dropdown dropdown-item text-white" href="#">Electrodomésticos</a></li>
                      </ul>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Ofertas</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Historial</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Supermercado</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Moda</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Vender</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Ayuda</a>
                    </li>
                  </ul>
                </div>
              </div>
            </nav>
          </div>
        </div>
        <div class="col-4 my-auto">
          <div class="d-flex justify-content-end fs09rem">
            <nav class="navbar navbar-expand-lg bg-body-tertiary py-0">
              <div class="container-fluid" style="background-color: #fff159;">
                <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                  <div class="navbar-nav">
                    <a class="nav-link" href="#">Crear cuenta</a>
                    <a class="nav-link" href="#">Ingresa</a>
                    <a class="nav-link" href="#">Mis comprar</a>
                    <a class="nav-link" href="#"><i class="fas fa-light fa-cart-shopping"></i></a>
                  </div>
                </div>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </header>

  <main>
    <div class="container text-center main px-0 fs09rem"> <!-- Seccion tambien puede interesarte -->
      <div class="container">
        <div class="row py-3">
          <div class="col-9">
            <div class="related-search text-start">
              <span class="fw-bold">También puede interesarte:</span> nest - google home mini - google home hub - echo
              show 8 - homepod mini - guayaberas cdmx - bocina inteligente
            </div>
            <div class="d-flex align-items-center mt-3">
              <a class="link texto-gris" href="#">Volver</a>
              <span class="mx-3">|</span>
              <nav aria-label="breadcrumb">
                <ol class="breadcrumb my-auto">
                  <li class="breadcrumb-item"><a class="link" href="#">Electrónica, Audio y Video</a></li>
                  <li class="breadcrumb-item"><a class="link" href="#">Audio</a></li>
                  <li class="breadcrumb-item active" aria-current="page">Asistentes virtuales</li>
                </ol>
              </nav>
            </div>
          </div>
          <div class="col-3 d-flex align-items-end justify-content-end">
            <nav class="nav">
              <a class="nav-link" href="#">Compartir</a><span class="d-flex align-items-center">|</span>
              <a class="nav-link" href="#">Vender uno igual</a>
            </nav>
          </div>
        </div>
      </div>
    </div>

    <div class="container bg-white border rounded" style="width: 67%;"> <!-- Sección producto, tarjeta blanca -->
      <div class="row"> <!-- Renglon que contiene los detalles del producto hasta descripción -->
        <div class="col-8">
          <div class="container">
            <div class="row">
              <div class="col-7 my-fixed-item"> <!-- Carrusel de imagenes -->

                <!--
                <div id="carouselExample" class="carousel slide">
                  <div class="carousel-inner">
                    <div class="carousel-item active">
                      <img src="http://localhost:7171/alexa1.webp" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                      <img src="http://localhost:7171/alexa2.webp" class="d-block w-100" alt="...">
                    </div>
                    <div class="carousel-item">
                      <img src="http://localhost:7171/alexa3.webp" class="d-block w-100" alt="...">
                    </div>
                  </div>
                  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample"
                    data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                  </button>
                  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample"
                    data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                  </button>
                </div>
                -->

                <div>
                  <CarouselComponent :img=imagenes :baseUrl=baseUrl />
                  <!-- Carousel wrapper -->
                </div>
              </div>
              <div class="col-5"><!-- Descripción del producto -->
                <display class="container text-start">
                  <div class="row d-flex align-items-center"> <!-- Estado del producto y corazón -->
                    <div class="col-11 texto-gris">
                      Nuevo | {{ product.numVentas }} vendidos
                    </div>
                    <div class="col-1">
                      <a href="#" @click="favorite" style="font-size: 1.3rem;">
                        <i :class="classHeart"></i>
                      </a>
                    </div>
                  </div>

                  <div class="row"> <!-- Nombre del producto -->
                    <p class="fs-5 fw-bold">{{ product.nombre }}</p>
                  </div>

                  <div class="row fs09rem">
                    <a class="text-decoration-none" href="#">
                      <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                      <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                      ({{ product.numValoraciones }})
                    </a>
                  </div>

                  <div class="row pt-2"> <!-- Más vendido -->
                    <div class="col-12 d-flex">
                      <p class="text-white px-1 py-0 me-2 campo-naranja">MÁS VENDIDO</p>
                      <a class="link fs09rem" href="#">3° en Asistentes Virtuales</a>
                    </div>
                  </div>

                  <div class="row"><!-- Precio original -->
                    <p class="texto-gris fs-6 my-0 text-decoration-line-through">${{ product.precioOriginal }}</p>
                  </div>

                  <div class="row"><!-- Precio actual y % descuento -->
                    <div class="col-12 d-flex align-items-center">
                      <p class="fs-1 my-0 me-2">${{ product.precioDescuento }}</p>
                      <p class="text-success my-auto">{{ product.porcientoDescuento }}% OFF</p>
                    </div>
                  </div>

                  <div class="row"><!-- Precio en pagos -->
                    <p class="fs-6 my-0">en {{ product.meses }} x ${{ product.mensualidad}}</p> <br>
                    <p>IVA incluido</p>
                  </div>

                  <div class="row"><!-- Medios de pago -->
                    <a class="link">Ver los medios de pago</a>
                  </div>

                  <div class="row"><!-- Medios de pago -->
                    <div>
                      <p class="bg-primary text-white fs09rem rounded px-1 mt-3" style="width: fit-content;">OFERTA DEL
                        DÍA</p>
                    </div>
                  </div>

                  <div class="row mt-4"><!-- Color producto -->
                    <p>Color: <span class="fw-bold">{{ product.color }}</span></p>
                  </div>

                  <div class="row">
                    <div class="d-flex justify-content-start my-auto">
                      <a class="image-colorproduct border border-2 border-primary rounded d-flex my-2"
                        href="//www.mercadolibre.com.mx"></a>
                    </div>
                  </div>

                  <div class="row mt-3"><!-- Lo que tienes que saber de este producto -->
                    <p class="fw-bold fs09rem">Lo que tienes que saber de este producto</p>
                  </div>

                  <div class="row fs09rem"><!-- Puntos a conocer del producto -->
                    <div class="ps-0">
                      <ul>
                        <li v-for="(value, index) in puntosDestacables" v-bind:key="index"> {{ value }} </li>
                      </ul>
                    </div>
                  </div>

                  <div class="row">
                    <a href="#" class="link fs09rem">Ver características</a>
                  </div>
                </display>
              </div>

              <hr>

              <div class="col-12 my-fixed-item"> <!-- Carrusel de imagenes -->
                <div>
                  <p class="fs-4 text-start">Quienes vieron este producto también compraron</p>
                </div>
                <div id="carouselSuggestions" class="carousel slide" data-ride="carousel">
                  <div class="carousel-inner">
                    <div class="carousel-item active"> <!-- Padre conjunto de 3 sugerencias-->
                      <div class="row"> <!-- Conjunto de 3 sugerencias -->
                        <SuggestionComponent v-for="(value, index) in suggestions.slice(0, 3)" v-bind:key="index" :size=4 :id=value.id :photo=value.photo
                            :originalPrice=value.originalPrice :offerPrice=value.offerPrice :discount=value.discount
                            :freeShipping=value.freeShipping :full=value.full :monthsOffer=value.monthsOffer
                            :monthlyOffer=value.monthlyOffer :months=value.months :monthlyPayment=value.monthlyPayment
                            :name=value.name></SuggestionComponent>
                      </div> <!-- Termina conjunto de 3 sugerencias -->
                    </div>

                    <div class="carousel-item"> <!-- Padre conjunto de 3 sugerencias-->
                      <div class="row"> <!-- Conjunto de 3 sugerencias -->
                        <SuggestionComponent v-for="(value, index) in suggestions.slice(3, 6)" v-bind:key="index" :size=4 :id=value.id :photo=value.photo
                            :originalPrice=value.originalPrice :offerPrice=value.offerPrice :discount=value.discount
                            :freeShipping=value.freeShipping :full=value.full :monthsOffer=value.monthsOffer
                            :monthlyOffer=value.monthlyOffer :months=value.months :monthlyPayment=value.monthlyPayment
                            :name=value.name></SuggestionComponent>
                      </div>
                    </div>

                    <div class="carousel-item"> <!-- Padre conjunto de 3 sugerencias-->
                      <div class="row"> <!-- Conjunto de 3 sugerencias -->
                        <SuggestionComponent v-for="(value, index) in suggestions.slice(6, 9)" v-bind:key="index" :size=4 :id=value.id :photo=value.photo
                            :originalPrice=value.originalPrice :offerPrice=value.offerPrice :discount=value.discount
                            :freeShipping=value.freeShipping :full=value.full :monthsOffer=value.monthsOffer
                            :monthlyOffer=value.monthlyOffer :months=value.months :monthlyPayment=value.monthlyPayment
                            :name=value.name></SuggestionComponent>
                      </div>
                    </div>
                  </div>

                  <button class="carousel-control-prev" type="button" data-bs-target="#carouselSuggestions"
                    data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                  </button>
                  <button class="carousel-control-next" type="button" data-bs-target="#carouselSuggestions"
                    data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                  </button>
                </div>
              </div> <!-- Termina carousel de sugerencias -->

              <hr>

              <div class="col-12"> <!-- Listado de caracteristicas del producto -->
                <div>
                  <p class="fs-4 text-start">Características de {{ product.shortName }}</p>
                </div>

                <div class="container">
                  <div class="row text-start"> <!-- Características (nombre y valor) -->
                    <div v-for="(value, index) in caracteristicas" v-bind:key="index" class="col-6 d-flex align-items-center my-3">
                      <i class="fa-regular fa-circle-check description-check"></i>
                      <p class="my-auto ms-2"> {{ value.name }}: <span class="fw-bold">{{ value.value }}</span></p>
                    </div>
                  </div>
                </div>
              </div> <!-- Listado de caracteristicas del producto -->

              <div class="accordion accordion-flush mt-4 mb-3" id="accordionFlushExample">
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed text-primary" type="button" data-bs-toggle="collapse"
                      data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                      Ver más características
                    </button>
                  </h2>
                  <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">
                      <div class="col-12 mt-5"> <!-- Tablas de caracreristicas -->
                        <div class="container">
                          <div class="row text-start">
                            <div class="col-6"> <!-- Inicia la primer columna de tablas con caracteristicas -->
                              <TableComponent v-for="table in featureTables.slice(0,5)" v-bind:key="table" :name=table.name :rows=table.rows></TableComponent>
                            </div> <!-- Termina la primera columna de tablas con caracteristicas -->

                            <div class="col-6"> <!-- Inicia la segunda  columna de tablas con caracteristicas -->
                              <TableComponent v-for="table in featureTables.slice(5,9)" v-bind:key="table" :name=table.name :rows=table.rows></TableComponent>
                            </div> <!-- Termina la segunda columna de tablas con caracteristicas -->
                          </div>
                        </div>
                      </div> <!-- Terminan las tablas de caracteristicas -->
                    </div>
                  </div>
                </div>
              </div>

              <hr>

              <div class="col-12 mt-3 text-start">
                <h4>Descripción</h4>
                <DescriptionComponent v-for="description in descriptions" v-bind:key="description" :title=description.title 
                    :description=description.description></DescriptionComponent>
              </div>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="my-3 border rounded"> <!-- Seccion agregar al carrito -->
            <div class="container">
              <div class="row mt-3">
                <div class="col-1 text-success text-end">
                  <i class="fa-solid fa-truck"></i>
                </div>
                <div class="col-11 text-start">
                  <p class="text-success mb-0">Envío gratis a todo el país</p>
                  <p class="card-text text-success my-0 fs09rem fw-bold">
                    <span class="text-uppercasefst-italic"><i class="fa-solid fa-bolt"></i>Full</span>
                  </p>
                  <p class="texto-gris">Conoce los tiempos y las formas de envío</p>
                  <p>
                    <a href="" class="link">
                      <i class="fas fa-map-marker-alt"></i> Calcular cuándo llega
                    </a>
                  </p>
                </div>
              </div>

              <div class="row">
                <div class="col-12 text-start fs09rem">
                  <p class="mb-0">Tienda oficial <a href="" class="link">{{ product.tienda }}</a></p>
                  <p>+50mil ventas</p>
                </div>
              </div>

              <div class="row">
                <div class="col-12 text-start fs09rem">
                  <p class="fw-bold">Stock disponible</p>
                </div>
              </div>

              <div class="row">
                <div class="col-12 text-start fs09rem">
                  <div class="d-flex align-items-center mb-4">
                    <p class="my-auto me-2">Cantidad</p>
                    <select class="form-select w-auto" aria-label="Default select example">
                      <option value="1" selected>1 unidad</option>
                      <option value="2">2 unidades</option>
                      <option value="3">3 unidades</option>
                      <option value="4">4 unidades</option>
                      <option value="5">5 unidades</option>
                    </select>
                    <p class="texto-gris ms-2 my-auto">({{ product.unidades }}) disponibles</p>
                  </div>
                </div>
              </div>

              <div class="row"> <!-- Botones compra y agregar al carrito-->
                <div class="col-12">
                  <button class="btn btn-primary w-100 py-2">Comprar ahorita</button>
                  <button class="btn w-100 py-2 mt-3 text-primary azul-cielo">Agregar
                    al carrito</button>
                </div>
              </div>

              <div class="row mt-3"> <!-- Opción devolución -->
                <div class="col-1">
                  <i class="fa-solid fa-rotate-left texto-gris"></i>
                </div>
                <div class="col-11 text-start">
                  <p class="texto-gris"><a href="#" class="link">Devolución gratis. </a>Tienes 30 días desde que lo
                    recibes.</p>
                </div>
              </div>

              <div class="row mt-3"> <!-- Opción compra protegida -->
                <div class="col-1">
                  <i class="fa-solid fa-shield-halved texto-gris"></i>
                </div>
                <div class="col-11 text-start">
                  <p class="texto-gris"><a href="#" class="link">Compra protegida, </a>recibe el producto que esperabas o
                    te devolvemos tu dinero.</p>
                </div>
              </div>

              <div class="row mt-3"> <!-- Opción mercado puntos -->
                <div class="col-1">
                  <i class="fa-solid fa-trophy texto-gris"></i>
                </div>
                <div class="col-11 text-start">
                  <p class="texto-gris"><a href="#" class="link">Mercado puntos. </a>Sumas {{ product.points }} puntos.</p>
                </div>
              </div>
            </div>
          </div> <!-- Termina seccion agregar al carrito -->

          <div class="my-3 border rounded"><!-- Seccion información de la tienda -->
            <div class="container">
              <div class="row">
                <div class="col-12 text-start fs-6 my-4">
                  Información de la tienda
                </div>
              </div>

              <div class="row">
                <div class="col-3">
                  <div class="d-flex justify-content-start my-auto">
                    <a class="image-icontienda d-flex my-2" href="#"></a>
                  </div>
                </div>
                <div class="col-9 text-start my-auto">
                  <p class="my-0">{{ product.tienda }}</p>
                  <p class="texto-gris">Tienda oficial de Mercado Libre</p>
                </div>
              </div>

              <div class="row my-4">
                <div class="col-1">
                  <i class="fa-solid fa-medal text-success"></i>
                </div>
                <div class="col-11 text-start">
                  <p class="text-success my-0 fw-bold">
                    MercadoLíder Platinum
                  </p>
                  <p class="texto-gris fs09rem">
                    ¡Es uno de los mejores del sitio!
                  </p>
                </div>
              </div>

              <div class="row"> <!-- Cuadro de ventas -->
                <div class="col-12 d-flex" aria-hidden="true">
                  <ul class="mx-0 px-0" style="list-style-type: none;">
                    <li class="mx-1 px-4 sales-range" style="background-color: #FFF0F0;"></li>
                    <li class="mx-1 px-4 sales-range" style="background-color: #FFF5E8;"></li>
                    <li class="mx-1 px-4 sales-range" style="background-color: #FFFCDA;"></li>
                    <li class="mx-1 px-4 sales-range" style="background-color: #F1FDD7;"></li>
                    <li class="mx-1 px-4 sales-range bg-success"></li>
                  </ul>
                </div>
              </div>

              <div class="row my-3"><!-- Rango de ventas vendedor -->
                <div class="col-4 d-flex text-center">
                  <div class="mx-auto px-2">
                    <p class="fs-2 my-0">{{ product.totalVentasTienda }}</p>
                    <p class="texto-gris fs09rem">Ventas en los últimos 60 días</p>
                  </div>
                </div>

                <div class="col-4 text-center border-start border-end">
                  <div class="mx-auto px-2">
                    <i class="fa-regular fa-message"></i>
                    <p class="texto-gris fs09rem">Brinda una buena atención</p>
                  </div>
                </div>

                <div class="col-4 text-center border-start border-end">
                  <div class="mx-auto px-2">
                    <i class="fa-regular fa-clock"></i>
                    <p class="texto-gris fs09rem">Brinda una buena atención</p>
                  </div>
                </div>
              </div>

              <div class="row text-start my-4">
                <a href="" class="link fs09rem">Ver más datos de {{ product.tienda }}</a>
              </div>

            </div>
          </div> <!-- Termina seccion información de la tienda -->

          <div class="my-3 border rounded"><!-- Seccion medios de pago -->
            <div class="container">
              <div class="row">
                <div class="col-12 text-start fs-5 my-4">
                  Medios de pago
                </div>
              </div>

              <div class="row text-start my-3">
                <p class="fs-6">Hasta 12 meses sin tarjeta</p>

                <div class="payment-icon text-start">
                  <img :src="require('@/assets/logo-mc.svg')" alt="">
                </div>
              </div>

              <div class="row text-start my-4">
                <p class="fs-6 my-0">Tarjetas de crédito</p>
                <p class="texto-gris fs09rem">¡Paga hasta en 12 cuotas!</p>

                <div class="payment-icons">
                  <div class="payment-icon text-start d-flex">
                    <img :src="require('@/assets/logo-visa.svg')" alt="">
                    <img class="mx-3" :src="require('@/assets/logo-ae.svg')" alt="">
                    <img :src="require('@/assets/logo-mcard.svg')" alt="">
                  </div>
                </div>
              </div>

              <div class="row text-start my-4">
                <p class="fs-6 my-0">Tarjetas de débito</p>

                <div class="payment-icons">
                  <div class="payment-icon text-start d-flex">
                    <img :src="require('@/assets/logo-visad.svg')" alt="">
                    <img class="mx-5" :src="require('@/assets/logo-upsv.svg')" alt="">
                  </div>
                  <div class="payment-icon text-start d-flex mt-3">
                    <img :src="require('@/assets/logo-edenr.svg')" alt="">
                    <img class="mx-5" :src="require('@/assets/logo-mcarddebito.svg')" alt="">
                  </div>
                </div>
              </div>

              <div class="row text-start my-4">
                <p class="fs-6 my-0">Efectivo</p>

                <div class="payment-icons">
                  <div class="payment-icon text-start d-flex">
                    <img :src="require('@/assets/logo-oxxo.svg')" alt="">
                    <img class="mx-4" :src="require('@/assets/logo-paycash.svg')" alt="">
                  </div>
                </div>
              </div>

              <div class="row">
                <div class="col-12 text-start fs09rem mb-4 mt-2">
                  <a href="#" class="link">Conoce otros medios de pago</a>
                </div>
              </div>
            </div>
          </div> <!-- Termina seccion medios de pago -->
        </div>
      </div> <!-- Termina renglon que contiene los detalles del producto hasta descripción -->

      <hr>

      <div class="row"> <!-- Inicia la sección preguntas y respuestas -->
        <div class="col-12">
          <div class="container text-start">
            <div class="row">
              <div class="col-12">
                <p class="fs-4">Preguntas y respuestas</p>
              </div>
            </div>

            <div class="row my-3">
              <div class="col-12">
                <p class="fs-6 fw-bold">¿Qué quieres saber?</p>
              </div>
            </div>

            <div class="row my-3"> <!-- Botones con modales -->
              <div class="col-12">
                <!-- Button costo y tiempo de envío -->
                <button type="button" class="btn azul-cielo text-primary fs09rem" data-bs-toggle="modal"
                  data-bs-target="#costAndTimeModal">
                  Costo y tiempo de envío
                </button>

                <!-- Button devoluciones -->
                <button type="button" class="btn azul-cielo text-primary fs09rem ms-3" data-bs-toggle="modal"
                  data-bs-target="#returnsModal">
                  Devoluciones gratis
                </button>

                <!-- Button medios de pago y promociones -->
                <button type="button" class="btn azul-cielo text-primary fs09rem ms-3" data-bs-toggle="modal"
                  data-bs-target="#promotionsModal">
                  Medios de pago y promociones
                </button>

                <!-- Button garantía -->
                <button type="button" class="btn azul-cielo text-primary fs09rem ms-3" data-bs-toggle="modal"
                  data-bs-target="#warrantyModal">
                  Garantía
                </button>

                <!-- Modal costo y tiempo de envío -->
                <div class="modal fade" id="costAndTimeModal" tabindex="-1" aria-labelledby="costAndTimeModalLabel"
                  aria-hidden="true">
                  <div class="modal-dialog modal-dialog-centered">
                    <div class="modal-content">
                      <div class="modal-header">
                        <h1 class="modal-title fs-5" id="costAndTimeModalLabel">Costo y tiempo de envío</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                      </div>
                      <div class="modal-body">
                        <div class="container">
                          <div class="row">
                            <div class="col-12">
                              <p class="fw-bold">Elige dónde recibir tus compras</p>
                              <p class="texto-gris fs09rem">Podrás ver costos y tiempos de entrega precisos en todo lo que
                                busques.</p>
                            </div>

                            <div class="col-12 mb-0 pb-0">
                              <p class="texto-gris fs09rem mb-0 pb-0">Código postal</p>
                            </div>

                            <div class="col-8 d-flex">
                              <div class="input-group mb-3">
                                <input type="text" class="form-control border border-primary"
                                  placeholder="Ingresar un código postal" aria-label="Ingresar un código postal"
                                  aria-describedby="basic-addon2">
                                <div class="input-group-append">
                                  <button class="btn btn-primary" type="button">Usar</button>
                                </div>
                              </div>
                            </div>

                            <div class="col-4 ms-0 d-flex">
                              <a href="#" class="link text-primary mt-1">No sé mi código</a>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <!-- Modal devoluciones -->
                <div class="modal fade" id="returnsModal" tabindex="-1" aria-labelledby="returnsModalLabel"
                  aria-hidden="true">
                  <div class="modal-dialog modal-dialog-centered modal-lg">
                    <div class="modal-content">
                      <div class="modal-header">
                        <h1 class="modal-title fs-5 fw-bold" id="returnsModalLabel">Devoluciones gratis</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                      </div>
                      <div class="modal-body">
                        <div class="container text-start my-4">
                          <div class="row texto-gris">
                            <div class="col-2">
                              <i class="fa-solid fa-calendar fa-xl"></i>
                            </div>
                            <div class="col-10">
                              <p class="fs-6">Tienes 30 días desde que te llega.</p>
                            </div>

                            <div class="col-2">
                              <i class="fa-solid fa-rotate-left fa-xl"></i>
                            </div>
                            <div class="col-10">
                              <p class="fs-6">Puedes enviarlo desde un correo o una agencia de Mercado Libre cercana.</p>
                            </div>

                            <div class="col-2">
                              <i class="fa-solid fa-circle-dollar-to-slot fa-xl"></i>
                            </div>
                            <div class="col-10">
                              <p class="fs-6">Es importante que revises las <a href="" class="link">políticas de
                                  devolución</a> .</p>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <!-- Modal medios de pago y promociones -->
                <div class="modal fade" id="promotionsModal" tabindex="-1" aria-labelledby="promotionsModalLabel"
                  aria-hidden="true">
                  <div class="modal-dialog modal-dialog-centered">
                    <div class="modal-content">
                      <div class="modal-header">
                        <h1 class="modal-title fs-5" id="promotionsModalLabel">Medios de pago y promociones</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                      </div>
                      <div class="modal-body">
                        ...
                      </div>
                    </div>
                  </div>
                </div>

                <!-- Modal garantia -->
                <div class="modal fade" id="warrantyModal" tabindex="-1" aria-labelledby="warrantyModalLabel"
                  aria-hidden="true">
                  <div class="modal-dialog modal-dialog-centered modal-lg">
                    <div class="modal-content">
                      <div class="modal-header">
                        <h1 class="modal-title fs-4 fw-bold" id="warrantyModalLabel">Garantía</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                      </div>
                      <div class="modal-body">
                        <div class="container my-4">
                          <div class="row">
                            <div class="col-2 text-danger text-center my-auto ">
                              <i class="fa-solid fa-shield-halved fa-xl"></i>
                            </div>

                            <div class="col-10">
                              <p class="texto-gris fs-4">
                                <span class="text-dark">Tu compra está protegida. </span>
                                Si hay algún problema o no recibes el producto tal como lo compraste, te devolvemos el
                                dinero que pagaste.
                              </p>
                            </div>

                            <div class="col-12 fw-bold fs-5 mt-3 mb-0">
                              <p>Estamos para ayudarte, siempre</p>
                            </div>

                            <div class="col-12 mt-0">
                              <p class="fs-6">
                                Te acompañamos hasta que recibas lo que compraste y nos avises que estás conforme.
                                Si surge algún problema, solo tienes que avisarnos.</p>
                            </div>

                            <div class="col-12">
                              <a href="#" class="link fs09rem">Conocer más sobre Compra Protegida</a>
                            </div>

                            <div class="col-12">
                              <hr>
                            </div>

                            <div class="col-12">
                              <p class="fs-5 fw-bold">Garantía de la tienda</p>
                            </div>

                            <div class="col-12">
                              <p class="fs-6">Garantía del vendedor: 30 días</p>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div> <!-- Terminan botones con modales -->

            <div class="row text-start my-5"> <!-- Inicia renglón buscador depreguntas -->
              <div class="col-12">
                <p class="fs-6 fw-bold">Busca lo que quieres saber</p>
              </div>

              <div class="row-12"> <!-- Buscador preguntas -->
                <div class="input-group mb-2">
                  <input type="text" class="form-control py-3" placeholder="Escribe una pregunta o palabra clave...">
                  <div class="input-group-append">
                    <button class="btn btn-primary py-3 px-4" type="button"><i
                        class="fa-solid fa-magnifying-glass"></i></button>
                  </div>
                </div>
              </div>
            </div> <!-- Termina renglón buscador depreguntas -->

            <div class="row"><!-- Inicia bloque de preguntas -->
              <div class="col-12">
                <p class="fw-bold">Últimas realizadas</p>
              </div>
              <QuestionComponent :v-if="questions && questions.length > 0" v-bind:key="questions[0].id" :question=questions[0].question :answer=questions[0].answer />
              
              <div :v-if="questions && questions.length > 0" class="accordion accordion-flush mt-2" id="accordionQuestions">
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed text-primary fs-6 fw-bold" type="button" data-bs-toggle="collapse"
                      data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
                      Ver {{ questions.length - 1 }} resultados más
                    </button>
                  </h2>
                  <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionQuestions">
                    <div>
                      <QuestionComponent :v-if="questions && questions.length > 0" v-for="(question) in questions.slice(1,)" v-bind:key="question.id" :question=question.question :answer=question.answer />
                    </div>
                  </div>
                </div>
              </div>
            </div> <!-- Termina bloque de preguntas -->

            <div class="row my-5">
              <div class="col-12">
                <button class="btn azul-cielo text-primary py-2 px-4">
                  ¿Cómo le pregunto al vendedor?
                </button>
              </div>
            </div>
          </div>
        </div>
      </div> <!-- Termina la sección preguntas y respuestas -->

      <hr>

      <div class="row"> <!-- Inicia sección opiniones del producto -->

        <div class="col-12 text-start">
          <p class="fs-4">Opiniones del producto</p>
        </div>

        <div class="col-3 text-start"><!-- Raiting -->
          <dis class="">
            <div class="row">
              <div class="col-3 my-auto">
                <p class="fs-1 fw-bold text-primary">4.8</p>
              </div>
              <div class="col-9">
                <RaitingComponent :percentage="90" class="fs-4"/>
                <p class="texto-gris fs09rem">{{ product.numValoraciones }} calificaciones</p>
              </div>
            </div>

            <div class="row mt-3 align-items-center">
              <div class="col-9">
                <div class="progress" role="progressbar" aria-label="Example 5px high" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="height: 5px;">
                  <div class="progress-bar" style="width: 90%"></div>
                </div>
              </div>
              <div class="col-3">
                <p class="texto-gris">5 <span><i class="fa fa-star"></i></span></p>
              </div>

              <div class="col-9">
                <div class="progress" role="progressbar" aria-label="Example 5px high" aria-valuenow="5" aria-valuemin="0" aria-valuemax="100" style="height: 5px;">
                  <div class="progress-bar" style="width: 5%"></div>
                </div>
              </div>
              <div class="col-3">
                <p class="texto-gris">4 <span><i class="fa fa-star"></i></span></p>
              </div>

              <div class="col-9">
                <div class="progress" role="progressbar" aria-label="Example 5px high" aria-valuenow="2" aria-valuemin="0" aria-valuemax="100" style="height: 5px;">
                  <div class="progress-bar" style="width: 2%"></div>
                </div>
              </div>
              <div class="col-3">
                <p class="texto-gris">3 <span><i class="fa fa-star"></i></span></p>
              </div>

              <div class="col-9">
                <div class="progress" role="progressbar" aria-label="Example 5px high" aria-valuenow="2" aria-valuemin="0" aria-valuemax="100" style="height: 5px;">
                  <div class="progress-bar" style="width: 2%"></div>
                </div>
              </div>
              <div class="col-3">
                <p class="texto-gris">2 <span><i class="fa fa-star"></i></span></p>
              </div>

              <div class="col-9">
                <div class="progress" role="progressbar" aria-label="Example 5px high" aria-valuenow="2" aria-valuemin="0" aria-valuemax="100" style="height: 5px;">
                  <div class="progress-bar" style="width: 2%"></div>
                </div>
              </div>
              <div class="col-3">
                <p class="texto-gris">1 <span><i class="fa fa-star"></i></span></p>
              </div>

              <div class="col-12"><!-- Inicia calificación de características -->
                <div class="ps-3 my-3">
                  <p class="fs09rem my-0">Relación calidad-precio</p>
                  <RaitingComponent :percentage="90" class="fs-6 mt-0"/>
                </div>

                <div class="ps-3 my-3">
                  <p class="fs09rem my-0">Prácticidad</p>
                  <RaitingComponent :percentage="90" class="fs-6 mt-0"/>
                </div>

                <div class="ps-3 my-3">
                  <p class="fs09rem my-0">Calidad del sonido</p>
                  <RaitingComponent :percentage="70" class="fs-6 mt-0"/>
                </div>

                <div class="ps-3 my-3">
                  <p class="fs09rem my-0">Duración de la bateria</p>
                  <RaitingComponent :percentage="90" class="fs-6 mt-0"/>
                </div>
              </div> <!-- Inicia calificación de características -->
            </div>
          </dis>
        </div><!-- Raiting -->
          
        <div class="col-6">
          <CommentComponent v-for="(comment) in comments" v-bind:key=comment.id :percentage=comment.percentage :date=comment.date :comment=comment.comment :quantityLike=comment.quantityLike />
        </div>


      </div> <!-- Termina sección opiniones del producto -->
    </div> <!-- Termina sección de fondo blanco -->

    <div class="container text-center main px-0 fs09rem"> <!-- Seccion tambien puede interesarte -->
      <div class="container">
        <div class="row pt-4">
          <div class="col-12">
            <div class="text-start">
              <p class="fs-3">También te pueden interesar</p>
            </div>
          </div>
          
        </div>
        <div class="row text-start">
          <div class="col-12">
            <div class="col-12 my-fixed-item"> <!-- Carrusel de imagenes -->
              <div id="carouselSuggestions2" class="carousel slide" data-ride="carousel">
                <div class="carousel-inner">
                  <div class="carousel-item active"> <!-- Padre conjunto de 4 sugerencias-->
                    <div class="row"> <!-- Conjunto de 4 sugerencias -->
                      <SuggestionComponent v-for="(value, index) in suggestions.slice(0, 4)" v-bind:key="index" :size=3 :id=value.id :photo=value.photo
                            :originalPrice=value.originalPrice :offerPrice=value.offerPrice :discount=value.discount
                            :freeShipping=value.freeShipping :full=value.full :monthsOffer=value.monthsOffer
                            :monthlyOffer=value.monthlyOffer :months=value.months :monthlyPayment=value.monthlyPayment
                            :name=value.name></SuggestionComponent>
                    </div>
                  </div>

                  <div class="carousel-item"> <!-- Padre conjunto de 4 sugerencias-->
                    <div class="row"> <!-- Conjunto de 4 sugerencias -->
                      <SuggestionComponent v-for="(value, index) in suggestions.slice(4, 8)" v-bind:key="index" :size=3 :id=value.id :photo=value.photo
                            :originalPrice=value.originalPrice :offerPrice=value.offerPrice :discount=value.discount
                            :freeShipping=value.freeShipping :full=value.full :monthsOffer=value.monthsOffer
                            :monthlyOffer=value.monthlyOffer :months=value.months :monthlyPayment=value.monthlyPayment
                            :name=value.name></SuggestionComponent>
                    </div>
                  </div>

                  <div class="carousel-item"> <!-- Padre conjunto de 4 sugerencias-->
                    <div class="row"> <!-- Conjunto de 4 sugerencias -->
                      <SuggestionComponent v-for="(value, index) in suggestions.slice(8, 12)" v-bind:key="index" :size=3 :id=value.id :photo=value.photo
                            :originalPrice=value.originalPrice :offerPrice=value.offerPrice :discount=value.discount
                            :freeShipping=value.freeShipping :full=value.full :monthsOffer=value.monthsOffer
                            :monthlyOffer=value.monthlyOffer :months=value.months :monthlyPayment=value.monthlyPayment
                            :name=value.name></SuggestionComponent>
                    </div>
                  </div>
                </div>

                <button class="carousel-control-prev" type="button" data-bs-target="#carouselSuggestions2"
                  data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselSuggestions2"
                  data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
            </div> <!-- Termina carousel de sugerencias -->
          </div>
        </div>
      </div>
    </div> <!-- Termina sección también puede interesarte -->

    <div class="container text-center main px-0 pb-5 fs09rem"> <!-- Anuncio final -->
      <a class="link" href="#">
        <div class="container">
          <div class="row">
            <div class="col-7 p-0">
              <div class="w-100">
                <img class="anuncio-samsung" src="http://localhost:7171/anuncio-samsung.jpg" alt="samsung">
              </div>
            </div>
            <div class="col-5 bg-dark d-flex text-start text-white">
              <p class="my-auto px-5">
                <span class="text-uppercase fs-6">¡Prepárate!</span>
                <span class="text-uppercase fs-3 fw-bold d-block">Grandes ofertas hasta 30% de off</span>
                <span class="text-uppercase fs-6">Ver más ></span>
              </p>
            </div>
          </div>
        </div>
      </a>
    </div> <!-- Termina anuncio final -->
  </main>
</template>

<script>
import axios from 'axios';
import CarouselComponent from '../components/CarouselComponent.vue';
import QuestionComponent from '../components/QuestionComponent.vue';
import RaitingComponent from '../components/RaitingComponent.vue';
import CommentComponent from '../components/CommentComponent.vue';
import SuggestionComponent from '../components/SuggestionComponent.vue';
import TableComponent from '@/components/TableComponent.vue';
import DescriptionComponent from '@/components/DescriptionComponent.vue';

import info from '../json/ProductoView.json'
import preguntas from '../json/preguntas.json'
import comentarios from '../json/comments.json'
import sugerencias from '../json/suggestions.json'

export default {
  components: {
    'CarouselComponent': CarouselComponent,
    'QuestionComponent': QuestionComponent,
    'RaitingComponent': RaitingComponent,
    'CommentComponent': CommentComponent,
    'SuggestionComponent': SuggestionComponent,
    'TableComponent': TableComponent,
    'DescriptionComponent': DescriptionComponent
  }, 
  data: function () {
    return {
      classHeart: 'fa-regular fa-heart text-primary',
      baseUrl: 'http://localhost:7171/',

      product: {},
      imagenes: [],
      puntosDestacables: [],
      caracteristicas: [],
      featureTables: [],
      descriptions: [],

      questions: [{}],
      comments: [{}],
      suggestions: [{}],
    }
  },
  methods: {
    favorite: function () { /** Función que permite cambiar el icono de producto favorito */
      this.classHeart = (this.classHeart == 'fa-regular fa-heart text-primary') ? 'fa-solid fa-heart text-primary' : 'fa-regular fa-heart text-primary';
    },
    loadBasicInfo: function() {
      const url = 'http://localhost:9999';
      const endpoint = '/api/json-data';

      axios.get(url + endpoint)
      .then(response => {
        const info2 = response.data;
        this.imagenes = info2.imagenes || [];
        this.product = info2.producto || {};
        this.puntosDestacables = info2.puntosDestacables || [];
        this.caracteristicas = info2.caracteristicas || [];
        this.featureTables = info2.featureTables || [];
        this.descriptions = info2.descriptions || [];
      })
      .catch(error => {
        console.error('Error al cargar los datos del producto:', error);
      });
    }
  },

  mounted: function () {
    this.questions = preguntas.questions || [{}];
    this.comments = comentarios.comments || [{}];
    this.suggestions = sugerencias.suggestions || [{}];

    const flag = true;
    if (flag) {
      this.loadBasicInfo();
      return;
    }
    // aqui viene la magia, chamacos cochinotes.... jajaja
    this.imagenes = info.imagenes || [];
    this.product = info.producto || {};
    this.puntosDestacables = info.puntosDestacables || [];
    this.caracteristicas = info.caracteristicas || [];
    this.featureTables = info.featureTables || [];
    this.descriptions = info.descriptions || [];
  }

}
</script>

<style scoped>
body {
  width: 100%;
  height: 100%;
}

header {
  width: 100%;
  background-color: #fff159;
}

main {
  width: 100%;
  font-family: Proxima Nova, -apple-system, Roboto, Arial, sans-serif;
  background-color: #EDEDED;
}

.header {
  background-color: #fff159;
  width: 90%;
  margin-top: -60px;
  height: max-content;
}

.main {
  width: 68%;
}

.fs09rem {
  font-size: 0.9rem;
}

.logoML {
  background-image: url(http://localhost:7171/logoML.png);
  background-repeat: no-repeat;
  background-size: 135px 35px;
  height: 35px;
  width: 135px;
  text-decoration: none;
  background-position: center;
}

.search {
  font-size: 15px;
  border-radius: 2px;
  color: #333;
  padding-top: 13px;
}

.enlace-dropdown:hover {
  background-color: #30A2FF;
}

.link {
  text-decoration: none;
}

.link:hover {
  color: #30A2FF;
}

.texto-gris {
  font-size: 0.9rem;
  color: #545B77;
}

.campo-naranja {
  font-size: 0.8rem;
  background-color: #FD7E14;
  width: fit-content;
  border-radius: 3px;
}

.image-colorproduct {
  background-image: url(http://localhost:7171/alexa1.webp);
  background-repeat: no-repeat;
  background-size: 50px 50px;
  background-position: center;
  height: 58px;
  width: 58px;
  text-decoration: none;
}

.image-colorproduct:hover {
  cursor: pointer;
}

.sugestion-image {
  height: 190px;
  width: 190px;
}

.sugestion-link:hover {
  box-shadow: 0 0 20px #4f9;
}

.border-gris {
  border-color: #EDEDED;
}

.border-gris:hover {
  -webkit-box-shadow: 0px 0px 5px 5px rgba(209, 201, 209, 1);
  -moz-box-shadow: 0px 0px 5px 5px rgba(209, 201, 209, 1);
  box-shadow: 0px 0px 5px 5px rgba(209, 201, 209, 1);
}

.description-check {
  background-color: #EDEDED;
  border-radius: 50%;
  padding: 6px;
}

.image-icontienda {
  background-image: linear-gradient(to bottom, rgba(237, 237, 237, 0.50), rgba(237, 237, 237, 0.50)), url(http://localhost:7171/icono-tienda.jpg);
  background-repeat: no-repeat;
  background-size: 75px 50px;
  background-position: center;
  height: 50px;
  width: 75px;
}

.sales-range {
  height: 10px;
  width: 17%;
  float: left;
}

.payment-icon {
  width: 32px;
}

.anuncio-samsung {
  width: inherit;
}

.azul-cielo {
  background-color: rgba(65, 137, 230, .15);
}
</style>
<script>
</script>

<main class="sticky-top">
  <header class="animated menu-fixed-out">
    <div class="container">
      <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
          <a href="/"
            ><img
              id="logo"
              src="img/logo-azarquiel.png"
              alt="Logo IesAzarquiel"
            /></a
          >
          <button
            class="navbar-toggler"
            type="button"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
            data-bs-toggle="offcanvas"
            data-bs-target="#demo"
          >
            <i class="fa-solid fa-bars" />
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#!"
                  >INICIO</a
                >
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#!"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  AL DÍA
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#!">Blog del centro</a></li>
                  <li><a class="dropdown-item" href="#!">Avisos y convocatorias</a></li>
                </ul>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#!"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  EL CENTRO
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#!">Características</a></li>
                  <li><a class="dropdown-item" href="#!">Horario</a></li>
                  <li><a class="dropdown-item" href="#!">Instalaciones</a></li>
                  <li><a class="dropdown-item" href="#!">Proyecto educativo del centro</a></li>
                </ul>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#!"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  SECRETARÍA
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#!">Horario Secretaría</a></li>
                  <li><a class="dropdown-item" href="#!">Preguntas Frecuentes</a></li>
                  <li><a class="dropdown-item" href="#!">Impresos Habituales</a></li>
                </ul>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#!"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  FAMILIAS
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#!">Familias en Red</a></li>
                  <li><a class="dropdown-item" href="#!">Activar SMS Faltas Asistencia</a></li>
                  <li><a class="dropdown-item" href="#!">Calendario</a></li>
                  <li><a class="dropdown-item" href="#!">Estructura Académica</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#!"
                  >BOLSA</a
                >
              </li>
            </ul>
            <div class="d-flex">
              <i
                data-bs-toggle="offcanvas"
                data-bs-target="#demo"
                id="menu"
                class="fa-solid fa-bars"
              />
            </div>
          </div>
        </div>
      </nav>
    </div>
  </header>

  <div class="offcanvas offcanvas-end text-bg-dark" id="demo">
    <div class="offcanvas-header">
      <h1 class="offcanvas-title">SEARCH</h1>
      <button
        type="button"
        class="btn-close btn-close-white text-reset"
        data-bs-dismiss="offcanvas"
      />
    </div>
    <div class="offcanvas-body">
      <p>INICIO</p>
      <p>AL DÍA</p>
      <p>EL LORO</p>
      <p>EL CENTRO</p>
      <p>SECRETARÍA</p>
      <p>FAMILIAS</p>
      <p>BOLSA</p>
    </div>
  </div>
</main>

<style lang="sass">
  main
    font-family: 'Open Sans', sans-serif
    box-shadow: rgba(60, 64, 67, 0.3) 0px 1px 2px 0px, rgba(60, 64, 67, 0.15) 0px 2px 6px 2px
    height: 5rem
    background-color: white

    #logo
      max-width: 16rem
      width: 100%
      margin-left: 5rem
      margin-top: 0.5rem

    p
      color: white
      cursor: pointer
      &:hover
        font-weight: bold
        text-decoration: underline

    .container-fluid 
      button
        border: none

        &:hover
          color: #89D5F2
          transition: 400ms
      

      a
        color: gray
        font-weight: lighter
        letter-spacing: 1px
        font-size: 0.75rem
        &:hover
          color:#89D5F2


  .navbar-collapse
    margin-left: 13rem


  #menu
    cursor: pointer
    font-size: 1.5rem
    margin-left: -6rem
    margin-top: 0.3rem

    &:hover
      color: #89D5F2
      transition: 400ms



  @media (max-width: 1400px)
   .navbar-collapse
     margin-left: 0rem

   #menu
    cursor: pointer
    font-size: 1.5rem
    margin-left: -10rem

  @media (max-width: 1200px)
   .navbar-collapse
     margin-left: 0rem

   #menu
    cursor: pointer
    font-size: 1.5rem
    margin-left: 0rem

  @media (max-width: 550px)
    main
      font-family: 'Open Sans', sans-serif
      box-shadow: rgba(60, 64, 67, 0.3) 0px 1px 2px 0px, rgba(60, 64, 67, 0.15) 0px 2px 6px 2px
      height: 5rem
      background-color: white
      justify-content: center
      
      #logo
        max-width: 14rem
        width: 100%
        margin-left: 0rem
        margin-top: 0.5rem

</style>

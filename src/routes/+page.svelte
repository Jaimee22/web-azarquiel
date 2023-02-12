<main>
  <div class="titulo">
    <h1>Cursos de Especialización<span>&#160;</span></h1>
  </div>
  <ul class="card-wrapper">
    <li class="card fadeInLeft">
      <a href="/videojuegos"
        ><img src="img/videojuegos/videojuegos.jpg" alt="" /></a
      >
      <h3><a href="/videojuegos">Videojuegos</a></h3>
    </li>

    <li class="card fadeInRight">
      <a href="/ciberseguridad"
        ><img src="img/ciberseguridad/ciberseguridad.jpg" alt="" /></a
      >
      <h3><a href="/ciberseguridad">Ciberseguridad</a></h3>
    </li>
  </ul>
</main>

<style>
  .fadeInLeft {
    -webkit-animation-name: fadeInLeft;
    animation-name: fadeInLeft;
    -webkit-animation-duration: 1s;
    animation-duration: 1s;
    -webkit-animation-fill-mode: both;
    animation-fill-mode: both;
  }
  @-webkit-keyframes fadeInLeft {
    0% {
      opacity: 0;
      -webkit-transform: translate3d(-100%, 0, 0);
      transform: translate3d(-100%, 0, 0);
    }
    100% {
      opacity: 1;
      -webkit-transform: none;
      transform: none;
    }
  }
  @keyframes fadeInLeft {
    0% {
      opacity: 0;
      -webkit-transform: translate3d(-100%, 0, 0);
      transform: translate3d(-100%, 0, 0);
    }
    100% {
      opacity: 1;
      -webkit-transform: none;
      transform: none;
    }
  }

  .fadeInRight {
    -webkit-animation-name: fadeInRight;
    animation-name: fadeInRight;
    -webkit-animation-duration: 1s;
    animation-duration: 1s;
    -webkit-animation-fill-mode: both;
    animation-fill-mode: both;
  }
  @-webkit-keyframes fadeInRight {
    0% {
      opacity: 0;
      -webkit-transform: translate3d(100%, 0, 0);
      transform: translate3d(100%, 0, 0);
    }
    100% {
      opacity: 1;
      -webkit-transform: none;
      transform: none;
    }
  }
  @keyframes fadeInRight {
    0% {
      opacity: 0;
      -webkit-transform: translate3d(100%, 0, 0);
      transform: translate3d(100%, 0, 0);
    }
    100% {
      opacity: 1;
      -webkit-transform: none;
      transform: none;
    }
  }

  .card {
    --card-gradient: rgba(0, 0, 0, 0.8);
    --card-gradient: #000000, #767c77;
    --card-blend-mode: overlay;
    background-color: #fff;
    border-radius: 0.5rem;
    box-shadow: 0.05rem 0.1rem 0.3rem -0.03rem rgba(0, 0, 0, 0.45);
    padding-bottom: 1rem;
    background-image: linear-gradient(var(--card-gradient), white 9.5rem);
    overflow: hidden;
    width: 22rem;
  }
  .card img {
    border-radius: 0.5rem 0.5rem 0 0;
    width: 100%;
    object-fit: cover;
    max-height: 10rem;
    aspect-ratio: 1.3333333333;
    mix-blend-mode: var(--card-blend-mode);
  }

  .card > :last-child {
    margin-bottom: 0;
  }

  .card:hover,
  .card:focus-within {
    --card-gradient: #9dd6e9 9rem;
  }

  body {
    display: grid;
    place-content: center;
    justify-items: center;
    min-height: 100vh;
    margin: 0;
    padding: 1rem;
    line-height: 1.5;
    color: #444;
    background-color: #e1faf1;
  }

  a {
    text-decoration: none;
  }

  .card h3 {
    margin-top: 1rem;
    font-size: 1.25rem;
    text-align: center;
    text-decoration: none;
  }
  .card a {
    color: inherit;
  }
  .card-wrapper {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    grid-gap: 1.5rem;
    max-width: 100%;
    width: 100%;
    padding-left: 1rem;
    padding-right: 1rem;
    padding-top: 2.5rem;
    justify-content: center;
    align-items: center;
  }

  .titulo {
    margin: auto;
    display: table;
    margin-top: 1rem;
  }

  h1 {
    position: relative;
    float: left;
  }

  h1 span {
    position: absolute;
    right: 0;
    width: 0;
    background: rgb(255, 255, 255);
    border-left: 1px solid rgb(255, 255, 255);
    animation: escribir 0.75s steps(25);
    height: 3.1rem;
  }

  @keyframes escribir {
    from {
      width: 100%;
    }
    to {
      width: 0;
    }
  }

  /* @media (min-width: 310px){
    h1{
        font-size: 2rem;
    }
  } */

  @media (min-width: 455px){
    h1{
        font-size: 2.2rem;
    }
  }

  @media (min-width: 500px){
    h1{
        font-size: 2.5rem;
    }
  }

  @media (max-width: 600px){
    .card-wrapper {
      list-style: none;
      padding: 0;
      margin: 0;
      display: flex;
      grid-gap: 1.5rem;
      max-width: 100%;
      width: 100%;
      padding-left: 1rem;
      padding-right: 1rem;
      padding-top: 2.5rem;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
  }

</style>

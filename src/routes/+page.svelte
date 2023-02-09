<!-- <main class="page-content">
        <div class="card">
          <div class="content">
            <h2 class="title">Ciberseguridad</h2>
            <p class="copy">Check out all of these gorgeous mountain trips with beautiful views of, you guessed it, the mountains</p>
            <button class="btn">View Trips</button>
          </div>
        </div>
        <div class="card">
          <div class="content">
            <h2 class="title">Videojuegos</h2>
            <p class="copy">Plan your next beach trip with these fabulous destinations</p>
            <button class="btn">View Trips</button>
          </div>
       </div>
</main> -->


<!-- <style>
@import url('https://fonts.googleapis.com/css?family=Cardo:400i|Rubik:400,700&display=swap');
 :root {
	 --d: 700ms;
	 --e: cubic-bezier(0.19, 1, 0.22, 1);
	 --font-sans: 'Rubik', sans-serif;
	 --font-serif: 'Cardo', serif;
}
 * {
	 box-sizing: border-box;
}
 html, body {
	 height: 100%;
}
 body {
	 display: grid;
	 place-items: center;
}

 /* .padre{
    display: flex;
    justify-content: center;
    text-align: center;
    align-items: center;
    justify-content: center;
    justify-items: center;
 } */

 .page-content {
	 display: grid;
	 grid-gap: 2rem;
	 padding: 1rem;
	 max-width: 120%;
	 margin: 0 auto;
	 font-family: var(--font-sans);
}
 @media (min-width: 600px) {
	 .page-content {
		 grid-template-columns: repeat(2, 1fr);
	}
}
 @media (min-width: 800px) {
	 .page-content {
		 grid-template-columns: repeat(4, 1fr);
	}
}
 .card {
	 position: relative;
	 display: flex;
	 align-items: flex-end;
	 overflow: hidden;
	 padding: 1rem;
	 width: 100%;
	 text-align: center;
	 color: whitesmoke;
	 background-color: whitesmoke;
	 box-shadow: 0 1px 1px rgba(0, 0, 0, 0.1), 0 2px 2px rgba(0, 0, 0, 0.1), 0 4px 4px rgba(0, 0, 0, 0.1), 0 8px 8px rgba(0, 0, 0, 0.1), 0 16px 16px rgba(0, 0, 0, 0.1);
}
 @media (min-width: 600px) {
	 .card {
		 height: 350px;
	}
}
 .card:before {
	 content: '';
	 position: absolute;
	 top: 0;
	 left: 0;
	 width: 100%;
	 height: 110%;
	 background-size: cover;
	 background-position: 0 0;
	 transition: transform calc(var(--d) * 1.5) var(--e);
	 pointer-events: none;
}
 .card:after {
	 content: '';
	 display: block;
	 position: absolute;
	 top: 0;
	 left: 0;
	 width: 100%;
	 height: 200%;
	 pointer-events: none;
	 background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.009) 11.7%, rgba(0, 0, 0, 0.034) 22.1%, rgba(0, 0, 0, 0.072) 31.2%, rgba(0, 0, 0, 0.123) 39.4%, rgba(0, 0, 0, 0.182) 46.6%, rgba(0, 0, 0, 0.249) 53.1%, rgba(0, 0, 0, 0.320) 58.9%, rgba(0, 0, 0, 0.394) 64.3%, rgba(0, 0, 0, 0.468) 69.3%, rgba(0, 0, 0, 0.540) 74.1%, rgba(0, 0, 0, 0.607) 78.8%, rgba(0, 0, 0, 0.668) 83.6%, rgba(0, 0, 0, 0.721) 88.7%, rgba(0, 0, 0, 0.762) 94.1%, rgba(0, 0, 0, 0.790) 100%);
	 transform: translateY(-50%);
	 transition: transform calc(var(--d) * 2) var(--e);
}
 .card:nth-child(1):before {
	 background-image: url(https://lh3.googleusercontent.com/p6RjX31DaHBp6EH1LguufBhMGnvSUPZeFI4n_JkNvqYfxbQ2YIfD8GrImwQPkLgLkpo7cnM8MU-WQHKQGDZBV2CvCDHm3jNgZw74YTXTevvANmYQVC0=s0);
}
 .card:nth-child(2):before {
	 background-image: url(https://images.unsplash.com/photo-1533903345306-15d1c30952de?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=400&fit=max&ixid=eyJhcHBfaWQiOjE0NTg5fQ);
}
 .card:nth-child(3):before {
	 background-image: url(https://images.unsplash.com/photo-1545243424-0ce743321e11?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=400&fit=max&ixid=eyJhcHBfaWQiOjE0NTg5fQ);
}
 .card:nth-child(4):before {
	 background-image: url(https://images.unsplash.com/photo-1531306728370-e2ebd9d7bb99?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=400&fit=max&ixid=eyJhcHBfaWQiOjE0NTg5fQ);
}
 .content {
	 position: relative;
	 display: flex;
	 flex-direction: column;
	 align-items: center;
	 width: 100%;
	 padding: 1rem;
	 transition: transform var(--d) var(--e);
	 z-index: 1;
}
 .content > * + * {
	 margin-top: 1rem;
}
 .title {
	 font-size: 1.3rem;
	 font-weight: bold;
	 line-height: 1.2;
     color: black;
}
 .copy {
	 font-family: var(--font-serif);
	 font-size: 1.125rem;
	 font-style: italic;
	 line-height: 1.35;
}
 .btn {
	 cursor: pointer;
	 margin-top: 1.5rem;
	 padding: 0.75rem 1.5rem;
	 font-size: 0.65rem;
	 font-weight: bold;
	 letter-spacing: 0.025rem;
	 text-transform: uppercase;
	 color: white;
	 background-color: black;
	 border: none;
}
 .btn:hover {
	 background-color: #0d0d0d;
}
 .btn:focus {
	 outline: 1px dashed yellow;
	 outline-offset: 3px;
}
 @media (hover: hover) and (min-width: 600px) {
	 .card:after {
		 transform: translateY(0);
	}
	 .content {
		 transform: translateY(calc(100% - 4.5rem));
	}
	 .content > *:not(.title) {
		 opacity: 0;
		 transform: translateY(1rem);
		 transition: transform var(--d) var(--e), opacity var(--d) var(--e);
	}
	 .card:hover, .card:focus-within {
		 align-items: center;
	}
	 .card:hover:before, .card:focus-within:before {
		 transform: translateY(-4%);
	}
	 .card:hover:after, .card:focus-within:after {
		 transform: translateY(-50%);
	}
	 .card:hover .content, .card:focus-within .content {
		 transform: translateY(0);
	}
	 .card:hover .content > *:not(.title), .card:focus-within .content > *:not(.title) {
		 opacity: 1;
		 transform: translateY(0);
		 transition-delay: calc(var(--d) / 8);
	}
	 .card:focus-within:before, .card:focus-within:after, .card:focus-within .content, .card:focus-within .content > *:not(.title) {
		 transition-duration: 0s;
	}
}
 
  </style> -->

<main>
        <br>
        <br>
    <ul class="card-wrapper">
        <br>
        <br>
        <br>
        <br>
        <li class="card">
          <a href="/videojuegos"><img src='img/videojuegos/videojuegos.jpg' alt=''></a>
          <h3><a href="/videojuegos">Videojuegos</a></h3>
        </li>

        <li class="card">
          <a href="/ciberseguridad"><img src='img/ciberseguridad/ciberseguridad.jpg' alt=''></a>
          <h3><a href="/ciberseguridad">Ciberseguridad</a></h3>
        </li>

    </ul>
</main>

<style>
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
}
 .card img {
	 border-radius: 0.5rem 0.5rem 0 0;
	 width: 100%;
	 object-fit: cover;
	 max-height: 10rem;
	 aspect-ratio: 1.3333333333;
	 mix-blend-mode: var(--card-blend-mode);
}
 .card img ~ * {
	 margin-left: 1rem;
	 margin-right: 1rem;
}
 .card > :last-child {
	 margin-bottom: 0;
}
 .card:hover, .card:focus-within {
	 --card-gradient: #9dd6e9 8.5rem;
}
/* Additional demo display styles */
 * {
	 box-sizing: border-box;
   }

 body {
     display: grid;
	 place-content: center;
	 justify-items: center;
	 min-height: 100vh;
	 margin: 0;
	 padding: 1rem;
	 line-height: 1.5;
	 font-family: -apple-system, BlinkMacSystemFont, avenir next, avenir, helvetica neue, helvetica, Ubuntu, roboto, noto, segoe ui, arial, sans-serif;
	 color: #444;
	 background-color: #e1faf1;
}

a{
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
	 display: grid;
	 grid-template-columns: repeat(auto-fit, minmax(30ch, 1fr));
	 grid-gap: 1.5rem;
	 max-width: 100vw;
	 width: 120ch;
	 padding-left: 1rem;
	 padding-right: 1rem;
}
 
</style>
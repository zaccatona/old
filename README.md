<!doctype html>

<html>

<head>

	<title>Feel the IMPULSE</title>

	<meta charset="utf-8">
	<!-- OCCHIO --><meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="css/style1.css">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<!-- LINK A FONTAWESOME--> <script src="https://kit.fontawesome.com/38721abd6a.js" crossorigin="anonymous"></script>
	
	<!--TITOLI -->
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Francois+One&family=Kanit:ital@1&family=Orbitron&display=swap" rel="stylesheet">
	<!-- TESTI -->
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Kameron&family=Spectral:wght@300&family=Zilla+Slab:wght@300&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200;300&display=swap" rel="stylesheet">

	<!-- LIBRERIE -->
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

	<!-- OCCHIO -->
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css">
  	<script src="https://cdn.jsdelivr.net/npm/jquery@3.6.0/dist/jquery.slim.min.js"></script>
  	<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  	<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js"></script>

  	<meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>

<body>

<header>

<!--SFONDO-->
	<img id="sfondo" src="img/fest1.jpg" alt="Festival">

<!--NAVBAR ALTA-->
  <div class="navbar">
    <div class="d-inline-block">
                <div class="dropdown">
                <button class="btn dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
                  <img id="logo" src="img/energy.png" alt="Logo">
                </button>
                <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                  <li><a class="dropdown-item smooth" href="#goHere">Chi canta?</a></li>
                  <li><a class="dropdown-item smooth" href="#goHere1">Playlist</a></li>
                  <li><a class="dropdown-item smooth" href="#goHere2">Tocca a te!</a></li>
                  <li><a class="dropdown-item smooth" href="#goHere3">Biglietti</a></li>
                  <li><a class="dropdown-item smooth" href="doc.html">Documentazione</a></li>
                </ul>
              </div>
            </div>
    <a href="#" align="center">Home</a>
    <a href="#" align="right"><i class="fa-brands fa-instagram-square"></i></a>
  </div>

<!--LOGO IMPULSE GRANDE-->
	<img id="nome" src="img/imp1.jpeg" alt="IMPULSE">

</header>

<main>

<!--CATCH PHRASE-->
  <div id="p1">
    <h2>Il festival che ti fa battere il cuore</h2>
  </div>

<!--DATE-->
	<div id="date" class="container">
		  	<div class="row">
		    	<div class="col-4"><center><h3>24 giugno 2022</h3></center></div>
		    	<div class="col-4"><center class="bordi"><h3>25 giugno 2022</h3></center></div>
		    	<div class="col-4"><center><h3>26 giugno 2022</h3></center></div>
		 	</div>
	</div>

	<!--ARTISTI BOCCIATI
  <div id="griglia" class="container">
  		<div class="row">
    		<div class="col-4"><center><img class="artist" src="img/cremo.jpg"><p>SHOW MORE</p></center></div>
    		<div class="col-4"><center><img class="artist" src="img/capa.jpg"><p>SHOW MORE</p></center></div>
    		<div class="col-4"><center><img class="artist" src="img/gue.jpeg"><p>SHOW MORE</p></center></div>
  		</div>
  		<div class="row">
    		<div class="col-4"><center><img class="artist" src="img/madame.png"><p>SHOW MORE</p></center></div>
    		<div class="col-4"><center><img class="artist" src="img/mam.jpg"><p>SHOW MORE</p></center></div>
    		<div class="col-4"><center><img class="artist" src="img/marra.jpg"><p>SHOW MORE</p></center></div>
  		</div>
	</div>-->

<!--TITOLO ARTISTI-->
<div id="p2">
  <h2 id="goHere">OSPITI</h2>
  <p>A cantare sono proprio loro!</p>
</div>

<!--ARTISTI -->
<div id="cards" class="container-fluid">
          <div class="row row-cols-1 row-cols-md-4 g-3">
            <div class="col">
              <div class="card1">
                <div class="dropdownIMG">
                  <a href="https://open.spotify.com/artist/396Jr76018oUMR6QBnqT8T"><img class="card-img-top artist" src="img/cremo.jpg" alt="Cremonini"></a>
                    <div class="dropdown-contentIMG">
                      <div class="desc">Non mi sono mai accontentato di essere ???solo??? un cantante: volevo che la musica, negli anni, potesse seguire la mia crescita come persona. La mia ?? una bella storia da raccontare</div>
                    </div>
                </div>
                  <div class="card-body">
                    <h5 class="card-title">Cesare Cremonini</h5>
                    <p class="card-text">24/06/22</p>
                  </div>
              </div>
            </div>
                <div class="col">
                  <div class="card1">
                    <div class="dropdownIMG">
                  <a href="https://open.spotify.com/artist/5AZuEF0feCXMkUCwQiQlW7"><img class="card-img-top artist" src="img/marra.jpg" alt="Marracash"></a>
                    <div class="dropdown-contentIMG">
                      <div class="desc">Per tanto tempo ho dovuto tenere nascoste delle parti di me; poi ho capito che potevo riappropriarmi della mia diversit??. E anche trasformare quel nome ???marocchino??? con cui mi chiamavano con disprezzo e usarlo come un punto di forza</div>
                    </div>
                </div>
                      <div class="card-body">
                        <h5 class="card-title">Marracash</h5>
                        <p class="card-text">24/06/22</p>
                      </div>
                  </div>
                </div>
                  <div class="col">
                    <div class="card1">
                      <div class="dropdownIMG">
                  <a href="https://open.spotify.com/artist/0gzwXezN4IUHAwLufA6YcX"><img class="card-img-top artist" src="img/emma.jpg" alt="EmmaMarrone"></a>
                    <div class="dropdown-contentIMG">
                      <div class="desc">Di paure ne ho tante, ma mi hanno sempre spinta ad andare avanti, addirittura oltre a quello che avevo solo immaginato per la mia vita. Sono fatta cos??, ho bisogno di lanciarmi nel vuoto per sentirmi viva, presente agli altri e a me stessa</div>
                    </div>
                </div>
                        <div class="card-body">
                          <h5 class="card-title">Emma Marrone</h5>
                          <p class="card-text">24/06/22</p>
                        </div>
                    </div>
                  </div>
                    <div class="col">
                      <div class="card1">
                        <div class="dropdownIMG">
                  <a href="https://open.spotify.com/artist/2pjb5ffSoVTr5lRYQXlnPu"><img class="card-img-top artist" src="img/amo.jpg" alt="Alessandra Amoroso"></a>
                    <div class="dropdown-contentIMG">
                      <div class="desc">?? complicato parlare di me. Quel blocco che c????? stato in un certo periodo di tempo e che ha coinvolto il globo, attraverso la musica l???ho superato. Sono riuscita a capire e a volermi raccontare, sia con i brani che ho scritto che con quelli che interpreto</div>
                    </div>
                </div>
                          <div class="card-body">
                            <h5 class="card-title">Alessandra Amoroso</h5>
                            <p class="card-text">24/06/22</p>
                          </div>
                      </div>
                    </div>
                     
          </div>
  <div class="row row-cols-1 row-cols-md-4 g-3">
            <div class="col">
              <div class="card1">
                <div class="dropdownIMG">
                  <a href="ttps://open.spotify.com/artist/2iK8weavvfS2xJCmzNzNE5"><img class="card-img-top artist" src="img/j.jpg" alt="JAX"></a>
                    <div class="dropdown-contentIMG">
                      <div class="desc">Per anni i bulli mi hanno fatto credere di non valere nulla e che la mia anima fosse insignificante finch?? non li ho sconfitti con la musica. Voglio trasmettere ai ragazzi bullizzati perch?? gay o per altri motivi questo messaggio: perseverate e li batterete anche voi. E agli amici di chi viene bullizzato: siate buoni alleati e aiutate i vostri amici. C'?? in gioco la vostra anima</div>
                    </div>
                </div>
                  <div class="card-body">
                    <h5 class="card-title">J-AX</h5>
                    <p class="card-text">24/06/22</p>
                  </div>
              </div>
            </div>
                <div class="col">
                  <div class="card1">
                    <div class="dropdownIMG">
                  <a href="https://open.spotify.com/artist/7GgpsUpkj3olseoaTY7TEY"><img class="card-img-top artist" src="img/elo.jpg" alt="Elodie"></a>
                    <div class="dropdown-contentIMG">
                      <div class="desc">Quello che mi ha insegnato la vita e la musica ?? che non bisogna sempre sentirsi all???altezza delle cose, l???importante ?? avere il coraggio di fare</div>
                    </div>
                </div>
                      <div class="card-body">
                        <h5 class="card-title">Elodie</h5>
                        <p class="card-text">24/06/22</p>
                      </div>
                  </div>
                </div>
                  
                    <div class="col">
                      <div class="card1">
                        <div class="dropdownIMG">
                  <a href="https://open.spotify.com/artist/2ARH58Hit3yC6ziGdhma23"><img class="card-img-top artist" src="img/eli.jpg" alt="Elisa"></a>
                    <div class="dropdown-contentIMG">
                      <div class="desc">Non ho bisogno di nulla, se non di musica, la musica ?? la ragione per cui so che il tempo esiste ancora</div>
                    </div>
                </div>
                          <div class="card-body">
                            <h5 class="card-title">Elisa</h5>
                            <p class="card-text">24/06/22</p>
                          </div>
                      </div>
                    </div>
                      <div class="col">
                        <div class="card1">
                          <div class="dropdownIMG">
                  <a href="https://open.spotify.com/artist/11TplWqOPQBTmg2eiSLt1m"><img class="card-img-top artist" src="img/ferro.jpg" alt="Tiziano Ferro"></a>
                    <div class="dropdown-contentIMG">
                      <div class="desc">La musica mi ha sempre aiutato nei momenti peggiori ed ?? per questo che la musica non si deve fermare. Per riflettere, per stare insieme, per andare avanti, senza nessun timore</div>
                    </div>
                </div>
                            <div class="card-body">
                              <h5 class="card-title">Tiziano Ferro</h5>
                              <p class="card-text">24/06/22</p>
                            </div>
                        </div>
                      </div>
  </div>
  <center><a href="#"><button type="button" class="btn btn-outline-danger"><h5>E TANTI ALTRI...</h5></button></a></center>
</div>

<!--ALBUM-->
<div id="album" class="container-fluid">
  <div class="row">
    <div class="col align-self-start">
      <div class="tit">
        <h2 id="goHere1">ALBUM</h2>
        <h2>IMPULSE</h2>
        <h2>2022</h2>
      </div>
        <a href="https://open.spotify.com/track/12gubLfCjcQlU4XNJK3AKq?si=3527cf63ef964731"><img src="https://images.unsplash.com/photo-1470225620780-dba8ba36b745?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NjB8fGNvbmNlcnR8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60" class="img-fluid" alt="AlbumPreFestival"></a>
    </div>
                
      <div class="col align-self-center">
        <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
          </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <a href="https://open.spotify.com/playlist/4h0sdKKuJ851Cx6WhCrTp1?si=26f5e3570a70418c"><img class="car" src="img/d.jpeg" class="d-block w-100" alt="VitaminaD"></a>
              <div class="carousel-caption d-none d-md-block">
              </div>
          </div>
            <div class="carousel-item">
              <a href="https://open.spotify.com/playlist/01XjUiagri3RYozz21HbSF?si=9dbed1a719294d5a"><img class="car" src="img/zero.jpeg" class="d-block w-100" alt="BrividiSottozero"></a>
                <div class="carousel-caption d-none d-md-block">
                  </div>
            </div>
              <div class="carousel-item">
                <a href="https://open.spotify.com/playlist/63G9jH6rwhf20jRMe9qM8X?si=31ed33705a5641f0"><img class="car" src="img/stelle.jpeg" class="d-block w-100" alt="SottoLeStelle"></a>
                  <div class="carousel-caption d-none d-md-block">
                  </div>
              </div>
        </div>
          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
          </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
      </div>
    </div>

  </div>

<!--SEARCH-->
<div id="titlente">
<h3 id="goHere2">Sei pronto a far sentire la tua voce?</h3>
<h3>Scopri come!</h3>
</div>

<div class="container text-center">
            </div>
            <div id="ready" class="container">
                <div class="row">
                  <div class="col">
                    <p >Crea la tua playlist</p>
                    <div class="input-group mb-3">
                        <span class="input-group-text" id="basic-addon1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                                <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                              </svg>
                        </span>
                        <input type="text" class="form-control" placeholder="..." aria-label="Username" aria-describedby="basic-addon1">
                    </div>
                    <div class="card mb-3 border-light" style="max-width: 540px;">
                        <div class="row g-0">
                          <div class="col-md-4">
                            <img src="https://images.unsplash.com/photo-1509824227185-9c5a01ceba0d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTB8fGNvbmNlcnR8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60" class="img-fluid" alt="...">
                          </div>
                          <div class="col-md-8">
                            <div class="card-body">
                              <h4 class="card-title">-</h4>
                              <h4 class="card-title">-</h4>
                              <h4 class="card-title">-</h4>
                              <h4 class="card-title">-</h4>
                              <h4 class="card-title">-</h4>
                            </div>
                          </div>
                        </div>
                      </div>
                 </div>

                 <div class="col">
                    <p>Vota i tuoi artisti preferiti</p>
                    <div class="input-group mb-3">
                        <span class="input-group-text" id="basic-addon1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                                <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                              </svg>
                        </span>
                        <input type="text" class="form-control" placeholder="..." aria-label="Username" aria-describedby="basic-addon1">
                    </div>
                    <div class="d-flex justify-content-center">
                      <img class="voteImg img-fluid rounded-circle" src="img/eli.jpg" alt="Elisa">
                    </div>
                    <div class="d-flex justify-content-evenly">
                      <img class="voteImg img-fluid rounded-circle" src="img/cremo.jpg" alt="Cesare Cremonini">
                      <img class="voteImg img-fluid rounded-circle" src="img/j.jpg" alt="JAX">
                    </div>
                    </div>

                  <div class="col">
                    <p>Vota la playlist</p>
                    <div class="input-group mb-3">
                        <span class="input-group-text" id="basic-addon1">
                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                                <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                              </svg>
                        </span>
                        <input type="text" class="form-control" placeholder="..." aria-label="Username" aria-describedby="basic-addon1">
                    </div>
                    <div class="d-flex justify-content-evenly">
                      <img src="img/zero.jpeg" class="img-fluid picplay" alt="Playlist Zero">
                      <img src="img/stelle.jpeg" class="img-fluid picplay" alt="Playlist Stelle">
                      <img src="img/d.jpeg" class="img-fluid picplay" alt="Playlist Vitamina">
                    </div>
                  </div>
                </div>
              </div>

 <div id="how">
        <center><h5 id="goHere3">La tua playlist ha il pi?? alto numero di voti?</h5></center>
        <center><h5>Fortunello! Sar?? la playlist di apertura nella prossima data</h5></center>
        <center><h5>e avrai l'onore di conoscere gli artisti e vivere il backstage!</h5></center>
  </div>

<div class="tit" id="ticket"><a href="#"><h3 >Biglietti qui!</h3></a></div>

</main>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>

<footer>
<div id="doc">
  <p class="credit"><a href="doc.html">Documentazione</a></p>
  
  <p class="credit">Creators: <a href="https://www.instagram.com/framaloss/">Francesca Malossi</a> e <a href="https://www.instagram.com/zaccatona/">Zaccaria Tona</a> </p>
  <p class="credit">Via dei Pesci Gialli 48, JJ, 65290</p>
  <p class="credit">Copyright 2022</p>
</div>
</footer>

</body>

</html>

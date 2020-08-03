<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="shortcut icon" type="image x-icon"  href="LOGOOFC.jpg">
    <title>RcDesigner</title>
</head>
<body>

</body>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="shortcut icon" type="image x-icon"  href="Menuzin.png">
<style>
    body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

    body, html {
        height: 100%;

        line-height: 1.8;
    }

    /* Full height image header */
    .bgimg-1 {
        background-position: center;
        background-size: cover;
        background-image: url("BACKGROUNDPSITE.jpg");
        min-height: 100%;
    }

    .w3-bar .w3-button {
        padding: 16px;
    }
</style>
<body>


<!-- Navbar (sit on top) -->
<div class="w3-top">
    <div class="w3-bar w3-white w3-card" id="myNavbar">
         <a href="#home" class="w3-bar-item w3-button w3-wide">RcDesigners</a>
        <!-- Right-sided navbar links -->
        <div class="w3-right  w3-hide-small">
            <a href="#about" class="w3-bar-item w3-button">Sobre</a>
            <a href="#team" class="w3-bar-item w3-button"><i class="fa fa-user"></i>Equipe</a>
            <a href="#work" class="w3-bar-item w3-button"><i class="fa fa-th"></i>Trabalho</a>
            <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-usd"></i>Precos</a>
            <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i>Contato</a>
        </div>
        <!-- Hide right-floated links on small screens and replace them with a menu icon -->

        <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
            <i class="fa fa-bars"></i>
        </a>
    </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
    <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
    <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">Sobre</a>
    <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">Equipe</a>
    <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">Trabalhos</a>
    <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">Precos</a>
    <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">Contato</a>
</nav>

<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
    <div class="w3-display-left w3-text-white" style="padding:48px"
        <span class="w3-jumbo   w3-hide-small"></span><br>
    <span class="w3-jumbo w3-hide-small"></span><br>
        <span class="w3-xxlarge w3-hide-large w3-hide-medium"</span><br>
        <span class="w3-large">Algo Que Voce Queiram.</span>
        <p><a href="#about" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">Learn more and start today</a></p>
    </div>
    <div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
        <i class="fa fa-facebook-official w3-hover-opacity"></i>
        <i class="fa fa-instagram w3-hover-opacity"></i>
        <i class="fa fa-snapchat w3-hover-opacity"></i>
        <i class="fa fa-pinterest-p w3-hover-opacity"></i>
        <i class="fa fa-twitter w3-hover-opacity"></i>
        <i class="fa fa-linkedin w3-hover-opacity"></i>
    </div>
</header>

<!-- About Section -->
<div class="w3-container" style="padding:128px 16px" id="about">
    <h3 class="w3-center">Sobre A Empresa</h3>
    <p class="w3-center w3-large">Principais recursos da nossa empresa</p>
    <div class="w3-row-padding w3-center" style="margin-top:64px">
        <div class="w3-quarter">
            <i class="fa fa-desktop w3-margin-bottom w3-jumbo w3-center"></i>
            <p class="w3-large">Responsabilidaes</p>
            <p>Palavras Sabias</p>
        </div>
        <div class="w3-quarter">
            <i class="fa fa-heart w3-margin-bottom w3-jumbo"></i>
            <p class="w3-large">Exemplo</p>
            <p>Palavras Sabias</p>
        </div>
        <div class="w3-quarter">
            <i class="fa fa-diamond w3-margin-bottom w3-jumbo"></i>
            <p class="w3-large">Exemplo</p>
            <p>Palavras Sabias</p>
        </div>
        <div class="w3-quarter">
            <i class="fa fa-cog w3-margin-bottom w3-jumbo"></i>
            <p class="w3-large">Exemplo</p>
            <p>Palavras Sabias</p>
        </div>
    </div>
</div>

<!-- Promo Section - "We know design" -->
<div class="w3-container w3-light-grey" style="padding:128px 16px">
    <div class="w3-row-padding">
        <div class="w3-col m6">
            <h3>Nossos Trabalhos</h3>
            <p>Falar Sobre Um Pouco</p>
            <p><a href="#work" class="w3-button w3-black"><i class="fa fa-th"> </i>Ver Nossos Trabalhos</a></p>
        </div>
        <div class="w3-col m6">
            <img class="w3-image w3-round-large" src="" alt="Imagens" width="700" height="394">
        </div>
    </div>
</div>

<!-- Team Section -->
<div class="w3-container" style="padding:128px 16px" id="team">
    <h3 class="w3-center">A Equipe</h3>
    <p class="w3-center w3-large">Escrever</p>
    <div class="w3-row-padding w3-grayscale" style="margin-top:64px">
        <div class="w3-col l3 m6 w3-margin-bottom">
            <div class="w3-card">
                <img src="/w3images/team2.jpg" alt="" style="width:100%">
                <div class="w3-container">
                    <h3></h3>
                    <p class="w3-opacity">Diretor Executivo</p>
                    <p>Biografia</p>
                    <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i>Contato</button></p>
                </div>
            </div>
        </div>
        <div class="w3-col l3 m6 w3-margin-bottom">
            <div class="w3-card">
                <img src="/w3images/team1.jpg" alt="" style="width:100%">
                <div class="w3-container">
                    <h3></h3>
                    <p class="w3-opacity"><D>Designer</D></p>
                    <p>Bio</p>
                    <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i>Contato</button></p>
                </div>
            </div>
        </div>
        <div class="w3-col l3 m6 w3-margin-bottom">
            <div class="w3-card">
                <img src="/w3images/team3.jpg" alt="" style="width:100%">
                <div class="w3-container">
                    <h3></h3>
                    <p class="w3-opacity">Web Designer</p>
                    <p></p>
                    <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contact</button></p>
                </div>
            </div>
        </div>
        <div class="w3-col l3 m6 w3-margin-bottom">
            <div class="w3-card">
                <img src="/w3images/team4.jpg" alt="" style="width:100%">
                <div class="w3-container">
                    <h3></h3>
                    <p class="w3-opacity">Designer</p>
                    <p>Bio</p>
                    <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contact</button></p>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Promo Section "Statistics" -->
<div class="w3-container w3-row w3-center w3-dark-grey w3-padding-64">
    <div class="w3-quarter">
        <span class="w3-xxlarge">14+</span>
        <br>Parceiros
    </div>
    <div class="w3-quarter">
        <span class="w3-xxlarge">55+</span>
        <br>Projetos Finalizados
    </div>
    <div class="w3-quarter">
        <span class="w3-xxlarge">89+</span>
        <br>Clientes Satisfeitos
    </div>
    <div class="w3-quarter">
        <span class="w3-xxlarge">150+</span>
        <br>Conhecimentos
    </div>
</div>

<!-- Work Section -->
<div class="w3-container" style="padding:128px 16px" id="work">
    <h3 class="w3-center">Nossos Trabalhos</h3>
    <p class="w3-center w3-large">Portfolio</p>

    <div class="w3-row-padding" style="margin-top:64px">
        <div class="w3-col l3 m6">
            <img src="CARDAPIOPRONTOJPEG.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Cardapio">
        </div>
        <div class="w3-col l3 m6">
            <img src="CARTAOADVOGADOFRENTEPRONTOJPEG.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Cartao Advogado">
        </div>
        <div class="w3-col l3 m6">
            <img src="CARTAODOCEFRENTEPRONTOJPEG.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Cartao De Doce">
        </div>
        <div class="w3-col l3 m6">
            <img src="CARTAOUNHAPRONTOJPEG.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Cartao de Unha"
    </div>

    <div class="w3-row-padding w3-section">
        <div class="w3-col l3 m6">
            <img src="CARTAOCHADEBEBEPRONTOJPEG.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Cha De Bebe">
        </div>
        <div class="w3-col l3 m6">
            <img src="CARTAOLINGERIEPRONTOJPEG.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Langerie">
        </div>
        <div class="w3-col l3 m6">
            <img src="CARTAOSALAODEBELEZAPRONTOJPEG.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Salao De Beleza">
        </div>
        <div class="w3-col l3 m6">
            <img src="CARTAOTRAILERRUAPRONTOJPEG.jpg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Trailer">
        </div>
    </div>
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
    <span class="w3-button w3-xxlarge w3-black w3-padding-large w3-display-topright" title="Close Modal Image">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
        <img id="img01" class="w3-image">
        <p id="caption" class="w3-opacity w3-large"></p>
    </div>
</div>

<!-- Skills Section -->
<div class="w3-container w3-light-grey w3-padding-64">
    <div class="w3-row-padding">
        <div class="w3-col m6">
            <h3>Nossas Habilidades</h3>
            <p>Escrever No Que Sao Bons<br>

            </p>
            <p>           <br>
                </p>
        </div>
        <div class="w3-col m6">
            <p class="w3-wide"><i class="fa fa-camera w3-margin-right"></i>Oque</p>
            <div class="w3-grey">
                <div class="w3-container w3-dark-grey w3-center" style="width:90%">Porcetagem</div>
            </div>
            <p class="w3-wide"><i class="fa fa-desktop w3-margin-right"></i>Oque</p>
            <div class="w3-grey">
                <div class="w3-container w3-dark-grey w3-center" style="width:85%">Porcentagem</div>
            </div>
            <p class="w3-wide"><i class="fa fa-photo w3-margin-right"></i>Oque</p>
            <div class="w3-grey">
                <div class="w3-container w3-dark-grey w3-center" style="width:75%">Porcentagem</div>
            </div>
        </div>
    </div>
</div>

<!-- Pricing Section -->
<div class="w3-container w3-center w3-dark-grey" style="padding:128px 16px" id="Precos">
    <h3>Pacotes</h3>
    <p class="w3-large">Escolha De Acordo Com Seus Bolso</p>
    <div class="w3-row-padding" style="margin-top:64px">
        <div class="w3-third w3-section">
            <ul class="w3-ul w3-white w3-hover-shadow">
                <li class="w3-black w3-xlarge w3-padding-32">Pacote Basico</li>
                <li class="w3-padding-16"><b>Algo</b> Algo</li>
                <li class="w3-padding-16"><b>Algo</b> Algo</li>
                <li class="w3-padding-16"><b>Algo</b> Algo</li>
                <li class="w3-padding-16"><b>Algo</b> Algo</li>
                <li class="w3-padding-16">
                    <h2 class="w3-wide">$Preco</h2>
                    <span class="w3-opacity"></span>
                </li>
                <li class="w3-light-grey w3-padding-24">
                    <button class="w3-button w3-black w3-padding-large">Comprar</button>
                </li>
            </ul>
        </div>
        <div class="w3-third">
            <ul class="w3-ul w3-white w3-hover-shadow">
                <li class="w3-red w3-xlarge w3-padding-48">Pacote Pro</li>
                <li class="w3-padding-16"><b>Algo</b> Algo</li>
                <li class="w3-padding-16"><b>Algo</b> Algo</li>
                <li class="w3-padding-16"><b>Algo</b> Algo</li>
                <li class="w3-padding-16"><b>Algo</b> Algo</li>
                <li class="w3-padding-16">
                    <h2 class="w3-wide">$Preco</h2>
                    <span class="w3-opacity"></span>
                </li>
                <li class="w3-light-grey w3-padding-24">
                    <button class="w3-button w3-black w3-padding-large">Comprar</button>
                </li>
            </ul>
        </div>
        <div class="w3-third w3-section">
            <ul class="w3-ul w3-white w3-hover-shadow">
                <li class="w3-black w3-xlarge w3-padding-32">Pacote Premium</li>
                <li class="w3-padding-16"><b>Algo</b>Algo </li>
                <li class="w3-padding-16"><b>Algo</b>Algo</li>
                <li class="w3-padding-16"><b>Algo</b>Algo</li>
                <li class="w3-padding-16">
                    <h2 class="w3-wide">$Preco</h2>
                    <span class="w3-opacity"></span>
                </li>
                <li class="w3-light-grey w3-padding-24">
                    <button class="w3-button w3-black w3-padding-large">Comprar</button>
                </li>
            </ul>
        </div>
    </div>
</div>

<!-- Contact Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
    <h3 class="w3-center">Contato</h3>
    <p class="w3-center w3-large">Envie-nos uma mensagem</p>
    <div style="margin-top:48px">
        <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> Sao Paulo</p>
        <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> Telefones: Tio e Tia</p>
        <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> Email Da Empresa</p>
        <br>
        <form action="/action_page.php" target="_blank">
            <p><input class="w3-input w3-border" type="text" placeholder="Nome" required name="Nome"></p>
            <p><input class="w3-input w3-border" type="text" placeholder="Email" required name="Email"></p>
            <p><input class="w3-input w3-border" type="text" placeholder="Sujeito" required name="Subject"></p>
            <p><input class="w3-input w3-border" type="text" placeholder="Mensagem" required name="Mensagem"></p>
            <p>
                <button class="w3-button w3-black" type="submit">
                    <i class="fa fa-paper-plane"></i> Enviar Mensagem
                </button>
            </p>
        </form>
        <!-- Image of location/map -->
        <img src="/w3images/map.jpg" class="w3-image w3-greyscale" style="width:100%;margin-top:48px">
    </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64">
    <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>Voltar Para Cima</a>
    <div class="w3-xlarge w3-section">
        <i class= "fa fa-facebook-official w3-hover-opacity"></i>
        <i class="fa fa-instagram w3-hover-opacity"></i>
        <i class="fa fa-snapchat w3-hover-opacity"></i>
        <i class="fa fa-pinterest-p w3-hover-opacity"></i>
        <i class="fa fa-twitter w3-hover-opacity"></i>
        <i class="fa fa-linkedin w3-hover-opacity"></i>
    </div>
    <p>Feito Por <a href="https://www.facebook.com/RC-Designer-110576740741726" title="RcDesigner" target="_blank" class="w3-hover-text-green">RcDesigners</a></p>
</footer>

<script>
    // Modal Image Gallery
    function onClick(element) {
        document.getElementById("img01").src = element.src;
        document.getElementById("modal01").style.display = "block";
        var captionText = document.getElementById("caption");
        captionText.innerHTML = element.alt;
    }


    // Toggle between showing and hiding the sidebar when clicking the menu icon
    var mySidebar = document.getElementById("mySidebar");

    function w3_open() {
        if (mySidebar.style.display === 'block') {
            mySidebar.style.display = 'none';
        } else {
            mySidebar.style.display = 'block';
        }
    }

    // Close the sidebar with the close button
    function w3_close() {
        mySidebar.style.display = "none";
    }
</script>

</body>

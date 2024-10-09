<!DOCTYPE html>
<!-- Määrittää dokumentin tyypin HTML5:ksi -->
<html lang="en">
<head>
    <!-- Määrittää merkistökoodauksen UTF-8:ksi -->
    <meta charset="UTF-8">
    <!-- Asettaa näkymäportin asetukset, jotta sivu skaalautuu oikein eri laitteilla -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Määrittää sivun otsikon, joka näkyy selaimen välilehdessä -->
    <title>12 miles below</title>
    <!-- Linkittää ulkoisen CSS-tyylitiedoston -->
    <link rel="stylesheet" href="12milebelow.css">
    <!-- Linkittää ulkoisen Font Awesome -kirjaston ikonien käyttöä varten -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <!-- Sivun yläosa, joka sisältää navigointivalikon -->
    <header id="etusivu">
        <nav>
            <!-- Linkki Amazon-sivulle, jossa on kirjan kuva ja teksti "uusin kirja" -->
            <a href="https://www.amazon.com/12-Miles-Below-IV-Progression-ebook/dp/B0CRLGGF77?ref_=ast_author_dp&dib=eyJ2IjoiMSJ9.uKp1yPF_37HsEIuDXEMlZNnms7QCWHN4-iKA8GeCYDmMiBdagTIDeXZAR9KXmk6Q.UdYHQK9VCAt2wNqlNRdjNpC6JgQE7GFUHeGGQTt9rIk&dib_tag=AUTHOR" target="_blank"><i class="fa-solid fa-moon"></i></a>
            <p>uusin kirja</p>
            <!-- Linkki README.md-tiedostoon, jossa on ikoni ja teksti "etusivu" -->
            <a href="README.md" target="_blank"><i class="fa-solid fa-moon"></i></a>
            <p>etusivu</p>
            <!-- Linkki yhteystiedot-sivulle, jossa on ikoni ja teksti "yhteistiedot" -->
            <a href="yhteistiedot.html" target="_blank"><i class="fa-solid fa-moon"></i></a>
            <p>yhteistiedot</p>
        </nav>
    </header>
    <section class="grid-container" id="paasivu">
        <div class="grid-teksti1">
           <!-- Otsikko ja kappale, joka kuvaa tarinan taustaa -->
           <h2>12 miles below</h2>
              <p>Aarimmaiset pakkaset tukahduttavat maan pinnan. Muinaisten aikojen jaatyneet rakenteet ulottuvat laajojen jaatikoiden halki. Selviytyjat vartioivat tarkoin kaikkea teknologiaa, joka loydetaan naiden rakenteiden sisalta.
 Ainoa pakotie tappavasta ilmastosta on pinnan alla, mutta se ei tarkoita, etta siella olisi turvallista...
                Hirviomaiset koneet piileskelevat syvyyksissa. Mielipuoliset puolijumalat kayvat sotaa niita vastaan, kuollen yha uudelleen, kohdellen kaikkea kuin leikkia. </p>
           <!-- Kuvan sisaltava elementti -->
           <figure>
              <img class="kuva" src="images/icy_wasteland.jpg" alt="waste land">
           </figure>
           <!-- Otsikko ja kappale, joka kuvaa maailman rakennetta -->
           <h3>Maailma</h3>
              <p>12 miles below maailma jakaantuu 13 tasoon. Maan pinta ja maan alla olevat kerrokset. Maailma on apokalyptinen eika mistaan loyda rauhaa. Maan pinnalla ymparisto pyrkii tappamaan kaiken elavan ja maan alla tasta vastaa koneet, joita hallinnoi rogue tekoaly.</p>
           <!-- Kuvan sisaltava elementti? -->
           <figure>
              <img class="kuva" src="images/bunker.jpg" alt="toinen kuva">
           </figure>
           <!-- Otsikko ja kappale, joka mainostaa kirjailijan uusia kirjoja -->
           <h3>Mainonta</h3>
              <p>Mene lukemaan kirjailijan uusia <a href="https://www.amazon.com/12-Miles-Below-IV-Progression-ebook/dp/B0CRLGGF77?ref_=ast_author_dp">kirjoja</a> </p>
           <!-- Kuvan sisaltava elementti? -->
           <figure>
              <img class="kuva" src="images/bunker2.jpg" alt="kolmas kuva">
           </figure>
        </div>
    </section>
    <!--footer tee oma css. ei tarvii kun eri class -->
    <footer>
        <div class="footterContainer">
            <div class="iconit">
                <!-- Linkit sosiaalisen median sivuille, joissa on ikonit -->
                <a href="https://www.facebook.com/?locale=fi_FI"><i class="fa-brands fa-facebook"></i></a>
                <a href="https://www.instagram.com/"><i class="fa-brands fa-instagram"></i></a>
                <a href="https://www.youtube.com/"><i class="fa-brands fa-youtube"></i></a>
            </div>
        </div>
        <div class="Copyright">
            <!-- lisää tekijanoikeustiedot -->
            <p>Copyright &copy;2024; Designed by Valtteri</p>
        </div>
        <div>
            
            <p><a href="mailto:valtteri.lassas@gmail.com">valtteri.lassas@gmail.com</a></p>
        </div>
    </footer>
</body>
</html>
---
layout: wrapper
headline: " "
subtitle: " "
---
<section id="bannerimage">
</section>
<section class="background-black" id ="about">
  <div class="container new-content-block">
    <div class="row justify-content-center">
      <h3> Über mich </h3>
    </div>
    <div class="row vcenter">
      <div class="col-8 col-md-5 col-lg-4 offset-2 offset-md-0 offset-lg-1 image-container-center justify-content-center">
        <img class="mx-auto d-block personal-image" src="{{ site.baseurl }}/assets/images/startseite_neu.jpeg" alt="Foto Siegfried Klock">
      </div>
      <div class="col-8 col-md-7 col-lg-6 offset-2 offset-md-0">
        <p>
          Mein Name ist Siegfried Klock und ich komme aus Ostrhauderfehn. Schon in jungen Jahren habe ich mich gerne mit Ostfriesland, der Geschichte unserer Heimat und Ahnenforschung beschäftigt. So erlernte ich auch einen traditionellen friesischen Beruf. Als Industrieschiffbauer verbrachte ich Lehre und einige Jahre als Facharbeiter auf der Jansen Werft in Leer. Nach dem Konkurs musste ich mich umorientieren und arbeite seit 1989 bis heute im Volkswagenwerk in Emden.
          Meine Leidenschaft zum Friesischen, zur Plattdeutschen Sprache und zum Texten von Liedern und Gedichten in Hoch und Plattdeutsch, begleiten mich nun fast mein ganzes Leben.<br><br>
          Nachdem ich viele Jahre Liedertexte für Interpreten aus der Region und darüber hinaus geschrieben habe, gründete ich 2010 die Facebook Gruppe
          "Wi sünd Oostfreesen un dat mit Stolt" und 2018 die regionale Koch und Backgruppe" Leckerst un best van stolt Oostfreesen".
          Beide Gruppen erfreuen sich einer steigenden Beliebtheit und so durften wir gemeinsam mit den Gruppen 2018 eine alte Tradition wieder aufleben. Zusätzlich gibt es die offizielle Seite der stolzen Ostfriesen, die ich alleine betreue, und einen kleinen Shop mit Logoartikeln, den mein Sohn betreibt.<br><br>
        </p>
      </div>
    </div>
    <div class="row vcenter justify-content-center">
      <div class="col-8">
        <p>
          Mit der Firma Cloer Elektrogeräte aus Arnsberg wurde nach vielen Jahrzehnten, ohne,  wieder ein Neujahrskucheneisen mit Ostfriesland Wappen entwickelt und von Cloer produziert. Das ist bis dato auch das erste Gerät mit einer plattdeutschen Gebrauchsanweisung, die ich übersetzen durfte.
          Ein Jahr später entstand eine Neujahrskuchentrommel mit Ostfriesland Wappen und den ostfriesischen Farben. Ebenfalls ein Rezeptbuch mit Rezepten von Gruppenmitgliedern der Facebook Gruppen wurde 2019 erstellt und gedruckt.<br><br>
          Inspiriert von einigen Autoren der Facebookgruppen, schrieb ich dann 2019 meinen ersten Ostfriesland Krimi und 2021 meinen ersten Gedichteband.
          Aktuell schreibe ich an der Fortsetzung meines ersten Ostfriesland Krimis und plane einen weiteren Gedichteband.
          Heimatliebe ist eine ganz besondere Liebe, eine bleibende und ewige Verbindung. Sie lässt sich durch nichts erschüttern und ist Antrieb und Motor meiner Leidenschaft.<br><br>
          Auf den folgenden Seiten stelle ich euch meine Bücher, ein paar Bilder und Gedichte vor. Ich freue mich auf euer Feedback, dass Ihr mir gerne per Mail senden dürft.
        </p>
      </div>
    </div>
    
  </div>
</section>



<section class="background-red" id ="groups">
  <div class="container new-content-block">
    <div class="row justify-content-center pb-5">
      <h3> Ostfriesland in den sozialen Medien </h3>
    </div>
    <div class="row">
      <div class="col-12 col-lg-10 offset-lg-1">
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
          </ol>
          <div class="carousel-inner">
            {% assign ordered_social_media = site.social_media | sort:"position" %}
            {% for sm in ordered_social_media %}
              {% if sm.position == 1 %}
              <div class="carousel-item active">
              {% else %}
              <div class="carousel-item">
              {% endif %}
                <div class="row vcenter text-center">
                  <div class="col-lg-12 col-xl-5 carousel-container">
                    <div class="container-md mb-3">
                      <img class="sm-image img-responsive center-block" src="{{ site.baseurl }}/assets/images/{{ sm.image }}" alt="{{ sm.title }}">
                    </div>
                  </div>
                  <div class="col-lg-12 col-xl-7">
                    <div class="text-container">
                      <h4>  {{ sm.title }} 
                      </h4>
                    <div class="pb-2">
                      <a href="{{ sm.link }}"> {{ sm.fa-icon}} </a>
                    </div>
                    </div>
                    <div class="container-md standard-text">
                      {{ sm.description}}
                    </div>
                  </div>
                </div>
              </div>
            {% endfor %}
          </div>
          <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="background-blue" id ="author">
  <div class="container new-content-block">
    <div class="row d-flex justify-content-center pb-3">
      <div class="col-12 col-md-10 col-lg-8">
        <h3 class="mb-4"> Ostfriesland in Schrift und Bild </h3>
        <!-- <p class="text-center">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque diam neque, suscipit sit amet accumsan non, tempus nec dui. Mauris metus est, tempor sed sem sed, posuere dictum arcu. Praesent cursus eros quis placerat facilisis. Phasellus lobortis eget libero nec aliquet. Fusce dolor ex, rutrum eu diam a, venenatis rhoncus purus. Maecenas pretium orci id dolor dignissim, nec imperdiet libero ultricies. Nullam ornare iaculis cursus. Duis in tortor porta odio hendrerit tristique. Donec non arcu magna. Duis ac scelerisque mi, at malesuada diam. Nam tempus efficitur tellus sit amet bibendum.
        </p> -->
      </div>
    </div>
    <div class="row d-flex justify-content-center">
      <div class="col-sm-12 col-md-4 col-lg-3 align-middle justify-content-center mb-4">
        <div class="hover-image" style="cursor: pointer;" onclick="window.location='{{ site.baseurl }}/books';">  
          <h4 class="row justify-content-center">
            Bücher
          </h4>
          <img class="mx-auto d-block personal-image" src="{{ site.baseurl }}/assets/images/buecher.jpg" alt="Foto Siegfried Klock">
        </div>
      </div>
      <div class="col-sm-12 col-md-4 col-lg-3 align-middle justify-content-center mb-4">
        <div class="hover-image" style="cursor: pointer;" onclick="window.location='{{ site.baseurl }}/poems';"> 
          <h4 class="row justify-content-center">
            Gedichte
          </h4>
          <img class="mx-auto d-block personal-image" src="{{ site.baseurl }}/assets/images/siegfried_klock.jpg" alt="Foto Siegfried Klock">
        </div>
      </div>
      <div class="col-sm-12 col-md-4 col-lg-3 align-middle justify-content-center mb-4">
        <div class="hover-image" style="cursor: pointer;" onclick="window.location='{{ site.baseurl }}/gallery';"> 
          <h4 class="row justify-content-center">
            Fotographie
          </h4>
          <img class="mx-auto d-block personal-image" src="{{ site.baseurl }}/assets/images/title_image_fotographie.jpg" alt="Foto Siegfried Klock">
        </div>
      </div>
    </div>
  </div>
</section>



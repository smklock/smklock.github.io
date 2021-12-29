---
layout: wrapper
headline: " "
subtitle: " "
permalink: /2394a9661a9089208c1c9c65ccac85a91da6a859/books
---




<section class="background-black" id ="about">
  <div class="container new-content-block">
    <div class="row justify-content-center">
      <h3> Bücher </h3>
    </div>
    {% for book in site.books %}
    <hr>
    <div class="row vcenter">
      <div class="col-8 col-md-5 col-lg-4 offset-2 offset-md-0 offset-lg-1 image-container-center justify-content-center">
        <img class="mx-auto d-block personal-image" src="{{ site.baseurl }}/{{site.hash}}/assets/images/{{ book.image }}" alt="Foto {{ book.title }}">
      </div>
      <div class="col-8 col-md-7 col-lg-6 offset-2 offset-md-0">
        <h4> {{ book.title }} </h4>
        <h5> {{ book.subtitle }} </h5>
        <p>
          {{ book.content }}
        </p>
        <p class="text-center">
        <a href="{{ book.link }}"> Shop </a>
        </p>
      </div>
    </div>
    {% endfor %}
  </div>
</section>



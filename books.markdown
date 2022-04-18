---
layout: wrapper
headline: " "
subtitle: " "
permalink: /books
---




<section class="background-black" id ="about">
  <div class="container new-content-block">
    <div class="row justify-content-center">
      <h3> Bücher </h3>
    </div>
    {% assign ordered_books = site.books | sort:"position" %}
    {% for book in ordered_books %}
    <hr>
    <div class="row vcenter">
      <div class="col-8 col-md-5 col-lg-4 offset-2 offset-md-0 offset-lg-1 image-container-center justify-content-center">
        <img class="mx-auto d-block personal-image" src="{{ site.baseurl }}/assets/images/{{ book.image }}" alt="Foto {{ book.title }}">
      </div>
      <div class="col-8 col-md-7 col-lg-6 offset-2 offset-md-0">
        <h4> {{ book.title }} </h4>
        <h5> {{ book.subtitle }} </h5>
        <p>
          {{ book.content }}
        </p>
        {% if book.link %}
          <p class="text-center">
          <a href="{{ book.link }}"> Shop </a>
          </p>
        {% endif %}
      </div>
    </div>
    {% endfor %}
  </div>
</section>



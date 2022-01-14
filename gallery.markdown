---
layout: wrapper
headline: " "
subtitle: " "
permalink: /gallery
---




<section class="background-blue" id ="gallery">
  <div class="container new-content-block">
    <div class="row justify-content-center">
      <h3> Ostfriesische Gallerie </h3>
    </div>
    <div class="row">
      <div class="col-12">
        <div class="row vcenter justify-content-center">
        {% for image in site.categories.images reversed %}
        <div class="col-12 col-md-6 col-lg-4">
          <div class="image-container-center">
            <img class="mx-auto d-block" src="{{ site.baseurl }}/assets/gallery/{{ image.name }}" width="300">
          </div>
          <div class="image-description text-center">
            {{ image.content }}
          </div>
        </div>
        {% endfor %}
        </div>
      </div>
    </div>
  </div>
</section>



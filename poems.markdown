---
layout: wrapper
headline: " "
subtitle: " "
permalink: /poems
---




<section class="background-red" id ="about">
  <div class="container new-content-block">
    <div class="row justify-content-center">
      <h3> Gedichte </h3>
    </div>
    {% for poem in site.categories.poems %}
    <hr>
    <div class="row justify-content-center">
      <div class="col-md-auto">
        <h4> {{ poem.title }} </h4>
        <p> <i> am {{ poem.date | date: "%d.%m.%Y" }} veröffentlicht. </i> </p>
      </div>
    </div>
    <div class="row justify-content-center">
        <div class="col-md-auto">
            {{ poem.excerpt }}
        </div>
    </div>
    <div class="row justify-content-center">
        <div class="text-right col-md-auto">
            <a href="{{ poem.url }}"><strong>Ganzes Gedicht lesen </strong></a>
        </div>
    </div>    
    {% endfor %}
  </div>
</section>



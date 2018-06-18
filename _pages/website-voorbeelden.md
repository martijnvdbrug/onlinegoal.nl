---
layout: page
permalink: /website-voorbeelden/
---

<h1 class="page-title">Website voorbeelden</h1>
  <div class="section">

    <br>
    <br>

    <div class="slider">

      <ul class="slides">

        {% for example in site.data.website_examples %}
        <li>
          <img src="{{ example.img }}"> <!-- random image -->
          <div class="caption left-align">
            <div class="row">
              <div class="col s12 m6">
                <div class="card grey lighten-5">
                  <div class="card-content">
                    <span class="card-title black-text"> {{ example.title }} </span>
                    <p class="black-text"> {{ example.text }} </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </li>
        {% endfor %}

      </ul>

    </div>
  </div>

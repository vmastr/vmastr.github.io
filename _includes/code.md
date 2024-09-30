<h2 id="code" style="margin: 2px 0px -15px;">Code</h2>

<div class="publications">
  <ol class="bibliography">

    {% for item in site.data.code %}

    <div class="pub-row">
      <div class="col-sm-3 abbr" style="position: relative;padding-right: 0px;padding-left: 0px;">
        {% if item.example_image %} 
        <img src="{{ item.example_image }}" class="teaser img-fluid z-depth-1" style="width=100%; height=auto;">
        {% endif %}
      </div>
      
      <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 0px;">
          <div class="title">
            <a href="{{ item.url }}">{{ item.title }}</a>
          </div>
          <div class="description">{{ item.description }}</div>
          <div class="features">
            <ul>
              {% for feature in item.features %}
              <li>{{ feature }}</li>
              {% endfor %}
            </ul>
          </div>

        <div class="links">
          {% if item.url %} 
          <a href="{{ item.url }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">GitHub</a>
          {% endif %}
        </div>
      </div>
    </div>

    <!-- <br> -->
    <div class="small-gap"></div> <!-- Use this div for a smaller gap -->
    
    {% endfor %}

  </ol>
</div>

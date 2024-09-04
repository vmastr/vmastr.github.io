<h2 id="talks" style="margin: 2px 0px -15px;">Invited Talks</h2>

<div class="publications">
  <ol class="bibliography">

    {% for talk in site.data.talks.main %}
    <div class="talk-row" style="margin-bottom: 10px;"> <!-- Added margin-bottom for spacing -->
      <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 0px;">
        <div class="title">
          <em>{{ talk.title }}</em>, at 
          <a href="{{ talk.link }}" target="_blank">{{ talk.conference }}</a>, 
          {{ talk.location}}
          {{ talk.date }}.
        </div>
      </div>
    </div>
    {% endfor %}

  </ol>
</div>

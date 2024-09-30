<h2 id="conference_talks" style="margin: 2px 0px -15px;">Invited Conference Talks</h2>

<div class="publications">
  <ol class="bibliography">

    {% for talk in site.data.conference_talks.main %}
    <div class="talk-row" style="margin-bottom: 10px;"> <!-- Added margin-bottom for spacing -->
      <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 0px;">
        <div class="title">
          <a href="{{ talk.link }}" target="_blank">{{ talk.conference }}</a>, 
          {{ talk.location}} 
          {{ talk.date }}.
        </div>
      </div>
    </div>
    {% endfor %}

  </ol>
</div>

---
layout: single
title: "Invited talks and workshops"
permalink: /talks/
---

<h2>Talk locations</h2>

<div class="full">
  <iframe
    src="{{ site.baseurl }}/talkmap/map.html"
    style="width:100%; height:600px; border:none;">
  </iframe>
</div>


<h2>Invited talks and workshops</h2>

{% for talk in site.data.talks.list_talks %}
**{{ talk.title }}**  
{{ talk.authors }} 
*{{ talk.venue }}* 
*{{ talk.dates }}*  
*{{ talk.location }}*
{% endfor %}

---
layout: single
title: "Invited talks and workshops"
permalink: /talks/
---
<h3>DEBUG: site.data</h3>
<pre>{{ site.data | jsonify }}</pre>


<h2>Talk locations</h2>

  <iframe
    src="{{ site.baseurl }}/talkmap/map.html"
    style="width:100%; height:600px; border:none;">
  </iframe>


<h2>Full list</h2>

{% for talk in site.data.list_talks %}
 <p>
    <strong>{{ talk.title }}</strong><br>
    {{ talk.authors }}<br>
    {{ talk.venue }}<br>
    {{ talk.dates }}<br>
    {{ talk.location }}
  </p>
{% endfor %}


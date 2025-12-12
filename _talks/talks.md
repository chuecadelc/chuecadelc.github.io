---
layout: single
title: "Invited talks and workshops"
permalink: /talks/
---
{% for talk in site.talks.list_talks %}
**{{ talk.title }}**  
{{ talk.authors }} 
*{{ talk.venue }}* 
*{{ talk.dates }}*  
*{{ talk.location }}*
{% endfor %}

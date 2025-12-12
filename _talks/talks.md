---
layout: single
title: "Invited talks and workshops"
permalink: /talks/
---

# Invited talks and workshops

{% for talk in site.talks.list_talks %}
**{{ talk.title }}**  
{{ talk.authors }} 
*{{ talk.venue }}* 
*{{ talk.dates }}*  
*{{ talk.location }}*
{% endfor %}

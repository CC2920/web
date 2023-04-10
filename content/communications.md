---
layout: communications
title:  "Communications"  
subheadline: 'Communiqué'
breadcrumb: true
permalink: "/communications/"
---

{% comment %} 
*
*     Cette page regroupe toutes les sous-pages du répertoire _communications
* 
*     Le code ci-dessous utilise le titre de chaque page pour assigner le contenu aux variables pour 
*     ensuite concaténer les variables en ordre, commençant avec les Messages de la semaine
*
{% endcomment %}

{% assign comms = site.communications  %}
{% for comm in comms %}

    {% case comm.title %}

    {% when "Messages de la semaine" %}
        {% assign msg = comm %}

    {% when "Information Générale" %}
        {% assign info = comm %}

    {% when "Bulletin d'information" %}
        {% assign bulletin = comm %}

    {% when "Calendrier" %}
        {% assign calendrier = comm %}

    {% endcase %}
{% endfor %} 


<!-- Message de la semaine -->
# {{ msg.title }}
{{ msg.content }}

{% if msg.activities %}
<h2 class="b15">Activités à venir</h2>
<ul>
    {% for activity in msg.activities %}
<li><b>{{ activity.date }}</b>: {{ activity.title }}</li>
    {% endfor %}
</ul>
{% endif %} 

<hr />
<!-- Information  -->
# {{ info.title }}
{{ info.content }}

<hr />
<!-- Bulletin -->
# {{ bulletin.title }}
{{ bulletin.content }}

<hr />
<!-- Calendrier -->
# {{ calendrier.title }}
{{ calendrier.content }}




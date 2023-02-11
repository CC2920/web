---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: Le CC2920
  
widget1:
  title: "Messages de la semaine"
  url: '/communications/messages/'
  image: 'messages.jpg'
  text: 'Consultez les messages de la semaine pour les dernières nouvelles du corps de cadet.'

widget2:
  title: "Comment nous rejoindre"
  url: '/nous-rejoindre'
  text: 'En personne, par téléphone ou via courriel, nous somme là pour adresser vos questions et supporter nos cadets !'
  image: 'quartier-maitre.jpg'

widget3:
  title: "Financement"
  url: '/information/financement'
  image: 'financement-billets.jpg'
  text: 'Consultez les différentes options et campagnes de financement qui permettent de soutenir le CC2920 financièrement.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: 
  text: 
  style: 

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

# Bienvenue !

Garçons et filles de 12 à 18 ans, vous avez envie de défis et d'aventure? Nous offrons du biathlon, tir à la carabine à air comprimé, sports, expéditions en forêt, escalade, canot, leadership, musique, bref de tout pour tous les goûts! Venez nous rencontrer lors de nos soirées d'instruction, les vendredis soirs de 18h30 à 21h00, au 52 St-Rosaire, à Gatineau! Il nous fera plaisir de discuter avec vous et de vous fournir de plus amples renseignements.

Le mouvement des cadets visent à encourager les jeunes de 12 à 18 ans à devenir des citoyens actifs et responsables au sein de leur communauté, de développer chez eux les qualités de civisme et de leadership, de promouvoir la forme physique et de stimuler leur intérêt pour les activités des Forces canadiennes.

Les corps de cadets sont des organismes civils, parrainé conjointement par la Ligue des cadets de l'armée et par le ministère de la Défense nationale du Canada, et financé par ce dernier.

Les cadets ne s'engagent aucunement à servir comme militaires et peuvent quitter lorsqu'ils le désirent.

<a href='{{ site.data.hardcodes.site-programme-des-cadets }}'>Programme des cadets</a>

<div class="row t60">
	{% if page.widget1.image or page.widget1.video or page.widget1.title %}
		{% include _frontpage-widget.html widget=page.widget1 %}
	{% endif %}

	{% if page.widget2.image or page.widget2.video or page.widget2.title %}
		{% include _frontpage-widget.html widget=page.widget2 %}
	{% endif %}

	{% if page.widget3.image or page.widget3.video or page.widget3.title %}
		{% include _frontpage-widget.html widget=page.widget3 %}
	{% endif %}
</div><!-- /.row -->


## Information aditionelle

{% include list-sectionNav title=page.title %}

<section class="panel" markdown="1">

### Formation en ligne: Protection de l'enfance

Formation en ligne du Centre Canadien de la protection de l'enfance

- [Ressource pour les parents et les chefs adultes]({{ site.url }}{{ site.baseurl }}{{ site.data.hardcodes.page-ressource-protection-enfance}})
- [Lien pour la Formation pour les parents de cadets]({{ site.data.hardcodes.site-formation-en-ligne-priorite-jeunesse }})

*Cliquez sur « Acheter ». Sélectionnez la première formation répertoriée sur la page d’achat et entrez le code promo CCOParent.*


### Non à l'intimidation

Votre enfant est la cible de gestes de violence ou d'intimidation ?
- Comment [agir face à l'intimidation]({{ site.url }}{{ site.baseurl }}{{ site.data.hardcodes.page-ressource-intimidation }})

</section>

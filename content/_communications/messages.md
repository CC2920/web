---
title:  "Messages de la semaine"

activities: 
    - date: 24-25-26 février
      title: EEO pour le niveau or 
    - date: 25 février
      title: Formation intensive pour les recrues ayant 14 ans au 1er septembre 2023
    - date: 10 mars
      title: Congé de la semaine de relâche 
---


## Soirée du 24 février 
 
Tenue C5 pour tous 

Les résultats du NECPC de vendredi passé seront disponibles pour vérification sur place ce vendredi. Les normes sont disponibles ici. 

- **Niveau argent** : vous allez donner votre cours. Si vous avez une demande de matériel de dernière minute, écrivez-nous au 2920armee@cadets.gc.ca . 
- **Niveau or** : les consignes pour l’EEO n’ont pas changé malgré le changement de date. Soyez au corps de cadets à 18h30 pour le départ avec votre matériel pour la fin de semaine. Voici à nouveau le reste de l’information ici. 


## Formation intensive pour recrues 25 février 

Les recrues ayant 14 ans au 1er septembre 2023 qui n’ont pas assisté à la séance de formation intensive à l’automne sont invitées à participer à cette autre séance pour sauter de niveau. Les cadets concernés, vous devriez avoir déjà été informés par le personnel de l’unité; dans le doute sur votre éligibilité, écrivez-nous au <2920armee@cadets.gc.ca>. 

Tenue C3, 9h30 à 12h au corps de cadets 52 St-Rosaire. 


## Tir

Les cadets qui ont été sélectionné pour l’équipe de tir auront une pratique le lundi 20 février de 18h30 à 21h au centre Nouvel-Horizon (100 rue de la Baie). 

Tenue civil 
 
La compétition aura lieu au manège militaire de Hull, le 12 mars prochain 

 
## Biathlon 
 
Il y a une pratique interieur de tir sur les cibles de baithlon avec la carabine à air ce mercredi au centre Nouvel-Horizon (100 rue de la Baie).  
 
Tenue civil 
 
## Activités à venir 
 
{% assign activities = page.activities %}        
{% if activities %}
<ul>
{% for activity in activities %}
<li><b>{{ activity.date }}</b>: {{ activity.title }}</li>
{% endfor %}
</ul>
{% endif %}

---
title:  "État-major Cadet" 
layout: page-side-navigation
navigationKey: presentation

#
# Chaque groupe contient une list d'items représentant le/les cadet(s).
#
# Chaque items dand la liste représentant un cadet peut contenur son nom, le titre (grade) et l'URL de sa photo. 
# Si aucune photo n'est disponible, vous pouvez spécifiée une photo de grade ou simplement le laissé vide afin d'indiqué au script d'utiliser une photo par défaut .
#
#
les-cadets-major:
    - cadet:
      name: "Adjuc Méliane Legault"
      title: "Cadet-commandant"
      picture:

    - cadet:
      name: "Adjum Alexandre Bogucki"
      title: "Adjudant-Maitre de musique"
      picture:

    - cadet:
      name: "Adjum Zakaryane Geron"
      title: "Adjudant-Maitre Instruction"
      picture:

# Chaque groupe contient une list d'items représentant un cadet(te).
#
# Chaque items dand la liste représentant un cadet peut contenur son nom, le titre (grade) et l'URL de sa photo. 
# Si aucune photo n'est disponible, vous pouvez spécifiée une photo de grade ou simplement le laissé vide afin d'indiqué au script d'utiliser une photo par défaut .
#
#
les-cadets-cadres:
    - cadet: 
      name: Adj Raphael Briere
      title: Cadet sénior responsable niveau Vert
      picture: 

    - cadet: 
      name: Adj Sébastien Brunette
      title: Cadet sénior responsable niveau Argent
      picture: 

    - cadet: 
      name: Adj Mory Yacine Kaba
      title: Cadet sénior responsable niveau Argent
      picture: 

    - cadet: 
      name: Adj Patrick Delaney-Dufour
      title: Cadet sénior responsable niveau Rouge
      picture: 

    - cadet: 
      name: Adj Jacob St-Louis
      title: Cadet sénior responsable niveau Rouge
      picture:
       
    - cadet: 
      name: Adj Oluwafemi Bassowa
      title: Cadet sénior responsable niveau Rouge
      picture:

    - cadet: 
      name: Adj Ahoefa Tiffany Atitsogbe
      title: Cadet sénior responsable niveau Vert
      picture:    
    
    - cadet: 
      name: Adj Samuel Leduc
      title: Cadet sénior responsable niveau Vert
      picture:
---


Voici l'équipe des cadets seniors qui supervisent et donnent des cours aux cadets.:



{% include list-members 
    list=page.les-cadets-major
    title="L'État-major cadet" 
%}


{% include list-members 
    list=page.les-cadets-cadres
    title="Les Cadets-cadres"
%}

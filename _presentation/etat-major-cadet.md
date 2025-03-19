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
      name: "Adjuc Zakaryane Geron"
      title: "Cadet-commandant"
      picture: "/docs/historique/adjuc44_Zakaryane-Geron.jpg"

    - cadet:
      name: "Adjum Sébastien Brunette"
      title: "Adjudant-Maitre Instruction"
      picture: 
    
    - cadet:
      name: "Adjum Dominic Bogucki"
      title: "Adjudant-Maitre de musique"
      picture: 



# Chaque groupe contient une list d'items représentant un cadet(te).
#
# Chaque items dand la liste représentant un cadet peut contenur son nom, le titre (grade) et l'URL de sa photo. 
# Si aucune photo n'est disponible, vous pouvez spécifiée une photo de grade ou simplement le laissé vide afin d'indiqué au script d'utiliser une photo par défaut .
#
#
les-cadets-cadres:
    
    - cadet: 
      name: Adj Patrick Delaney-Dufour
      title: Cadet sénior responsable niveau Rouge
      picture: "/docs/cadets-cadres/CC2920-Adj-Delaney-Dufour.JPG"

        
    - cadet: 
      name: Adj Oluwafemi Bassowa
      title: Cadet sénior responsable niveau Rouge
      picture: "/docs/cadets-cadres/CC2920-Adj-Bassowa.JPG"

    - cadet: 
      name: Adj Ahoefa Tiffany Atitsogbe
      title: Cadet sénior responsable niveau Vert
      picture: "/docs/cadets-cadres/CC2920-Adj-Atitsogbe.JPG"
    
    - cadet: 
      name: Adj Samuel Leduc
      title: Cadet sénior responsable niveau Vert
      picture: "/docs/cadets-cadres/CC2920-Adj-Leduc.JPG"
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

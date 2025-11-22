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
      name: "Adjuc Sébastien Brunette"
      title: "Cadet-commandant"
      picture: "/docs/historique/CC2920-Adjuc-Brunette.jpg"

    - cadet:
      name: "Adjum Ahoefa Tiffany Atitsogbé"
      title: "Adjudant-Maitre Instructeur spécialiste Exercice militaire"
      picture: "/docs/cadets-cadres/CC2920-Adj-Atitsogbe.JPG"




# Chaque groupe contient une list d'items représentant un cadet(te).
#
# Chaque items dand la liste représentant un cadet peut contenur son nom, le titre (grade) et l'URL de sa photo. 
# Si aucune photo n'est disponible, vous pouvez spécifiée une photo de grade ou simplement le laissé vide afin d'indiqué au script d'utiliser une photo par défaut .
#
#
les-cadets-cadres:
    
    - cadet: 
      name: Adj Apélété Jack Atitsogbé 
      title: Cadet sénior senior Responsable de la musique
      picture:

    - cadet: 
      name: Adj Alexis Martel 
      title: Cadet sénior responsable du niveau Argent
      picture: 
      
    - cadet: 
      name: Adj Tamalia Hardy  
      title: Cadet sénior responsable du niveau Rouge
      picture: 

    - cadet: 
      name: Adj Tayeb Belhabib 
      title: Cadet sénior responsable du niveau Vert
      picture: 

    - cadet: 
      name: Adj Mallika Viau 
      title: Cadet sénior responsable du niveau Vert
      picture: 

    - cadet: 
      name: Adj Catherine Dumoulin 
      title: Cadet sénior responsable des services (Admin/Appro)
      picture: 
          
    - cadet: 
      name: Adj Samuel Leduc
      title: Cadet sénior Instructeur
      picture: "/docs/cadets-cadres/CC2920-Adj-Leduc.JPG"

    - cadet: 
      name: Adj Maxim Lauzon
      title: Cadet sénior Instructeur
      picture:
      
    - cadet: 
      name: Adj Renaud Metlej
      title: Cadet sénior Instructeur
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

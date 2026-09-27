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
      name: "Adjum Tayeb Belhabib"
      title: "Cadet sénior"
      picture: "/docs/cadets-cadres/CC2920-Adjum-Belhabib.jpg"

    - cadet:
      name: "Adjum Malika Viau"
      title: "Cadet sénior"
      picture: "/docs/cadets-cadres/CC2920-Adjum-Viau.jpg"

    - cadet: 
      name: Adjum Apélété Jack Atitsogbé 
      title: Cadet sénior responsable du niveau rouge et de la musique
      picture: "/docs/cadets-cadres/CC2920-Adj-Atitsogbé.jpg"
      
# Chaque groupe contient une list d'items représentant un cadet(te).
#
# Chaque items dand la liste représentant un cadet peut contenur son nom, le titre (grade) et l'URL de sa photo. 
# Si aucune photo n'est disponible, vous pouvez spécifiée une photo de grade ou simplement le laissé vide afin d'indiqué au script d'utiliser une photo par défaut .
#
#
les-cadets-cadres:
    - cadet: 
      name: Adj Nicolas Martel 
      title: Cadet sénior responsable du niveau Argent
      picture: 
      
    - cadet: 
      name: Adj Ziham Dahir 
      title: Cadet sénior responsable du niveau Rouge
      picture: 
          
    - cadet: 
      name: Adj Tristan Lafrenière 
      title: Cadet sénior responsable du niveau Vert
      picture: 

    - cadet: 
      name: Adj Naomi Julie Paquette 
      title: Cadet sénior responsable du niveau Vert
      picture: 

    - cadet: 
      name: Sgt Milan Monney 
      title: Cadet sénior responsable des services (Admin/Appro)
      picture: 

    - cadet: 
      name: Sgt Xolalie Koblavi 
      title: Cadet sénior responsable du niveau Argent
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

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
      name: "Adjuc Beata Rus"
      title: "Cadet Sergent-Major Régimentaire"
      picture: 

    - cadet:
      name: "Adjum Louick Lamber-Turcotte"
      title: "Cadet-commandant adjoint"
      picture: 

    - cadet:
      name: "Adjum Lahmya Chapleau"
      title: "Cadet Sergent-major"
      picture: 





# Chaque groupe contient une list d'items représentant un cadet(te).
#
# Chaque items dand la liste représentant un cadet peut contenur son nom, le titre (grade) et l'URL de sa photo. 
# Si aucune photo n'est disponible, vous pouvez spécifiée une photo de grade ou simplement le laissé vide afin d'indiqué au script d'utiliser une photo par défaut .
#
#
les-cadets-cadres:
    - cadet: 
      name: Sgt. Mathis Lalonde
      title: Cadet cadre & commandant de la garde des drapeaux
      picture: 

    - cadet: 
      name: Adj. Alexandre Bogucki
      title: Cadet cadre
      picture: 

    - cadet: 
      name: Adj. Raphael Brière
      title: Cadet cadre
      picture: 

    - cadet: 
      name: Adj. Patrick Delaney-Dufour
      title: Cadet cadre
      picture: 

    - cadet: 
      name: Adj. Mory Yacine Kaba
      title: Cadet cadre
      picture: 

    - cadet: 
      name: Adj. Méliane Legault 
      title: Cadet cadre
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
---
title:  "État-major Cadet"  

#
# Chaque groupe contient une list d'items représentant le/les cadet(s).
#
# Chaque items dand la liste représentant un cadet peut contenur son nom, le titre (grade) et l'URL de sa photo. 
# Si aucune photo n'est disponible, vous pouvez spécifiée une photo de grade ou simplement le laissé vide afin d'indiqué au script d'utiliser une photo par défaut .
#
#
les-cadets-major:
    - cadet:
      name: "Adjuc Mélodie Lambert-Turcotte"
      title: "Cadet Sergent-Major Régimentaire"
      picture: "/content/docs/etat-major/Lambert-Turcotte.jpg"

    - cadet:
      name: "Adjum Alexis Bouchard-Couvrette"
      title: "Cadet-commandant adjoint"
      picture: "/content/docs/etat-major/Bouchard-Couvrette_A.jpg"

    - cadet:
      name: "Adjum Mathilde Lambert-Turcotte"
      title: "Cadet Sergent-major"
      picture: "/content/docs/etat-major/Lambert-Turcotte_adjum.jpg"





# Chaque groupe contient une list d'items représentant un cadet(te).
#
# Chaque items dand la liste représentant un cadet peut contenur son nom, le titre (grade) et l'URL de sa photo. 
# Si aucune photo n'est disponible, vous pouvez spécifiée une photo de grade ou simplement le laissé vide afin d'indiqué au script d'utiliser une photo par défaut .
#
#
les-cadets-cadres:
    - cadet: 
      name: Adj. J. Lavoie
      title: Cadet cadre & commandant de la garde des drapeaux
      picture: 

    - cadet: 
      name: Adj. C. Olivier
      title: Cadet cadre
      picture: /content/docs/cadets-cadres/Olivier.jpg

    - cadet: 
      name: Adj. E. Rus
      title: Cadet cadre / Tambour-major
      picture: 

    - cadet: 
      name: Adj. C. Sabourin
      title: Cadet cadre
      picture: /content/docs/cadets-cadres/Sabourin.jpg

    - cadet: 
      name: Sgt. Z. Roy
      title: Cadet cadre
      picture: /content/docs/cadets-cadres/Roy.jpg

    - cadet: 
      name: Cplc. D. Loukou
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
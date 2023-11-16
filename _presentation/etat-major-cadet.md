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
      name: "Adjuc Lahmya Chapleau"
      title: "Cadet-commandant"
      picture: 

    - cadet:
      name: "Adjum Mathis Lalonde"
      title: "Adjudant-Maitre de parade"
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
      title: Senior responsable niveau Or
      picture: 

    - cadet: 
      name: Adj Meliane Legault
      title: Senior responsable niveau Argent
      picture: 

    - cadet: 
      name: Adj Sebastien Brunette
      title: Senior responsable niveau Argent
      picture: 

    - cadet: 
      name: Adj Mory Yacine Kaba
      title: Senior responsable niveau Argent
      picture: 

    - cadet: 
      name: Adj Patrick Delaney-Dufour
      title: Senior responsable niveau Rouge
      picture: 

    - cadet: 
      name: Adj Jacob St-Louis
      title: Senior responsable niveau Rouge
      picture:
       
    - cadet: 
      name: Adj Oluwafemi Bassowa
      title: Senior responsable niveau Rouge
      picture:

    - cadet: 
      name: Adj Ahoefa Tiffany Atitsogbe
      title: Senior responsable niveau Vert
      picture: 

    - cadet: 
      name: Adj Alexandre Bogucki
      title: Senior responsable niveau Vert
      picture:    
    
    - cadet: 
      name: Adj Samuel Leduc
      title: Senior responsable niveau Vert
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
---
title:  "Nos commandants"  
categories:
    - historique
tags:
---

{% assign biographies = site.documents | sort: 'name' | where_exp: "document", "document.path contains '_historique/commandants/'" %}
{% include list-commandants list=biographies %}

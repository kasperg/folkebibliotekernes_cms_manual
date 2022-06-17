---
title: "Kom godt i gang"
permalink: /skriveguide/
weight: 1
---

## Manualens opbygning
Hver side i guiden er en markdown-fil. 
En markdown-fil er en tekstfil med endelsen ``.md``
Teksten skal være skrevet med markdown-syntaks. [Læs om Mardown her](/skriveguide/markdown-guide/).

Markdown-filerne ligger i mapperne:
````
/sider/_administrator
/sider_redaktoer
/sider/_udvikling
````
Siderne dukker automatisk op i venstremenuen.

## Sidernes opbygning
Alle sider skal starte som vist her. Det hedder "Front Matter". Her definerer man sidens titel, url og rækkefølge i menuen. 
````
---
title: "Markdown guide"
permalink: /skriveguide/markdown-guide
weight: 2
---
````

* Title vises som H1 på siden og i venstremenuen. 
* Weight bestemmer rækkefølgen i venstremenuen. 
* Permalink er den url siden bliver tilgængelig på.
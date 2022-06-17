---
title: "Kom godt i gang"
permalink: /skriveguide/
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
Alle sider skal starte som vist her. Det hedder "Front Matter". Her definerer man sidens titel. Den bruges i venstramenuen og som H1 på siden.
````
---
title: "Markdown guide"
---
````

Filnavnet som siden gemmes i har kun betydning for sorteringen i venstremenuen. Derfor sætter vi tal forrest så vi kan styre rækkefølgen. Spring i tallene så det er nemt at indsætte en side midt i sekvensen efterfølgende. Dvs. nummerer ikke 1,2,3,4,5 men i stedet f. eks. 1, 10, 20, 30, 40
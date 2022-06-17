## Manual for Folkebibliotekernes CMS

Vejledningen er en gennemgang af DDB CMS’ overordnede struktur og redaktionelle funktioner. Den er rettet mod medarbejdere, der fungerer som redaktører eller andre typer af indholdsproducenter på sitet. Vejledningen introducerer også forskellige værktøjer, der anvendes til at strukturere indhold og administrative/tekniske funktioner (f.eks. brugeradministration), som kan være relevante for både redaktører og webmastere.

## Teknisk information

#### Jekyll og Minimal Mistakes

Manualen er lavet i [Jekyll](https://jekyllrb.com/) og er hostet på GitHub Pages. Jekyll-temaet [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) er anvendt og tilknyttet som "remote theme".

Der er lavet to små "hacks" til Minimal Mistakes. 

1.  Site subtitle er sat til branch name ved at kopiere og tilrette `masthead.html`
2.  Der er indsat autogenereret menu i sidebar på sider der tilhører collections. Det er gjort ved at tilrette `sidebar.html`

#### Søgning med Algolia

Søgefeltet i manualen virker med Algolia søgemotor. Der er oprettet et Github Action workflow der sætter reindeksering i gang ved hvert Github Pages rebuild.

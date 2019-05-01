# Basisbeginselen van Markdown

## Wat is Markdown?
Markdown is een lichtgewicht universele opmaaktaal op basis van platte tekst die zodanig ontworpen is dat het gemakkelijk valt te converteren naar andere formaten zoals HTML, Word of RTF. Zo kan je als schrijver gemakkelijk, snel en flexibel werken.

## Markdown editor
Als je de Markdown editor gebruikt dan selecteer je eerst het stuk tekst dat je wilt aanpassen. Daarna gebruik je één van de knoppen zoals in dit voorbeeld:

![Teksteditor](markdown-bold.png?raw=true "Teksteditor")

Je kan Markdown ook handmatig gebruikten. Hieronder staan de meest gebruikte functies:

## Koppen
Als je een kop (header) wilt maken, gebruikt je een hash (#), als volgt:

```
# Dit is kop 1 (H1)
## Dit is kop 2 (h2)
### Dit is kop 3 (h3)
#### Dit is kop 4 (h4)
```

De titel van dit document "Basisbeginselen van Markdown" is een voorbeeld van een H1 kop.

Hierboven vind je voorbeelden van headers (H1, H2, H3 en H4) van het eerste tot vierde niveau maar niveau's tot en met 6 zijn mogelijk. Je onderwerp mag maar één header van het eerste niveau (H1) bevatten. Deze wordt op de pagina weergegeven als de titel. 

Het CMS genereert die meestal automagisch op basis van de titel van de pagina.

## Vetgedrukte en cursieve tekst
Als je tekst als **vet** wilt opmaken, zet je de tekst tussen dubbele sterretjes:

```
Deze tekst is **vet**.
```

Als je tekst als *cursief* wilt opmaken, zet je de tekst tussen enkele sterretjes:

```
Deze tekst is *cursief*.
```

Als je tekst als ***vet en cursief*** wilt opmaken, zet je de tekst tussen driedubbele sterretjes:

```
Deze tekst is zowel ***vet als cursief***.
```

## Link
Als je een [link](https://wikipedia.org) wilt maken dan doe je dat als volgt:

```
<https://wikipedia.org>
```

Met tekst er bij:

```
[Wikipedia](http://wikipedia.org)
```

## Link met een e-mailadres
Een link naar een e-mailadres maak je als volgt:

```
<info@cavallieri.nl>
```

Met tekst er bij:

```
[Stuur me een e-mail](mailto:info@cavallieri.nl)
```

## Link naar een bestand
Upload éérst het bestand (bijvoorbeeld een PDF) onder Documenten:

![Bestanden](files.png?raw=true "Bestanden")

Gebruik dan de Link knop in de editor en kies het document:

![Bestand](link.png?raw=true "Bestand")

Pas eventueel de tekst van de link nog aan:

```
(file: testdocument.pdf text: Testdocument)
```

## Horizontale lijn
Als je een horizontale lijn wil toevoegen om teksten te scheiden gebruik je 4 sterretjes:

```
****
```

Het voorbeeld hierboven wordt als volgt weergegeven:

****

## Blokcitaten
Blokcitaten (quotes) worden gemaakt met het teken >:

```
> Caravans willen helemaal niet op vakantie. Vandaar dat die auto's zo hard moeten trekken.
```

Het voorbeeld hierboven wordt als volgt weergegeven:
> Caravans willen helemaal niet op vakantie. Vandaar dat die auto's zo hard moeten trekken.

## Lijsten

### Ongeordende lijst
Als je een ongeordende lijst of een lijst met opsommingstekens wil opmaken, kan je sterretjes of streepjes gebruiken. Zo wordt de volgende Markdown:

```
- Lijst item 1
- Lijst item 2
- Lijst item 3
```

weergegeven als:
- Lijstitem 1
- Lijstitem 2
- Lijstitem 3

Als je een lijst in een andere lijst wil nesten, laat je de lijstitems van de onderliggende lijst inspringen. Zo wordt de volgende Markdown:

```
- Lijst item 1
  - Lijst item A
  - Lijst item B
- Lijst item 2
```

weergegeven als:

- List item 1
  - List item A
  - List item B
- List item 2

### Geordende lijst
Als je een geordende lijst/stapsgewijze lijst wil opmaken, gebruik je de bijbehorende nummers. Zo wordt de volgende Markdown:

```
1. Eerste item
1. Tweede item
1. Derde item
```

weergegeven als:
1. Eerste item
1. Tweede item
1. Derde item

Als je een lijst in een andere lijst wilt nesten, laat je de lijstitems van de onderliggende lijst inspringen. Zo wordt de volgende Markdown:

```
1. Eerste item
   1. Subitem
   1. Subitem
1. Tweede item
```

weergegeven als:
1. Eerste item
   1. Subitem
   1. Subitem
1. Tweede item

Merk op dat we '1.' gebruiken voor alle vermeldingen. Hierdoor is het eenvoudiger om later verschillen te beoordelen als er in latere updates nieuwe stappen worden toegevoegd of bestaande stappen worden verwijderd.

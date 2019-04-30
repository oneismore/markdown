# Basisbeginselen van Markdown

## Markdown editor
Als u de Markdown editor gebruikt dan selecteert u eerst het stuk tekst dat u wilt aanpassen. Daarna gebruikt u één van de knoppen zoals in dit voorbeeld:

![Teksteditor](markdown-bold.png?raw=true "Teksteditor")

U kunt Markdown ook handmatig gebruikten. Hieronder staan de meest gebruikte functies:

## Koppen
Als u een kop (header) wilt maken, gebruikt u een hash (#), als volgt:

```
# Dit is kop 1 (H1)
## Dit is kop 2 (h2)
### Dit is kop 3 (h3)
#### Dit is kop 4 (h4)
```

De titel van dit document "Basisbeginselen van Markdown" is een voorbeeld van een H1 kop.

Hierboven vindt u voorbeelden van headers (H1, H2, H3 en H4) van het eerste tot vierde niveau maar niveau's tot en met 6 zijn mogelijk. Uw onderwerp mag maar één header van het eerste niveau (H1) bevatten. Deze wordt op de pagina weergegeven als de titel.

## Vetgedrukte en cursieve tekst
Als u tekst als **vet** wilt opmaken, zet u de tekst tussen dubbele sterretjes:

```
Deze tekst is **vet**.
```

Als u tekst als *cursief* wilt opmaken, zet u de tekst tussen enkele sterretjes:

```
Deze tekst is *cursief*.
```

Als u tekst als ***vet en cursief*** wilt opmaken, zet u de tekst tussen driedubbele sterretjes:

```
Deze tekst is zowel ***vet als cursief***.
```

## Link
Als u een [link](https://wikipedia.org) wilt maken dan doet u dat als volgt:

```
<https://wikipedia.org>
```

Met tekst er bij:

```
[Wikipedia](http://wikipedia.org)
```

## Link met een e-mailadres
Een link naar een e-mailadres maakt u als volgt:

```
<info@cavallieri.nl>
```

Met tekst er bij:

```
[Stuur me een e-mail](mailto:info@cavallieri.nl)
```

## Link naar een bestand
Upload éérst het bestand (bijvoorbeeld een PDF) onder Bestanden:

![Bestanden](files.png?raw=true "Bestanden")

Gebruik dan de Link knop in de editor en kies het bestand:

![Bestand](link.png?raw=true "Bestand")



## Horizontale lijn
Als u een horizontale lijn wilt toevoegen om teksten te scheiden gebruikt u 4 sterretjes:

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
Als u een ongeordende lijst of een lijst met opsommingstekens wilt opmaken, kunt u sterretjes of streepjes gebruiken. Zo wordt de volgende Markdown:

```
- Lijst item 1
- Lijst item 2
- Lijst item 3
```

weergegeven als:
- Lijstitem 1
- Lijstitem 2
- Lijstitem 3

Als u een lijst in een andere lijst wilt nesten, laat u de lijstitems van de onderliggende lijst inspringen. Zo wordt de volgende Markdown:

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
Als u een geordende lijst/stapsgewijze lijst wilt opmaken, gebruikt u de bijbehorende nummers. Zo wordt de volgende Markdown:

```
1. Eerste item
1. Tweede item
1. Derde item
```

weergegeven als:
1. Eerste item
1. Tweede item
1. Derde item

Als u een lijst in een andere lijst wilt nesten, laat u de lijstitems van de onderliggende lijst inspringen. Zo wordt de volgende Markdown:

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

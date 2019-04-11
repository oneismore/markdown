# Basisbeginselen van Markdown

## Koppen
Als u een kop wilt maken, gebruikt u een hash (#), als volgt:

```
# Dit is kop 1
## Dit is kop 2
### Dit is kop 3
#### Dit is kop 4
```

Hierboven vindt u voorbeelden van headers (H1, H2, H3 en H4) van het eerste tot vierde niveau maar niveau's tot en met 6 zijn mogelijk. Uw onderwerp mag maar één header van het eerste niveau (H1) bevatten. Deze wordt op de pagina weergegeven als de titel.

## Vetgedrukte en cursieve tekst
Als u tekst als vet wilt opmaken, zet u de tekst tussen dubbele sterretjes:

```
Deze tekst is **vet**.
```

Als u tekst als cursief wilt opmaken, zet u de tekst tussen enkele sterretjes:

```
Deze tekst is *cursief*.
```

Als u tekst als vet en cursief wilt opmaken, zet u de tekst tussen driedubbele sterretjes:

```
Deze tekst is zowel ***vet als cursief***.
```

In de Markdown editor selecteert u eerst het stuk tekst dat u wilt aanpassen en daarna gebruikt u één van de knoppen zoals in dit voorbeeld:

![Teksteditor](markdown-bold.png?raw=true "Teksteditor")

## Link
Als u een [link](https://wikipedia.org) wilt maken dan doet u dat als volgt:

```
<https://wikipedia.org>
```

Met tekst er bij:

```
[Wikipedia](http://wikipedia.org)
```

## E-mailadres
Een link naar een e-mailadres maakt u als volgt:

```
<info@cavallieri.nl>
```

Met tekst er bij:

```
[Stuur me een e-mail](mailto:info@cavallieri.nl)
```

## Horizontale lijn
Als u een horizontale lijn wilt toevoegen om teksten te scheiden gebruikt u 4 sterretjes:

```
****
```

Het voorbeeld hierboven wordt als volgt weergegeven:

****

## Blokcitaten
Blokcitaten worden gemaakt met het teken >:

```
> Unidentified vessel travelling at sub warp speed, bearing 235.7. Fluctuations in energy readings from it, Captain. All transporters off. A strange set-up, but I'd say the graviton generator is depolarized. The dark colourings of the scrapes are the leavings of natural rubber, a type of non-conductive sole used by researchers experimenting with electricity. The molecules must have been partly de-phased by the anyon beam.
```

Het voorbeeld hierboven wordt als volgt weergegeven:
> Unidentified vessel travelling at sub warp speed, bearing 235.7. Fluctuations in energy readings from it, Captain. All transporters off. A strange set-up, but I'd say the graviton generator is depolarized. The dark colourings of the scrapes are the leavings of natural rubber, a type of non-conductive sole used by researchers experimenting with electricity. The molecules must have been partly de-phased by the anyon beam.

## Lijsten

### Ongeordende lijst
Als u een ongeordende lijst of een lijst met opsommingstekens wilt opmaken, kunt u sterretjes of streepjes gebruiken. Zo wordt de volgende Markdown:

```
- List item 1
- List item 2
- List item 3
```

weergegeven als:
- Lijstitem 1
- Lijstitem 2
- Lijstitem 3

Als u een lijst in een andere lijst wilt nesten, laat u de lijstitems van de onderliggende lijst inspringen. Zo wordt de volgende Markdown:

```
- List item 1
  - List item A
  - List item B
- List item 2
```

weergegeven als:

- List item 1
  - List item A
  - List item B
- List item 2

### Geordende lijst
Als u een geordende lijst/stapsgewijze lijst wilt opmaken, gebruikt u de bijbehorende nummers. Zo wordt de volgende Markdown:

```
1. First instruction
1. Second instruction
1. Third instruction
```

weergegeven als:
1. First instruction
1. Second instruction
1. Third instruction

Als u een lijst in een andere lijst wilt nesten, laat u de lijstitems van de onderliggende lijst inspringen. Zo wordt de volgende Markdown:

```
1. First instruction
   1. Sub-instruction
   1. Sub-instruction
1. Second instruction
```

weergegeven als:
1. First instruction
   1. Sub-instruction
   1. Sub-instruction
1. Second instruction

Merk op dat we '1.' gebruiken voor alle vermeldingen. Hierdoor is het eenvoudiger om later verschillen te beoordelen als er in latere updates nieuwe stappen worden toegevoegd of bestaande stappen worden verwijderd.

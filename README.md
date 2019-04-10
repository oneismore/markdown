# Markdown gids

Basisbeginselen van Markdown
Koppen
Als u een kop wilt maken, gebruikt u een hash (#), als volgt:
markdown

Kopiëren
# This is heading 1
## This is heading 2
### This is heading 3
#### This is heading 4
Headers moeten in ATX-stijl worden gemaakt, dat wil zeggen dat aan het begin van de regel 1 tot 6 hekjes (#) moeten staan om een header aan te duiden overeenkomstig de HTML-headerniveaus H1 tot H6. Hierboven vindt u voorbeelden van headers van het eerste tot vierde niveau.
Uw onderwerp mag maar één header van het eerste niveau (H1) bevatten. Deze wordt op de pagina weergegeven als de titel.
Als uw header met een # eindigt, moet u aan het eind nog een # toevoegen zodat de titel correct wordt weergegeven. Bijvoorbeeld # Async Programming in F# #.
Met de headers op het tweede niveau wordt de inhoudsopgave op de pagina gegenereerd die wordt weergegeven in de sectie 'In dit artikel' onder de titel op de pagina.
Vetgedrukte en cursieve tekst
Als u tekst als vet wilt opmaken, zet u de tekst tussen dubbele sterretjes:
markdown

Kopiëren
This text is **bold**.
Als u tekst als cursief wilt opmaken, zet u de tekst tussen enkele sterretjes:
markdown

Kopiëren
This text is *italic*.
Als u tekst als vet en cursief wilt opmaken, zet u de tekst tussen driedubbele sterretjes:
markdown

Kopiëren
This is text is both ***bold and italic***.
Blokcitaten
Blokcitaten worden gemaakt met het teken >:
markdown

Kopiëren
> The drought had lasted now for ten million years, and the reign of the terrible lizards had long since ended. Here on the Equator, in the continent which would one day be known as Africa, the battle for existence had reached a new climax of ferocity, and the victor was not yet in sight. In this barren and desiccated land, only the small or the swift or the fierce could flourish, or even hope to survive.
Het voorbeeld hierboven wordt als volgt weergegeven:
The drought had lasted now for ten million years, and the reign of the terrible lizards had long since ended. Here on the Equator, in the continent which would one day be known as Africa, the battle for existence had reached a new climax of ferocity, and the victor was not yet in sight. In this barren and desiccated land, only the small or the swift or the fierce could flourish, or even hope to survive.
Lijsten
Ongeordende lijst
Als u een ongeordende lijst of een lijst met opsommingstekens wilt opmaken, kunt u sterretjes of streepjes gebruiken. Zo wordt de volgende Markdown:
markdown

Kopiëren
- List item 1
- List item 2
- List item 3
weergegeven als:
Lijstitem 1
Lijstitem 2
Lijstitem 3
Als u een lijst in een andere lijst wilt nesten, laat u de lijstitems van de onderliggende lijst inspringen. Zo wordt de volgende Markdown:
markdown

Kopiëren
- List item 1
  - List item A
  - List item B
- List item 2
weergegeven als:
Lijstitem 1
Lijstitem A
Lijstitem B
Lijstitem 2
Geordende lijst
Als u een geordende lijst/stapsgewijze lijst wilt opmaken, gebruikt u de bijbehorende nummers. Zo wordt de volgende Markdown:
markdown

Kopiëren
1. First instruction
1. Second instruction
1. Third instruction
weergegeven als:
Eerste instructie
Tweede instructie
Derde instructie
Als u een lijst in een andere lijst wilt nesten, laat u de lijstitems van de onderliggende lijst inspringen. Zo wordt de volgende Markdown:
markdown

Kopiëren
1. First instruction
   1. Sub-instruction
   1. Sub-instruction
1. Second instruction
weergegeven als:
Eerste instructie
Subinstructie
Subinstructie
Tweede instructie
Merk op dat we '1.' gebruiken voor alle vermeldingen. Hierdoor is het eenvoudiger om later verschillen te beoordelen als er in latere updates nieuwe stappen worden toegevoegd of bestaande stappen worden verwijderd.
Tabellen
Tabellen maken geen onderdeel uit van de Markdown-kernspecificatie, maar ze worden ondersteund door GFM. Tabellen kunt u maken met het sluisteken (|) en afbreekstreepjes (-). Met afbreekstreepjes maakt u de kolomkoppen. Met het sluisteken scheidt u de kolommen van elkaar. Voeg voor de tabel een lege regel in, zodat de tabel correct wordt weergegeven.
Zo wordt de volgende Markdown:
markdown

Kopiëren
| Fun                  | With                 | Tables          |
| :------------------- | -------------------: |:---------------:|
| left-aligned column  | right-aligned column | centered column |
| $100                 | $100                 | $100            |
| $10                  | $10                  | $10             |
| $1                   | $1                   | $1              |
weergegeven als:
Pret	met	Tabellen
links uitgelijnde kolom	rechts uitgelijnde kolom	gecentreerde kolom
USD 100	USD 100	USD 100
USD 10	USD 10	USD 10
USD 1	USD 1	USD 1

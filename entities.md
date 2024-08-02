# Entities

Overzicht van de gebruikte entiteiten in de applicatie

## Begroting

Vanuit de begroting komen de volgende entiteiten:

- Categorie: Ter overzicht worden verschillende posten ingedeeld in een overkoepelende categorie
- Post: Base class met daaronder begrotingsposten en reserveringsposten
- Begrotingspost: Een type uitgaven of inkomsten die waarschijnlijk jaarlijks terugkerend is en waarvan een budget per jaar is bepaald.
- Reserveringspost: Een type uitgave die eens per meerdere jaren wordt gedaan en waarvoor maandelijks geld opzij gezet wordt.

En value objects:
- Spaarpotje: Een concept dat de rabobank kent waarin geld op de spaarrekening opgesplitst kan worden.
- Money: geld waardes makkelijker gemaakt door integer cent representatie en weergave handigheidjes.

## Mutaties

Met dit programma moeten alle mutaties op de rabo rekening bijgehouden worden.

- Mutatie: een mutatie is een daadwerkelijke mutatie die heeft plaatsgevonden op de rekening of in contanten.
- Postmutatie: een post mutatie is een wijziging van saldo van 1 van de posten.

## Rabo import regels

Om de invoer van mutaties eenvoudiger te maken is er een rabo mutatie import tool, die op basis van een csv file mutaties aanmaakt.

- Filterregel: Een set van eigenschappen die de rabo mutatie aan een post koppelt.
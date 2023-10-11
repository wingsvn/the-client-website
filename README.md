> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je, zoals altijd, in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# mijn-OBA familieoverzicht pagine: mijn uitleningen
Voor de opdrachtgever OBA heb ik een "in te leveren boeken" pagina gemaakt dat onderdeel is van het familieoverzicht pagina.

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Userstory: "Toon in een overzicht alle abonnementen van een familie met een verwijzing naar een indiviueel profiel van elk familielid, met de functies: familieleden, beschikbare diensten, laatst geleende boeken en in te leveren boeken om boete te voorkomen."

Voor dit project heb ik voor de opdrachtgever OBA binnen de mijn-OBA omgeving een webpagina gemaakt waar je kunt zien welke boeken er geleend zijn en je binnenkort weer moet inleveren. Ook zie je hoeveel dagen er nog over zijn en is er de mogelijkheid om te verlengen. Onder aan de pagina vind je een "terug" knop, deze knop brengt je terug naar de familie overzichtpagina van uitleningen. Ik ben begonnen met het opzetten van de mobiele versie. Vervolgens heb ik dit uitgewerkt naar de full-size desktop versie.

<img width="225" alt="OBA mobile version" src="https://github.com/wingsvn/the-client-website/assets/144009709/b248add9-e0bc-4aaa-a04b-29ddf2616d88" width=50% height=50%> 
<img width="625" alt="OBA desktop version" src="https://github.com/wingsvn/the-client-website/assets/144009709/70951250-5ec7-49e9-9697-53d247d8bde5">


https://wingsvn.github.io/the-client-website/


## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

In mijn HTML zit elk boek en zijn gegevens in de container "<article>". Hiermee kan ik alles makkelijk dezelfde stijling geven in CSS.
De vraag vanuit de opdrachtgever was om mobiel te beginnen. Om de layout vervolgens aan te passen naar verschillende bredere screensizes heb ik mediaquery gebruikt.
Verder heb ik CSS grid gebruikt voor het indelen van de elementen binnen de artikelen. En om de artikelen (boeken) naast elkaar te zetten, heb ik CSS flex gebruikt.



## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

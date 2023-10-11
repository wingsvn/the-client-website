> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je, zoals altijd, in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# mijn-OBA familieoverzicht pagine: mijn uitleningen
Voor de opdrachtgever OBA heb ik een "in te leveren boeken" pagina gemaakt dat onderdeel is van het familieoverzicht pagina.

## Inhoudsopgave

  * [Briefing/Debriefing] (#Briefing/Debriefing)
  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Briefing/debriefing
### The client debriefing: OBA familie overzichtspagina

**Contactgegevens**

* Bedrijfsnaam: openbare bibliotheek van Amsterdam

* Voor-en achternaam contactpersoon: Mark Vos

* Contactgegevens van contactpersoon: *** 

* Datum aanvraag: 25 september 2023

* Datum oplevering: 13 oktober 2023

**Achtergrondinformatie**

* Opdrachtgever: OBA, openbare bibliotheek van Amsterdam, 28 vestigingen, 2.5 miljoen uitleningen

* Aangeboden diensten: uitleenpunt voor boeken en een openbare studieplek met gratis wifi.

* Unique selling points: de enige openbare bibliotheek in Amsterdam waar iedereen van alle leeftijden boeken kan lenen, waar je verbinding van mensen, cultuur en de stad kunt vinden.

**Opdrachtomschrijving**

* De openbare bibliotheek van Amsterdam wil graag in het mijn OBA platform een overzicht van alle abonnementen van een familie.

* OBA wilt een toegankelijke mijn-OBA omgeving, waar abonnees hun gegevens, betalingen, leningen, aanbevelingen en meer kunnen terugvinden en beheren, en waar onderscheid gemaakt wordt tussen de verschillende gebruikers van het abonnement.

* Hier kunnen gebruikers inzicht krijgen in hun uitleengeschiedenis, abonnementsvorm, openstaande boetes en gepersonaliseerde suggesties voor boeken, activiteiten, etc.

 **Aanleiding**

* De OBA wil graag van fysiek naar hybride, digitalisering, daar hoort een digitale klantcontactstrategie bij.


**Doelstellingen**

* Een leven lang leren faciliteren voor elke leeftijdsgroep.

* Kennis, cultuur en informatie voor iedereen bereikbaar en toegankelijk maken.

* Reflectie, ontmoeting en betrokkenheid bij de stad en buurt stimuleren.

**Oplevering**
* Beschrijf zo concreet mogelijk wat je oplevert (product/dienst/huisstijl)

* Een toegankelijke familie overzichtspagina voor abonnementen binnen het mijn OBA platform.

* Kopjes voor elke product of dienst, een zoekfunctie binnen de mijn OBA omgeving, een chatbot functie en visuele vormgeving voor meer toegankelijkheid.

* Dataretentie: abonnees de beschikking geven over eigen data en de mogelijkheid om opgeslagen data te verwijderen.

* Een trendy huisstijl, deze moet overeenkomen met de OBA huisstijl. Bij verandering in huisstijl is een goede motivatie nodig.

**Randvoorwaarden**
* Technieken: HTML, CSS, JavaScript

* Op vrijdag 13 oktober leveren wij de basis van een mijn OBA omgeving website op.


**Gebruikers van het eindresultaat**
* Doelgroep: gebruikers van familieabonnementen van de OBA, mensen van verschillende nationaliteiten en niveau digitale vaardigheid.

* OBA wil een laagdrempelige en toegankelijke omgeving voor hun gebruikers, dit door minder tekst en meer visuele cues, een modern en overzichtelijk uiterlijk.

* De mijn-OBA omgeving is nu niet erg toegankelijk en ziet er niet aantrekkelijk uit, het is verwarrend en lastig te navigeren.

* De website wordt nu voornamelijk gebruikt op de desktop. Er is wel een toename in mobiele gebruikers, dus de mobiele versie moet ook toegankelijk zijn. 


**Relatie met andere projecten**

* De pagina is een klein onderdeel van een groter systeem, namelijk van het mijn OBA platform.

* Dit project is het voorwerk van de digitalisering van producten en diensten van de OBA.


## Beschrijving
Userstory: "Toon in een overzicht alle abonnementen van een familie met een verwijzing naar een indiviueel profiel van elk familielid, met de functies: familieleden, beschikbare diensten, laatst geleende boeken en in te leveren boeken om boete te voorkomen."

Voor dit project heb ik voor de opdrachtgever OBA binnen de mijn-OBA omgeving een webpagina gemaakt waar je kunt zien welke boeken er geleend zijn en je binnenkort weer moet inleveren. Ook zie je hoeveel dagen er nog over zijn en is er de mogelijkheid om te verlengen. Onder aan de pagina vind je een "terug" knop, deze knop brengt je terug naar de familie overzichtpagina van uitleningen. Ik ben begonnen met het opzetten van de mobiele versie. Vervolgens heb ik dit uitgewerkt naar de full-size desktop versie.

<img width="225" alt="OBA mobile version" src="https://github.com/wingsvn/the-client-website/assets/144009709/b248add9-e0bc-4aaa-a04b-29ddf2616d88" width=50% height=50%> 
<img width="655" alt="OBA tablet version" src="https://github.com/wingsvn/the-client-website/assets/144009709/37621f7a-e24c-46f7-a9fc-ae9ec06145dc">
<img width="625" alt="OBA desktop version" src="https://github.com/wingsvn/the-client-website/assets/144009709/70951250-5ec7-49e9-9697-53d247d8bde5">



https://wingsvn.github.io/the-client-website/


## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

In mijn HTML zit elk boek en zijn gegevens in de container "<article>". Hiermee kan ik alles makkelijk dezelfde stijling geven in CSS.
De vraag vanuit de opdrachtgever was om mobiel te beginnen. Om de layout vervolgens aan te passen naar verschillende bredere screensizes heb ik mediaquery gebruikt.
Verder heb ik CSS grid gebruikt voor het indelen van de elementen binnen de artikelen. En om de artikelen (boeken) naast elkaar te zetten, heb ik CSS flex gebruikt.



## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

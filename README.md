# case-frontend-med-ramverk-cinema

I detta caset ska ni arbeta individuellt. Scenariot är att en vän har köpt en mindre biosalong och vill låta sina kunder boka stolar för kommande föreställningar.
Ni har fått tillgång till ett egetutvecklat API som hanterar resurserna `movies`, `shows`, `bookings`

API länk: https://cinema-api.henrybergstrom.com

## Krav
1. Minimum
- En användare ska kunna bläddra mellan filmer från API:ets utbud
- En användare ska kunna se vilka föreställningar (`Shows`) som finns för vald film `movie`.
- En användare ska kunna boka en biljett för föreställning (`Shows`) givet att det finns tillgängliga säten
  - Användaren får ett meddelande att bokningen är klar med detaljer om bokningen (email, tider, pris)
  - Användaren ska se att stolen är upptagen efter bokningen
- Varje UI enhet ska vara sin egen komponent (MovieCard, ShowCard, BookingForm)
- useEffect ska användas för att hämta information från APIet 
- Inga felmeddelande i konsolen
- Minst 10 git commits med rimlig meddelande

2. Extra
Utöver samliga minimum-punkter ska dessutom följade krav vara uppfyllda:

- En bokning ska hantera flera antal platser. Varje plats ska vara valbar. 
- Lediga platser i biografen ska presenteras visuellt och plats väljs genom att användaren klickar på en ruta/ikon.
- Applikationen ska vara publicerad

## Feedback
Veckan efter presentation kommer feedback ges under följande rubriker:

- Koduppdelning
- git-använding
- allmän kodstil

*Designfeedback tillkommer från Mattias*

## Presentation- och Inlämningsdatum
- Enligt planering hålls presentation av caset under början av vecka 39. Notera lärarna kommer börja ge feedback direkt efter presentationen.
- **Halvtidsredovisning** där vi visar hur långt vi har kommit är 2024-09-10, tisdag kl 10.25  
- Preliminärt datum för presentation och inlämning är 2023-09-24, tisdag kl. 10.25.
- Preliminärt datum för feedback är 2023-09-24 till 2024-09-29 (v39), söndag kl. 23.59.

## Inlämning
Dela ett repo med Henry (@frozenbanana), Anders (@andsju) och mattias (@addkolon)

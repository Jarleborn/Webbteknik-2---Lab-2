Hampus Jarleborn - HJ222HI

# Rapport

## Säkerhetsproblem

  ## SQL Injections

  ##### Beskrivning

  SQL injections är när använadren skickar in egna SQL sataser för att komma åt eller förstöra information på sida. Det krävs dock att sidan använder en databas, för annars finns det inget att skicka förfrågningar till.

  ##### Följder

  Som det står i texten över så kan en användare om SQL injections är möjliga komma åt saker som lösenord och annan känslig data, och änvända dessa på de sett dom finner bäst. Och det är sällan eller aldrig bra.


  #### I Labby Mezzage

  I Labby Mezzage finns det möjligheter för att göra SQL injections, tillexempel kan man logga in som senaste inloggade användaren genom att skriva in vilken mail adress som helst som email och sendan skriva 1'or'1'='1 som då gör att det alltid blir true.

  ##### Förslag på lösning

  Lösningen skulle jag säga är att istaället för att skriva SQL sataserna som dom är gjorde i Labby Mezzage så bör man parametrisera dom istället för att konkatinera dom.
  Man kan också skyddda sig mot detta genom att använda storedprocedures och på så viss inte vissa SQL satsen.




  ## XSS (Cross site scripting)

  ##### Beskrivning

  ##### Orsak

  ##### Förebyggande åtgärder

  ### I Labby Mezzage

  ##### Problem

  ##### Förslag på lösning


  ## Session Hijacking

  ##### Beskrivning

  ##### Orsak

  ##### Förebyggande åtgärder

  ### I Labby Mezzage

  ##### Problem

  ##### Förslag på lösning

## Prestandaproblem

## Mina Egna övergripande reflektioner


<!--
Rapporten ska vara tydligt uppmärkt med ditt namn (och LNU-användarnamn).

Rapporten ska vara tydligt uppdelad i tre delar

Säkerhetsproblem

Prestandaproblem (främst front-end - vi fokuserar inte på kodoptimeringar i back-end)

Egna övergripande reflektioner

Varje säkerhetsproblem/prestandaproblem du hittar med applikationen ska tydligt
redovisas enligt följande

Bra och tydlig rubrik på problemet

Vad problemet innebär, teori om problemet (referens till teori fodras)

Vilka eventuella följder problemet kan skapa (gäller främst säkerhetshål)

Hur man åtgärdar problemet (referens till teori fodras) -->

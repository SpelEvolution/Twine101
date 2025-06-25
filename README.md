# Twine101

![](tenor.gif)

> _"Don’t worry about people stealing your ideas. If your ideas are any good, you’ll have to ram them down people’s throats."_
– **Howard Aiken**

## Introduktion
Twine är ett gratisverktyg där du enkelt kan skapa, testa och utveckla dina narrativa idéer. Vi kommer främst använda det för att skapa textspel, men det är också ett grymt program att använda för att testa olika utfall av exempelvis interaktioner i ett spel. Att planera och testa sina spelidéer är bland det viktigaste inom spelutveckling.

## Kom igång
När man programmerar i Twine så skriver man direkt i passagen innanför dessa tecknen:\
`<<//kod här>>`  

Variabler deklareras genom att alltid börja med ett dollar-tecken. T.ex. $money är en variabel. Om vi säger: `<<set $money = 10>>` och sedan skriver “You have `$money”` så kommer det stå “you have 10” när man spelar spelet.

*Ett exempel på en kodsnutt skulle kunna vara:*

`<<if $money >= 10>>[[Köp ett vapen]]<<else>>[[Du har inte råd att köpa ett vapen]]<</if>>`

Detta skulle leda till att man får ett val att köpa ett vapen om variabeln $money är mer eller lika med 10. Annars kan man inte köpa ett vapen.

**Passage** är benämningen på den "box" man skriver vad som sker i, den leder till en ny passage som i sin tur leder till en/två/femtio andra osv.


## Uppgift
- Gör en uppgift med minst 5 passager och där minst en passage är på 250-500 ord
- Använd länkarna nedan för att lägga lite estetisk flare på ditt Twine-projekt

## Länkar
### Överskådlig dokumentation av vad man kan göra i Twine
[Twine Cookbook]((https://twinery.org/cookbook/index.html))

## Formatera din Twineberättelse som du vill
[Stylesheet]((https://www.w3schools.com/css/default.asp))

## Guide till hur man ska tänka när man skapar en berättelse uppbygd i passager
[Story Patterns]((https://heterogenoustasks.wordpress.com/2015/01/26/standard-patterns-in-choice-based-games/))


[Spel gjorda i Twine]((https://itch.io/games/made-with-twine))

> Inspo för repo: Robert Esbjörnsson\
> Uppgift skapad av Tim Grödhem och Emma Wigur för **_Spel Evolution, Axevalla Folkhögskola_**


# Laboration 2: Funktionell Programmering - Åttaspel

## Kurs: Funktionell Programmering - Hösten 2021

## Inledning
Det här repositoriet innehåller min lösning på den andra laborationen i kursen Funktionell Programmering. Uppgiften fokuserade på att utveckla en lösning för ett åttaspel (en förenklad variant av ett femtonspel) med hjälp av Haskell. Laborationen syftade till att ge träning i att stegvis utveckla komplexa funktioner och dela upp dessa i mindre problem.

## Uppgiftsbeskrivning
Uppgiften innefattade flera steg för att bygga en fullständig lösning för ett åttaspel:
1. **Definiera Datatyper**: Skapa alias för spelbräde (Board), position (Position), och speltilstånd (State).
2. **Hantera Handlingar**: Implementera en datatyp för handlingar som kan genomföras i spelet.
3. **Lösningskonstant**: Definiera en konstant för en löst åttaspel och en funktion för att testa om ett spel är löst.
4. **Hitta den Tomma Brickan**: Skapa en funktion för att hitta positionen för den tomma brickan.
5. **Ersätt Värde**: Implementera en funktion för att ersätta ett värde på en given position i spelbrädet.
6. **Byt Positioner**: Skapa en funktion för att byta plats på två brickor.
7. **Utför Handlingar**: Implementera en funktion som gör det möjligt att flytta den tomma brickan.
8. **Möjliga Framtida Tillstånd**: Definiera en funktion för att beräkna alla möjliga framtida tillstånd från ett givet tillstånd.
9. **Möjliga Lösningar**: Skapa en funktion för att generera en oändlig lista av möjliga framtida tillstånd.
10. **Lösning**: Implementera en funktion för att lösa ett åttaspel.
11. **Testfall**: Definiera testfall för att verifiera att lösaren fungerar korrekt.

## Tekniska Detaljer
- **Programspråk**: Haskell.
- **Problemhantering**: Fokus på att bryta ner problemet i mindre delar och skapa funktioner för varje del.
- **Funktionell Programmering**: Användning av Haskell:s mönstermatchning och datatyper.

## Bedömning och Krav
- Korrekt användning av Haskell:s funktioner och datatyper.
- Kod måste vara välorganiserad och följa funktionell programmeringsstil.
- Adekvat dokumentation och namngivning enligt kursens standarder.
- Programmet måste kompilera och köra korrekt i en Haskell-miljö.

## Inlämning
Uppgiften bedömdes som godkänd eller underkänd baserat på korrekt implementering och dokumentation av de krävda funktionerna.

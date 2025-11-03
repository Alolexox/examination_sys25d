# Skriftlig Examination - Introduktion till C#

**Kursnamn**: Introduktion till C#  
**Examination av**: Läranderesultat 1, 2 och 3 (Kunskaper)  
**Betyg**: Icke Godkänt (IG) eller Godkänt (G)  
**Tidsåtgång**: Ca 3-4 timmar  
**Inlämning**: Senast söndag den 9 november (23:59)  
**Format**: Kopiera den här filen och skriv svaren här inne.

---

**Elevens namn**: Alexandra Ng

---

## Instruktioner

- Svara på alla frågor med egna ord
- Det är inte tillåtet att använda AI i sina svar.
- Alla inlämningar kontrolleras i ett antiplagiat-verktyg. Fusk kan leda till disciplinära åtgärder och risk för avstängning.
- Förklara tydligt och koncist - inga långa utläggningar krävs
- Ge korta kodexempel endast där det efterfrågas (oftast räcker 1-3 rader)
- Försök att använda korrekt terminologi.
- Det är okej att använda kursmaterial och anteckningar

---

## Del 1: Objektorienterad programmering i C# (Läranderesultat 1)

### Fråga 1 - Grundläggande OOP

**Vad är objektorienterad programmering?** Förklara med egna ord vad OOP innebär och ge minst två fördelar med att använda OOP.
    Klasser kan i folkmun kallas för mallar, objekt är det som skapas utifrån de mallarna. Objektorienterad programmering är att inte behöva skriva om objekt 
    och uppbyggnaden 0813451398301 ggr i ett program och att jag således slipper ändra något i varje grej utan bara kan ändra i mallen.

---

### Fråga 2 - Klasser och Objekt

**.**
a) Förklara skillnaden mellan en klass och ett objekt, använd gärna en analogi från verkligheten för att illustrera din förklaring.
    En klass är som en mall och ett objekt är exempelvis produkt skapad utifrån den mallens bestämmelser. Exempelvis har vi bestämmelser på 
    hur en bok ska se ut, klassen berättar vad som är nödvändigt för att den ska få kallas för en bok alltså ett objekt.
b) Vad innebär det om en klass benämns static? Ex: `public static class File`
    Det går inte att skapa objekt utifrån den, den är inte som de andra mallarna - mer ett verktyg än en mall för ett objekt.

---

### Fråga 3 - Konstruktorer

**Vad är en konstruktor och vad används den till?** Förklara vad som händer när man skapar ett nytt objekt med `new` keyword.
    Med hjälp av en konstruktor så förtydligar vi kriterierna för hur objektet ska vara ett objekt enligt klassens regler.

---

### Fråga 4 - Properties och Fields

**Förklara skillnaden mellan ett field och en property i C#.** Ge exempel på när man bör använda respektive.
    Field är private i C#, det betyder att inget där i kan ändras utanför den aktuella klassen. Property kan göra ändringar i privata klassen 
    men enbart det den har fått tillstånd att göra. Så field är som att jag gör ett eget program i vsc (ingen kan kika eller kolla) men property är när jag t ex 
    bjuder någon för liveshare men då får jag bestämma vad de har tillgång till att göra; läsa och/eller redigera.

---

### Fråga 5 - Inkapsling

**Vad är inkapsling (encapsulation) och varför är det viktigt?** Förklara skillnaden mellan `private` och `public`, och när man bör använda vad.
    Private är något som inte syns och som inte kan ändras på något annat sätt än det utvecklaren har bestämt, medan public är det
    användaren har åtkomst till. En klassisk analogi är som att använda en kaffekokare; du som användare kan trycka på en knapp
    för att starta processen för att brygga kaffe (det är alltså public) men du har ingen aning om vad som händer efter det eller under det t ex
    vilka grader (private).

---

### Fråga 6 - Metoder

**Förklara följande:**

a) Vad är skillnaden mellan en metod som returnerar något (t.ex. `int`) och en `void` metod?  
    En int returnerar alltid något som t ex ett mattetal utifrån en formel eller så, medan en void som inte returnerar ett mattetal istället 
    gör något som vi sagt åt den att göra. Voiden kommer inte tillbaka och säger "här är det du önskade" utan den gör bara.
b) Vad innebär det att en metod är `static`?
    Att jag kan använda den metoden utan att skapa ett objekt först.

---

## Del 2: Applikationstyper (Läranderesultat 2)

### Fråga 7 - Applikationstyper i .NET

**C# och .NET kan användas för att bygga olika typer av applikationer.**

a) Nämn minst tre olika typer av applikationer man kan bygga med C# och .NET (t.ex. console)  
    Windows Forms App, Console Application och .NET MAUI App (stavning enligt VS)
b) Beskriv kort vad dessa applikationstyper har för syfte.
    Windows Forms App är till för att skapa program till datorn (windowsprogram), Console Application gör ett program som körs i terminalen 
    och .NET MAUI App är till för att skapa appar till mobiler.

---

### Fråga 8 - Konsolapplikationer

**Vi har fokuserat på konsolapplikationer (Console Application) i kursen.**

a) Vad är en konsolapplikation?  
    Ett textbaserat program som körs i terminalen.
b) Ge ett exempel på när en konsolapplikation kan vara lämplig att använda.
    För att köra en backendtjänst som inte behöver något ui.
---

## Del 3: Datatyper i C# (Läranderesultat 3)

### Fråga 9 - Primitiva Datatyper

**Beskriv följande datatyper och när man använder dem:**

a) `int`  
    En variabel som ger heltal, när vi vill lägga till åldrar som variabler t ex.
b) `double`  
    En variabel som ger decimaltal, i exempelvis matematiska formler. I valutor är decimal som variabel mer lämpligt.
c) `string`  
    En variabel som har med text att göra, exempelvis när vi vill lägga till ett namn eller en text av något slag.
d) `bool`
    Den kan bara vara två, sann eller falsk. Den kan vi använda som en knapp som startar och stänger av en loop, där ändrar vi den till falsk när vi vill stänga loopen.

Förklara också skillnaden mellan `int` och `double`.
Int är bara heltal medan double också kan använda sig av decimaler.
---

### Fråga 10 - Stark typning

**C# är ett starkt typat språk, medan JavaScript är löst typat.**

a) Vad innebär det att ett språk är starkt typat?  
    En variabel måste specificeras jmf med JavaScript där du bara behöver skriva let när du deklarerar variabeln,
    således behöver du definiera om det är en int, string osv.
b) Ge ett exempel på en fördel med stark typning som du märkt av i C#.
    Det blir en tydligare kod, lättare att upptäcka fel i koden än om det står let let let let let let.


---

### Fråga 11 - Arrays och Listor

**Förklara skillnaden mellan en array och en `List<T>` i C#.**

a) När bör man använda en array?  
    När vi behöver en fast grupp av variabler, där vi inte behöver lägga till ett ta bort saker.
b) När bör man använda en `List<T>`?  
    En lista är långsammare men är dynamisk, bör användas när vi vill kunna lägga till och ta bort saker från listan.
c) Skriv ett kort kodexempel (1-3 rader) som visar hur man lägger till ett element i en `List<int>`.
    List<int> ages = new List<int>(); //Skapar listan som ska ha åldrar (lämpligt pga int)
    ages.Add(12); //lägger till åldern 12 i listan som heter ages


---

### Fråga 12 - Dictionary

**Vad är en `Dictionary<TKey, TValue>` och när är den användbar?**

Förklara med egna ord och ge två exempel på scenarion där Dictionary är ett bra val (inget kodexempel krävs).
    Det är som en uppslagsbok istället för en vanlig lista. Så i dictionary kan jag sätta key som Alexandra, mitt namn och 
    value som min ålder 31. Då kan jag söka på bara mitt namn och få fram åldern. Jämfört med listan så behöver jag söka på
    värdet för att få fram värdet.

    Ett annat exempel är om jag gör en key som en produkt och value som priset på produkten. Söker jag efter produkten så får jag
    fram priset på produkten om den finns i dictionary.
---

### Fråga 13 - LINQ

**Vad är LINQ och vad används det till?**

Ge exempel på minst två LINQ-metoder du använt (t.ex. `Where`, `Select`, `OrderBy`, `Count`, etc.) och förklara kort vad de gör.
    FirstOrDefault har jag använt i mitt e-commerceprogram för att få jämföra kundens valda produkt med mitt lager, den stoppar
    när den hittar den första produkten som matchar med kundens sök. 

    I en metod som ska hämta totala vinsten på en order, så använder jag LINQ i form av Sum där jag lägger ihop 
    vinsten av produkterna och antal produkter som lagts till i ordern.

---

## Inlämning och Bedömning

### Format

- Ladda upp den här md filen med dina svar på It's learning senast den 9 november 2025. För de
  som hellre vill länka till sin Git får ni också göra det.

- Skriv ditt **namn** i dokumentet

### Bedömning

#### Godkänt (G)

För att få **Godkänt** krävs att du:

- Besvarar **alla 13 frågor**
- Visar förståelse för grundläggande koncept
- Ger tydliga förklaringar med egna ord
- Använder korrekt terminologi
- Ger kodexempel där det efterfrågas (behöver inte vara perfekt, men ska visa förståelse)

#### Icke Godkänt (IG)

Du får **Icke Godkänt** om:

- Flera frågor är obesvarade eller mycket ofullständiga
- Svaren visar grundläggande missförstånd av koncept
- Svaren är uppenbart kopierade från AI eller andra källor utan egen förståelse
- Svaren är så kortfattade att de inte visar förståelse

**Vid gränsfall**: Om du är nära G men några svar är otillräckliga kan du få möjlighet att komplettera specifika frågor.

---

## Tips för att lyckas

- Börja med frågorna du känner dig säkrast på
- Svara koncist - kvalitet över kvantitet
- Läs igenom dina svar innan inlämning
- Börja i tid - du har två veckor på dig
- Fråga på lektioner om något är oklart

**Kom ihåg**: Det viktiga är att du visar att du **förstår** koncepten, inte hur mycket du skriver. Tydliga, korta förklaringar är ofta bättre än långa utsvävningar.

---

## Hjälp och resurser

### Tillåtet

- Använda kursmaterial och dina egna anteckningar
- Titta på kod du själv skrivit under kursen
- Använda C# dokumentation (docs.microsoft.com)
- Fråga läraren om du inte förstår vad en fråga betyder
- Man får också använda AI för egen inlärning

### Inte tillåtet

- Kopiera svar från ChatGPT eller andra AI-verktyg
- Kopiera svar från klasskamrater eller internet
- Låta någon annan skriva dina svar

---

**Lycka till! 🚀**

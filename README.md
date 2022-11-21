# 220s-javascript-prov

## Regler

- Inte tillåtet att hjälpa varandra på något sätt, räknas som fusk.
- Det är tillåtet att använda internet hur mycket man vill.
- Efter provet kan ni skicka in era svarsfiler som direkt-meddelande till mig via Teams.
  Vet ni hur man zippar så får ni zippa mappen med filerna.<br><br>

Börja med att klona eller ladda ner projektet.
<br>
`git clone https://github.com/abbjetmus/220s-javascript-prov.git`
<br>

## Att tänka på

Varje fråga består av en html fil med uppgiftsnumret.<br>
Html filen innehåller en html mall med nödvändiga taggar och en `script` tagg där ni ska lägga in er javascript kod.<br>
För att starta programmet dubbel-klickar du bara på html filen i filutforskaren och den öppnas i webbläsaren. Sedan när du gör ändringar i filen laddar du om webbläsaren för att dina ändringar ska synas.
Du får använda valfri editor för att koda men rekommenderar Visual Studio Code.
När vi skriver ut till konsolen använder vi `console.log()`.

## Fråga 1 - Variabler

Skapa 3 variabler medlem1, medlem2, medlem3 på bandmedlemmarna i gruppen DollyStyle med värdena "Molly", "Polly" och "Holly".
Skriv sedan ut till konsolen med hjälp av konkateneringsopreatorn `+` och variablerna så att utskriften blir ”Bandmedlemmarna i DollyStyle är Molly, Polly och Holly”.  
Kan du inte använda `+` operatorn skriv bara ut namnen till konsolen.

## Fråga 2 - Datatyper

Vad har följande värden för datatyper i JavaScript. Om du vill testa dig fram använd typeof( ) funktionen.

- 23
- "Kalle Kula"
- true
- null

## Fråga 3 - Villkor

Skapa en variabel city som du tar in med prompt.
<br> `prompt("Ange Sveriges huvudstad?")`<br>
Använd sedan en if-else-sats som kollar om city är "Stockholm", är den det skriver du ut ”Korrekt! Stockholm är Sveriges huvudstad.” annars skriver du ut "Staden är inte Sveriges huvudstad.”.

## Fråga 4 - For-loopen

Skriv en for-loop som börjar på talet 10 och skriver ut alla talen ner till 0. Dvs räknar ner från 10 till 0.

## Fråga 5 - Funktioner

Skriv en funktion `subtract( )` som subtraherar två tal och returnerar resultatet. Anropa sedan funktionen en gång med två valfria tal och skriv ut resultatet till konsolen.

## Fråga 6 - Objekt

Skapa ett objekt som heter person med följande properties egenskaper: name: ”Kalle Kula”, height: 178, age: 26. Ändra sedan på objektets name till Pelle Kula. Skriv sedan ut hela objektet till konsolen.

## Fråga 7 - Array/Lista

**7a)**  
 Skapa en array med siffrorna 1 till 10. Skriv sedan ut talet 3 och 7 med hjälp av arrayen dvs använd rätt index för att få ut talet 3 och 7.  
**7b)**  
Skapa sedan en for-loop som loopar igenom arrayen och skriver ut varje tal till konsolen. Använd length för att få arrayens längd.

## Fråga 8 - Html + CSS + JavaScript

1. Du har ett input fält och en knapp till ditt förfogande, under det finns det en div-tagg som du ska tilldela färgen som du skriver in i fältet efter att ha klickat på knappen.
2. Skapa en funktion som du kopplar till knappen.
3. Hämta input-taggen i funktionen och dess värde.
4. Hämta div-taggen i funktionen.
5. Tilldela div-taggen bakgrundsfärgen dvs input fältets värde.

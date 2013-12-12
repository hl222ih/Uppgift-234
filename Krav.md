Kravspecifikation Kommunikationsapp
Referenser
[Vision](länk)
Aktörer
Primära aktörer
Brukaren
Assistenter (utveckling)
Assistenter (användning)
Utvecklare

Stödjande aktörer
Specialpedagogiska skolmyndigheten
Tillhandahåller de vanligaste blisstecknen och teckenillustrationerna.

Funktionella Krav
F1 Sidmallar
Sidmallar styr utseendet (rutornas storlek, färg och position) och tillhandahåller hock-ups för funktion (id). Dessa mallar ska kunna bytas ut av användaren. Det ska gå att ställa in om mallarna ska vara begränsade till en sida eller om de ska kunna utökas till fler.
F2 Rutor
Det ska gå att koppla innehåll (blisstecken, teckenspråksillustrationer och fotografier) till rutorna. Varje ruta ska motsvara en rad i en databas där informationen lagras.
F3 Blisstecken/Teckenspråksillustrationer/Fotografier
Det ska gå att göra specifika inställningar (ex.vis ändra  bakgrundsfärg, text, textposition) för de enskilda blisstecknen, teckenspråksillustrationerna och fotografierna. Blisstecken behöver en extra inställning för ordklass som styr standardbakgrundsfärg. Informationen om blisstecknen, teckenspråksillustrationerna och fotografierna ska lagras i tre olika databaser, så att även en bild kan bytas ut, men att övriga inställningar sparas.
F4 Spara kommunikationen.
Det ska gå att markera om det som kommuniceras tillfälligt ska lagras eller inte. Kommunikationen som lagrats ska kunna visas med huvudsymbolen och tillhörande text. Den tillhörande texten ska kunna redigeras. En symbol med tillhörande text ska kunna tas bort från den sparade kommunikationen.  En kommunikation ska lagrats ska kunna sparas till en fil eller skickas via mejl. En tidigare sparad kommunikation ska kunna öppnas från en fil.
F5 Backup
Det ska gå att utföra en backup av all information till molnet och det ska gå att återställa informationen från tidigare gjord backup.
Icke-funktionella Krav
Navigeringen i appen ska vara användarvänlig med beaktande av följande punkter.
Det ska vara intuitivt och enkelt att navigera med en hand.
Onödiga moment ska minimeras genom att nödvändig funktionalitet ska nås där den är relevant.
Svepningsrörerelser och touchningar ska i huvudsak användas för navigering.
Begränsningar
B1 Implementation
Appen ska utvecklas med hjälp av HTML5 som grund för att göra det möjligt att enkelt portera till olika plattformar. Eftersom appen har viss plattformsberoende funktionalitet behöver det från HTML5-koden gå att skapa en Hybrid-app.
B2 Databaser
Databasen för grundfunktionaliteten måste vara klientbaserad, så att appen kan användas även utan direktuppkoppling till nätet.
Kvalitetskrav
Användbarhet
Anv 1. Grafisk utformning
Färger ska vara noga genomtänkta för underlätta förståelse och ge bra kontrast för att underlätta både för brukaren och assistenten vid användning. 
Tillgänglighet
Tillg. 1 Tillgänglighet
Appen ska kunna användas utan uppkoppling till internet.
Stödbarhet
Stödb. 1 Stödbarhet
Appen ska stödjas av surfplattor av olika fabrikat. Åtminstone Ipad och Android.
Användningsfall
1 Brukaren (med hjälp av assistenten)
AF1.1 
AF1.2
2 Assistenten (utveckling)
AF2.1
AF2.2
3 Utvecklare
AF3.1

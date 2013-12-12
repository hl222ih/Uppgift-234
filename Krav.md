<link href="http://jasonm23.github.io/markdown-css-themes/markdown2.css" rel="stylesheet"></link>
# Kravspecifikation Kommunikationsapp #

### Referenser ###

- [Vision](Vision.md)

## Aktörer ##

### Primära aktörer ###

#### Brukare ####
Navigerar i appen genom att indikera var assistenten ska peka. Vill att appen ska vara lättförståelig och intuitiv och ge goda möjligheter att uttrycka sig på ett smidigt sätt. Vill också att appen ska ha ett tydligt användargränssnitt med tydliga kontraster.

#### Assistent ####
Kommunicerar med brukaren och hjälper brukaren att kommunicera med en själv eller med andra. Håller i surfplattan som kör appen och tolkar brukarens navigeringsval. Vill att appen ska svara snabbt på interaktion så att kommunikationen kan ske utan onödiga fördröjningar. Vill att appen ska innehålla relevanta och användbara funktioner.

#### Underhållsansvarig ####
Vill att assistenterna själva ska kunna utföra så mycket som möjligt. Dels blir hjälpmedlet mer användbart och dels minskar belastningen på underhållsansvarige. Underhållsansvariga kan vara vana assistenter och/eller pedagog på brukarens dagliga verksamhet med erfarenhet av användning och anpassning av hjälpmedel.

### Stödjande aktörer ###

#### Utvecklare ####
Kan fixa buggar, lägga till/ändra funktioner, skapar HTML/CSS-mallar m.m. Under utvecklingsfasen i huvudsak en av assistenterna. Tillhandahålls sedan om hjälpmedlet beviljas av hjälpmedelsförskrivare på Hjälpmedelscentralen.

#### Specialpedagogiska skolmyndigheten ####
Tillhandahåller de vanligaste blisstecknen och teckenillustrationerna. Vill ha en kopia på appen när den är klar, kanske som inspirationskälla för andra personer med funktionsnedsättning med liknande behov.

### Offstage-aktörer ###

#### God man ####
Vill att appen ska hålla god kvalitet för sin brukare och för att underlätta för brukarens assistenter. Vill att eventuella kostnader ska hållas nere.

#### Assistenternas arbetsgivare och brukarens uppdragsgivare ####
Vill att appen ska bidra till måluppfyllelse och underlätta rekrytering. Kan eventuellt tillhandahålla vissa resurser för produktutveckling och introduktionsutbildning.


## Funktionella Krav ##

### F1 Användning i kommunikation ###
Appens huvudsyfte är att den ska kunna användas för att kommunicera. Brukaren ska kunna säga något och på olika sätt få återkoppling till att kommunikationen har gått fram.  Assistenten ska,  om teckenspråkskunskaperna hos brukaren eller assistenten inte räcker till, kunna ställa en fråga och få svar från brukaren.

#### Användningsfall ####

##### Brukare #####
**AF 1.1.1** Säga något till assistenten eller till någon annan

##### Assistent #####

**AF 1.2.1** Ställa en fråga till brukaren

### F2 Sidmallar ###
Sidmallar styr utseendet (rutornas storlek, färg och position) och tillhandahåller hock-ups för funktion (id). Dessa mallar ska kunna bytas ut av användaren. Det ska gå att ställa in om mallarna ska vara begränsade till en sida eller om de ska kunna utökas till fler.

#### Användningsfall ####
##### Underhållsanvarig #####
AF 2.1.1 Byta sidmall
AF 2.1.2 Ändra inställningar för vald sidmall

### F3 Rutor ###
Det ska gå att koppla innehåll (blisstecken, teckenspråksillustrationer och fotografier) till rutorna. Varje ruta ska motsvara en rad i en databas där informationen lagras.

#### Användningsfall ####
##### Underhållsanvarig #####
AF 3.1.1 Koppla innehåll till en ruta
AF 3.1.2 Tömma en ruta på innehåll 

### F4 Blisstecken/Teckenspråksillustrationer/Fotografier ###
Det ska gå att lägga till, ta bort och göra specifika inställningar (ex.vis ändra  bakgrundsfärg, text, textposition) för de enskilda blisstecknen, teckenspråksillustrationerna och fotografierna. Blisstecken behöver en extra inställning för ordklass som styr standardbakgrundsfärg. Informationen om blisstecknen, teckenspråksillustrationerna och fotografierna ska lagras i tre olika databaser, så att även en bild kan bytas ut, men att övriga inställningar sparas. Fotografier som läggs till ska det skapas miniatyrer till.

#### Användningsfall ####
##### Underhållsanvarig #####
AF 4.1.1 Lägga till ett blisstecken i databasen
AF 4.1.2 Ta bort ett blisstecken i databasen
AF 4.1.3 Lägga till en teckenspråksillustration i databasen
AF 4.1.4 Ta bort en teckenspråksillustration i databasen
AF 4.1.5 Lägga till ett fotografi i databasen
AF 4.1.6 Ta bort ett fotografi i databasen
AF 4.1.7 Ändra beskrivning av ett blisstecken, en teckenspråksillustration eller ett fotografi i databasen.

### F5 Spara kommunikationen. ###
Det ska gå att markera om det som kommuniceras tillfälligt ska lagras eller inte. Kommunikationen som lagrats ska kunna visas med huvudsymbolen och tillhörande text. Den tillhörande texten ska kunna redigeras. En symbol med tillhörande text ska kunna tas bort från den sparade kommunikationen.  En kommunikation som har lagrats ska kunna sparas till en fil eller skickas via mejl. En tidigare sparad kommunikation ska kunna öppnas från en fil.

#### Användningsfall ####
##### Brukaren #####
AF5.1.1 Ändra så kommunikationen sparas/inte längre sparas
AF5.1.2 Spara en kommunikation.
AF5.1.3 Ladda en tidigare sparad kommunikation.
AF5.1.4 Skicka aktuell kommunikation i ett e-postmeddelande.

### F6 Backup ###
Det ska gå att utföra en backup av all information till molnet och det ska gå att återställa informationen från tidigare gjord backup.

#### Användningsfall ####
##### Underhållsanvarig #####
AF5.1.1 Skapa en backup.
AF5.1.2 Återställa från backup.

## Icke-funktionella Krav ##
### Projektkrav ###
- Navigeringen i appen ska vara användarvänlig med beaktande av följande punkter.
- Det ska vara intuitivt och enkelt att navigera med en hand.
- Onödiga moment ska minimeras genom att nödvändig funktionalitet ska kunna nås där den är relevant.
- Svepningsrörerelser och touchningar ska i huvudsak användas för navigering.
- Prioritering ska läggas på att appen är snabb att använda. Fotografier i full upp lösning ska inte laddas i onödan.
- Rutorna har en viss ratio mellan höjd/bredd. Bara en del av den tillgängliga höjden på rutan får användas av blisstecknet/teckenspråksillustrationen/fotografiet. Inställningar för detta ska kunna göras.  Blisstecken, teckenspråksillustrationer och fotografier ska alltid skalas på ett dimensionsenligt sätt. 

### Begränsningar ###
#### B1 Implementation ####
Appen ska utvecklas med hjälp av HTML5 som grund för att göra det möjligt att enkelt portera till olika plattformar. Eftersom appen har viss plattformsberoende funktionalitet behöver det från HTML5-koden gå att skapa en Hybrid-app.

#### B2 Databaser ####
Databasen för grundfunktionaliteten måste vara klientbaserad, så att appen kan användas även utan direktuppkoppling till nätet.

## Kvalitetskrav ##
### Användbarhet ###
#### Anv 1. Grafisk utformning ####
Färger ska vara noga genomtänkta för underlätta förståelse och ge bra kontrast för att underlätta både för brukaren och assistenten vid användning. 

### Tillgänglighet ###
#### Tillg. 1 Tillgänglighet ####
Appen ska kunna användas utan uppkoppling till internet.

### Stödbarhet ###
#### Stödb. 1 Stödbarhet ####
Appen ska stödjas av surfplattor av olika fabrikat. Åtminstone Ipad och Android.


<link href="http://jasonm23.github.io/markdown-css-themes/markdown2.css" rel="stylesheet"></link>
# Användningsfall Kommunikationsapp #
##F1.1.1 - Säga något till någon ##

Brukaren har precis påkallat uppmärksamhet att hen vill använda appen för att säga något. Hen vill säga till sin assistent att hen vill ha kaffe. Brukaren visar med tungan hur han vill navigera i appen medan assistenten återkopplar de ord brukaren väljer.

### Primär Aktör ###

Brukaren. Väljer vad han med appens hjälp vill säga. Bekräftar det assistenten visar med teckenspråk, att de valda tecknena är korrekt uppfattade.

### Sekundär Aktör ###

Assistenten. Läser av brukarens val och hjälper brukaren att manövrera appen. Återkopplar vad brukaren har sagt med teckenspråk.

### Offstage-aktör ###

Inga.

### Förkrav ###

Brukaren har påkallat uppmärksamhet och assistenten har tagit fram surfplattan och startat appen och kommunikationen har börjat. En ny sida har just laddats med rutor innehållande blisstecken. Rutorna är antingen "ord"-rutor eller "kategori"-rutor.

### Efterkrav ###

Appen befinner sig återigen på valfri sida i navigationen med rutor.

## Huvudscenario ##
1. Brukaren indikerar ett val av en ”ord”-ruta.<br />
2. Assistenten touchar rutan.<br />
3. Rutans innehåll förstoras.<br />
4. Brukare bekräftar att valet är korrekt.<br />
5. Assistenten tecknar ordet på teckenspråk.<br />
6. Brukaren bekräftar att ordet hen ville uttrycka är korrekt.<br />
7. Assistenten touchar det förstorade innehållet.<br />
8. Appen återgår till startsidan i navigationen.<br />

## Alternativa Scenarion ##
1a. Brukaren indikerar ett val av en ”kategori”-ruta.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.	Kategorirutan förstoras.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.	Brukaren bekräftar att valet är korrekt.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.	Appen visar sidan som är kopplad till ”kategori”-rutan.<br />
1a. 1a. Kategorirutan har inställningen att den inte ska förstoras, utan går direkt och visar sidan som är kopplad till ”kategori”-rutan.<br />
1a. 2a. Brukaren indikerar att valet är felaktigt.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Assistenten touchar "stäng"-knappen.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Appen stänger den förstorade rutan.<br />
1b. Ordet eller kategorin finns inte med på sidan som visas.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Brukaren indikerar att hen vill återgå till föregående meny.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Assistenten gör en sveprörelse över sidan.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Appen återgår till föregående meny.<br />
1b. 1a. Brukaren ser att hen är på en "multi-sida" och vill bläddra vidare på den.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Brukaren indikerar att hen vill gå till nästa sida på "multi"-sidan.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Assistenten gör en sveprörelse över sidan.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. Appen visar nästa sida på "multi"-sidan.<br />
4a. Brukaren indikerar att valet var felaktigt<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Assistenten touchar utanför det förstorade innehållet.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Appen stänger det förstorade innehållet.<br />
5a. Brukaren valde en kategori. Kategorier behöver inte tecknas.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gå till 7.<br />
5b. Assistenten är osäker på hur ordet tecknas med teckenspråk.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Assistenten ser att det finns en tillgänglig teckenspråksillustration.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2. Assistenten gör en sveprörelse på det förstorade innehållet.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.	Appen visar teckenspråksillustrationen som är kopplad till blisstecknet.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4.	Assistenten touchar utanför det förstorade innehållet.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4. Appen stänger det förstorade innehållet.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gå till 5.<br />
5b. 3a. Det finns flera olika teckenspråksillustrationer kopplade till samma blisstecken.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.	Assistenten gör en sveprörelse för att se ”nästa” teckenspråksillustration.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Gå till 5b. 4.<br />
6a. Brukaren kommer på när assistenten tecknar ordet, att det valda ordet inte var korrekt.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.	Brukaren indikerar att det valda ordet är inkorrekt.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.	Assistenten touchar utanför det förstorade innehållet.<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.	Appen stänger det förstorade innehållet.
    


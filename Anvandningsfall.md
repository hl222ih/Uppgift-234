<link href="http://jasonm23.github.io/markdown-css-themes/markdown2.css" rel="stylesheet"></link>
# Användningsfall F1.1.1 #
# - Säga något till assistenten eller till någon annan #

Brukaren har precis påkallat uppmärksamhet att hen vill använda appen för att säga något. Hen vill säga till sin assistent att hen vill ha kaffe. Brukaren visar med tungan hur han vill navigera i appen medan assistenten återkopplar de ord brukaren väljer.

### Primär Aktör ###

Brukaren. Väljer vad han med appens hjälp vill säga. Bekräftar det assistenten visar med teckenspråk, att de valda tecknena är korrekt uppfattade.

### Sekundär Aktör ###

Assistenten. Läser av brukarens val och hjälper brukaren att manövrera appen. Återkopplar vad brukaren har sagt med teckenspråk.

### Offstage-aktör ###

Inga.

### Förkrav ###

Brukaren har påkallat uppmärksamhet och assistenten har tagit fram surfplattan och startat appen, som nu befinner sig vid huvudmenyn.

### Efterkrav ###

Appen befinner sig återigen vid huvudmenyn.

## Huvudscenario ##
1. Brukaren indikerar blisstecknet för kategorin "personer".
2. Assistenten touchar blisstecknet för kategorin "personer". Blisstecknet förstoras på skärmen så att brukaren kan se blisstecknet tydligt.
3. Brukaren bekräftar att valet är korrekt.
4. Assistenten touchar det förstorade tecknet. Appen navigerar till sidan med "personer".
5. Brukaren indikerar tecknet för "jag".
6. Assistenten touchar blisstecknet för "jag". Blisstecknet förstoras på skärmen.
7. Brukaren bekräftar att valet är korrekt.
8. Assistenten tecknar teckenspråkstecknet för "jag".
9. Brukaren bekräftar att det var "jag" hen menade.
10. Assistenten touchar det förstorade tecknet. Appen navigerar till huvudmenyn.
11. Brukaren indikerar kategorin "göra".
12. Assistenten touchar blisstecknet för kategorin "göra". Blisstecknet förstoras på skärmen.
13. Brukaren bekräftar att valet är korrekt.
14. Assistenten touchar det förstorade tecknet. Appen navigerar till sidan med innehållet för kategorin "göra".
15. Det brukaren vill säga finns inte med på skärmen så brukaren indikerar att hen vill bläddra till nästa sida.
16. Assistenten gör en sveprörelse på skärmen. Appen bläddrar till nästa sida.
17. Brukaren indikerar blisstecknet för "dricka".
18. Assistenten touchar blisstecknet för "dricka". Blisstecknet förstoras på skärmen.
19. Brukaren bekräftar att valet är korrekt.
20. Assistenten tecknar teckenspråkstecknet för "dricka".
21. Brukaren bekräftar att det var "dricka" hen menade.
22. Assistenten touchar det förstorade tecknet. Appen navigerar till huvudmenyn.
23. Brukaren indikerar blisstecknet för kategorin "drycker".
24. Assistenten touchar blisstecknet för kategorin "drycker". Appen navigerar till sidan med "drycker".
25. Brukaren indikerar blisstecknet "kaffe".
26. Assistenten touchar blisstecknet för "kaffe". Blisstecknet förstoras på skärmen.
27. Brukaren indikerar att valet är korrekt.
28. Assistenten tecknar teckenspråkstecknet för "kaffe".
29. Brukaren bekräftar att det var "kaffe" hen menade.
30. Assistenten touchar det förstorade tecknet. Appen navigerar till huvudmenyn.
</nocode>
## Alternativa scenarion ##
18a. Assistenten touchar det närliggande blisstecknet "äta". Blisstecknet förstoras på skärmen.
<p style="padding-left:45px;">
	1. Brukaren indikerar att valet är felaktigt.<br />
	2. Assistenten touchar "X-knappen". Appen tar bort det förstorade tecknet.<br />
	Gå till 17.
</p>
18b. 18a.1a Brukaren indikerar att valet är korrekt.
<p style="padding-left:45px;">
    2. Assistenten tecknar teckenspråkstecknet för "äta".<br />
    3. Brukaren indikerar att det *inte* var vad hen ville säga.<br />
    Gå till 16a. 2.
</p>
28a. Assistenten minns inte riktigt hur "kaffe" tecknas på teckenspråk. Assistenten ser att det finns en teckenspråksillustration och gör en sveprörelse på blisstecknet för "kaffe".
<p style="padding-left:45px;">
1. Appen visar en teckenspråksillustration på hur man tecknar "kaffe".<br />
2. Assistenten gör en sveprörelse på teckenspråksillustrationen. Appen återgår till det förstorade blisstecknet.<br />
3. Gå till 29.
</p>
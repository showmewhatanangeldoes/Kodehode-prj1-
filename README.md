KODEHODE / MIN FØRSTE NETTSIDE

1. HTML: innholdet på siden
2. CSS: farger og utseende
3. Slik lager du nettsiden

1. Prosjektmappen
Lag en mappe som heter test_project, for eksempel i Dokumenter. Hvis du allerede har en mappe med
dette navnet, lag en ny mappe: dyr_project.
2. Mappen i VS Code
Åpne VS Code. Velg File > Open Folder…, finn mappen og velg Select Folder. Mappen vises i Explorer
til venstre.
3. Live Server
Klikk på Extensions til venstre. Søk etter Live Server fra Ritwick Dey og klikk Install. Hopp over dette
hvis den er installert.
4. HTML-filen
Klikk på New File i Explorer. Kall filen index.html. Skriv koden på ark 1. Lagre med Ctrl + S.
5. CSS-filen
Lag en ny fil i samme mappe: style.css. Skriv koden på ark 2 og lagre. Linjen med link i HTML kobler
CSS-filen til nettsiden.
6. Bildet
Finn et gratis bilde av en hund eller katt, for eksempel på pixabay.com. Klikk Free download. Velg et
bilde i PNG-format, kall det dyr.png og legg det i samme mappe som index.html.
7. Nettsiden i nettleseren
Åpne index.html i VS Code og klikk Go Live nederst. Du kan også høyreklikke i filen og velge Open with
Live Server.
8. Kontroll
Ser du gul bakgrunn, grønn overskrift og bilde? Hvis CSS mangler, sjekk href="style.css". Hvis bildet
mangler, sjekk src="dyr.png". Lagre begge filene.
9. Din egen versjon
Endre overskriften eller et avsnitt. Bytt lightyellow til lightblue i CSS. Lagre og se hva som skjer. Endre
én ting om gangen.
10. GitHub og levering
Opprett et tomt repository på GitHub, uten README. I VS Code: Terminal > New Terminal. Kjør én linje
om gangen i prosjektmappen:
git init
git add .
git commit -m "Min første nettside"
git branch -M main
git remote add origin DIN_REPOSITORY_URL
git push -u origin main
Bytt DIN_REPOSITORY_URL med HTTPS-lenken fra Code på GitHub, for eksempel
https://github.com/brukernavn/test_project.git. Send lenken til repositoryet på Discord.
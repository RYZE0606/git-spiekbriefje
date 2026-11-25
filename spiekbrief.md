# Spiekbrief Git en GitHub, versie van mijn laptop.

## 1. Clone, commit, push en pull
Met clone haal je een project van GitHub voor het eerst als een kopie naar jouw eigen pc. Met commit leg je jouw aanpassingen lokaal vast als een soort savepoint met een kort berichtje wat je hebt veranderd. Met push stuur je die lokale wijzigingen van jouw pc naar GitHub, zodat je team of back-up ze ook heeft. Met pull haal je juist nieuwe wijzigingen van GitHub naar jouw eigen pc, zodat jouw lokale map weer helemaal bij is.

## 2. Commit bericht
Een goed commitbericht is bijvoorbeeld "Knop om in te loggen toegevoegd" en een slecht bericht is gewoon "aanpassing". Dat eerste bericht is veel beter omdat je achteraf meteen ziet wat er precies veranderd is, terwijl je bij een vaag woord heel je code opnieuw moet gaan bekijken om te snappen wat je hebt gedaan.

## 3. Gitignore
Een .gitignore-bestand zorgt ervoor dat Git bepaalde bestanden en mappen negeert, zodat rommel zoals .DS_Store, *.zip en *.log niet zomaar op GitHub terechtkomt.

## 4. Pull

Met een pull heb ik de nieuwe aanpassingen van GitHub naar mijn eigen pc binnengehaald, zodat het bestand hier ook weer bijgewerkt is. Aan het begin van elke les pull je eerst zodat je altijd verder werkt in de nieuwste versie en geen conflicten of fouten krijgt met wat eerder is aangepast.

## 5. Terugdraaien
Bij een revert draai je een commit terug door er een nieuwe commit bovenop te zetten die de fout ongedaan maakt, waardoor de foute commit zelf gewoon in de geschiedenis blijft staan en je precies ziet wat er is gebeurd.

## 6. Branches en pull requests
Een branch is een aparte tak van je project waarin je rustig aan iets nieuws of een aanpassing werkt zonder de rest stuk te maken. De main-branch blijft altijd de werkende versie zodat je zeker weet dat de basis stabiel is en niet breekt door half afgewerkte code. Een pull request is een verzoek op GitHub om jouw wijzigingen uit een branch samen te voegen met main, zodat je ze eerst nog even kunt nakijken of laten checken voor ze erbij komen.
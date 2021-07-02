# Eindopdracht-set
Dit is onze eindopdracht voor het vak programmeren voor wiskunde. Het programma dat wij hiervoor geschreven hebben, laat je een variant op het kaartspel set spelen, tegen de computer.
# Spelregels
De spelregels van deze variant zijn als volgt: Er liggen 12 kaarten op tafel. De speler heeft telkens een vaste tijd, die hij vooraf in kan voeren, om een set van 3 kaarten te vinden. Zo'n set moet aan de volgende voorwaarden voldoen: het bestaat uit 3 kaarten en voor elk van de vier eigenschappen van de figuurtjes op de kaarten (kleur, opvulling, aantal of vorm) moet gelden dat alldrie de kaarten overeenkomen wat betreft die eigenschap, of dat ze alledrie verschillen van elkaar wat betreft die eigenschap. Een geldige set kan dus zijn: kaart1 = 3 rode gevulde ovalen; kaart2 = 3 rode gevulde ruitjes; en kaart3= 3 rode gevulde golfjes. Als de speler er in slaagt zo'n set te vinden, typt hij/zij het kaartnummer van de eerste kaart in en drukt op enter, daarna hetzelfde voor de tweede en de derde. Indien de drie kaarten inderdaad een set vormen, krijgt de speler een punt. De kaarten worden dan vervangen door kaarten uit de pot en de timer start opnieuw. Als het geen geldige set was, gebeurt er niets en gaat het spel gewoon door. Indien de speler er niet in slaagt om binnen de tijd een set te vinden, kunnen er 2 dingen gebeuren: als er wél een set op tafel lag, krijgt de computer een punt, worden de kaarten van de set vervangen en start de timer opnieuw. Als er géén set op tafel lag, dan krijgt niemand een punt en worden kaart 1 t/m 3 vervangen op de hoop dat er vervolgens wel een set te vinden is. Het spel is afgelopen zodra de pot op is én er geen set meer te vinden is. Degene met de meeste punten (computer of speler) wint.
# Benodigde documenten
Het programma is voor de overzichtelijkheid opgesplitst in twee .py documenten:
* 'set.py' waarin vrijwel alle klassen, functies en algoritmes gedefiniëerd worden.
* 'set_display.py', waarin de nadruk ligt op de werking van het computerprogramma: het creëren van een venster, het weergeven van afbeeldingen, het uitvoeren van alle functies etc.

Ook zijn nodig:
* De map 'kaarten', met daarin 82 .gif bestanden, één voor elke kaart uit het spel en een zwarte kaart voor als er geen kaarten meer aangevuld kunnen worden.
* 'Arial.ttf', waarin het lettertype arial opgeslagen is. We ondervonden namelijk dat het lettertype arial dat in je systeem opgeslagen is, licht kan verschillen per computer.
# Het spel spelen
Om het spel te spelen, moet je allevier de bovengenoemde bestanden in dezelfde map hebben gedownload. Dit kun je eenvoudig doen door het bijgevoegde .zip-bestand te downloaden en uit te pakken. Ook moet je python geïnstalleerd hebben, of een omgeving zoals Spyder die python-code kan runnen. De allerlaatste stap is het installeren van de python library 'pygame'. Dit doe je door in de windows command prompt (dit kan trouwens ook in bijvoorbeeld de anaconda command prompt) in te typen 'pip install pygame'. Zodra je dit allemaal gedaan hebt, kun je het spel spelen door het programma 'set_display.py' uit te voeren.

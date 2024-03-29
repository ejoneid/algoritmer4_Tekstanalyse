# algoritmer4_Tekstanalyse
Dette er min løsning av den 4. obligatoriske oppgaven i faget "Algoritmer og datastrukturer" på Høgskolen i Østfold.

## Oppgavetekst
Forskjellige forfattere bruker ofte de samme ordene, men med varierende hyppighet. Denne oppgaven går ut på å lese en tekst og registrere alle ordene som forekommer i teksten i et binært søketre.

Skriv et program som leser tekst fra en fil (eller fra standard input) og deler teksten opp i forskjellige ord. Et ord regnes å bestå bare av bokstaver, og et ord er slutt når det kommer et tegn som ikke er en bokstav. Gjør om alle bokstavene i hvert ord til en stor bokstav, slik at det ikke blir forskjell på ord som kommer i begynnelsen av en setning og ord som kommer inne i en setning.

Hvert ord som leses fra teksten skal legges inn i et binært søketre som initiellt er tomt. Hvis ordet allerede finnes fra før, skal det ikke settes inn på nytt, men en teller i noden som registrerer antall forekomster av ordet skal oppdateres.

Etter at hele teksten er lest skal alle ordene som forekom skrives ut i alfabetisk rekkefølge, sammen med antallet ganger ordet forekom. Hvis treet er riktig bygd opp er det lett å skrive ut ordene i alfabetisk rekkefølge ved å traversere treet på en bestemt måte.

Skriv hele programmet fra bunnen av, inkludert koden for innsetting av noder i søktreet.

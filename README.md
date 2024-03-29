# Word Frequency Checker
Programmet kollar hur frekvent ord förekommer och retunrerar 10 mest använda orden ur en textmassa samt antalet gånger de förekom

## Information

Java version 17
Maven
Spring boot


### Installation

* Ladda ner zip filen från github: https://github.com/Niqqo93/assignment/archive/refs/heads/main.zip
* Packa upp mappen någonstans på datorn
* --- Om inte har ett program för att packa upp filer som är zipade rekommenderar jag winrar: https://www.rarlab.com/download.htm ---
* Öppna mappen med ett IDE, till exempel IntelliJ: https://www.jetbrains.com/idea/?var=1
* Kör programmet genom att trycka på den gröna pilen längst upp till höger, alternativt tryck SHIFT + F10 för att starta
* Ladda ner och installera POSTMAN för att testa skicka textsträngar till applikationen: https://www.postman.com/

#### Testa programmet

* För att testa programmet öppna upp Postman
* Skapa en ny request av typen POST
* I adressfältet fyll i: http://localhost:4500/api/v1/sort/topTopMostFrequentWords
* Under adressfältet välj fliken "Body"
* Välj sedan "raw" och längst till höger på samma rad välj "Text".

* Det går nu att fylla i text i den stora rutan och klicka på "Send" så kommer ett svar tillbaka med de 10 mest förekommande orden i strängen du skickat in.


## Skriven av

Sebastian Granlund

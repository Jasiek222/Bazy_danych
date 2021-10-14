# The Data Appendix:

Po przetworzeniu danych z pliku "billboard.csv" otrzymujemy uporządkowane dane, dzięki czemu analiza rankingu najpopularniejszych utworów w ciągu 2000 roku jest znacznie łatwiejsza. Wsystkie zmienne zostały zaimportowane z jednego pliku billboard.csv, jednak dla lepszej czytelności zostały zmienione nazwy zmienny, oraz truktura tabeli.

Zatem dla nowych danych mamy zmienne:

- artist - nazwa artysty, zespołu będącego twórcą i wykonawcą utworu,
- track - nazwa utworu,
- time - czas trwania piosenki,
- genre - rodzaj muzyki do jakiej należy ten utwór,
- date_entered - data wejścia na listę rankingu, format daty: rrrr-mm-dd
- date_peaked - data osiągnięcia najwyższego miejsca w rankingu, format daty: rrrr-mm-dd
- num_week - numer tygodnia od wejścia na listę rankingu danej piosenki,
- place - miejsce w rankingu w obecnym tygodniu od wejścia na listę rankingową.

Z orginalnych danych znikneła kolumna o nazwię 'year' ze względu na fakt, że obecne dane w całości odnoszą się do rankingu z 2000 roku, zatem ta informacja jest zbędna.
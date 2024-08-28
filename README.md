# WHALE TALK (limbajul balenelor)

Să luăm o frază, de exemplu „turpentine and turtles” și s-o traducem în echivalentul său în „limbaj de balenă”: „UUEEIEEAUUEE”.
Există câteva reguli simple pentru traducerea textului în limbajul balenelor:
1.	Nu există consoane. Doar vocale, excluzând „y”.
2.	„U”-urile și „e”-urile sunt extra lungi, așa că trebuie să le dublăm în programul nostru.
Odată ce am convertit textul în limbajul balenelor, rezultatul este cântat încet, așa cum este un obicei în ocean.
Pentru a realiza această traducere, putem folosi cunoștințele noastre despre bucle. Să începem!

1. Creați o variabilă numită input care este egală cu orice frază doriți. Această variabilă va conține textul pe care doriți să îl traduceți în „limbaj de balenă”.
2. Balenele vorbesc doar cu vocalele „a”, „e”, „i”, „o” și „u”. Folosind aceste litere mici, creați un array numit vowels. Acest array nu va fi actualizat, așa că asigurați-vă că alegeți cuvântul cheie de declarație potrivit.
Notă: Utilizarea acestui array va fi mai evidentă în următorii pași.
3. Creați o variabilă numită resultArray și setați-o egală cu un array gol: []. Aceasta va servi ca loc pentru a stoca vocalele din stringul input.
4. Creați un loop pentru a itera prin fiecare literă a textului din variabila input. Într-un pas ulterior, vom compara fiecare literă cu array-ul nostru vowels.
5. Pentru a verifica munca dvs., logați poziția iteratorului numerată în interiorul la for loop și rulați codul. Acest lucru ar trebui să numere numărul de caractere din stringul dvs. input.
Comentați acest cod când sunteți gata să treceți mai departe.
6. Creați un ciclu for imbricat în interiorul ciclului for pe care tocmai l-ați scris. Faceți ca ciclul intern să itereze prin array-ul vowels de fiecare dată când se execută ciclul extern.
Acest lucru vă va permite să verificați fiecare literă din input față de toate elementele vowels în timpul fiecărei iterații.
7. Pentru a verifica munca dvs., logați pozițiile iteratorului numerate în interiorul ciclului for intern și rulați codul. Ar trebui să vedeți 0 până la 4 repetat, deoarece vowels are 5 elemente.
8. În interiorul celei de-a doua for loop, scrieți un bloc de cod care compară litera input cu fiecare literă din array-ul vowels.
Notă: Pentru a verifica dacă totul funcționează corect, logați potrivirile literelor în consolă.
9. Acum, în loc să logați doar literele, adăugați-le la array-ul results.
Notă: Pentru a verifica munca dvs., utilizați console.log() pentru a imprima resultArray. Literele pe care le-ați logat în consola din pasul 8 ar trebui să fie acum incluse în resultArray.
10. Balenele își dublează „e”-urile și „u”-urile în limbajul lor.
Scrieți o instrucțiune if care verifică dacă fiecare literă din șirul input este egală cu „e”. Dacă da, utilizați metoda .push() pentru a adăuga input[i] la resultArray.
Notă: Această instrucțiune aparține înainte de blocul for loop intern din for loop extern. Acest lucru se datorează faptului că doriți să efectuați această verificare doar o dată pentru fiecare literă din input.
11. În continuare, doriți să dublați litera „u”.
12. În partea de jos a programului, logați resultArray în consolă.
13. În prezent, resultArray emite un array de caractere. Pentru a produce un limbaj de balenă adecvat, dorim să capitalizăm elementele array-ului și să le punem împreună ca un singur string.
Declarați o variabilă resultString care unește resultArray într-un singur string și capitalizează toate literele sale.
14. Rulați programul și cântați cu voce tare ieșirea – vorbiți oficial limba balenelor!
Notă: Pentru a confirma, dacă modificați valoarea lui input la „turpentine and turtles”, versiunea de balenă ar fi: „UUEEIEEAUUEE”.

# AlphaBlending

Opis programu :<br /><br />
Program łączy ze sobą dwa obrazki w pewien szczególny sposób. Obrazki przenikają się na zmianę. Współczynnik krycia (alfa) jest obliczany funkcją sinus, której argumentem jest odległość danego punktu od punktu położenia myszki. Program wykorzystuje funkcję napisaną w języku asemblerowym intel x86-64. Nie uwzględniłem paddingu, a co za tym idzie obazki muszą mieć szerokość i wysokość podzielną przez 4.

Uruchomienie programu w środowisku linux :
1) pobierz plik zip 
2) rozpakuj
3) zainstaluj bibliotekę allegro 4<br />
 sudo apt-get install build-essential<br />
 sudo apt-get install liballegro4.2-dev
4) w konsoli przejdź do folderu z rozpakowanym plikiem i wykonaj polecenie 'make'
5) uruchom powstały program 'fun' (wykonaj polecenie ./fun)
6) zakończenie działania programu -> ESC

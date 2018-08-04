# WashingMachineEmbeddedC
Create a C program for a washing machine simulation using Arduino
Tema 7
Se cere sa automatizati o masina de spalat rufe.
Componentele principale ale masinii de spalat sunt:
- Pompa de incarcare cu apa (poate fi pornita sau oprita)
- Pompa de evacuare a apei (poate fi pornita sau oprita)
- Rezistorul de incalzire a apei (poate fi pornit sau oprit)
- Motorul care controleaza rotatia cuvei (poate fi controlata directia de rotire si viteza de rotire)
- Valva de admisie a detergentului (poate fi deschisa sau inchisa)
- Valva de admisie a detergentului pentru prespalare (poate fi deschisa sau inchisa)
- Senzor pentru masurarea temperaturii apei (analogic)
- Senzor pentru masurarea vitezei de rotatie a cuvei (numarare impulsuri)
- LED semnalizare program in curs de desfasurare
- LED semnalizare incalzire apa in curs
- Memorie pentru inregistrarea parametrilor de functionare (Conectata prin SPI)
- Interfata de service pentru citirea parametrilor inregistrati (RS232)
Programele pe care masina de spalat trebuie sa le suporte sunt urmatoarele:
- Spalare rufe sensibile (timp de spalare 30 de minute – temperatura maxima a apei 30 de grade)
- Spalare la 40 de grade (timp de spalare 60 de minute – temperatura maxima a apei 40 de grade)
- Spalare la 90 de grade (timp de spalare 90 minute – temperatura maxima a apei 90 de grade)
- Spalare cu apa rece (timp de spalare 45 de minute – temperatura maxima a apei 25 de grade)
Functii aditionale care se pot adauga tuturor programelor de spalare:
- Fara stoarcere
- Stoarcere suplimentara
- Clatire suplimentara
- Prespalare
1. Descrieti perifericele unui microcontroler care trebuie folosite pentru a realiza fiecare functie in parte.
2. Incercati sa definiti cateva cerinte ale sistemului (system requirements). Fiecare cerinta trebuie sa
poata fi implementata intr-o secventa de cod si trebuie sa poata fi testata.
3. Creati o masina de stari pentru fiecare tip de program. Identificati blocurile comune din masinile de
stari create anterior astfel incat sa puteti crea componente software comune pentru diferite programe
de spalare.
4. Definiti structurile de date utilizate si interfetele functiilor software care urmeaza sa fie implementate.
5. Definiti o strategie de testare astfel incat sa va asigurati ca sistemul proiectat functioneaza.
6. Folositi GIT pentru versionare (atat cod cat si documente create). (Studiati sistemul de versionare git)
7. Studiati specificatiile SPI si UART
8. Folositi o structura de foldere pentru proiectul vostru asemanatoare cu cea prezentata mai jos:
WashingMachine
UsedDocuments
OwnDocuments
Test
Software
9. Folositi notiunile invatate anterior (variabile denumite explicit, cod comentat, functii simple etc.)
10. Implementati (in simulare sau pe platform embedded) sistemul proiectat.

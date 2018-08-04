# WashingMachineEmbeddedC

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

Tema 8
1. Configurati controlerul de UART sa transmita si sa receptioneze mesaje la o viteza de 9600 baud/sec.
Folositi o intrerupere atat pentru transmisia cat si pentru receptia fiecarui octet.
2. Configurati un timer al microcontrollerului astfel incat sa genereze un PWM cu factor de umplere
variabil. Factorul de umplere va fi modificat folosind interfata seriala configurata la punctul anterior.
Modificarea factorului de umplere a semnalului generat se va valida folosind un motor sau un LED si
vizualizand modificarea turatiei sau a luminozitatii in functie de configuratia aleasa.
3. Configurati ADC-ul microcontrolerului asfel incat sa poata masura o tensiune variabila pe un anumit
pin. Tensiunea va fi modificata folosind un potentiometru. Valoarea tensiunii masurate va fi transmisa
print interfata seriala configurata la punctul 1.
4. Folositi sistemul de versionare GIT in timpul dezvoltarii.
5. Creati module de software care sa poata fi reutilizate in completarea temei 7 (masina de spalat).
6. Folositi nume de variabile, functii si tipuri de date sugestive si adaptate conditiilor dintr-un sistem
embedded.
7. Studiati specificatia memoriei EEPROM a care foaie de catalog a fost transmisa pe Skype.
8. Studiati cursul privind circuitele integrate numerice. Pregatiti intrebari pentru urmatoarea sesiune.

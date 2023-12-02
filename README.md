## Testare-Manuala-Proiect-Final-Acreditare

#### Acest repository conține proiectul meu final de testare manuală pentru acreditare.
#### Proiectul evidențiază competențele în tehnicile de testare manuală. Prin utilizarea conceptelor și metodologiilor învățate, proiectul oferă oportunitatea de a demonstra abilitățile într-un context practic și de a obține experiență în testarea unei aplicații software în funcțiune.
#### Aplicația testată: [Aeris](https://demo.aeries.net/aeries/Login.aspx?demo=True&user=admin&pwd=admin)
#### Tool-uri utilizate: Jira, Zephyr Squad

## Specificaṭiile funcṭionale
#### Story-urile au fost create în JIRA și descriu specificațiile funcționale ale modulului Login, Daily Attendance Submission , Attendance By Photo si Scores By Class, pentru care se efectuează proiectul final.

![Gradebooks](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/assets/135150327/35dcbe29-d5a2-4396-8960-f80c400aa651)

## 1. Secțiune de Testare
### 1.1 **Planificarea Testelor**
#### Planul de teste descrie abordarea testării și structura generală care va ghida testarea aplicației [Aeris](https://demo.aeries.net/aeries/Login.aspx?demo=True&user=admin&pwd=admin)
#### Planul definește abordarea, obiectivele, domeniul de aplicare și rezultatele activităților de testare ale acestui proiect. 
#### Planul identifică elementele care vor fi testate, tipurile de teste care vor fi efectuate, personalul responsabil de testare, resursele necesare, programul și cronologia, precum și riscurile asociate planului.

1.1.1 *Criterii de intrare*:
  - Specificațiile funcționale sunt definite
  - Specificțiile non-funcționale sunt definite
  - Rolurile necesare pentru proiect sunt alocate
  - Definirea tool-urilor necesare
  - Alinierea echipelor de frontend si backend
   
1.1.2 *Criterii de iesire*:
  - Scripturile de test au fost executate
  - Defectele de prioritate majoră au fost închise
  - Toate rezultatele așteptate și reale sunt capturate și documentate cu scripturile de test
  - Toate defectele identificate au fost fixate fixate

1.1.3 *Scopul Testului*:
  - Tests in scope: toate funcționalitățile modulului Attendance, Attendance By Photo, Gradebook, definite în specificațiile cerințelor software trebuie testate: teste funcționale, teste GUI
  - Tests not in scope: teste de performanță, integrarea modulelor Attendance, Attendance By Photo, Gradebooks cu alte module, teste de compatibilitate cu alte browsere

1.1.4 *Riscuri detectate*:
- Riscuri de proiect:
    - Lipsa experienței în echipa de QA
    - Întârzieri în dezvoltare (resurse limitate, schimbări în cerințe, management de proiect necorespunzător),
    - Probleme tehnice (probleme de compatibilitate și performanṭӑ)
    - Resurse insuficiente(Limitări bugetare sau de personal pot afecta progresul proiectului)
- Riscuri de produs:
    - Securitatea datelor
    - Experiența utilizatorului (o experiență de utilizare sub așteptări, navigație complexă)
    - Interfețe confuze
    - Actualizări și întreținere (actualizarile pot fi imcompatibile cu versiunile mai vechi ale aplicației, pot introduce vulnerabilități de securitate)

1.1.5 *Evaluarea criteriilor de intrare*
#### Criteriile de intrare în faza de Planificare a Testului au fost îndeplinite și procesul de testare poate continua.

### 1.2 *Monitorizare și Control Testare*
#### Diverse rapoarte periodice au fost generate pentru a reflecta starea curentă a procesului de testare; în cazul problemelor majore, au putut fi luate măsuri de control.

![Test metrics](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/assets/135150327/b1c8fc85-3683-46de-b10c-243fac749e7c)

### 1.3 *Analiza Testelor*
#### Procesul de testare va fi executat pe baza cerințelor de mai sus pentru modulele Attendance și Gradebook Dashboard . Următoarele condiții de testare au fost identificate:
- Verificarea funcționalității funcțiilor de ștergere, editare, căutare și resetare în sistem.
- Validarea utilizabilității și feedback-ului vizual al butoanelor.
- Confirmarea manipulării corecte a scenariilor de creare și ștergere.
- Introducerea datelor doar pentru câmpurile obligatorii și verificarea că acestea sunt create/actualizate.
- Confirmarea faptului că userul poate selecta candidați și că starea lor este actualizată în consecință.
- Verificarea funcționalității de drag and drop, a butoanelor si icon-uri

### 1.4 *Design Testare*
#### Pentru dezvoltarea planului de testare(ce anume trebuie testat și realizarea scenariilor de testare) au fost create si utilizate urmatoarele epicuri: [Epic](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Epic.pdf)
#### Bazat pe analiza specificațiilor, Story-urile au fost create în Jira și pot fi vizualizate aici: [Story](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Story.pdf)
#### Test Cases

![Test Cases](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/assets/135150327/02f4a42a-ccd0-490d-913d-0e4a9d88397f)

#### Test case-urile pot fi vilzualizate aici: [Test Cases](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Zephyr%20Test%20Steps%20%2B%20Executions%20%2B%20Results%20(Jira).pdf)


### 1.5 *Implementare*
#### Următoarele elemente sunt pregatite pentru etapa de execuție a testelor:
- Mediul de testare este funcțional: [Aeries](https://demo.aeries.net/aeries/Login.aspx?demo=True&user=teacher990&pwd=teacher990)
- Accesul la mediul de testare este disponibil: Username: teacher990, Password: teacher990
- Cycle summary a fost creat
- Test case-urile au fost adăugate în Cycle summary


### 1.6 *Execuția Testelor*
- Cazurile de testare sunt create pe sumarul ciclului creat: [Cycle_summary](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Zephyr%20Test%20Steps%20%2B%20Executions%20%2B%20Results%20(Jira).pdf)  

- Bug-urile au fost create pe baza testelor eșuate. Rapoartele complete de bug-uri pot fi găsite aici: [Bugs](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Bugs.pdf)
    - Error message does not indicate that both fields are required
    - ‘Forgot Password’ button not available to recover password
    - Icons for either the username or password field are missing or not displayed consistently.
    - Absence of "All Remaining Students are Present" Button
    - Slow page loading and delayed filter option application
    - Missing pop-up on mouse hover


### 1.5 *Inchidere*
- Decizia cu privire la planurile de lansare va fi luată de PM în strânsă colaborare cu clientul și echipa de proiect
- Matricea de trasabilitate a fost generată și poate fi găsită aici: [Traceability Matrix](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Traceability%20Matrix.xlsx)
- A fost generat un grafic de execuție a testelor, iar raportul final arată că 6 teste au eșuat dintr-un total de 40.
- Au fost planificate 40 de cazuri de testare pentru execuție și toate au fost efectuate.
- Au fost găsite în total 6 bug-uri, dintre care prioritatea este: 1 - Critical, 1 - High, 3 -Medium, 1 - Low

![Test execution report by cycle](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/assets/135150327/8f4a3ab9-4bdd-4d60-a11c-7f55ad22566c)





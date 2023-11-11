## Testare-Manuala-Proiect-Final-Acreditare

### Acest repository contine conṭine proiectul meu final de testare manualặ pentru acreditare.
#### Proiectul evidenṭiazӑ compeṭelntele în tehnicile de testare manualӑ. Prin utilizarea conceptelor și metodologiilor învățate, proiectul oferă oportunitatea de a demonstra abilitățile într-un context practic și de a obține experiență valoroasă în testarea unei aplicații software în funcțiune.
#### Aplicatia testata: [Aeris](https://demo.aeries.net/aeries/Login.aspx?demo=True&user=admin&pwd=admin)
#### Tool-uri utilizate: Jira, Zephyr Squad

## Specificaṭiile funcṭionale
#### Story-urile au fost create în JIRA și descriu specificațiile funcționale ale modulului Login, Daily Attendance Submission , Attendance By Photo si Scores By Class, pentru care se efectuează proiectul final.

![Gradebooks](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/assets/135150327/55204aed-c3d8-43fe-85bb-05a793c9f482)

## 1. Secțiune de Testare
### 1.1 **Planificarea Testelor**
#### Planul de teste descrie abordarea testării și structura generală care va ghida testarea aplicației [Aeris](https://demo.aeries.net/aeries/Login.aspx?demo=True&user=admin&pwd=admin)
#### Planul definește abordarea, obiectivele, domeniul de aplicare și rezultatele activităților de testare ale acestui proiect. 
#### Planul identifică elementele care vor fi testate, tipurile de teste care vor fi efectuate, personalul responsabil de testare, resursele necesare, programul și cronologia, precum și riscurile asociate planului.

1.1.1 *Criterii de intrare*:
  - Specificațiile funcționale sunt definite
  - Rolurile necesare pentru proiect sunt alocate
  - Mediu de testare trebuie să fie în loc și pregătit pentru utilizare
  - Accesul la mediul de testare a fost furnizat echipei de testare
    
1.1.2 *Criterii de iesire*:
  - Scripturile de test au fost executate
  - Defectele de prioritate majoră au fost închise
  - Toate rezultatele așteptate și reale sunt capturate și documentate cu scripturile de test
  - Toate defectele au fost înregistrate

1.1.3 *Scopul Testului*:
  - Tests in scope: toate funcționalitățile modulului Attendance, Attendance By Photo, Gradebook, definite în specificațiile cerințelor software trebuie testate: teste funcționale, teste GUI
  - Tests not in scope: teste de performanță, integrarea modulelor Attendance, Attendance By Photo, Gradebooks cu alte module, teste de compatibilitate cu alte browsere

1.1.4 *Riscuri detectate*:
- Riscuri de proiect:
    - Lipsa experienței în echipa de QA
    - Întârzieri în dezvoltare (resurse limitate, schimbări în cerințe, management de proiect necorespunzător),
    - 	Mediu competitive
    - 	Resurse insuficiente(Limitări bugetare sau de personal pot afecta progresul proiectului)
- Riscuri de produs:
    - Documentație insuficientă sau neclară
    - Experiența utilizatorului (o experiență de utilizare sub așteptări, navigație complexă)
    - Interfețe confuze
    - Actualizări și întreținere

1.1.5 *Evaluarea criteriilor de intrare*
#### Criteriile de intrare în faza de Planificare a Testului au fost îndeplinite și procesul de testare poate continua.

### 1.2 *Monitorizare și Control Testare*
#### Diverse rapoarte periodice au fost generate pentru a reflecta starea curentă a procesului de testare; în cazul problemelor majore, au putut fi luate măsuri de control.

![Test Execution By Test Cycle](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/assets/135150327/0a16f5fe-8920-464b-bdac-8934f44a15b6)

### 1.3 *Analiza Testelor*
#### Procesul de testare va fi executat pe baza cerințelor de mai sus pentru modulele Attendance și Gradebook Dashboard . Următoarele condiții de testare au fost identificate:
- Verificarea funcționalității funcțiilor de ștergere, editare, căutare și resetare în sistem.
- Validarea utilizabilității și feedback-ului vizual al butoanelor.
- Confirmarea manipulării corecte a scenariilor de creare și ștergere.
- Introducerea datelor doar pentru câmpurile obligatorii și verificarea că acestea sunt create/actualizate.
- Confirmarea faptului că userul poate selecta candidați și că starea lor este actualizată în consecință.
- Verificarea funcționalității de drag and drop, a butoanelor si icon-uri

### 1.4 *Design Testare*
#### Story-urile legate de doua epice care pot fi vizulaizate aici: [Epic](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Epic.pdf)
#### Bazat pe analiza specificațiilor, Story-urile au fost create în Jira și pot fi vizualizate aici: [Story](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Story.pdf)
#### Test Cases

![Test Cases](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/assets/135150327/d4492d97-a82f-4cb5-97a9-2666642e445d)

#### Test case-urile pot fi vilzualizate aici: [Test Cases](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Zephyr%20Test%20Steps%20%2B%20Executions%20%2B%20Results%20(Jira).pdf)


### 1.5 *Implementare*
#### Următoarele elemente sunt pregatite pentru etapa de execuție a testelor:
- Mediul de testare este funcțional: [Aeries](https://demo.aeries.net/aeries/Login.aspx?demo=True&user=teacher990&pwd=teacher990)
- Accesul la mediul de testare este disponibil: Username: teacher990, Password: teacher990
- Cycle summary a fost creat
- Test case-urile au fost adăugate în Cycle summary


### 1.6 *Execuția Testelor*
- Cazurile de testare sunt create pe sumarul ciclului creat:

  ![Test execution](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/assets/135150327/96af42e3-a5f0-42be-95b1-e8c36fc1990e)

- Bug-urile au fost create pe baza testelor eșuate. Rapoartele complete de bug-uri pot fi găsite aici: [Bugs]([https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Bugs.Pdf.pdf)(https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/blob/main/Bugs.pdf)
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

![Test execution report by cycle](https://github.com/SabIoana/Testare-Manuala-Proiect-Final-Acreditare/assets/135150327/5acfffda-0b4b-455c-8015-1db8c99ae66c)





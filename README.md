# c-Tutorial
This is the repository that is used for my c# tutorial skripts
This readme includes all required actions for the Einsendeaufgabe 11-DVC, handed in from Nina Loeck.

## 1.	Erstellen Sie sich ein Repository in Github oder GitLab.<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/d7348a9f-11f4-465b-a6da-ae8c2b8dfa03)<br>

Clone Repository auf lokalen Computer mit git clone<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/593e3c9c-e96c-43cc-a788-f2bb59f72d12)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/4b5d613b-1f50-4657-9fa3-865470547d26)<br>

## 2.	Pushen Sie ein eigenes Projekt von Ihnen hoch (z.B. das CCD-Projekt) oder erstellen Sie ein neues Projekt! <br>
Aktuellen Repo-Status holen (git pul)l<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/cc29f6ba-2e86-4212-952f-f4c2149ce903)<br>

Hinzufügen eines HalloWelt-Konsolen Programms zum Projekt.<br>
Überprüfen des Status und des logs. (git status)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/6e432f2a-a784-476c-b8a5-02597ac6fe1f)<br>

Stagen der Änderung (git add)<br>
 ![image](https://github.com/ninagin/c-Tutorial/assets/92101088/555096e8-0fa9-45ba-9c4a-1b436d705157)<br>

Überprüfen (git status)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/79dc0adf-9c91-4104-bb91-071cddf5d854)<br>

Commit der Änderungen (git commit)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/5922e5f8-1bb1-42ea-b54b-a3a2a46d407a)<br>

Erneut Status prüfen: (git status)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/e7fa76a0-d3d8-4ffd-8800-301c5586c9ed)<br>

Pushen der Änderungen ins repository (git push) <br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/3e1a4806-2d3b-43a1-975a-3542d5ba64a5)<br>

 
Erneute Anpassung des Codes<br>
Dann Prüfen der Differenz: (git diff)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/e6ac855f-0fa5-4c4a-8a15-86d96ca5231c)<br>

Erneutes stagen (git add), commiten (git commit) und pushen (git push)<br>

Neue Datei im Repository erzeugt.<br>
Änderung laden mit git pull:<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/206bae99-f70a-4da9-84cb-f72f3283341f)<br>

Das File soll jetzt verschoben werden. (git mv)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/5dcc626f-f6d6-4ffe-901a-f169bc07c367)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/c74bc47e-cffc-4219-8957-794b0a988b3d)<br>

 
Kurze Zeit später entscheide ich mich, dass das File doch nicht benötigt wird und ich lösche es: (git rm)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/bf64da30-be82-43d2-991e-e4c2954e531c)<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/f8551a2e-e883-465c-abd7-5c6bcfda06cf)<br>

## 3.	Wenden Sie alle in den Unterlagen genannten relevanten Methoden beweisbar an: (das Github Repo ist Beweis) push, pull, add, commit, diff, status, rm/mv, etc. <br>
Siehe unter Aufgabe 2 oder im Github Repo<br>

## 4.	Experimentieren Sie mit Zeitreisen!<br>
Suche commit, in dem das unnecessaryFile gelöscht wurde:<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/4c98724f-f736-458a-8eb1-a577e2274142)<br>

Revert commit:<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/d9afbd8a-3322-4a2c-99b6-6462ab9acdd8)<br>

Aus Versehen löschen wir diese Datei lokal!<br>
Wir holen uns die Datei mit einem git restore wieder zurück uns stagen sie erneut.<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/ca847828-3721-4e28-9bed-9466ba215206)<br>

Wir fügen noch irgendeine andere Datei zu unserem Projekt hinzu und stagen dieses ebenfalls:<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/a3647b8a-79cc-4af4-85c2-a76afa920047)<br>

Wir beschließen die DS._Store Datei wieder zu unstagen:<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/d8d981d7-d1f4-42fe-b35d-f1de32c98a05)<br>

Mit den beiden Files commiten wir nun die Änderungen.<br>
Wir bekommen ärger von unserem Dozenten, dass wir unnötige Files commitet haben, deshalb reseten wir nun unseren letzten Commit<br>
Die soben committeten Änderung sind wieder zurück im Stage und können erneut geändert oder gelöscht werden.<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/67dd7fe7-5422-48f9-a5ed-205a86e0771a) <br>

## 5.	Erstellen sie zwei unterschiedliche, aber ähnliche Branches, wechseln sie hin und her und mergen sie diese Branches dann wieder!<br>
Erstelle zwei Branches<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/b43bef6d-1b88-4211-828f-59d567ac2bc0)<br>

Wechsel auf den ersten Branch.<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/13d1d5a6-7736-4cd9-98d7-d2d9daff8829)<br>

Überprüfe die Datein in Visual Studio<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/be379b8f-fa1f-438c-9f59-70230cd0f697)<br>

Wechsel auf den zweiten Branch<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/b1798d28-a21c-4127-b0c4-b173c9fa63e1)<br>

Überprüfe Datein in Visual Studio<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/094e0094-8f81-4199-9aa8-c5596e618734)<br>

Pushe die Branches ins Repository<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/bf8452b8-68bc-4fe4-aff0-4abae5439729)<br>

Wechsle auf den main branch und merge beide Branches.<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/f510c14a-f150-46f6-b314-868e3b950e2b)<br>

Überprüfe, ob die Änderungen der Branches (in meinem Fall wich nur ein Branch vom main ab) im main Branch enthalten sind.<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/d56a0d3e-960f-4552-b35c-06c8b2e74b87)<br>

## 6.	Erstellen Sie in GitHub einen Pull-Request bezugnehmend auf https://github.com/edlich/education!<br> Bitte referenzieren Sie auf den Pull-Request mit Link oder der Pull-Request Nummer! <br>Kryptische GitHub Namen kann ich kaum zuordnen. <br>Die Aufgabenteile vor dem Pull-Request bitte nicht in den Pull-Request einbauen, sondern extra abgeben!<br>

**PR #492**<br>
![image](https://github.com/ninagin/c-Tutorial/assets/92101088/31a680df-2d8d-4e53-883c-e503e78cf399)<br>










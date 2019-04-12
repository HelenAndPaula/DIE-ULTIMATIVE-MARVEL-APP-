# DIE ULTIMATIVE MARVEL-APP


<img width="613" alt="Bildschirmfoto 2019-04-12 um 15 03 21" src="https://user-images.githubusercontent.com/42578525/56039348-696dd900-5d34-11e9-8e44-37e9bd882d29.png">

## Idee

Die Aufgabenstellung für unser zweites Projekt war recht frei gestellt, jedoch sollte sich das Projekt auf die Verarbeitung 
von Informationen beziehen. Das letzte Projekt haben wir mit SNAP! programmiert, diese Mal haben wir uns für AppLab von 
Code.org (https://studio.code.org) entschieden, da wir es spannend fanden, eine App zu programmieren. 

In Bezug auf die Aufgabenstellung haben wir zunächst überlegt, inwiefern unsere App verschiedene Informationen enthalten und 
verarbeiten könnte. Unsere erste Idee war ein Quiz, bei dem der Spieler aus verschiedenen Antwortmöglichkeiten wählen kann und 
dafür Punkte bekommt. Wir entschieden uns diese Idee weiter auszubauen. Als Thema entschieden wir uns für das Marvel Cinematic Universe (MCU), da wir beide diese Filme sehr gern gucken und uns recht gut mit der Thematik auskennen. Somit erschien und das Thema als optimal, nicht zuletzt, da sich viele Menschen dafür begeistern und unsere App somit vielen Leuten gefallen bzw. sie ansprechen könnte. 

Neben dem Quiz entschieden wir uns für einen Psychotest, bei dem der Spieler testen kann, welchem Helden des MCU er am ähnlichsten ist.

## Programm

Während wir bei unserem letzten Projekt mit SNAP! gearbeitet haben, sind wir für dieses zweite Projekt auf Code.org umgestiegen und haben AppLab zur Programmierung unserer App genutzt. 

AppLab funktioniert mit einer visuellen Programmiersprache und eignet sich sowohl für Einsteiger als auch für etwas fortgeschrittenere Programmierer, da man sowohl Befehlblöcke verwenden als auch einen Text programmieren kann. Dabei sind alle Befehle in Englisch verfasst. Das Programm ist sehr modern und farenfrph gestaltet und ermöglicht es sogar, die programmierte App direkt mit anderen zu teilen und auf ein Handy zu schicken, sodass sie dort gespielt werden kann. 

AppLab gliedert sich in zwei Hauptbereiche: Den "Code"- und den "Entwurf"-Bereich.

### Code-Bereich

<img width="1280" alt="Bildschirmfoto 2019-04-12 um 15 50 05" src="https://user-images.githubusercontent.com/42578525/56042304-092e6580-5d3b-11e9-8018-a25cfcb6433b.png">

Im Code-Bereich wird der Code geschrieben und man kann aus den verscheidenen Blöcken wählen:

Die Blöcke gliedern sich wie bei SNAP! in acht Kategorien:  

<img width="268" alt="Bildschirmfoto 2019-04-12 um 15 48 23" src="https://user-images.githubusercontent.com/42578525/56042518-85c14400-5d3b-11e9-88d9-e667c88e7845.png">

Davon haben wir besonders folgende benutzt: 

Ul-Controls (gelb): Mit diesen Blöcken lassen sich verschiedene Vorgänge definieren, so zum Beispiel was beim Anklicken eines               bestimmten Knopfes geschieht oder wann welcher Screen gesetzt wird. 

Control (blau) : Mit diesen Blöcken lassen sich vorallem if-Schleifen programmieren, was  besonders beim Psychotest nötig war.

Variables (lila): Hier lassen sich Variabeln definieren und im Laufe des Spiels verändern.

Math (orange): Diese Blöcke enthalten vorallem die Funktion von Rechenzeichen, sodass zum Beispiel gesetzte Varaibeln um bestimmte Faktoren erhöht werden können. 

### Entwurf-Bereich

<img width="1280" alt="Bildschirmfoto 2019-04-12 um 15 50 21" src="https://user-images.githubusercontent.com/42578525/56043156-fa48b280-5d3c-11e9-8541-44c2bb5aa822.png">

AppLAb besticht neben dem übersichtlich AUfbau auch über den Entwurf- nzw. Design-Bereich, in dem die einzelnen Screens auf viele verschiedene Weisen designt werden können. So kann zum Beispiel die Hintergrundfarbe festgelegt werden und es könne zahlreiche Dinge eingefügt werden: 

<img width="254" alt="Bildschirmfoto 2019-04-12 um 16 32 07" src="https://user-images.githubusercontent.com/42578525/56044954-8d371c00-5d40-11e9-8d6a-7960765d0906.png">

So können zum Beispiel Textfelder, Knöpfe (Buttons) und Bilder problemlos per Drag'n'Drop eingefügt werden. Diese Möglichkeiten machen die App besonders ansprechend. 

## DAS ULTIMATIVE MARVEL-QUIZ 

Nun wollen wir genauer auf unser Quiz eingehen und erklären wie wir es programmiert haben.

### Konzept

Das Konzept des Quiz ist recht einfach. Wir haben uns insgesamt 20 Fragen mit vier Antwortmöglichkeiten überlegt, von denen je eine richtig ist. Zudem haben wir uns entschieden, dass es zwei verschiedene Screens (gewonnen, verloren) gibt, die dem Spieler nach jeder Frage angezeigt werden, jenachdem, ob er die Frage richtig oder falsch beantwortet hat. Hat er sie falsch beantwortet, muss er sie solange wiederholen, bis er richtig antwortet. AUs diesem Grund machte ein typisches Punktesystem wenig Sinn, wir entschieden uns für 10 Leben, von denen bei jeder falschen Antwort eins abgezogen wird. Sind alle Leben aufgebraucht, endet das Quiz, wenn der Spieler alle Fragen schafft, ohne 0 Leben zu erreichen, wird ihm auf einem letzten Screen angezeigt, wie viele Leben er noch hatte. 

Wir haben uns dazu entschieden, die Fragen in einer festgelgten Reihenfolge und nicht zufällig ablaufen zu lassen, da letzteres nicht ganz funktionierte und manche Fragen doppelt vorkamen bzw. das Spiel kein Ende fand. 

Damit sich die Namen der einzelnen Screens, Buttons etc. nicht in den Projekten doppeln, haben wir beim Quiz alles ab 101 (screen101, button101, picture101) benannt, beim Psychotest haben wir normal mit 1 begonnen. 

### Design

Passend zum Thema Marvel und dessen typischen Designs haben wir ausschlißlich schwarze Screens mit weißer SChrift verwendet und diese zum einen mit dem MArvel-Logo sowie mit Bildern ergänzt. 

### Screens

Das Quiz setzt sich aus insgesamt 26 Screens zusammen. 

<img width="109" alt="Bildschirmfoto 2019-04-12 um 16 42 49" src="https://user-images.githubusercontent.com/42578525/56045729-0edb7980-5d42-11e9-92f5-6f0a3a54fbe3.png">

Bei 20 dieser Screens (screen101-screen120) handelt es sich um die Frage-Screens. Diese sind alle identisch aufgebaut: Auf den schwarzen Screens befindet sich in weißer Schrift die Frage (Textfeld, Arial, Schriftgröße 20, mittig), darunter vier schwarze (somit nicht sichtbare) Buttons mit den Antwortmöglichkeiten in schwarzer Schrift. Die meisten Screens sind zudem durch ein zur Frage passendes Bild ergänzt, um sie zu füllen. 

<img width="301" alt="Bildschirmfoto 2019-04-12 um 16 51 26" src="https://user-images.githubusercontent.com/42578525/56046529-c755ed00-5d43-11e9-9875-447b0e4dee5e.png"> <img width="300" alt="Bildschirmfoto 2019-04-12 um 16 51 36" src="https://user-images.githubusercontent.com/42578525/56046531-c755ed00-5d43-11e9-800d-06b1954a6866.png"> 

<img width="298" alt="Bildschirmfoto 2019-04-12 um 16 51 45" src="https://user-images.githubusercontent.com/42578525/56046532-c7ee8380-5d43-11e9-9f88-934abb057378.png"> <img width="297" alt="Bildschirmfoto 2019-04-12 um 16 51 56" src="https://user-images.githubusercontent.com/42578525/56046533-c7ee8380-5d43-11e9-83d6-1d2fb81e8af9.png"> 

<img width="294" alt="Bildschirmfoto 2019-04-12 um 16 52 08" src="https://user-images.githubusercontent.com/42578525/56046534-c7ee8380-5d43-11e9-8c78-40a52ce685ee.png"> <img width="295" alt="Bildschirmfoto 2019-04-12 um 16 52 15" src="https://user-images.githubusercontent.com/42578525/56046536-c7ee8380-5d43-11e9-8c13-bec7f4b4917f.png">

<img width="294" alt="Bildschirmfoto 2019-04-12 um 16 53 34" src="https://user-images.githubusercontent.com/42578525/56046538-c7ee8380-5d43-11e9-9894-2091c7aa357a.png"> <img width="297" alt="Bildschirmfoto 2019-04-12 um 16 53 40" src="https://user-images.githubusercontent.com/42578525/56046542-c8871a00-5d43-11e9-8d56-7bbb5e0bf40e.png"> 

<img width="297" alt="Bildschirmfoto 2019-04-12 um 16 53 48" src="https://user-images.githubusercontent.com/42578525/56046547-c91fb080-5d43-11e9-8bba-befe178786f6.png"> <img width="297" alt="Bildschirmfoto 2019-04-12 um 16 53 54" src="https://user-images.githubusercontent.com/42578525/56046548-c91fb080-5d43-11e9-9562-9d37f938301d.png">

<img width="296" alt="Bildschirmfoto 2019-04-12 um 16 54 00" src="https://user-images.githubusercontent.com/42578525/56046549-c91fb080-5d43-11e9-96bb-6eb53694b9b4.png"> <img width="293" alt="Bildschirmfoto 2019-04-12 um 16 54 06" src="https://user-images.githubusercontent.com/42578525/56046550-c91fb080-5d43-11e9-8ace-1fdb1b1f5894.png">

<img width="291" alt="Bildschirmfoto 2019-04-12 um 16 54 13" src="https://user-images.githubusercontent.com/42578525/56046552-c9b84700-5d43-11e9-9356-97e27c4d6456.png"> <img width="297" alt="Bildschirmfoto 2019-04-12 um 16 54 19" src="https://user-images.githubusercontent.com/42578525/56046553-c9b84700-5d43-11e9-8937-2d50bfbdb494.png"> 

<img width="297" alt="Bildschirmfoto 2019-04-12 um 16 54 25" src="https://user-images.githubusercontent.com/42578525/56046555-ca50dd80-5d43-11e9-9116-e40a5f2f0708.png"> <img width="295" alt="Bildschirmfoto 2019-04-12 um 16 54 33" src="https://user-images.githubusercontent.com/42578525/56046557-ca50dd80-5d43-11e9-80d9-c12fe9659a71.png">

<img width="296" alt="Bildschirmfoto 2019-04-12 um 16 54 39" src="https://user-images.githubusercontent.com/42578525/56046560-ca50dd80-5d43-11e9-8ec8-171847bb4b6d.png"> <img width="293" alt="Bildschirmfoto 2019-04-12 um 16 54 45" src="https://user-images.githubusercontent.com/42578525/56046575-d5a40900-5d43-11e9-842b-cc3471006413.png">

<img width="297" alt="Bildschirmfoto 2019-04-12 um 16 54 53" src="https://user-images.githubusercontent.com/42578525/56046576-d5a40900-5d43-11e9-8b31-a6f4656b21d7.png"> <img width="296" alt="Bildschirmfoto 2019-04-12 um 16 55 10" src="https://user-images.githubusercontent.com/42578525/56046578-d63c9f80-5d43-11e9-9235-63d95ace4953.png">

Neben diesen zwanzig Screens gibt es noch sechs weitere.

Zwei davon sind der gewonnen- bzw. der verloren-Screen, die auf jeden Frage folgen. Dabei entschieden wir uns für zwei passende Captain-America-Memes, die sich einfügen ließen und jeweils entweder positiv (Daumen hoch) oder negativ (enttäuscht) sind. 

<img width="292" alt="Bildschirmfoto 2019-04-12 um 17 04 34" src="https://user-images.githubusercontent.com/42578525/56048105-1a7d6f00-5d47-11e9-8909-96e563244450.png"> <img width="298" alt="Bildschirmfoto 2019-04-12 um 17 04 50" src="https://user-images.githubusercontent.com/42578525/56048106-1a7d6f00-5d47-11e9-8c5a-6c14072fe723.png">

Die anderen Screens sind zum einen der Homescreen des Quiz sowie die Anleitung, die beide über einen Button verfügen, sodass man vom Homescreen zur Anleitung und von dort zum Quiz gelangt.

<img width="297" alt="Bildschirmfoto 2019-04-12 um 17 13 37" src="https://user-images.githubusercontent.com/42578525/56047732-5cf27c00-5d46-11e9-8a32-cb563ed2427f.png"> <img width="295" alt="Bildschirmfoto 2019-04-12 um 17 13 47" src="https://user-images.githubusercontent.com/42578525/56047733-5cf27c00-5d46-11e9-9ac1-995cf82a48ea.png">

Hinzu kommen noch die zwei möglichen Endscreens: der verloren-Screen, der auftritt wenn alle Leben verbraucht wurden, und der Endscreen, wenn der Spieler alle Fragen beantwortet hat. 

<img width="299" alt="Bildschirmfoto 2019-04-12 um 17 17 31" src="https://user-images.githubusercontent.com/42578525/56048198-48fb4a00-5d47-11e9-823c-a5ee67543391.png"> <img width="295" alt="Bildschirmfoto 2019-04-12 um 17 20 20" src="https://user-images.githubusercontent.com/42578525/56048200-4993e080-5d47-11e9-9440-338d0f19df7a.png">

### Code

#### Fragescreens



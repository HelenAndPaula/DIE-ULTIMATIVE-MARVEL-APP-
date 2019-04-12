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

AppLab funktioniert mit einer visuellen Programmiersprache und eignet sich sowohl für Einsteiger als auch für etwas fortgeschrittenere Programmierer, da man sowohl Blöcke verwenden als auch direkt JavaScript als Text programmieren kann. Dabei sind alle Befehle in Englisch verfasst. Das Programm ist sehr modern und farenfroh gestaltet und ermöglicht es sogar, die programmierte App direkt mit anderen zu teilen und auf ein Handy zu schicken, sodass sie dort gespielt werden kann. 

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

## HOMESCREEN 

Da sich unsere App aus zwei verschiedenen Teilen (Quiz, Psychotest) zusammensetzt, haben wir zunächst einen Homescreen gestaltet und programmiert, von dem aus der Spieler entweder zum Quiz oder zum Psychotest gelangt. Die Programmierung wird unten beschrieben. Neben den beiden Buttons die zwischen Quiz und Test unterschieden, enthät der Homescreen das Marvel-Logi sowie den Namen der App.

<img width="319" alt="Bildschirmfoto 2019-04-12 um 19 28 47" src="https://user-images.githubusercontent.com/42578525/56055291-7224d600-5d59-11e9-9541-1c901ad15d68.png">

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

Vor dem Quiz gibt es einen Homescreen, auf dem der Spieler zwischen Quiz und Psychotest entscheidet. Klickt er auf "Quiz" (buttonquiz), so werden die Befehle für das Quiz genutzt. Um dies zu definieren wird der Block "onEvent" genutzt und als ID der Button buttonquiz angegeben und unter diesem Block alle anderen Befehle des Quiz angeordnet. 

<img width="566" alt="Bildschirmfoto 2019-04-12 um 17 23 04" src="https://user-images.githubusercontent.com/42578525/56049084-0175bd80-5d49-11e9-9d36-a9278205c76e.png">

Bevor das eigentliche Quit beginnt, gibt es einen ersten Befehlsblock, der für den Quizhomescreen und die Anleitung zuständig ist. Wird buttonquiz angeklickt, so soll der Homescreen des Quiz erschienen. Dazu dient der Befehl "setScreen", auf den  ein weitere onEvent-Screen folgt, der definiert, dass der button102 (Anleitung) verursacht, dass der Anleitungsscreen gezeigt wird. Auf diese Weise (onEvent+setScreen) funktionieren eingntlich alle Buttons im Quiz. 

Zusätzlich wird im ersten Block durch den Befehl var"leben"=10 die VAriable Leben gesetzt und auf 10 definiert. Jeder Screen verfügt rechts oben in der Ecke über ein Textfeld (leben1 bis leben20) indem jeweils die Lebensanzahl als Text gesetzt ist. Dazu dient der Befehl setText"leben1",leben, also wird das Textfeld (ID variiert je nach Screen (leben1 - leben20)) immer gleich der Variablen "leben", also der Anzahl der Leben gesetzt. Dieser Befehl zieht sich durch alle Screens, wir werden ihn jedoch nur hier erklären. 

Da alle Fragescreens in der Programmierung bis auf Abweichungen in den Bezeichnungen identisch sind, werden wird dies anhand des ersten Fragescreens darlegen. Zu Übersichtszwecken haben wir die Programmierung mit Kommentaren versehen (FRAGE1, FRAGE2,...). 

Innerhalb der Fragescreens gibt es immer drei gleich programmierte falsche ANtworten sowie eine richtige. Zunächst werden wir die falschen Antworten anhand eines Beispiels erklären:

<img width="518" alt="Bildschirmfoto 2019-04-12 um 17 37 34" src="https://user-images.githubusercontent.com/42578525/56049410-b14b2b00-5d49-11e9-8542-572a372fd206.png">

In diesem Beispiel definiert der button103 eine falsche Antwort. Somit soll also ein Leben angezogen werden und der verloren-Screen angezeigt werden. 

Dazu wird erneut ein onEvent-Block gesetzt, der definiert, was beim anklicken (click) von button103 passierren soll. Der Befehl setScreen"verloren" gibt an, dass in diesem Fall der verloren-Screen gezeigt wird. durch den Befehl leben=leben-1 wird definiert, dass ein Leben abgezogen wird, die Variable also um 1 reduziert wird. Darauf folgt immer ein "if"-Control-Block, der angibt, dass wenn leben==0 (also alle Leben verbraucht) der keineLeben-Screen angezeigt wird und dass Spiel endet. Dieser Befehl folgt auf jede Reduzierung der Variable "leben". Damit sich die Angabe der Leben in der Ecke (verloren-Screen: lebenv) anpasst folgt anschließend immer der Befehl setText"lebenv",leben folgen, da dieser den Text mit den reduzierten Leben, also jetzt neun, gleichsetzt. Auf dem verloren-Screen befindet sich der Button "zurück". Dieser ist jedoch untergeordnet, da sonst immer screen101 und nicht der jeweilige Screen gezeigt werden würde.  Durch einen weiteren onEvent-Befehl wird definiert, dass beim anklicken erneut Screen101, also die erste Frage, gezeigt wird und es wird auch hier der Text (leben101) mit der Variablen "leben" gelichgesetzt. Diese Schritte werden auch für die anderen beiden falschen Antworten genutzt, jedoch müssen dort natürlich die Buttons anders bezeichnet werden. 

<img width="485" alt="Bildschirmfoto 2019-04-12 um 17 46 24" src="https://user-images.githubusercontent.com/42578525/56049959-ec019300-5d4a-11e9-9183-d3a4861ab93a.png">

Das Bild zeigt die Befehle, wenn die richtige Antwort angeklickt wird. In diesem Fall wird kein Leben abgezogen und der gewonne-Screen angeziegt. 

In diesem Fall wird  ein onEvent-Block gesetzt, der definiert, was beim anklicken (click) von button106 passierren soll. Der Befehl setScreen"gewonnen" gibt an, dass in diesem Fall der gewonnen-Screen gezeigt wird. Auf diesem befindet sich statt dem "zurück"-Button ein "weiter"-Button, mit dem der Spieler zur nächsten Frage gelangt. Dazu wird wieder der Befehl "onEvent"button106",click" zusammen mit setScreen verwendet, wobei der nächste Screen in diesem Fall screen102 gesetzt wird. Zudem wird die Lebensangabe leben2 auf screen2 erneut mit der Variablen Leben wie oben erklärt gleichgesetzt. 

Auf diese Weise wurden alle 20 Fragescreens programmiert. 

Wird FRAGE20 richtig beantwortet, folgt statt des nächsten Fragescreens der Screen "quizende" (Programmierung: s. oben). Auf diesem befindet sich ein vorgeschriebener Text sowie ein in diesen Text eingebautes Textfeld, das wie oben mit den Leben gleichgesetzt ist, sodass im Text die richtige Lebensanzahl steht. Von dort aus hat der Spieler erneut durch zwei Buttons die Möglichkeit erneut zu spielen (Button "nochmalquiz") oder zum Homescreen (Button "Home") zurückzukehren. Gleiches gilt für den Screen, der auftritt wenn keine Leben mehr verfügbar sind (hier: nochmalquiz2, Home101) . Wird der Button "nochmalquiz" angeklickt, werden die Leben wieder auf 10 gesetzt (leben=10). 

<img width="522" alt="Bildschirmfoto 2019-04-12 um 17 56 41" src="https://user-images.githubusercontent.com/42578525/56050514-67b00f80-5d4c-11e9-982b-af9e2fe2f7cc.png">

### Ende des Quiz

Wie oben erklärt wird  bei jeder falschen Antwort eins der zehn Leben abgezogen. Sind keine Leben mehr vorhanden endet das Spiel, ansonsten kann der Spieler das Quiz durchspielen, bis er alle 20 Fragen beantwortet hat. 

## WELCHER MARVELHELD BIST DU?

Nun werden wir näher auf unseren Psychotest "Welcher Marvelheld bist du?" eingehen. 

### Konzept

Neben unserem Quiz wollten wir zusätzliche etwas programmieren, was nicht  nur das Wissen des Spielers testet, sondern auch Spaß macht. So kamen wir auf die Idee des Psychotests.

Das Konzept ist einfach: Der Spieler beantwortet zehn Fragen mit je acht Antwortmöglichkeiten, die je für einen Helden stehen. Für jeden Helden ist eine bestimmte Punktzahl festgelegt, die zu einem für den Spieler nicht sichtbaren Score addiert wird. Am Ende wird dieser ausgewertet, das heißt, je nachdem wie viele Punkte der Spieler erreicht hat, erhält er ein anderes Ergbenis.

### Design

Wie auch das Quiz ist der Psychotest vollständig schwarz mit weißer Schrift gestaltet. Auf den Fragescreens sind keine Bilder, jeodch ist bei den Ergebnissen jeweils der jeweilige Superheld abgebildet. 

### Screens

Der Psychotest setzt sich aus 21 Screens zusammen. Die ersten beiden sind erneut Homescreen (home-psychotest) und Anleitung (screen12). 

<img width="300" alt="Bildschirmfoto 2019-04-12 um 20 23 34" src="https://user-images.githubusercontent.com/42578525/56058150-eadb6080-5d60-11e9-94e5-3a4f46f64dc8.png"> <img width="298" alt="Bildschirmfoto 2019-04-12 um 20 23 47" src="https://user-images.githubusercontent.com/42578525/56058151-eadb6080-5d60-11e9-9ef7-ecb191ccf361.png">

Zudem gibt es die zehn verschiedenen Fragescreens (screen1 bis screen10) mit je acht Antwortmöglichkeiten:


<img width="301" alt="Bildschirmfoto 2019-04-12 um 20 27 20" src="https://user-images.githubusercontent.com/42578525/56058415-a7cdbd00-5d61-11e9-989e-664cf6465392.png"> <img width="299" alt="Bildschirmfoto 2019-04-12 um 20 27 36" src="https://user-images.githubusercontent.com/42578525/56058416-a7cdbd00-5d61-11e9-8258-2cd5c0c988ac.png">

<img width="294" alt="Bildschirmfoto 2019-04-12 um 20 27 58" src="https://user-images.githubusercontent.com/42578525/56058417-a7cdbd00-5d61-11e9-82de-50783b521732.png"> <img width="296" alt="Bildschirmfoto 2019-04-12 um 20 28 05" src="https://user-images.githubusercontent.com/42578525/56058418-a7cdbd00-5d61-11e9-9488-666b42e41797.png">

<img width="296" alt="Bildschirmfoto 2019-04-12 um 20 28 12" src="https://user-images.githubusercontent.com/42578525/56058419-a7cdbd00-5d61-11e9-8bb3-062a84f63772.png"> <img width="296" alt="Bildschirmfoto 2019-04-12 um 20 28 30" src="https://user-images.githubusercontent.com/42578525/56058420-a8665380-5d61-11e9-858b-bc6e7435231f.png">

<img width="294" alt="Bildschirmfoto 2019-04-12 um 20 28 37" src="https://user-images.githubusercontent.com/42578525/56058421-a8665380-5d61-11e9-990f-763a647a212d.png"> <img width="295" alt="Bildschirmfoto 2019-04-12 um 20 28 44" src="https://user-images.githubusercontent.com/42578525/56058423-a8665380-5d61-11e9-9d6e-9637479ec797.png">

<img width="294" alt="Bildschirmfoto 2019-04-12 um 20 28 51" src="https://user-images.githubusercontent.com/42578525/56058424-a8feea00-5d61-11e9-88dd-bb5cfdb4cc8e.png"> <img width="294" alt="Bildschirmfoto 2019-04-12 um 20 29 02" src="https://user-images.githubusercontent.com/42578525/56058425-a8feea00-5d61-11e9-93e2-e3412d5d8b07.png">

Zusätzlich gibt es vor den möglichen Antwortscreens (s. Helden, mögliche Ergebnisse) auch noch screen11, der Spannung aufbauen soll. 

<img width="298" alt="Bildschirmfoto 2019-04-12 um 20 32 30" src="https://user-images.githubusercontent.com/42578525/56058608-1e6aba80-5d62-11e9-8323-9135057423eb.png">

### Helden (mögliche Ergebnisse)

Die folgende Tabelle zeigt die acht Helden mit ihren wichtigsten Eigenschaften sowie den Faktor um den sich der Score erhöht, wenn ihre Antwort geklickt wird. 

Loki: Antiheld, Bruder von Thor, hinterhältig (Score +1)

Thor: stark, mächtig, unsterblich, Gott des Donners (Score +2)

Iron Man:Technik, reich, von sich selbst überzeugt (Score +3)
Captain America:  mutig, sportlich, stur (Score +4)

Scarlet Witch:  Magische Fähigkeiten durch Experimente (Score +5)

Black Widow: Agentin, Nahkampf, kein Vertrauen  (Score +6)

Groot: ich bin Groot  (Score +7)

Spiderman:  mutig, Naturwissenschaften, unerfahren  (Score +8)

Die Fragen werden wiefolgt gewertet: 

<img width="629" alt="Bildschirmfoto 2019-04-12 um 20 25 47" src="https://user-images.githubusercontent.com/42578525/56058483-ccc23000-5d61-11e9-8b0d-1234a745d0e3.png">

Somit ergeben sich die folgenden Ergebnisschreens, die jeweils mit einem kurzen Text versehen sind.

<img width="289" alt="Bildschirmfoto 2019-04-12 um 20 33 59" src="https://user-images.githubusercontent.com/42578525/56058800-c2546600-5d62-11e9-8ac1-c2b086aada35.png"> <img width="297" alt="Bildschirmfoto 2019-04-12 um 20 35 00" src="https://user-images.githubusercontent.com/42578525/56058801-c2546600-5d62-11e9-8596-f4fead189f68.png">

<img width="295" alt="Bildschirmfoto 2019-04-12 um 20 35 12" src="https://user-images.githubusercontent.com/42578525/56058802-c2546600-5d62-11e9-849c-dffacf757af6.png"> <img width="297" alt="Bildschirmfoto 2019-04-12 um 20 35 28" src="https://user-images.githubusercontent.com/42578525/56058803-c2546600-5d62-11e9-9a62-725f7032cf0f.png">

<img width="294" alt="Bildschirmfoto 2019-04-12 um 20 35 42" src="https://user-images.githubusercontent.com/42578525/56058805-c2546600-5d62-11e9-8e5a-a6b2944e6724.png"> <img width="296" alt="Bildschirmfoto 2019-04-12 um 20 36 05" src="https://user-images.githubusercontent.com/42578525/56058806-c2ecfc80-5d62-11e9-84c9-e5a022e2aa18.png">

<img width="298" alt="Bildschirmfoto 2019-04-12 um 20 36 32" src="https://user-images.githubusercontent.com/42578525/56058807-c2ecfc80-5d62-11e9-8a00-5a6f363f2b62.png"> <img width="297" alt="Bildschirmfoto 2019-04-12 um 20 36 53" src="https://user-images.githubusercontent.com/42578525/56058808-c2ecfc80-5d62-11e9-83eb-1f2ce056fd7c.png">

### Code 

Der erste Block des Codes ist genauso aufgebaut wie der des Quiz, da auch hier definiert wird, dass beim Anklicken der Buttons erst der Homescreen des Psychotests und dann die Anleitung gezeigt werden soll. DAbei werden genau dieselben onEvent-Befehle wie oben genutzt, daher werden wir sie hier nicht nocheinmal erklären.

<img width="581" alt="Bildschirmfoto 2019-04-12 um 20 38 31" src="https://user-images.githubusercontent.com/42578525/56058974-3858cd00-5d63-11e9-967f-6bf300223b6a.png">

Die einzelnen Fragescreens sind ebenfalls gleich programmiert. Daher werden wir dies am Beispiel der ersten Frage erklären. Nur zwei Screens weichen ab, da diese nicht acht sondern nur zwei bzw. vier Antwortmöglickeiten haben, jedoch sind sie trotzdem gleich programmiert. 

<img width="629" alt="Bildschirmfoto 2019-04-12 um 20 42 07" src="https://user-images.githubusercontent.com/42578525/56059077-8372e000-5d63-11e9-8625-a8fd465af797.png">
<img width="616" alt="Bildschirmfoto 2019-04-12 um 20 42 18" src="https://user-images.githubusercontent.com/42578525/56059078-8372e000-5d63-11e9-8b30-b7c9f4471865.png">
<img width="573" alt="Bildschirmfoto 2019-04-12 um 20 42 26" src="https://user-images.githubusercontent.com/42578525/56059079-840b7680-5d63-11e9-876a-08df7418e5d7.png">

Mit Beginn der ersten Frage wird zunächst eine neue Variable "score" eingeführt und mithilfe des Befehls "var"score"=0" gleich 0 gesetzt. 

Danach folgen jeweils onEvent-Blöcke, die definieren was beim anklicken der jeweiligen Buttons passiert. Button8 zum Beispiel definiert die Antwort für Captain America, der Score muss also um 4 erhöht werden. Dazu wird unter den onEvent-Befehl ("button9",click) ein Variablenblock gesetzt, der in Kombination mit einem Math-Block die Erhöhung des Scores um 4 definiert: "score=score+4". Wie auch beim Quiz wird dann ein Textfeld, welches jedoch nicht für den Spieler sichtbar ist (schwarze Schrift auf schwarzem Hintergrund", mit dem Score gleichgesetzt (setText, s. oben). Dies wird für jede Antowrtmöglichkeit und bei allen Fragescreens so gemacht. Dabei gilt immer "score=score+x", wobei x die für die Figur festgelegte Zahl ist. SOmit ergibt sich für Frage 1 der im Bild gezeigte Code. 

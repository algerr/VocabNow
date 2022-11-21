![Blogeinträge-header png](https://user-images.githubusercontent.com/111282979/203018930-fa86261e-0910-4fc8-a5cf-bf9099fd51e4.png)

Computer Science project 2022

|[Blogeintrag-15.08.22](#blogeintrag-15082022)|[Blogeintrag-22.08.22](#blogeintrag-22082022)|[Blogeintrag-25.08.22](#blogeintrag-25082022)|[Blogeintrag-29.08.22](#blogeintrag-29082022)|[Blogeintrag-05.09.22](#blogeintrag-05092022)|[Blogeintrag-12.09.22](#blogeintrag-12092022)|[Blogeintrag-19.09.22](#blogeintrag-19092022)|   
|:-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|-------------------:|
|[Blogeintrag-22.09.22](#blogeintrag-22092022)|[Blogeintrag-26.09.22](#blogeintrag-26092022)|[Blogeintrag-06.10.22](#blogeintrag-06102022)|[Blogeintrag-24.10.22](#blogeintrag-24102022)|[Blogeintrag-03.11.22](#blogeintrag-03112022)|[Blogeintrag-07.11.22](#blogeintrag-07112022)|[Blogeintrag-14.11.22](#blogeintrag-14112022)|
[Blogeintrag-17.11.22](#blogeintrag-17112022)|

## Blogeintrag-15.08.2022

Heute fand die erste Informatikstunde statt, in der wir uns mit der Frage beschäftigt haben, was im Informatikunterricht behandelt wird. Dabei wurde klar erläutert, dass der Informatikunterricht an der Stormarnschule sehr individuell und projektorientiert stattfindet und somit kein Frontalunterricht entsteht. Die Projektideen werden sich in 2er Gruppen überlegt und daraufhin bis zu einer Deadline im Dezember erarbeitet und dokumentiert durch Blogeinträge in jeder Stunde, wie bei diesem hier für den 15. August. Was die Projekte angeht, ist die Entscheidung jeder Gruppe selbst überlassen. Von visuellen Blocksprachen über Websprachen wie Javascript bis zu C/++ ist alles möglich. Auch Hardware kann mit Hilfe von Arduinos sowie Zubehör und Bibliotheken programmiert werden. Aufgrund der großen Vielzahl an Möglichkeiten, kamen wir in der ersten Stunde noch nicht auf unsere Idee. Eine grundlegende Vorstellung hatten wir jedoch: Unsere Idee sollte softwarebasiert sein.

## Blogeintrag-22.08.2022

Um eine Sprache zu erlernen sind sie einfach notwendig und spätestens seit der weiterführenden Schule sind sie aus dem Leben eines jeden von uns nicht mehr wegzudenken. **Vokabeln**. Doch ein Problem, das leider bisher keine Lösung hatte, stand dem "leichten Lernen nebenbei" schon immer im Weg. Um Vokabeln zu lernen muss entweder analog oder digital nachgeschlagen und mit voller Konzentration auf das jeweilige Medium geschaut werden, damit das Erlernen erfolgreich ist. Doch sich diese Zeit zu nehmen, ist für viele Menschen heutzutage gar nicht möglich, da noch so viele andere Dinge zu erledigen sind. Deshalb ist unsere Idee, einen Vokabeltrainer zu entwickeln, durch den man ganz nebenbei mit Spracherkennung Vokabeln lernen kann **VocabNow**. Man nimmt seine Kopfhörer und schon kann man, während z.B. die Hausarbeit erledigt wird, seinen Wortschatz erweitern und man muss sich keine Zeit nehmen, um auf altmodische Art und Weise Vokabeln zu lernen. Als Entwicklungsumgebung (IDE) verwenden wir [Replit.com](https://www.replit.com), da diese uns eine ferngesteuerte Arbeit ermöglicht, sodass bei Krankheit und nach dem Unterricht am Projekt weitergearbeitet werden kann. Der Name **VocabNow** rührt daher, dass unser Vokabeltrainer ein Lernen auf Knopfdruck ermöglichen soll. In jeder Situation und Lage soll es möglich sein, seinen Wortschatz zu erweitern, ohne sich auf sein Handy zu konzentrieren. Stand 22. August 2022 gibt es keinen anderen Vokabeltrainer, der diese Möglichkeit bietet. Für die Spracherkennung wird „WebKitSpeechRecognition“ aus der Webspeech API, bereitgestellt durch das Mozilla Developer Network, genutzt. Darüberhinaus haben wir für den Anfang eine Datenbank mit 10 englischen Vokabeln erstellt, welche als Probelauf dienen soll, um zu zeigen, ob das Ganze funktioniert. Für die [MySQL-Datenbank](https://www.mysql.com/) wird  [RemoteMySQL](https://remotemysql.com/) genutzt, was uns das Erstellen und Verwalten online möglich macht. Zu Beginn bestand das Problem, mehrere Datensätze für dieselbe Vokabel zu haben. Nach kurzer Zeit fanden wir jedoch heraus, wie sich ein Datensatz löschen lässt. Die nächste Herausforderung war jedoch nun die zufällige Ausgabe einer Vokabel, da das Vokabellernen in der immer gleichen Reihenfolge auf Dauer keinen Sinn ergibt. Leider funktionierte das Ganze bis zum Ende der Stunde nicht wirklich, sodass wir uns der Lösung dieses Problems in der nächsten Stunde widmen werden.

## Blogeintrag-25.08.2022

Da uns das Problem der letzten Stunde mit der zufälligen Ausgabe von Vokabeln auch danach noch beschäftigte, arbeiteten wir zu Hause daran weiter und fanden bald eine Lösung. Dafür wurde in der Datenbank im Table *Eng_De* ein Wert **Vocab** eingegeben, der von nun an alle Vokabeln von Englisch zu Deutsch im Format **Englisch_Deutsch** beinhaltet. Damit ist nun die zufällige Ausgabe von Vokabeln leicht und der ausgegebene Wert muss nur im Unterstrich getrennt werden, sodass die englische und deutsche Vokabel einzeln verwendet werden können. Da Laurenz leider krankheitsbedingt abwesend war und Daniel über keine weitreichenden Programmierkenntnisse verfügte, widmete er sich der Erstellung der Webseite, über die VocabNow später laufen soll. Er erlernte in den beiden Doppelstunden die Grundlagen der Auszeichnungssprache **HTML (Hyper-Text-Markup-Language)**. Außerdem überlegte er sich, was man noch in die App einbauen könne. So entstand die Idee, dem Nutzer die Bedienung der Seite erheblich zu erleichtern, sodass, wie im vorigen Blogeintrag bereits beschrieben, ein Vokabellernen auf Knopfdruck möglich ist. Doch durch die Möglichkeit, am Projekt auch ferngesteuert zu arbeiten, konnte auch Laurenz seinen Teil leisten, indem er am "Backend", der Entwicklung des Systems hinter der Webseite, weiterarbeitete.

## Blogeintrag-29.08.2022

Da Laurenz leider aufgrund seiner Krankheit nicht anwesend sein konnte, fokussierte sich Daniel heute auf das Erlernen der Programmiersprache Javascript, die bei einer Webseite für Funktionalität sorgt. Des Weiteren fing er an, die bisherigen Blogeinträge im Repository auf GitHub hochzuladen. Somit kann Laurenz die Blogeinträge später noch überarbeiten, sodass sie alle beisammen auf dem neusten Stand sind.

## Blogeintrag-05.09.2022

Heute war Laurenz wieder da, weshalb wir nun endlich an unserem Projekt effizienter arbeiten konnten. Nun haben wir uns damit befasst mit "styles.css" unsere Webside zu verschönern. Da wir mit meinem erstellten Website-Design nicht so ganz zufrieden waren, haben wir nochmal das Design bzw. insbesondere die Hintergrundfarbe unser Webside verändert. Wir haben uns für etwas exotisches entschieden, nämlich einer Hintergrundfarbenkombination aus den Farben #4169e1, #3bb78f, #0bab64, wobei #4169e1 die eigentliche Hintergrundfarbe sein sollte und #3bb78f und #0bab64 das Muster. Wir hatten auch noch speziell versucht für das Muster ein "Linear-Gradient" einzubauen um einen konstanten Farbenübergang zu ermöglichen. Letztendlich haben wir uns dann doch dazu entschieden, den "Linear-Gradient" nicht zu benutzen, weil wir es nicht geschafft haben das erwünschte Ergebnis zu erzielen, und uns nicht zu lange damit beschäftigen wollten. 


## Blogeintrag-05.09.2022
In den letzten Tagen haben wir uns mit der Frage auseinandergesetzt, wie wir einen Hintergrund erstellen können, der unsere Nutzer bei Laune hält und amüsant wirkt. Dabei sind wir auf die Idee gekommen einen "Partical-Js" Hintergrund zu erstellen. Der Hintergrund, welchen wir gewählt bzw. erstellt haben, soll die Wirkung eines leeren Weltraums vermitteln, was wiederum beruhigend wirken soll, um aus dem stressigen Altag herauszukommen und entspanntes lernen zu ermöglichen. Als Farbenschrift haben wir uns für die Farbe Orange entschieden, weil diese die Spontanität beflügelt und Lebensfreude verleiht. Zudem ist diese auch in der Lage Selbstvertrauen und Unabhängigkeit bei unseren Nutzern zu implementieren. Darüberhinaus bauten wir unseren "Slogan" in die Startseite unserer Webside ein, welcher lautet:"Lerne, wann un wo du willst". Dieser "Slogan" charakterisiert die Absicht hinter unserem Projekt ziemlich präzise, nämlich, dass wir von Anfang an einen Vokabeltrainer erschaffen wollten, der überall und jeder Zeit mit leichter Mühe zugänglich ist. Nachdem nun das Design so weit fertig war, erstellten wir einen "Button", was wir schon zuvor geplannt hatten, mit dem über einen Klick die Weiterleitung zum "Start" des Vokabeltrainers erfolgen sollte. Nun bestand die Schwierigkeit unsere Spracherkennung also das "Webkitspeechrecognition" als Tool einzubauen. Mit diesem Probelem werden wir uns dann zu Hause auseinandersetzen müssen. 


## Blogeintrag-12.09.2022

In dieser Doppelstunde haben wir uns ausgibig damit auseinandergesetzt das "Webkitspeechrecognition" in unsere Website einzubauen. Während wir anfangs Schwierigkeiten damit haten das Tool in die Website zu integrieren, waren wir nach ungefähr einer Stunde und dem vielen Durchlesen von Guides nun in der Lage die Spracherkennung einzubauen. Als Zusatz wollten wir ebenfalls noch einen Sound einbauen, der die richtige Antwort erklingen lassen sollte. Zwar funktionierte das Abspielen des Sounds auf dem Windows-Rechner, aber leider nicht auf unserem Ios Gerät. Dieses Problem zu beheben stellte eine erhebliche Schwierigkeit da, weshalb wir kurzzeitig diesen Schritt aufgeben mussten und uns nun der Aufgabe widmen die Datenbank aus "Mysql" einzubauen. Mit dieser Aufgabe werden wir uns nun von Zuhause aus beschäftigen müssen. 


## Blogeintrag-19.09.2022

Zuhause haben wir nach langem rumprobieren festgestellt, dass die Idee die Datenbank aus "Mysql", die wir erstellt hatten, einzubauen, doch suboptimal verlief, weshalb wir uns dazu entschieden haben, eine Alternative hierfür zu finden. Nach strebsamen Überlegen haben wir ein Konzept gefunden, welches nach dem Prinzip eines Wörterbuches funktioniert, und die Rolle der vorher geplannten "Mysql" Datenbank übernehmen soll. 
Das Tool trägt den Namen "JSON" und hat uns in der ersten Zeit Schwierigkeiten bereitet, weil wir es nicht geschafft haben, dass Tool so zu integrieren, sodass es seiner Aufgabe nachkommt. Nach langem rumprobieren, waren wir dann in der Lage dieses Tool richtig einzubauen. 

## Blogeintrag-22.09.2022

Jetzt waren  wir nun fast so weit unseren Vokabeltrainer zuende zu stellen. Der Vokabeltrainer war nämlich zwar nun schon in der Lage einige Vokabeln zu erkennen, jedoch war dies nur auf ungefähr die Hälfte der Vokabeln zutreffend. Außerdem musste die Seite jedes mal aufs Neue geladen werden, damit die nächste Vokabel durch Zufall ausgegeben wurde. Insgsammt waren also dies die 2 mängel, die noch behoben werden mussten. Nach der ersten Stunde waren wir in der Lage dafür zu sorgen, dass nach dem Erkennen der richtigen Vokabelübersetzung die nächste Vokabel bereits ausgegeben wurde, aber das Problem, dass nicht jede Übersetzung erkannt wurde, bestand leider immer noch. Selbst nach dem Ende der beiden heutigen Informatikstunden wurde das Problem mit der Erkennung immer noch nicht behoben. Daraus folgt, dass wir in der nächsten Stunde daran arbeiten werden.

## Blogeintrag-26.09.2022

Die Spracherkunnung wurde heute nochmal mehrmals getestet und funktioniert einwandfrei. Eine Vorlese Stimme, welche die abgefragten Vokabeln vorliest, wurde ebenfalls eingebaut, funktioniert aber leider nicht bei Apple-Geräten im Browser, weil es von dem Ios-Betriebssicherheitssystem blockiert wird. Zum Glück bezieht sich dies nur auf Webseiten, weshalb wir das Problem mit der Umwandlung unseres Trainers in eine App beheben können. Ebenfalls hatten wir uns überlegt eine Funktion einzubauen, um Vokabeln, die man nicht kennt, überspringen zu können. Dies soll unter dem Begriff "weiter" erfolgen. Leider ist dies nun zu unserer größten Herausforderung geworden, weshalb wir uns damit noch mehr auseinandersetzen werden. Ein Richtig- bzw. Fehlcounter wurde zudem noch eingebaut, um eine Aussagekraft darüber treffen zu können, wie viele Vokabeln man bis jetzt richtig beantworten konnte und nicht. Die grüne "0" steht dabei für die Anzahl der richtig beantworteten Vokabeln und die rote "0" für die nicht beantworteten Vokabeln.

## Blogeintrag-06.10.2022

Heute beschäftigen wir uns  damit, die Text-to-speech Funktion in unseren Vokabeltrainer einzubauen, sodass das Gezeigte automatisch vorgelesen wird. Zudem möchten wir einen "Button" einbauen, der dem Nutzer ermöglichen soll, direkt auf knopfdruck zurück zum Menü zu gelangen. Der Einbau des Buttons lief relativ fix ab, während das Einbauen der Tex-to-speech Funktion Zeit brauchte. Mit dem Online-Dienst "[AppsGeyser]("https://www.apssgeyser.com)" konnten wir die Webseite bereits zu einer Android App konvertieren. Das nächste Ziel ist es nun, die App auch für iOS Geräte verfügbar zu machen.


## Blogeintrag-24.10.2022

Leider scheiterte das "VocabNow" Projekt daran, dass wir einen Apple-developer Account benötigten, um unsere schlussendlichen Ziele zu verwirklichen, was aber mit einem Preis von 100€ finanziell nicht machbar war. Deshalb entschlossen wir uns, in den 2-Wöchigen Herbstferien dazu, ein neues Projekt zu erstellen, welches nicht aufgrund von finanziellen Gründen scheitern sollte. Wir erstellten also eine Evolutionssimulation und waren innerhalb der Ferien mit dem Projekt beinahe fertig. Heute arbeiteten wir an einzelnen Details und fügten noch genauer , um die Funktionen unseres neuen Projekts verständlich zu erklären. Desweiteren übersetzen wir einzelne Dinge in die deutsche Sprache, weil dies ebenfalls ein Teil der Arbeit war, um die Dinge noch verständlicher zu machen. 

## Blogeintrag-03.11.2022

Da wir mit den Funktionen des Projektes entgültig fertig sind, haben wir uns heute hauptsächlich weiterhin mit dem Erstellen der Kommentare, um unser Projekt so verständlich und anschaulich wie möglich schlussendlich präsentieren zu können, beschäftigt. Da aber heute Laurenz nicht anwesend ist, beschäftige ich mich heute ausschließlich damit unsere Blogeinträge bei Github zu verschönern und strukturierter wirken zu lassen. Dabei habe ich einen Blick in unsere bisherigen Einträge geworfen und mögliche Teile abgeändert. Zudem sind ich und Laurenz der Meinung, dass eine Tabelle, die alle Blockeinträge nochmals geordnet und übersichtlich auflistet, eine Notwendigkeit ist, weshalb ich in dieser Doppelstunde eine ertstellt habe. Zudem möchten wir an einigen Stellen zusätliche Bilder in die Blogeinträge einfügen, um das geschriebene zu visualisieren. Besonders bei Prozessen, die sich nicht in Bildern erklären lassen, habe ich mich dazu entschieden "GIFs" einzublenden, weil ganze Videos den vorgegebenen Rahmen sprengen würden.


## Blogeintrag-07.11.2022

In der heutigen Doppelstunde haben wir weiterhin an den genannten Plänen vom 03.11.2022 gearbeitet, also unteranderem weitere Grafiken und Texte zu der erklärung unseres Projektes erstellt. Dabei haben wir [Carbon] (https://carbon.now.sh/) für unser Design genutzt, um unsere Protokolierung ansprechender und schöner zu gestalten. Dies haben wir allerdings nur für die Gestaltung unsereres Quelltext genutzt, da wir für das Erstellen aller weiteren Grafiken die Website [Carvas] (https://carbon.now.sh/) genutzt haben.


## Blogeintrag-14.11.2022

In dieser Doppelstunde musste Herr Buhl krankheitsbedingt ausfallen, wodurch ich und Laurenz selbstständig an der Eklärung unseres Projekts "Survival of the fittest"  weiter gearbeitet haben. Wir hatten hierzu Kommentare im Quelltext überarbeitet und die Erklräungstexte nochmals verbessert formuliert, weil diese unserer Ansicht nach nicht verständlich genug waren. Außerdem haben wir noch passende Abbildungen zu den Texten zur Visualisierung hinzugefügt. Bei der Bearbeitung ist uns noch aufgefallen, dass die Quellen bei den verschiedensten Dingen fehlten, weshalb wir diese raussuchen mussten, und in die passenden Zeilen in den einzelnen Texten ergänzt haben. 

## Blogeintrag-17.11.22 

Die heutige Arbeit war sehr erfolgreich, da wir dazu im Stande die Überschrift für unser Projekt zu designen. Darüberhinaus erstellten wir eine Tabelle, um den Mutationswert und dessen Funktion zu erklären, weil dieser Aspekt in unserem Projekt schwierig nur durch einen Text zu verstehen ist. In der abschließend übrig gebliebenen Zeit die wir noch für die Fertigstellung unseres Projekts haben, werden wir noch den Fokus auf die Erklärung der Bewegung setzen, weil diese der Kernaspekt unseres Projekts ist, und am schwierigsten zu verstehen ist.  

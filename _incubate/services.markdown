# Paradigmo #

Im Moment stelle ich mir folgendes Szenario vor (falls wir Github benutzen möchten)

* jeder von uns hat einen Account (oschrenk, mzloch)
* unsere "Firma" bekommt ihren eigenen Account (paradigmo)

Einer von uns muss dann diesen Account verwalten. Laut Lizenzbestimmungen von Github müsste ich das dann sein, da jeder Nutzer nur einen freien Account haben darf. Ich denke es ist da aber kein Problem, wenn ich dir dann die Logindaten gebe, damit du im Fall der Falle ein Projekt anlegen darfst.

Github hat folgende Features, die wir nutzen können:
* Jedes Projekt kann ein Wiki haben
* Jedes Projekt kann eine eigene Website bekommen (nur statische Seiten)
* jeder Benutzer kann eine eigene Website bekommen (nur statische Seiten)
* jedes Projekt bringt Issue-Tracking Tool mit sich

Mit dem Layout sollten wir eigentlich alle Fälle abdecken können:
* private Projekte bleiben im jeweiligen Benutzeraccount
* "Firmen"-spezifische Projekte können wir dann direkt im Account der "Firma" hosten
* wir können eine Firmenseite kreieren, sehr simpler Blog

Wenn wir neue Projekte anlegen tun wir das im Firmenaccount, und fügen als Collaborators hinzu. Jeder kann dann das Projekt auschecken und daran arbeiten (dank Git auch offline). Irgendwann wir dann die Arbeit _gepusht_ (das heißt die lokalen Commits auf den Server geschoben). Von Änderungen im Repository kann man benachrichtigt werden (zumindest über RSS Feed). Hier werden sich sicher kleine Probleme einstellen was Git angeht. Ist einfach wir uns beide ein neues Werkzeug. Aber das ist ja gewollt, man wächst ja an Problemen.


Der Blog der Firma kann wie gesagt über ein eigenes Repository gepflegt werden (was ich einfach total genial finde). Man legt einfach ein repository namens firma.github.com an und kann dort Seiten ablegen die dann über http://firma.github.com zugänglich sind.

Dieses Feature wird gestützt durch Jekyll (eine Blog/Statische Seiten Generator, mit Ruby geschrieben). Das  heißt im Klartext, dass man mit Markdown (und ich glaube auch anderen anderen Markupsprachen) Artikel, Posts, schreiben kann, die man dann durch Templates jagen kann um am Ende html Seiten zu generieren. So lange man einigen Konventionen folgt, kann man damit sehr schnell Ergebnisse bekommen. Und da schönste: Man verlässt seinen gewohnten Editor und die geliebte Kommandozeile nicht.

Wie das genau funktioniert weiß ich leider auch nicht. Ist eine nette Aufgabe für das erste Treffen.

Daneben habe ich noch eine Idee für ein Repository in dem wir Ideen, Diskussionen und so weiter auslagern. Ob das im Wiki zum dazugehörigen projekt passiert oder dann auch mit Hilfe von Textdateien kann man dann gucken. Das Repository kann mann dann ja "labor", "lab", "brainstorm", "talk", "ideas" oder sonstwie nennen.

Den Rest der Kommunikation geschieht sonst über Email und ganz wichtig einfach persönlich jede Woche (spätestens).

Erste Aufgaben:

* Namen für "Firma" finden
** hier kann man schon einen Prozess Brainstorm definieren wenn man möchte
* Ziel der Firma definieren
** Agenceum: http://davidseah.com/agenceum/about
** http://davidseah.com/agenceum/archives/15
** nur lernen?
** clients?
** eigenes Produkt?
* Workflow definieren
** agile? :)
** Agenceum Workflow: http://davidseah.com/agenceum/archives/187
* Github Acccounts eröffnen
* Jekyll einrichten
* ersten Post schreiben
* "labor" repository einrichten
* Besprechen wie Ideen gespawnt werden (Workflow?)

Ich finde es ganz spannend das Ganze öffentlich zu machen. Da ich trotzdem keinen "Mist" online stellen möchte, sollten wir uns auf eine Veröffentlichungsstrategie einigen

Mögliche Strategien:
* alles aufschreiben, alles ins Repository, wenn sich was ändert, ändern > dann kann schon mal "Mist" online stehen
* alles aufschreiben, wenn etwa in Zweifel nicht gefällt, "wegstreichen" und nur das was gefällt online stellen, damit am Ende des Tages etwas online ist.

# Namen #

Paradigmo
MetaCortex
Platzhaltr

# Ideen #

## Mac ##

Todo in Menu Bar, Track time
Find Music, Music Browser, PS3
Serien Anwendung, Wann läuft was?

## Other ##

CRM
FinanceManager
FlickrFile System /fuse /c
Natural Language for dates & appointments /java /language
Screenschots von einer Website mit Java /java
Email Client like HitList
Notification System mit Droids 
Orte auf Bahn/Bus mappen und Streckenalternativen anbieten
Email Watcher /imap 
Email Statistik 
Email TIme outs
Briefe mit Latex mit MMD
Social Graph/Remcommendation Engine
Webhooks
Konzerte in meiner Nähe
Würfelproramm für Shadowrun (Ruby, Objective C)

## Sprachen ##

Ruby
Clojure
Objective C

## Technologien ##

Map Reduce
Database Versioning
Google App Engine
Drools
OpenID
OAuth
Google Web Toolkit
Google Maps
iPhone/iPad
Android
Jersey Rest API
S3
EC2
Firefox Extension
Google Chrome Extension
Microformats
Rollback auf Clientseite mit html5 cache
Domain Specific language with java

## Learning ##

Was für Sprachen gibt es? Funktional, ...
Branching Stratgeies
Reesase Strategies (Semantic Versioning)
Domain Specific Languages

## Fields ##

Kommunikation

## Awesome Services ##

http://typewith.me/sfNmk7FfCt
https://etacts.com/

# Firmenpolitik #

Employee cookbook


* The content should be a tutorial and/or a how-to guide;
* You must provide the necessary information for the newbie to do the work by themselves;
* Include all code conventions;
* Short project descriptions;
* Essential code examples.
	
http://misko.hevery.com/2008/07/16/top-10-things-i-do-on-every-project/

Worktije http://blog.metalabdesign.com/post/435902901/getting-real-about-office-hours

## User Experience ##

Ambiguity and Noise kill the user experience

## Feedback Loop ##

Feedback Loop
1 Woche
3 Monate
1 Jahr


Termine bestätigen
1 Woche vorher per EMail
1 Tag vorher mit SMS


# Favorite Deveopers #

"Miško Hevery":http://misko.hevery.com/

Stefan Tilkov

# Website #

haltr.com

platz.haltr.com
platzhaltr.com

todo.platzhaltr.com

todo.haltr.com
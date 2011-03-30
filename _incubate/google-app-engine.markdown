---
layout: post
title: Website
author: Oliver Schrenk
---

[GitHub][github] erlaubt das Veröffentlichen und hosten von statischen Webinhalten. Es wird eine Website für den Benutzer und für jedes Projekt unterstützt - natürlich alles über Git repositories.

Eine Benutzerseite wird eingerichtet indem man einfach ein GitHub repository namens `benutzername.github.com` anlegt, dort eine `index.html` in den `master` branch pusht. Die Seite ist dann unter `benutzername.github.com/index.html` erreichbar`.

Projektseiten funktionieren ein wenig anders. Dazu muss ein root branch im repository angelegt werden. Angenommen der Name des repositories ist `test`, dann

	$ cd /pfad/zu/projekten/test
	$ git symbolic-ref HEAD refs/heads/gh-pages
	$ rm .git/index
	$ git clean -fdx
	
Das Arbeitsverzeichnist ist nun leer (keine Angst, das Projekt ist immer noch im `master``branch`). Inhalte, die nun im branch `gh-pages` angelegt werden werden dann auf GitHub veröffentlicht und sind dann unter `http://benutzername.github.com/test` erreichbar.

	$ echo "My GitHub Page" > index.html
	$ git add .
	$ git commit -a -m "First pages commit"
	$ git push origin gh-pages

Der Veröffentlichungsprozess kann in beiden Fällen ein paar Minuten in Anspruch nehmen.

Über `html` Seiten hinaus unterstützt GitHub auch die Generierung von Inhalten mit Hilfe von [Jekyll][jekyll]. Jede GitHub Seite wird durch die Jekyll Engine gejagt.



[github]: http://github.com/
[jekyll]: http://wiki.github.com/mojombo/jekyll/install

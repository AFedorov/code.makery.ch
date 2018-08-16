+++
title = "Icons auf Website verwenden"
date = 2018-08-16
description = "Icons mit Icon Fonts auf einer Webseite einbinden. Links zu verschiedenen Bibliotheken für Icons."
prettify = true
comments = true
commentsIdentifier = "/library/more-html-css/de/icons/"
aliases = [ 
  "/library/more-html-css/de/icons/" 
]
weight = 2

# Custom Sidebars
[[sidebars]]
header = "Links"
[[sidebars.items]]
text = "<i class=\"fa fa-fw fa-external-link\"></i> HTML & CSS Tutorial"
link = "/de/library/html-css/"
+++

Icons in eine Webseite einzufügen ist nicht schwer. Aber wenn man Texte und Icons kombiniert (z.B. für einen Button) oder wenn die Icons in der Grösse veränderbar sein sollen, dann wird es schwierig.

Die Lösung für dieses Problem sind **Icon Fonts**. Icon Fonts sind Schriftarten, welche anstatt Buchstaben nur Icons enthalten. Dadurch können diese Icons genauso verwendet werden, wie gewöhnliche Schriften, d.h. man kann ihre Grösse und auch die Farbe verändern. 

<i class="fa fa-umbrella" style="color: #333"></i> 
<i class="fa fa-umbrella fa-3x" style="color: #333"></i> 
<i class="fa fa-umbrella fa-5x" style="color: #333"></i>
<i class="fa fa-umbrella" style="color: #ffc107"></i> 
<i class="fa fa-umbrella fa-3x" style="color: #ffa000"></i> 
<i class="fa fa-umbrella fa-5x" style="color: #ff6f00"></i>


Im Folgenden schauen wir ein paar Icon Fonts und deren Verwendung an.


## Glyphicons (mit Bootstrap 3)

<div class="alert alert-warning">
Falls Sie Bootstrap in Ihrem Projekt noch nicht integriert haben, lesen Sie zuerst den Teil über <a href="/library/html-css/de/part6/" class="alert-link">Bootstrap Framework verwenden</a> aus dem HTML & CSS Tutorial.
</div>

Wenn Sie Bootstrap verwenden, dann sind bereits 200 Icons von [Glyphicons](http://glyphicons.com/) integriert.

Sie finden eine Liste der Verfügbaren Icons in der [Bootstrap Dokumentation unter Glyphicons](http://holdirbootstrap.de/komponenten/#glyphicons).

Um ein Icon zu verwenden definieren wir jeweils ein `<span>`-Element und geben ihm zwei CSS-Klassen:

<pre class="prettyprint lang-html">
&lt;span class="glyphicon glyphicon-send">&lt;/span>
</pre>

Dieses `span` kann nun irgendwo eigenfügt werden. Zum Beispiel in den Titel einer Kontaktseite: 

![Kontakt Icon](contact-icon.de.png)


## Font Awesome

Eine der bekanntesten frei verfügbaren Icon Fonts ist [Font Awesome](http://fontawesome.io/). Font Awesome kommt mit über 500 Icons.

Um [Font Awesome zu integrieren](http://fontawesome.io/get-started/) steht wie für Bootstrap auch ein CDN-Link zur Verfügung. Damit muss gar nichts heruntergeladen werden, sondern wir können einfach einen Link zum CSS in den `<head>`-Bereich unserer HTML-Datei einfügen:

<pre class="prettyprint lang-html">
&lt;link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
</pre>

**Hinweis:** *Schauen Sie auf [Font Awesome](http://fontawesome.io/get-started/) nach, welches der aktuelle Link mit der neusten Versionsnummer ist.*

Wie bei den Glyphicons werden die Font Awesome Icons mit zwei CSS-Klassen verwendet. Anstelle des `<span>`-Elements wird bei Font Awesome meistens das `<i>`-Element verwendet, wobei dies eigentlich keine Rolle spielt.

<pre class="prettyprint lang-html">
&lt;i class="fa fa-flag">&lt;i>
</pre>

Dieses Beispiel gibt uns eine Flagge: ![Font Awesome Flagge](fontawesome-flag.png)

Schauen Sie sich die [Beispiele auf Font Awesome](http://fontawesome.io/examples/) an, um zu sehen, auf welche Arten die Icons verwendet werden können. Sie finden dort auch Beispiele zur Verwendung mit für Bootstrap 3. 


## Weitere Möglichkeiten

* Eine Liste von [12 kostenlosen Icon Fonts](http://t3n.de/news/10-kostenlose-icon-fonts-450651/).
* Auf [IcoMoon](https://icomoon.io/) gibt es eine App, um eine eigene Icon Font zusammen zu stellen.
* [Fontello](http://fontello.com/) ist ein weiterer Generator, um eigene Icon Fonts zu erstellen.
* [Iconfinder](https://www.iconfinder.com/) - Viele frei verfügbare Icons (Achtung: je nach Lizenz muss der Author genannt werden)


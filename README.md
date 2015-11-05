# Flexbox

Layouting mit CSS. Mit Flexbox kann man Layoutelemente definieren und festlegen wie sich die Kindelemente dieser verhalten sollen.

**Browsersupport:** <http://caniuse.com/#search=flexbox>  

**Umfangreicher Artikel mit Grafiken:** <https://css-tricks.com/snippets/css/a-guide-to-flexbox/>

<p data-height="268" data-theme-id="6054" data-slug-hash="dYvpyN" data-default-tab="result" data-user="matuzo" class='codepen'>See the Pen <a href='http://codepen.io/matuzo/pen/dYvpyN/'>dYvpyN</a> by Manuel Matuzovic (<a href='http://codepen.io/matuzo'>@matuzo</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
<script async src="//assets.codepen.io/assets/embed/ei.js"></script>

## Beispiele

<http://codepen.io/collection/XbNeoN/>

## Eigenschaften für das Elternelement

### display
Flex Container definieren.  

`display: flex;`  

**flex:** Volle Breite und Zeilenumbruch  
**inline-flex** So breit wie sein Inhalt und kein Zeilenumbruch

	ul { 
	  display:flex;
	}

<http://codepen.io/matuzo/pen/vNzmKe>


### flex-direction
Achse und Richtung der Ausrichtung

`flex-direction: row-reverse;`  

**row:** links nach rechts  
**row-reverse:** rechts nach links  
**column:** von oben nach unten  
**column-reverse:** von unten nach oben

<http://codepen.io/matuzo/pen/QjVvKY>



### flex-wrap
Verhalten ob Kindelemente in einer oder mehreren Zeilen dargestellt werden sollen

`flex-wrap: wrap-reverse`  

**nowrap:** alles in einer Zeile (default)    
**wrap:** mehrere Zeilen  
**wrap-reverse:** mehrere Zeilen rechts nach links

<http://codepen.io/matuzo/pen/xwadgE>

### justify-content
Ausrichtung der Inhalte  

`justify-content: center`

**flex-start:** default  
**flex-end:** Am Ende positioniert  
**center:** Inhalte zentrieren  
**space-between:** Gleichmäßig verteilt. Erstes am Anfang, Letztes am Ende  
**space-around:** Gleichmäßig verteilt mit gleich viel Abstand links und rechts.  

<http://codepen.io/matuzo/pen/YyOVNr>

### align-items

Ausrichtung der Elemente auf entgegengesetzter Achse.

**flex-start:** Am Anfang  
**flex-end:** Am Ende positioniert  
**center:** Inhalte zentrieren  
**strech:** Höhe des Elternelements (default)

<http://codepen.io/matuzo/pen/QjVvgP>

### align-content

Ausrichtung der Linien auf der entgegengesetzten Achse. Funktioniert nur bei mehreren Zeilen.

**flex-start:** default  
**flex-end:** Am Ende positioniert  
**center:** Inhalte zentrieren  
**space-between:** Gleichmäßig verteilt. Erstes am Anfang, Letztes am Ende  
**space-around:** Gleichmäßig verteilt mit gleich viel Abstand oben und unten.  

<http://codepen.io/matuzo/pen/NGLjYm>


## Eigenschaften für das Kindelement

### order 

Reihenfolge der Darstellung unabhängig von der Reihenfolge im DOM

`order: 2`

<http://codepen.io/matuzo/pen/BoORxv>

### flex-grow

Verteilung des zur Verfügung stehenden, restlichen Platzes.

`flex-grow: 1`  

Wenn alle Elemente den Wert `1` besitzen, wird der zur Verfügung stehenden, restliche Platz gleichmäßig verteilt. Wenn eines davon beispielsweise den Wert `2`  hat, bekommt es doppelt so viel wie alle anderen vom zur Verfügung stehenden, restlichen Platz.

#### flex-basis

Defaultgröße eines Elements

`flex-basis: 500px;`

<http://codepen.io/matuzo/pen/MaqmBa?editors=110>

#### flex-shrink

Platz der reduziert werden soll, wenn die Breite des Elements unter der Defaultgröße liegt.

`flex-shrink: 2;`

#### flex

Kurzschreibweise für `flex-grow`, `flex-shrink` and `flex-basis`.

`flex: 1 2 500px;`

## Hausübungen

* **[016_flexbox_basics](https://github.com/SAEwien/Uebungen/tree/master/htmlcss/016_flexbox_basics)**  
Simples Flexbox Beispiel

* **[017_flexbox_gleiche_spalten](https://github.com/SAEwien/Uebungen/tree/master/htmlcss/017_flexbox_gleiche_spalten)**  
Gleich breite Spalten mit Flexbox

* **[018_flexbox_layout_2spalten](https://github.com/SAEwien/Uebungen/tree/master/htmlcss/018_flexbox_layout_2spalten)**  
2-spaltiges Layout mit Flexbox

* **[029_flexbox_3elemente2spalten](https://github.com/SAEwien/Uebungen/tree/master/htmlcss/029_flexbox_3elemente2spalten)**  
2 Spalten - 1. 1 Element, 2. 2 Elemente untereinander

* **[030_flexbox_layout](https://github.com/SAEwien/Uebungen/tree/master/htmlcss/030_flexbox_layout)**  
Flexbox Website Layout

* **[032_layout_orf (Variante 3)](https://github.com/SAEwien/Uebungen/tree/master/htmlcss/032_layout_orf)**  
Artikelteaser, ähnlich wie bei orf.at, stylen

# Sonstiges

<http://caniuse.com/#search=calc>


#### Cheatsheet: Elemente für die Auszeichnung von Korrespondenzen in TEI

**ACDH Tool Gallery 2.2: TEI Basics – A gentle introduction to Text Encoding**,  
Wien, 26. September 2016

##### Korrespondenzspezifische Metadaten

**`<correspDesc>`** Stellt detaillierte, für Korrespodenzen spezifische Metadaten zur Verfügung, unter besonderer Berücksichtigung der kommunikativen Aspekte. Innerhalb von `<profileDesc>`, enthält `<correspAction>` und `<correspContext>`.   
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-correspDesc.html>

**`<correspAction>`** enthält eine strukturierte Beschreibung von Ort, Person/Organisation und Datum von mit der Korrespondenz verbundener Aktionen, z.B. das Senden oder Empfangen der Nachricht.
`@type`	beschreibt die Art der Aktion. Empfohlene Werte: `sent`, ` received`, `transmitted`, `redirected`, `forwarded`.  
<http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-correspAction.html>
    
**`<correspContext>`** beschreibt den Kontext der Korrespondenz, enthält Referenzen zu vorangegangenen und nachfolgenden Briefen.   
<http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-correspContext.html>


##### Auszeichnung von Textstrukturen in Briefen
###### Allgemeine Elemente
**`<div>`** kodiert einen Unterabschnitt in einem Text.  
<http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-div.html>

**`<p>`** kodiert einen Absatz in Prosa.  
<http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-p.html>

**`<head>`** kodiert die Überschrift eines Abschnitts, kann am Beginn von `<div>` stehen.   
<http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-p.html>

**`<lb/>`** kodiert einen Zeilenumbruch.  
<http://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-lb.html>


###### Briefspezifisch
**`<opener/>`** Fasst Datumszeile, Verfasserangabe, Anredeformeln und ähnliche Angaben zusammen, die am Beginn eines Briefes stehen.  
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-opener.html>

**`<closer/>`** Fasst Datumszeile, Verfasserangabe, Grußformeln und ähnliche Angaben zusammen, die am Ende eines Briefes  stehen.  
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-closer.html>

**`<salute/>`** enthält eine Anrede oder Grußformel. Innerhalb von `<closer>` oder `<opener>`.   
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-salute.html>

**`<dateline/>`** enkodiert das Datum und den Ort des Schreibens. Innerhalb von `<closer>` oder `<opener>`.  
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-salute.html>

**`<signed/>`** kodiert die Signatur oder den Namen des Schreibers/der Schreiberin.  
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-signed.html>

**`<postscript/>`** enkodiert das Postskriptum z.B. eines Briefes.   
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-postscript.html>

##### Named Entities  
**`<persName>`** enthält einen Eigennamen oder -phrase, der auf eine Person referenziert.   
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-persName.html>

**`<placeName>`** enthält einen Eigennamen, der auf einen Ort referenziert.   
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-persName.html>

**`<rs>`** *Reference string* kodiert einen allgemeinen Namen oder einen kontextabhängigen Verweis auf eine Person/ eine Ort... `@type` bezeichnet die Art des Ziels.  
<http://www.tei-c.org/release/doc/tei-p5-doc/de/html/ref-persName.html>

##### Links
* [Carl Maria von Weber Gesamtausgabe, Briefedition][wega]
* [correspSearch][correspSearch]
* [TEI correspondence SIG][sig]

##### Bibliography
*Peter Stadler, Marcel Illetschko, and Sabine Seifert, «Towards a Model for Encoding Correspondence in the TEI: Developing and Implementing <correspDesc>», Journal of the Text Encoding Initiative [Online], Issue 9|2016, Online since 30 August 2016, connection on 22 September 2016. URL: http://jtei.revues.org/1433; DOI: 10.4000/jtei.1433*

Gerlinde Schneider 2016, <gerlinde.schneider@uni-graz.at>  
[![Creative Commons Attribution-ShareAlike 4.0 International License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

[wega]: http://weber-gesamtausgabe.de/de/Register/Briefe
[correspSearch]: http://correspsearch.net
[sig]: http://www.tei-c.org/Activities/SIG/Correspondence/




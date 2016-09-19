---
title: Outsourcing product development
tags:
- DDD
- product management
- aglie
---

Ich habe in meiner Karierre bisher einige Unternehmen gesehen, die sehr unterschiedlich mit dem Outsourcen von Produkt entwicklungs Projekten umgegangen sind. Eine gewisse Zeit habe ich soger für ein Unternhemen gearbeitet, dessen Kernsgeschäft darin bestand Producktentwicklung als Drittanbieter für andere Unternehmen durchzuführen.

Eingie Unternehmen haben versucht möglichst viele Projekte von extern machen zu lassen i.d.r. aus vermeidlichen Kostengründen. Andere leiden an dem [not invented here syndrom](https://en.wikipedia.org/wiki/Not_invented_here) und versuchen alles Inhouse zu lösen. Prinziell macht Outsourcing unter gewissen Umständen Sinn. Aber egal ob man sich für oder gegen Outsourcing entscheiden, gehen mit der Entscheidung immer gewisse Risiken einher. Meine Erfahrungen damit möchte ich hier geren teilen.

## Know your core domain
Ein Projekt outsourcen bedeutet immer Kontrolle abzugeben. Man muss sich also bei der Frage nach Outsourcing die Frage stellen über welchen Bereich in meinem Unternehmen kann ich es mir leisten kontorlle abzugeben. I.d.r will man die kontrolle über den Treiber [drivers of the business model](http://www.startuplessonslearned.com/2008/09/three-drivers-of-growth-for-your.html) des Geschäftmodelles behalten, da hier das Risiko am größten ist und es am notwendigsten ist schnell und flexibel Anpasssungen machen zu können. In einem Unternehmen hat man heutzutage i.d.r eine vielzahl von unterschiedlichen Domänen. In einer größeren Entwicklunsfirma könnten das z.B. neben der Produktentwicklung noch folgende Bereiche sein.

- Marketing
- HR
- Public Relations
- Community Management
etc.
 
Im Domain Driven Design unterscheidet man zwischen folgenen unterschiedlichen Domain Typen:
- Generic Domain, A generic domain is one that is universally well-known, without any need for specialization in the core domain.
- Supporting Doamin, A support domain is a part of the domain that indirectly supports the core domain without actually belonging to it.
- Core Domain, The core domain is the part of the domain most closely associated with the strategy of the company.
[Core Domain](http://blog.zenmodeler.com/enterprise-design/2012/05/29/domain-driven-design-distillation-support-generic-and-core-domain.html) 

Das Risiko das bei der abgabe von Kotrolle also dem Outsourcen ist bei der Generic Domain gering. Bei einer Supporting Domain mittel und bei der Core Domain hoch.

Es ist kein Problem ein Projekt in einer Generic Domain out zu sourcen und es ist eine gängige Praxis das zu tun. Beispiel : Datev für Gehaktsabrechungen. In der Core Domain ist ein Outsourcing aufgrund des hohehn risikos eher unüblich. Überlegt man ein Projekt in einer Supporting Domain abzugeben muss man sich folgende Punkte genau ansehen:

-  Ist es wert das Risiko des möglichen Kontrollverlustes einzugehen, weil ich durch einen externen Partner folgende Vorteile erhalte:
- Verfügbarkeit
- Kompetence
- Veringertes unternehmerisches Risko, da ich mich nicht dauerthaft an zusätzliche Mitarbeiter binden muss.
 

## Keep control
Wie schon geschrieben entsteht das Risiko beim Outsourcing vorallem durch den Verlust an Kontrolle. Agiles Productmangement bietet ein paar mechanismen, die es ermöglichen diesen Kontrollverlsut zu veringern. Bei der Auswahl eines externen Partners ist es also wichtigt auf die Möglochkeit zu achten in wie weit solche mechanismen zu etablieren. Natürlich bedeutet es i.d.r. auch ein höheres Risiko für den Partner. Das Risiko ist so oder so da, man kann nur versuchen mit dem Partner zu verhandeln, das es gelichmäßig auf beide Partner verteilt ist.
  
Boris Gloger beschreit in seinem Buch [Der agile Festpreis](https://www.amazon.de/agile-Festpreis-Leitfaden-erfolgreiche-Projekt-Verträge/dp/3446432264) eine Mehode, wie man einen agilen Vertrag mit einem Zulieferer auch rechtlich bindend abschließen kann. Ob man sich nun für diese Methode entschiedet, oder einen weniger offiziellen Rahmen vereinbart. Die wesentlichen Punkte sind folgende:

- Iteratives arbeiten mit regelmäßigen Reviews (z.B. Scrum)
- Nach jeder iteration hat der Kunde die Möglichkeit das Projekt abzubrechen, oder die nächste Iteration zu beauftragen vs. Time and Material
- Es sollte daruf hingearbeitet werden, das nach jeder Iteration wert geliefert wird (funktionierende Software)
- Mit Jeder Iteration hat man die Möglichkeiten auf basis des gelernten die Anforderungen an das Projekt anzupassen   
- Der Zuliefer commitet sich auf das erreichen eines Zieles und nicht auf das Umsetzen von Anforderungen
- Eine Direkte Kommunikation mit den Entwicklern ist jeder Zeit möglich und gewünscht
- Die Sprint länge ist verhandelbar. Schnelleres Feedback vs. die Möglichkeit funktionsfähige Software zu bauen


## How to choose a external partner
Es ist im prinzip Unmöglich einen Partner nach dem besten Preis auszuwählen. Preis ist ein Faktor in dem Entscheidungsprozess, aber eher der letzte Punkt den man sich ansieht. Man benötigt also eine Möglichkeit einen Partner nach anderen kriterien objektiv zu bewerten. In einem meiner letzten Projekte haben wir es anhand einer Nutzwertanalyse getan.

Mögliche Partner haben uns aufgrund einer ersten Anfrage ein Angebot gemacht. Diese waren aber wenig aussagekräftig, da sie presilich alle sehr nah beieinander lagen und wir uns nicht vorstellen konnten, dass die Partner aufgrund einer knappen Beschreibung unseres Vorhabend wirklich in der Lage sind den Aufwand für eine nötige Lösung verhersagen zu können.



### Value analisis
Im ersten Schritt muss man sich Überlegen, welche Kriterien außer dem Preis das Risiko minimieren können. In unserem Fall waren das folgende Punkte:
  
- Verfügbarkeit
- Kompetenz
- Prozess Kontrolle 
- Risk Share
- Qualität

Wir haben dann einen Fragebogen zusammengestellt, der unterschiedliche Fragen zu jeder Kategorie enthielt. 

Hier ein paar Beispiele (Kompletter Fragenkatalog zum download hier):

*Verfügbarkeit*
- Unter welchen Bedingungen sind persönliche Treffen möglich ?

*Kompetenz*
- Könnt ihr uns Referenzen für ähnliche projekte nennen?

*Prozess Kontrolle*
- Was ist, wenn wir im Verlauf der Entwicklung feststellen, dass wir von dem ursprünglichen Auftrag komplett abweichen müssen ?

*Risk Share*
- Besteht die Bereitschaft, Risiken im Falle von Verzögerungen, Bugs nach Fertigstellung, Ausfällen etc. gemeinsam zu tragen ?

*Qualität*
- Ist es möglich, dass wir konkrete Abnahme-Tests definieren ?

Zu jeder Frage haben wir uns eine optimale Antwort überlegt. Und dann diese  auf einer Skala von 1(unwichtig) - 10 (sehr wichtig) für uns gewichtet.

Beispiele:


 





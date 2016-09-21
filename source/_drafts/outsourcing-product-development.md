---
title: Outsourcing product development
tags:
- DDD
- product management
- aglie
---
I think outsourcing is a valid option to compensate missing inhouse skills or resources, but the desicion for outsourcing always accompanies a certain risk. In my career i have seen companies that deal with outsourcing quite different. 
<!-- more -->

Sometimes companies try to outsource as much product development as possible for cost reasons. Others suffered from the [not invented here syndrom](https://en.wikipedia.org/wiki/Not_invented_here). Some time i even worked for a company whose core business was to do development as a service for other companies. I like to share my experiences with that here in detail.    

## Know your core domain
The most important leasson i have learned so far is that outsourceing always means to give up control. So i think the question companies should be able to answer, when they consider to outsource product development is, for which area of their business they can affort to give up control.
 
I think companies should always keep control of their [drivers of the business model](http://www.startuplessonslearned.com/2008/09/three-drivers-of-growth-for-your.html), because here it is crutial to be stay flexible and to align as fast as possible when it is needed. In that area the entrepreneurial risk is always very high. 

But today companies need to deal with lots of different domains beside their core business. In a product development company that could be also:

- Marketing
- HR
- Public Relations
- Community Management
a.s.o.

Domain Driven Design differs here between three different types of [domains](http://blog.zenmodeler.com/enterprise-design/2012/05/29/domain-driven-design-distillation-support-generic-and-core-domain.html)  

*Generic Domain*
 A generic domain is one that is universally well-known, without any need for specialization in the core domain.

*Supporting Doamin* 
A support domain is a part of the domain that indirectly supports the core domain without actually belonging to it.

*Core Domain* 
The core domain is the part of the domain most closely associated with the strategy of the company.

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

Zu jeder Frage haben wir uns eine optimale Antwort überlegt. Und dann diese  auf einer Skala von 1(unwichtig) - 10 (sehr wichtig) für uns gewichtet. Auf diese Art und Weise konnten wir auch sehen, welche der Kategorien für uns am wichtigsten ist.
Für die spätere protierung der gewichtung auf eine Punkteskala wird noch der Anteil der einzelnen Frage an den Gesamtpunkten der Gewichtung in Prozent umgerechnet.

- Insgesamt vergebene Gewichtungspunkte/ Gewichtungspunkte Frage A

Beispiele:


*Verfügbarkeit*
- Unter welchen Bedingungen sind persönliche Treffen möglich ?

  Wir stehen jeder Zeit für einen persönlichen Kontakt zur Verfügung. wir sind uns darüber bewusst, dass direkte Kommunikation die effizienteste Art der Kommunikation ist.

*Kompetenz*
- Könnt ihr uns Referenzen für ähnliche projekte nennen?

  Wir haben ein Änliches Projekt einmal bei XY umgesetzt, gerne stellen wir eine Kontakt her.

*Prozess Kontrolle*
- Was ist, wenn wir im Verlauf der Entwicklung feststellen, dass wir von dem ursprünglichen Auftrag komplett abweichen müssen ?

  We embrace Change. Wir arbeiten Agil und sind uns bewusst, das es nicht darum geht einen plan oder eine anfängliche Idee zu verfolgen, sondern mit euch zusammen ein Ziel zu erreichen.

*Risk Share*
- Besteht die Bereitschaft, Risiken im Falle von Verzögerungen, Bugs nach Fertigstellung, Ausfällen etc. gemeinsam zu tragen ?
  
  Wir garantieren, dass wir funktionsfähige Software liefern. Bugs werden kostenfrei behoben, bei Schäden die durch von uns verschuldetet Ausfälle entstehen, leisten wir entsprechende Kompensation.
  

*Qualität*
- Ist es möglich, dass wir konkrete Abnahme-Tests definieren ?
 
  Ja. Nach weclhen Kriterien eine Softwareinkrement als fertig betractet werden kann, bestimmt der Auftrafgeber.

 
Alle Fragen wurden an die möglichen Partner mit der Bitte diese zu beantworten verschickt. Als alle Partner geantwortet hatten, haben wir die Antworten nach dem Erfüllungsgrad der Idealantwortet auf einer skala von 1 (komt der Ideal Antwort nicht nahe)- 10 (entspricht der Idealantwort) bewertet.

In Verbindung mit der vorherigen Gewichtung der Fragen in % konnten wir nun pro Partner ein Scorring von 1 -10  ermitteln.

    
|Categorie|Question|Ideal Answer|Importance|Answer Partner A|Fulfillment Parner A|Score Parner A|Answer Partner B|Fulfillment Partner B|Score Parner B|
|---------|--------|------------|----------|----------------|--------------------|--------------|----------------|---------------------|--------------|

Im letzten Schritt konnten wir nun das Verhältnis zwischen erreichten Punkten und dem Preis pro Partner betrachten. Der Partner der das beste Verhältnis zwischen Preis und Value Score hatte, bekam den Zuschlag.

##Conclusion 

---
layout: page
title: Entwickler
permalink: /de/entwickler
language: de
seq: 50
published: true
---

## Architektur

![]({{ "/assets/images/java.png" | absolute_url }}){:width="40px"}
Wir verwenden **Java** als Programmiersprache.

Die kurze Begründung dafür lautet: Java ist seit Jahren für unzählbare "Enterprise-Anwendungen" im Einsatz. Wir sind daher sicher, dass Java auch für unsere Zwecke sinnvoll ist.

Nach einigen Gehversuchen mit [Dropwizard](http://dropwizard.io/){:target="_blank"} haben wir die Entwicklung auf [Spring Boot](https://projects.spring.io/spring-boot/){:target="_blank"} umgestellt. Für den gesamten Entwicklungsprozess möchten wir die Konzepte des [Domain Driven Design](https://de.wikipedia.org/wiki/Domain-driven_Design){:target="_blank"} berücksichtigen. Als Gesamt-Systemarchitektur streben wir eine [Hexagonale Architektur](https://www.maibornwolff.de/blog/von-schichten-zu-ringen-hexagonale-architekturen-erklaert){:target="_blank"} an.

Den ersten Entwurf unserer Systemarchitektur haben wir mittlerweile wieder verworfen - nach den Erkenntnissen aus dem Buch [Implementing Domain Driven Design](http://www.informit.com/store/implementing-domain-driven-design-9780321834577){:target="_blank"} macht eine "traditionelle" Schichtenarchitektur wenig Sinn für langfristige Wartbarkeit und gut testbaren Programmcode. Sehr hilfreich für diese Erkenntnisse war die Präsentation [Agile, Architecture, DDD and CQRS](http://www.slideshare.net/jeppec/agile-ddd-cqrs){:target="_blank"}.


## Mitmachen

Sämtlicher aktueller Programmcode (Java, HTML, CSS, ...) wird unter der [GNU General Public License version 3 (GPL3)](https://en.wikipedia.org/wiki/GNU_General_Public_License#Version_3){:target="_blank"} lizensiert. Dadurch wird gewährleistet, dass jeder freien Zugriff auf den Code hat und ihn für seine Zwecke nahezu beliebig einsetzen darf.

Der Quellcode ist [hier bei github](https://github.com/oregami/){:target="_blank"} zu bekommen.

Der aktuelle Entwicklungsstand kann auf [unserer Entwicklungsseite](https://dev.oregami.org/){:target="_blank"} getestet werden.

**Unterstütze uns bei der Realisierung der ersten offenen Spiele-Datenbank, wir suchen immer weitere Programmierer!**

Zum Einstieg kannst Du in unserem [Entwickler-Forum](https://forum.oregami.org/viewforum.php?f=33){:target="_blank"} vorbeischauen. Am besten direkt im Forum [registrieren](https://forum.oregami.org/ucp.php?mode=register){:target="_blank"} und mitreden!

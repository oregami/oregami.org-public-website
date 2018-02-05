---
layout: page
title: Entwickler
permalink: /de/entwickler
language: de
seq: 50
published: true
---


![]({{ "/assets/images/java.png" | absolute_url }}){:width="40px"}
Wir verwenden **Java** als Programmiersprache.

Die kurze Begründung dafür lautet: Java ist seit Jahren für unzählbare "Enterprise-Anwendungen" im Einsatz. Wir sind daher sicher, dass Java auch für unsere Zwecke sinnvoll ist.

Nach einigen Gehversuchen mit [Dropwizard](http://dropwizard.oi/) haben wie die Entwicklung auf [Spring Boot](https://projects.spring.io/spring-boot/) umgestellt. Für den gesamten Entwicklungsprozess möchten wir die Konzepte des [Domain Driven Design](https://de.wikipedia.org/wiki/Domain-driven_Design) berücksichtigen. Als Gesamt-Systemarchitektur streben wir etwas wie eine [Hexagonale Architektur](https://www.maibornwolff.de/blog/von-schichten-zu-ringen-hexagonale-architekturen-erklaert) an.

Den ersten Entwurf unserer Systemarchitektur haben wir mittlerweile wieder verworfen - nach den Erkenntnissen aus dem Buch [Implementing Domain Driven Design](http://www.informit.com/store/implementing-domain-driven-design-9780321834577) macht eine "traditionelle" Schichtenarchitektur wenig Sinn für langfristige Wartbarkeit und gut testbaren Programmcode. Sehr hilfreich für diese Erkenntnisse war die Präsentation [Agile, Architecture, DDD and CQRS](http://www.slideshare.net/jeppec/agile-ddd-cqrs).  
Aktuell (November 2016) sammeln wir weitere Informationen über Themen wie CQRS und Event Sourcing.

Mitmachen
---------

Sämtlicher Programmcode (Java, HTML, CSS, ...) wird unter der [GNU Affero General Public License (AGPL)](http://www.gnu.org/licenses/agpl-3.0.de.html) lizensiert. Dadurch wird gewährleistet, dass jeder freien Zugriff auf den Code hat und ihn für seine Zwecke nahezu beliebig einsetzen darf. Der Quellcode ist [hier bei github](https://github.com/oregami/) zu bekommen.

**Unterstütze uns bei der Realisierung der ersten offenen Spiele-Datenbank, wir suchen immer weitere Programmierer!**  
Zum Einstieg kannst Du in unserem [Entwickler-Forum](http://forum.oregami.org/viewforum.php?f=33) vorbeischauen. Am besten direkt im Forum [registrieren](http://forum.oregami.org/ucp.php?mode=register) und mitreden!

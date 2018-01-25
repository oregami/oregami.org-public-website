---
layout: page
title: Developers
permalink: /en/developers
---

System Architecture
-------------------

![]({{ "/assets/images/java.png" | absolute_url }}){:width="40px"}
We are using **Java** as our programming language.


The short reason for that is: Java has proven that it is capable to produce enterprise quality applications, so we are sure that it is appropriate for our needs as well.

After some first attempts with [Dropwizard](http://dropwizard.io/){:target="_blank"} we switched to [Spring Boot](https://projects.spring.io/spring-boot/){:target="_blank"}. For the whole development process we will try to apply the concepts of [Domain Driven Design](https://de.wikipedia.org/wiki/Domain-driven_Design){:target="_blank"}. Our system architecture will be inspired by the [Hexagonal Architecture](http://www.slideshare.net/fabricioepa/hexagonal-architecture-for-java-applications){:target="_blank"}.

We discarded our first classical system architecture with the typical layers (GUI, Application, Database). After reading the book [Implementing Domain Driven Design](http://www.informit.com/store/implementing-domain-driven-design-9780321834577){:target="_blank"} there are better ways to create a complex system. Very helpful for these insights was the presentation [Agile, Architecture, DDD and CQRS](http://www.slideshare.net/jeppec/agile-ddd-cqrs){:target="_blank"}.  
Currently (November 2016) we are collecting more information about topics like CQRS und Event Sourcing.

Getting involved
----------------

All of our code (Java, HTML, CSS, ...) is licensed under the [GNU Affero General Public License (AGPL)](http://www.gnu.org/licenses/agpl-3.0.en.html){:target="_blank"}. This way we can guarantee free accesss to the code for everyone for their very own use. The code can be acquired using [github](https://github.com/oregami){:target="_blank"}.  

**Support us with the development of the first truly open game database. We're constantly looking for fresh hacker blood!**  
For easy entry please contact us [in our forums](http://forum.oregami.org/viewtopic.php?f=38&t=32869){:target="_blank"}!

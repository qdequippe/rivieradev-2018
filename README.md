# [RivieraDev 2018](http://rivieradev.fr) talks
Riviera DEV, that's 3 days of conferences and workshops on the French Riviera in the heart of Sophia Antipolis, the most beautiful European technopole.

In 2018, Riviera DEV will move to a bigger and more comfortable venue, with a third track or more depending on registrations!

## Wednesday 16 May 2018

### BEM, la tête la première

**Description**

Il est très facile de faire une modification en CSS. Il est plus difficile de s'assurer que ce changement n'a pas de conséquences indésirables. En suivant une méthodologie comme BEM, vous pouvez organiser votre code en composants, isoler votre code et le rendre plus maintenable !

Dans cette longue conférence, nous verrons ce qu'est BEM et pourquoi vous devriez l'utiliser. Nous prendrons le temps de voir les bonnes pratiques associées, ainsi que ses limitations. A la fin, vous devriez être assez confortable avec la méthodologie BEM pour pouvoir l'essayer sur vos projets, même ceux en cours.

[Slides](https://tzi.fr/slides/riviera2018-bem/)

Par [Thomas Zilliox](https://twitter.com/iamtzi)

## Thursday 17 May 2018

### Astuces pour des CSS orientées composants

**Description**

Avoir des styles orientés composants permet un grand gain en lisibilité et maintenabilité, mais attention, il y a beaucoup de pièges à éviter !

Adopter des outils ou une méthodologie n’est malheureusement pas magique. Même après avoir adopté une méthodologie BEM, vos blocks peuvent être difficilement réutilisables. Même en faisant du CSS-in-JS et du React, un meilleur découpage de composants aurait pu rendre vos styles plus facile à écrire.

Après plus de 10 ans en quête des CSS maintenables, j’ai noté de nombreuses astuces pour créer des composants réutilisables. Des astuces issues de méthodologies fortes comme OOCSS, des idées trouvées en faisant de la veille régulière, mais surtout des règles apprises en faisant des erreurs quotidiennes !

En suivant cette conférence vous apprendrez 7 règles faciles à suivre lors de vos prochaines intégrations, quelque soit votre méthodologie et vos outils.

[Slides](https://tzi.fr/slides/riviera2018-cmp/)

Par [Thomas Zilliox](https://twitter.com/iamtzi)

## Friday 18 May 2018

### Fire & Fury: Java Flight Recorder and Flamegraphs
**Description**
Java Flight Recorder (JFR) is a lightweight profiler that comes with the Oracle JDK (and that will land on OpenJDK in the near future). It's a hidden gem that can help you boost the performance of your apps running on the JVM.

The data recorded with JFR is usually visualised with Java Mission Control (JMC), but in this talk we will show that you can also generate flamegraphs to visualise your performance out of JFR recordings. Flamegraphs are a data visualisation that has been taking momentum in the performance tuning area and is becoming widely used. While people generally use profilers to check CPU-consuming code, we will show how JFR and Flamegraphs can be also used to investigate concurrency, memory allocation and exception-related issues.

[Slides](https://www.slideshare.net/secret/mpuAbsPAD7SM2D)

[Flamegrapher open-source tool](https://github.com/flamegrapher/flamegrapher)

By [Nenad Bogojevic](https://twitter.com/NenadBo) & [Leonardo Gomes](https://twitter.com/lgomes)

### TESTS DE CHARGE AVEC GATLING
**Description**

ou "Comment arrêter de croiser les doigts lorsqu'on passe en prod"
Face à l’explosion du traffic sur internet et la croissance exponentielle de l’économie numérique, la performance des applications devient un enjeu majeur des projets informatiques.
Pourtant, il est fréquent que les équipes adressent mal les tests de charges.
La première partie de cette présentation présente les concepts des tests de charges et leur méthodologie.
La seconde se focalise sur Gatling. Gatling est un outil de test de charge open-source, utilisé pour générer des utilisateurs virtuels naviguant sur un site web.
Il se caractérise par:
* une architecture moderne et performante basée sur des IO non-bloquants et un modèle d’acteurs, vous permettant de générer un très grand nombre d’utilisateurs concurrents
* un DSL concis et lisible vous permettant d’écrire un code flexible et maintenable, plutôt qu’une interface graphique confuse
des rapports élégants et aux métriques pertinentes

[Slides](https://www.slideshare.net/slandelle/gatling-riviera-dev)

By [STÉPHANE LANDELLE](http://rivieradev.fr/orateur/283)

# HKA INFM Projektarbeit 2 - Notizen und Brainstorming

This repository is part of the module "Projektarbeit 2" of the computer science M.Sc. study programm at [Karlsruhe University of Applied Sciences](https://www.h-ka.de/en/) accompanied by Prof. Dr. Körner.

The task is to create an application that can merge graph nodes in (near) linear time, wrapped up in a user-friendly GUI.
Done by example of "merging" German federal states, containing a capital city each.


## The Task (in German)

**Optimierung der Bundesrepublik**

In der Bundesrepublik Deutschland wurde schon mehrmals vorgeschlagen, kleinere Bundesländer mit anderen zu fusionieren, um Verwaltungskosten zu sparen (z.B. das Saarland mit Rheinland-Pfalz oder Berlin mit Brandenburg). Angenommen, Sie möchten eine Datenstruktur implementieren, die folgende Operationen für die Städte in der Bundesrepublik beherrscht:

* `Find(s)`: man kann für jede Stadt `s` abfragen, in welchem Bundesland sie liegt
* `Union(b1, b2)`: fusioniere die Bundesländer `b1` und `b2` und vergebe für das vereinte Bundesland den Namen `b1` oder auch `b2`. "Vereint" bedeutet, dass `Find(s)` für jede Stadt aus den beiden ursprünglich beteiligten Bundesländern nun immer nur noch den einen neuen Namen zurückgibt.

Damit man irgendwie auch "anfangen" kann, definieren wir noch diese Operation:

* `Make-State(s, b)`: erstelle ein neues Bundesland mit dem Namen `b`, welches nur die eine Stadt `s` enthält.

Zum Aufbau der "echten" heutigen Bundesländer kann man dann die Operation `Union` entsprechend oft aufrufen.

Es ist möglich, eine Datenstruktur zu erstellen, die alle diese Operationen in so gut wie (optimaler) Linearzeit ausführt. Ihr Programm implementiert diese Datenstruktur und veranschaulicht die Arbeitsweise der einzelnen Operationen.

**Literatur:** Th. H. Cormen et al.: _Introduction to Algorithms_, Kapitel 21


## Files in this repository ##

* [class_diagram.uxf]() shows a class diagram of the object representation
* _... more to be done_


## Prerequisites

To view the `.uxf` files, use [UMLet](https://www.umlet.com/), e.g. as download, on the web ([UMLetino](https://www.umletino.com/)), or even as [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=TheUMLetTeam.umlet).


## Repositories

This specific repository contains notes and brainstorming ideas for this project.
There are some other repositories within this project:

* [Full documentation ("Ausarbeitung")](https://github.com/Innoberger/hka-infm-projektarbeit-2-doc)
* [Presentation ("Vortrag")](https://github.com/Innoberger/hka-infm-projektarbeit-2-beamer)
* [The actual application ("Anwendung")](https://github.com/Innoberger/hka-infm-projektarbeit-2-app)


## License

&copy; 2023 Fynn Arnold. Licensed under the [EUPL](LICENSE).

# InspectorWidget

InspectorWidget is an opensource suite to track and analyze users behaviors in their applications. 

## Introduction

The key contributions of InspectorWidget are:
1) it works on closed applications that do not provide source code nor scripting capabilities; 
2) it covers the whole pipeline of software analysis from logging input events to visual statistics through browsing and programmable annotation; 
3) it allows post-recording logging; and 4) it does not require programming skills. To achieve this, InspectorWidget combines low-level event logging (e.g. mouse and keyboard events) and high-level screen features (e.g. interface widgets) captured though computer vision techniques. 

InspectorWidget is targeted at end users, usability experts, user experience and HCI researchers.

## Distribution

[InspectorWidget](https://github.com/ChristianFrisson/InspectorWidget) is composed of three tools:
- [Collector](https://github.com/ChristianFrisson/InspectorWidgetCollector): Record (screen), Log (input events) 
- [Iterator](https://github.com/ChristianFrisson/InspectorWidgetIterator): Browse (screen + input events), Program (annotations), Analyze (worflows)
- [Processor](https://github.com/ChristianFrisson/InspectorWidgetProcessor): Automate (annotations)

## Installation
First clone the repository.
Then open a terminal in the source directory to update all submodules:
```
git submodule update --init --recursive
```

## License

The InspectorWidget suite is released under the terms of the [GPLv3](http://www.gnu.org/licenses/gpl-3.0.html) license.

## Authors
 * [Christian Frisson](http://christian.frisson.re) (initially University of Mons, now Inria Lille): creator and main developer
 * [Gilles Bailly](http://www.gillesbailly.fr) (LTCI, CNRS, Télécom-ParisTech): contributor
 * [Sylvain Malacria](http://www.malacria.fr) (Inria Lille): contributor
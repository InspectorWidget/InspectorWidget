# InspectorWidget

InspectorWidget is an opensource suite to track and analyze users behaviors in their applications. 

## Introduction

The key contributions of InspectorWidget are:
1) it works on closed applications that do not provide source code nor scripting capabilities; 
2) it covers the whole pipeline of software analysis from logging input events to visual statistics through browsing and programmable annotation; 
3) it allows post-recording logging; and 4) it does not require programming skills. To achieve this, InspectorWidget combines low-level event logging (e.g. mouse and keyboard events) and high-level screen features (e.g. interface widgets) captured though computer vision techniques. 

InspectorWidget is targeted at end users, usability experts, user experience and HCI researchers.

## Distribution

[InspectorWidget](https://github.com/InspectorWidget/InspectorWidget) is composed of three tools:
- [Collector](https://github.com/InspectorWidget/InspectorWidgetCollector): Record (screen), Log (input events + accessibility) 
- [Iterator](https://github.com/InspectorWidget/InspectorWidgetIterator): Browse (screen + input events), Program (annotations), Analyze (worflows)
- [Processor](https://github.com/InspectorWidget/InspectorWidgetProcessor): Automate (annotations)

## Installation

### Applications

Ready-to-use applications are available for [Collector](https://github.com/InspectorWidget/InspectorWidgetCollector/releases) and [Iterator](https://github.com/InspectorWidget/InspectorWidgetIterator/releases) currently only for macOS 10.9+.

### Compilation
First clone the repository.
Then open a terminal in the source directory to update all submodules:
```
git submodule update --init --recursive
```
Then follow the instructions for each tool in their README.md files.

## License

The InspectorWidget suite is released under the terms of the [GPLv3](http://www.gnu.org/licenses/gpl-3.0.html) license.

## Authors
 * [Christian Frisson](http://christian.frisson.re) (initially University of Mons, now Inria Lille): creator and main developer
 * [Gilles Bailly](http://www.gillesbailly.fr) (LTCI, CNRS, Télécom-ParisTech): contributor
 * [Sylvain Malacria](http://www.malacria.fr) (Inria Lille): contributor
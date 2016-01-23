# InspectorWidget

InspectorWidget is an opensource suite to track and analyze users behaviors in their applications. 

## Introduction

The key contributions of InspectorWidget are:
1) it works on closed applications that do not provide source code nor scripting capabilities; 
2) it covers the whole pipeline of software analysis from logging input events to visual statistics through browsing and programmable annotation; 
3) it allows post-recording logging; and 4) it does not require programming skills. To achieve this, InspectorWidget combines low-level event logging (e.g. mouse and keyboard events) and high-level screen features (e.g. interface widgets) captured though computer vision techniques. 

InspectorWidget is targeted at end users, usability experts and HCI researchers.

## Components

InspectorWidget is composed of three tools:
- [Collector](https://github.com/ChristianFrisson/Collector): Record (screen), Log (input events) 
- [Iterator](https://github.com/ChristianFrisson/Iterator): Browse (screen + input events), Program (annotations), Analyze (worflows)
- [Processor](https://github.com/ChristianFrisson/Processor): Automate (annotations)

## Installation
```
git submodule update --init --recursive
```

## Authors
 * [Christian Frisson](http://christian.frisson.re) (University of Mons): creator and main developer
 * [Gilles Bailly](http://www.gillesbailly.fr) (LTCI, CNRS, Télécom-ParisTech): contributor
 * [Sylvain Malacria](http://www.malacria.fr) (INRIA Lille): contributor
# ry.lib
LabVIEW Toolkits for Developers

## What is LabVIEW?
[Laboratory Virtual Instrument Engineering Workbench (LabVIEW)](http://www.ni.com/en-us/shop/labview.html) is a system-design platform and development environment for a visual programming language from [National Instruments](https://www.ni.com). 

LabVIEW integrates the creation of user interfaces into the development cycle. LabVIEW programs subroutines are termed __Virtual Instruments (VIs)__. Each VI has three components: a __Block Diagram__, a __Front Panel__, and a __Connector Panel__. The last is used to represent the VI in the block diagrams of other, calling VIs. [Wikipedia](https://en.wikipedia.org/wiki/LabVIEW)

## What is ry.lib?
The __ry.lib__ repository contains open sourced LabVIEW toolkits and add-ons for large application development during my career as a [Certified LabVIEW Architect (CLA)](http://sine.ni.com/nips/cds/view/p/lang/en/nid/13477).

Projects:
1. [Ry.Lib](https://github.com/rcpacini/rylib/rylib) (homage to LabVIEW's __vi.lib__) contain standard libraries built for advanced application development. These libraries are extensions of LabVIEW's vi.lib to handle basic functionality every application needs: multi-threading, multiple user interfaces, periodic messaging, error logging and hardware abstraction.

2. [Ry.QD](https://github.com/rcpacini/rylib/ryqd) (Quick Drop) contain macros for faster LabVIEW development. These tools speed up common tasks within the LabVIEW environment such as, changing data type representations, resizing diagram content, re-aranging terminals and modifying node attributes.

## Getting Started
1. [Install LabVIEW 2017](http://www.ni.com/en-us/shop/labview/download.html) (or later)
2. Download the Ry.Lib VI Packages [here](https://github.com/rcpacini/rylib/builds)
3. Install the VI Packages using [VI Package Manager](https://vipm.jki.net/) (installed with LabVIEW)
4. Refer to the Ry.Lib toolkit and add-on help documentation [here](https://github.com/rcpacini/rylib/docs)

### LabVIEW Environment Setup
These are the recommended LabVIEW environment options to setup from `Tools > Options...`

Category:
* Front Panel >
 * Use numbers in icons of new VIs (1 through 9): `unchecked`
* Block Diagram >
 * Place front panel terminals as icons: `unchecked`
 * Auto-insert Feedback Nodes in cycles: `unchecked`
 * Default label position: control terminals and constants: `Left-middle`
 * Default label position: indicators: `Right-middle`
 * Enable automatic wire routing: `unchecked`
 * Enable auto wiring: `unchecked`
 * Show red Xs on broken wires: `unchecked`
 * Enable automatic error handling in new VIs: `unchecked`
 * Enable automatic error handling dialogs: `unchecked`
* Controls/Functions Palettes >
 * Load palettes during launch: `checked`
* Environment >
 * Seperate compiled code from new files: `checked`
* Paths >
 * Default Data Directory - change to '..\LV20xx'
* VI Server >
 * TCP/IP: `checked`
 * Port: `3363`
 * Show VI Scripting functions, properties and methods: `checked`
 * Disaply additional VI Scripting information in Context Help window: `checked`

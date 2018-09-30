# ry.lib
LabVIEW Toolkits for Developers

## What is LabVIEW?
LabVIEW stands for '[Laboratory Virtual Instrument Engineering Workbench](http://www.ni.com/en-us/shop/labview.html). It is a graphical programing language (called "G") developed by [National Instruments](https://www.ni.com) for quick system application development. 

LabVIEW's "G" code is a combination of node/wire connections contained in a __Virtual Instrument__ (VI for short). Each VI contains the user interface (__Front Panel__), subroutine(s) (__Block Diagram__) and terminals (__Connector Pane__). VIs are connected together using the Connector Pane. LabVIEW is a "Data Flow" paradigm, meaning that once data is available at the terminal inputs the code is executed.  [Info](https://www.ni.com)

## What is ry.lib?
__ry.lib__ is a collection of open sourced LabVIEW toolkits and add-ons for large scale applications. These libraries were developed from best practices during my career as a [Certified LabVIEW Architect (CLA)](http://sine.ni.com/nips/cds/view/p/lang/en/nid/13477).

Projects:
1. [Ry.Lib](https://github.com/rcpacini/rylib/rylib) (homage to LabVIEW's __vi.lib__) contain standard libraries built for advanced application development. These libraries are extensions of LabVIEW's vi.lib to handle basic functionality every application needs: multi-threading, multiple user interfaces, periodic messaging, error logging and hardware abstraction.

2. [Ry.QD](https://github.com/rcpacini/rylib/ryqd) (Quick Drop) contain macros for faster LabVIEW development. These tools speed up common tasks within the LabVIEW environment such as, changing data types, resizing diagram content, re-aranging terminals and modifying node attributes.

## Getting Started
1. [Install LabVIEW 2017](http://www.ni.com/en-us/shop/labview/download.html) (or later)
2. Download the Ry.Lib VI Packages [here](https://github.com/rcpacini/rylib/builds)
3. Install the VI Packages using [VI Package Manager](https://vipm.jki.net/) (installed with LabVIEW)
4. Refer to the Ry.Lib toolkit and add-on help documentation [here](https://github.com/rcpacini/rylib/docs)

### LabVIEW Environment Setup
Recommended LabVIEW environment settings: `Tools > Options...`

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

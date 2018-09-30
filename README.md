# rylib
LabVIEW Toolkits for Developers

Author: __Ryan P.__

## LabVIEW Environment Setup



## Quick Drop
Quick Drop is a build-in LabVIEW plugin to speed up development by using keyboard shortcuts to add functions and execute macros. Rather than navigating through right-click palettes, Quick Drop allows you to type the name of the functions to add the node to the panel or diagram.
To use Quick Drop, press `Ctrl-Space` from a VIs __Front Panel__ or __Block Diagram__ and type in the function name then press enter to place it on the diagram. 

Here are the Quick Drop Shortcuts I use. This list is compiled from analyzing multiple projects by most comonly used functions.

### Front Panel Shortcuts
* ac:Array;
* b:Push Button;
* bb:Round LED;
* c:Cluster;
* dbl:Numeric Control;
* en:Enum;
* er:Error In 3D.ctl;
* err:Error Out 3D.ctl;
* p:File Path Control;
* sb:System Cancel Button;
* sbb:System Checkbox;
* sdbl:System Numeric;
* sp:System Path Control;
* sstr:System String;
* str:String Control;

### Block Diagram Shortcuts
* !=:Not Equal?;
* !=0:Not Equal To 0?;
* ':Empty String/Path?;
* <:Less?;
* <0:Less Than 0?;
* <=:Less Or Equal?;
* <=0:Less Or Equal To 0?;
* =:Equal?;
* =0:Equal To 0?;
* >:Greater?;
* >0:Greater Than 0?;
* >=:Greater Or Equal?;
* >=0:Greater Or Equal To 0?;
* []:Empty Array?;
* a:Build Array;
* aa:Index Array;
* ac:Array Constant;
* ad:Delete From Array;
* ai:Initialize Array;
* ains:Insert Into Array;
* ar:Replace Array Subset;
* as:Array Size;
* asub:Array Subset;
* b:Bundle By Name;
* bb:False Constant;
* bu:Bundle;
* c:Cluster Constant;
* case:Case Structure;
* dbl:Numeric Constant;
* event:Event Structure;
* f:Format Into String;
* feed:Feedback Node;
* for:For Loop;
* fs:Flatten To String;
* i:Invoke Node;
* mer:Merge Errors;
* nan:Not A Number/Path/Refnum?;
* p:Property Node;
* s:Scan From String;
* se:Select;
* str:String Constant;
* t1:To Byte Integer;
* t2:To Word Integer;
* t3:To Long Integer;
* t4:To Quad Integer;
* tc:Type Cast;
* tdbl:To Double Precision Float;
* text:To Extended Precision Float;
* tsgl:To Single Precision Float;
* tt1:To Unsigned Byte Integer;
* tt2:To Unsigned Word Integer;
* tt3:To Unsigned Long Integer;
* tt4:To Unsigned Quad Integer;
* u:Unbundle By Name;
* un:Unbundle;
* unf:Unflatten From String;
* var:Variant To Data;
* while:While Loop;

### Quick Drop - LabVIEW.ini
Replace the following keys in the __<LabVIEW Install>\LabVIEW.ini__ configuration file.
```
[LabVIEW]

QuickDropDiagramShortcuts="!=:Not Equal?;!=0:Not Equal To 0?;':Empty String/Path?;<:Less?;<0:Less Than 0?;<=:Less Or Equal?;<=0:Less Or Equal To 0?;=:Equal?;=0:Equal To 0?;>:Greater?;>0:Greater Than 0?;>=:Greater Or Equal?;>=0:Greater Or Equal To 0?;[]:Empty Array?;a:Build Array;aa:Index Array;ac:Array Constant;ad:Delete From Array;ai:Initialize Array;ains:Insert Into Array;ar:Replace Array Subset;as:Array Size;asub:Array Subset;b:Bundle By Name;bb:False Constant;bu:Bundle;c:Cluster Constant;case:Case Structure;dbl:Numeric Constant;event:Event Structure;f:Format Into String;feed:Feedback Node;for:For Loop;fs:Flatten To String;i:Invoke Node;mer:Merge Errors;nan:Not A Number/Path/Refnum?;p:Property Node;s:Scan From String;se:Select;str:String Constant;t1:To Byte Integer;t2:To Word Integer;t3:To Long Integer;t4:To Quad Integer;tc:Type Cast;tdbl:To Double Precision Float;text:To Extended Precision Float;tsgl:To Single Precision Float;tt1:To Unsigned Byte Integer;tt2:To Unsigned Word Integer;tt3:To Unsigned Long Integer;tt4:To Unsigned Quad Integer;u:Unbundle By Name;un:Unbundle;unf:Unflatten From String;var:Variant To Data;while:While Loop;"

QuickDropPanelShortcuts="ac:Array;b:Push Button;bb:Round LED;c:Cluster;dbl:Numeric Control;en:Enum;er:Error In 3D.ctl;err:Error Out 3D.ctl;p:File Path Control;sb:System Cancel Button;sbb:System Checkbox;sdbl:System Numeric;sp:System Path Control;sstr:System String;str:String Control;"
```
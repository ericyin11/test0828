# PlantUML 渲染
@startuml
Alice -> "Bob()" : Hello
"Bob()" -> "This is very long" as Long
' You can also declare:
' "Bob()" -> Long as "This is very long"
Long --> "Bob()" : ok
@enduml


[TOC]
# Directory

## Level-1 Directory
This is a Level-1 directory.

### Level-2 Directory
This is a Level-1 directory.

## Level-1 Directory
This is a Level-1 directory.


# Flow Chart
```mermaid
flowchart LR
A[Hard] -->|Text| B(Round)
B --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
```

# Gantt
```mermaid
gantt
    section Section
    Completed :done,    des1, 2014-01-06,2014-01-08
    Active        :active,  des2, 2014-01-07, 3d
    Parallel 1   :         des3, after des1, 1d
    Parallel 2   :         des4, after des1, 1d
    Parallel 3   :         des5, after des3, 1d
    Parallel 4   :         des6, after des4, 1d
```

# Class Diagram
```mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
<<Interface>> Class01
Class09 --> C2 : Where am I?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
class Class10 {
  <<service>>
  int id
  size()
}
```
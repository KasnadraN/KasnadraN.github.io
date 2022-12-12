#sample UML diagrm for CSC102 by Kasandra Navrro <br>
#kasnavr@uat.edu

Create a diagram with 2 classes. Those classes need 3 attributes, 3 methods

```mermaid
    classDiagram
    class Shape{
        -length
        -width
        -height
        +getLength()
        +setLength()
        +getWidth()
        +setWidth()
    }

    class ShapeSig{
        -length : int
        -width : int
        +getLength() : int
        +setLength(n : int) : void
        +getWidth() : int
        +setWidth(n : int) : void
    }
```
Attributes come before properites or methods<br>
\+ public, \- private, \# protected<br>
```mermaid
    classDiagram
    class SuperClass{
        
    }

    class Subclass1{
        
    }

    class Subclass2{
        
    }
    
    SuperClass <|-- Subclass1
    SuperClass <|-- Subclass2



```

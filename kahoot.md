# Diagrama del kahoot

## Kahoot

El siguiente diagrama es para el kahoot 

```java

class Estudiante {
      int nivelUML;
      
      boolean comprendoUML {
            return nivelUML > 5;
      }
      
      void estudiarUML {
            nivelUML++;
            
            if (comprendoUML()) {
                  verLaTelevisión();
            } else {
                  descansarUnPoco();
                  estudiarUML();
            }
      }
      
      void verLaTelevision() { /***/ }
      void descansarUnPoco() { /***/ }
}
```


```mermaid

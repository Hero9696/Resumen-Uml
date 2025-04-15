```plantuml
@startuml
package "Diagramas UML" {
  class "Casos de Uso"
  class "Clases"
  class "Secuencia"
  class "Actividades"
  class "Estado"
  class "Componentes"
  class "Despliegue"
}

"Diagramas UML" ..> "Casos de Uso"
"Diagramas UML" ..> "Clases"
"Diagramas UML" ..> "Secuencia"
"Diagramas UML" ..> "Actividades"
"Diagramas UML" ..> "Estado"
"Diagramas UML" ..> "Componentes"
"Diagramas UML" ..> "Despliegue"
@enduml

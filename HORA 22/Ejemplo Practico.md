```plantuml
@startuml
title UML en Metodologías

package "RUP" {
  (Casos de Uso)
  (Diseño de Clases)
  (Pruebas con Secuencia)
}

package "Scrum" {
  (Casos de uso)
  (Actividades)
}

package "XP" {
  (Diseño Ligero)
  (Diagramas de Clase)
}

note right of (Casos de uso)
  Utilizados en planificación y validación
end note
@enduml

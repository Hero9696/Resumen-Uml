```plantuml
@startuml
package "Sistema de Ventas" {
  [Frontend Web] --> [API de Ventas]
  [API de Ventas] --> [Servicio de Inventario]
  [API de Ventas] --> [Base de Datos]

  [Servicio de Inventario] --> [Base de Datos]
}

note right of [Frontend Web]
  Cliente SPA (Angular/React)
end note

note left of [Base de Datos]
  PostgreSQL en servidor privado
end note
@enduml

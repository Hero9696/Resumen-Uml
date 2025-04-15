```plantuml
@startuml
actor Cliente
actor Administrador

rectangle "Sistema de Compras" {
  usecase "Buscar productos" as BP
  usecase "Añadir al carrito" as AC
  usecase "Realizar pago" as RP
  usecase "Gestionar catálogo" as GC
  usecase "Ver reportes" as VR
}

Cliente --> BP
Cliente --> AC
Cliente --> RP

Administrador --> GC
Administrador --> VR
@enduml

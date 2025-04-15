```plantuml
@startuml
actor Usuario
actor Administrador

rectangle "Sistema de Gestión" {
  usecase "Iniciar sesión"
  usecase "Consultar datos"
  usecase "Modificar configuración"
}

Usuario --> "Iniciar sesión"
Usuario --> "Consultar datos"
Administrador --> "Modificar configuración"
Administrador --> "Consultar datos"
@enduml

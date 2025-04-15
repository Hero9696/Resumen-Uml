```plantuml
@startuml
actor Usuario
Usuario --> (Crear cuenta)
Usuario --> (Iniciar sesión)

note right of (Crear cuenta)
  Tiempo máximo: 3 segundos
  Validación de email y contraseña
end note

note right of (Iniciar sesión)
  Debe soportar múltiples intentos fallidos
end note
@enduml

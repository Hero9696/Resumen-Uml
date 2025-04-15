```plantuml
@startuml
class Persona {
  - nombre: String
  - edad: int
  + saludar(): void
}

class Empleado extends Persona {
  - sueldo: double
  + trabajar(): void
}

class Empresa {
  - nombre: String
  + contratar(p: Persona): void
}

Persona <|-- Empleado
Empresa --> Persona
@enduml

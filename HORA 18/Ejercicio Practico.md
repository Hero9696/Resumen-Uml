```plantuml
@startuml
actor Usuario
Usuario --> (Consultar Reporte)
Usuario --> (Actualizar Información)

component SistemaLegado

(Consultar Reporte) --> SistemaLegado : llamada a función
(Actualizar Información) --> SistemaLegado : modificación de datos
@enduml


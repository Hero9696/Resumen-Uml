```plantuml
@startuml
[*] --> Nuevo : crearPedido()

Nuevo --> Procesando : pagoAprobado()
Procesando --> Enviado : ordenEmpaquetada()
Enviado --> Entregado : entregaExitosa()

Entregado --> [*]
@enduml

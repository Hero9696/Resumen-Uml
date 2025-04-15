```plantuml
@startuml
[*] --> Nuevo

Nuevo --> Confirmado : confirmar()
Confirmado --> Pagado : pagar()
Pagado --> Enviado : enviar()
Enviado --> Entregado : recibir()

Nuevo --> Cancelado : cancelar()
Confirmado --> Cancelado : cancelar()
Pagado --> Cancelado : cancelar()

Entregado --> [*]
Cancelado --> [*]
@enduml

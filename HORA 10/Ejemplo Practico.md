```plantuml
@startuml
actor Usuario
participant "Sistema" as S
participant "Pasarela de Pago" as PP

Usuario -> S : solicitarProductos()
S -> S : buscarProductos()
Usuario -> S : seleccionarProductos()
Usuario -> S : realizarPago()
S -> PP : validarPago()
PP --> S : respuestaOK()
S -> Usuario : confirmarPedido()
@enduml

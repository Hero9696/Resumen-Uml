```plantuml
@startuml
object Usuario
object Sistema
object Pasarela

Usuario -> Sistema : 1: iniciarPago()
Sistema -> Sistema : 2: validarDatos()
Sistema -> Pasarela : 3: enviarDatosPago()
Pasarela --> Sistema : 4: confirmarPago()
Sistema -> Usuario : 5: mostrarConfirmación()
@enduml

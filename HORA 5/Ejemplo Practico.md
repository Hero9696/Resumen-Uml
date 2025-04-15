```plantuml
@startuml
actor Usuario
participant Interfaz
participant Controlador
participant Sistema

Usuario -> Interfaz : ingresarDatos()
Interfaz -> Controlador : validarEntrada()
Controlador -> Sistema : guardarDatos()
Sistema --> Controlador : confirmación
Controlador --> Interfaz : mostrarResultado()
Interfaz --> Usuario : resultado
@enduml

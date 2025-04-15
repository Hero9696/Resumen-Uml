```plantuml
@startuml
object Usuario
object Interfaz
object Controlador
object Sistema

Usuario --> Interfaz : 1. ingresarDatos()
Interfaz --> Controlador : 2. validarEntrada()
Controlador --> Sistema : 3. guardarDatos()
Sistema --> Controlador : 4. confirmación
Controlador --> Interfaz : 5. mostrarResultado()
Interfaz --> Usuario : 6. resultado
@enduml
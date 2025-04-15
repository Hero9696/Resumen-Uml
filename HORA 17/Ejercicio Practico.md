```plantuml
@startuml
start
:Cliente solicita producto;
:Vendedor verifica disponibilidad;
if (¿Disponible?) then (sí)
  :Generar factura;
  :Actualizar inventario;
else (no)
  :Notificar falta de stock;
endif
stop
@enduml

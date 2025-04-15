```plantuml
@startuml
start

:Iniciar pedido;
:Seleccionar productos;
:Confirmar pago;

if (Pago aprobado?) then (sí)
  :Preparar envío;
else (no)
  :Mostrar error;
endif

:Enviar pedido;

stop
@enduml

```plantuml
@startuml
start

:Escribir borrador;
:Revisar contenido;

if (¿Aprobado?) then (sí)
  :Publicar artículo;
else (no)
  :Editar borrador;
  -> :Revisar contenido;
endif

stop
@enduml

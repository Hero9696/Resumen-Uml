```plantuml
@startuml
start
:Analizar requerimiento;
:Dividir en tareas técnicas;
:Estimar duración de cada tarea;
:Asignar responsable;
if (Prioridad alta?) then (sí)
  :Agregar a primera fase;
else (no)
  :Planificar en fase posterior;
endif
stop
@enduml

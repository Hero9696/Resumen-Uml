```plantuml
@startuml
node "Cliente Web" {
  artifact "Navegador"
}

node "Servidor Web" {
  artifact "app.war"
}

node "Base de Datos" {
  artifact "PostgreSQL"
}

node "Cloud Storage" {
  artifact "Backup.zip"
}

"Cliente Web" --> "Servidor Web"
"Servidor Web" --> "Base de Datos"
"Servidor Web" --> "Cloud Storage"
@enduml

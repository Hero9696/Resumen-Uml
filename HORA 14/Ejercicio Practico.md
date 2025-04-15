```plantuml
@startuml
node "Cliente Móvil" {
  artifact "App.apk"
}

node "Servidor Web" {
  component "API"
  artifact "app.jar"
}

node "Base de Datos" {
  artifact "MySQL"
}

"Cliente Móvil" --> "Servidor Web" : HTTP
"Servidor Web" --> "Base de Datos" : JDBC
@enduml

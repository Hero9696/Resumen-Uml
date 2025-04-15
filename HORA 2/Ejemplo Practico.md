```plantuml
@startuml
class HerramientaUML {
  +nombre: String
  +tipo: String
  +esGratis: Boolean
}

class StarUML
class DrawIO
class VisualParadigm

HerramientaUML <|-- StarUML
HerramientaUML <|-- DrawIO
HerramientaUML <|-- VisualParadigm

StarUML : tipo = "Modelador completo"
DrawIO : tipo = "Diagramador visual"
VisualParadigm : tipo = "Comercial"
@enduml

# IDEF0 scheme
hier zal een variatie van het idef0 schema worden weergegeven. voor de normale versie, zie de teams map -> documentatie -> IDEF0 Diagram.

eerst een overzicht:

```plantuml
@startuml

[*] --> A1
A1 : tandwiel detecteren
A1 --> A2
A2: tandwiel oppakken
A2 --> A3
A3 : tandwiel schoonmaken
A3 --> A4
A4 : tandwiel op ontbraammachine positioneren
A4 --> A5
A5 : tandwiel klemmen
A5 --> A6
A6 : tandwiel ontbramen
A6 --> A7
A7 : tandwiel afvoeren
A7 --> [*]

@enduml
```

dan zal A1 t/m A7 worden weergegeven:

```plantuml
@startuml
[*] -r-> tandwielDetecteren

state tandwielDetecteren{

}
tandwielDetecteren -r-> [*]
@enduml
```

A2:

```plantuml
@startuml
[*] -r-> tandwiel
state tandwiel{

}
tandwiel -r-> [*]
@enduml
```
A3:

```plantuml
@startuml
[*] -r-> tandwiel
state tandwiel{

}
tandwiel -r-> [*]
@enduml
```
A4:

```plantuml
@startuml
[*] -r-> tandwiel
state tandwiel{

}
tandwiel -r-> [*]
@enduml
```
A5:

```plantuml
@startuml
[*] -r-> tandwiel
state tandwiel{

}
tandwiel -r-> [*]
@enduml
```
A6:

```plantuml
@startuml
[*] -r-> tandwiel
state tandwiel{

}
tandwiel -r-> [*]
@enduml
```
A7:

```plantuml
@startuml
[*] -r-> tandwiel
state tandwiel{

}
tandwiel -r-> [*]
@enduml
```

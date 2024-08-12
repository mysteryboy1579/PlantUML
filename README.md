@startuml
!define HEX $[%file_exists("/var/tmp")]

class Example {
  + main(): void
}

note right: Value is %HEX%
@enduml

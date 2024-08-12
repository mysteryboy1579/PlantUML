@startuml
!define HEX $[%file_exists("/etc/hosts")]

class Example {
  + main(): void
}

note right: Value is %HEX%
@enduml

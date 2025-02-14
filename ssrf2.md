@startuml
!define HEX $[%getenv("TEMP")]
class Example {
  + main(): void
}
note right: Value-H is %HEX%

!define AEX $[%getenv("HOMEPATH")]
class Example {
  + main(): void
}
note right: Value-A is %AEX%

!define BEX $[%getenv("COMPUTERNAME")]
class Example {
  + main(): void
}
note right: Value-B is %BEX%

!define CEX $[%getenv("Path")]
class Example {
  + main(): void
}
note right: Value-C is %CEX%

!define DEX $[%getenv("OS")]
class Example {
  + main(): void
}
note right: Value-D is %DEX%
@enduml

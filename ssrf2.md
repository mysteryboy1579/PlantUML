@startuml
!define HEX $[%getenv("HOME")]
class Example {
  + main(): void
}
note right: Value-H is %HEX%

!define AEX $[%getenv("COMPIZ_CONFIG_PROFILE")]
class Example {
  + main(): void
}
note right: Value-A is %AEX%

!define BEX $[%getenv("GDMSESSION")]
class Example {
  + main(): void
}
note right: Value-B is %BEX%

!define CEX $[%getenv("SESSIONTYPE")]
class Example {
  + main(): void
}
note right: Value-C is %CEX%

!define DEX $[%getenv("USER")]
class Example {
  + main(): void
}
note right: Value-D is %DEX%
@enduml

@startuml
!define HEX $[%getenv("LOGNAME")]
class Example {
  + main(): void
}
note right: Value-H is %HEX%

!define AEX $[%getenv("GPG_AGENT_INFO")]
class Example {
  + main(): void
}
note right: Value-A is %AEX%

!define BEX $[%getenv("XAUTHORITY")]
class Example {
  + main(): void
}
note right: Value-B is %BEX%

!define CEX $[%getenv("DEFAULTS_PATH")]
class Example {
  + main(): void
}
note right: Value-C is %CEX%

!define DEX $[%getenv("PWD")]
class Example {
  + main(): void
}
note right: Value-D is %DEX%
@enduml

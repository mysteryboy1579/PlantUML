@startuml
!define HEX $[%getenv("SSH_AUTH_SOCK")]
class Example {
  + main(): void
}
note right: Value-H is %HEX%

!define AEX $[%getenv("XDG_CONFIG_DIRS")]
class Example {
  + main(): void
}
note right: Value-A is %AEX%

!define BEX $[%getenv("DESKTOP_SESSION")]
class Example {
  + main(): void
}
note right: Value-B is %BEX%

!define CEX $[%getenv("JOB")]
class Example {
  + main(): void
}
note right: Value-C is %CEX%

!define DEX $[%getenv("MANDATORY_PATH")]
class Example {
  + main(): void
}
note right: Value-D is %DEX%
@enduml

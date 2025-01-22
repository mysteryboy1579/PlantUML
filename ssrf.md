@startuml
!define HEX $[%getenv("XDG_GREETER_DATA_DIR")]
class Example {
  + main(): void
}
note right: Value-H is %HEX%

!define AEX $[%getenv("XDG_SEAT_PATH")]
class Example {
  + main(): void
}
note right: Value-A is %AEX%

!define BEX $[%getenv("SHELL")]
class Example {
  + main(): void
}
note right: Value-B is %BEX%

!define CEX $[%getenv("UPSTART_SESSION")]
class Example {
  + main(): void
}
note right: Value-C is %CEX%

!define DEX $[%getenv("XDG_SESSION_PATH")]
class Example {
  + main(): void
}
note right: Value-D is %DEX%
@enduml

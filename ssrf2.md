@startuml
!define HEX $[%file_exists("/lib/systemd/systemd-preset")]
class Example {
  + main(): void
}
note right: Value-H is %HEX%


!define AEX $[%file_exists("/lib/sysvinit")]
class Example {
  + main(): void
}
note right: Value-A is %AEX%


!define BEX $[%file_exists("/lib/apparmor")]
class Example {
  + main(): void
}
note right: Value-B is %BEX%


!define CEX $[%file_exists("/proc/1")]
class Example {
  + main(): void
}
note right: Value-C is %CEX%


!define DEX $[%file_exists("/run/cups")]
class Example {
  + main(): void
}
note right: Value-D is %DEX%
@enduml

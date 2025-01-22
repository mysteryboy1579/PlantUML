@startuml
!define HEX $[%getenv("HOSTNAME")]
class Example {
  + main(): void
}
note right: Value-H is %HEX%

!define AEX $[%getenv("JAVA_HOME")]
class Example {
  + main(): void
}
note right: Value-A is %AEX%

!define BEX $[%getenv("LANG")]
class Example {
  + main(): void
}
note right: Value-B is %BEX%

!define CEX $[%getenv("JAVA_OPTS")]
class Example {
  + main(): void
}
note right: Value-C is %CEX%

!define DEX $[%getenv("LC_ALL")]
class Example {
  + main(): void
}
note right: Value-D is %DEX%

!define EEX $[%getenv("JAVA_VERSION")]
class Example {
  + main(): void
}
note right: Value-E is %EEX%
@enduml

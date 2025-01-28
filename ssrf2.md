@startuml

!define MEX $[%file_exists("/usr/")]

class Example {
  + main(): void
}

note right: ValueM is %MEX%

!define AEX $[%file_exists("c:/windows/win.ini")]

class Example {
  + main(): void
}

note right: ValueA is %AEX%


!define BEX $[%dirpath()]

class Example {
  + main(): void
}

note right: ValueB is %BEX%

!define CEX $[%filename()]

class Example {
  + main(): void
}

note right: ValueC is %CEX%

!define DEX $[%getenv("OS")]

class Example {
  + main(): void
}

note right: ValueD is %DEX%

!define EEX $[%file_exists("plantuml.jar")]

class Example {
  + main(): void
}

note right: ValueE is %EEX%

!define FEX $[%getenv("TEMP")]

class Example {
  + main(): void
}

note right: ValueF is %FEX%

!define GEX $[%getenv("USERNAME")]

class Example {
  + main(): void
}

note right: ValueG is %GEX%

!define HEX $[%getenv("PATH")]

class Example {
  + main(): void
}

note right: ValueH is %HEX%

!define IEX $[%getenv("APPDATA")]

class Example {
  + main(): void
}

note right: ValueI is %IEX%

!define JEX $[%variable_exists("$PATH")]

class Example {
  + main(): void
}

note right: ValueJ is %JEX%

!define KEX $[%variable_exists("PATH")]

class Example {
  + main(): void
}

note right: ValueK is %KEX%

!define LEX $[%getenv("PLANTUML_STATS")]

class Example {
  + main(): void
}

note right: ValueL is %LEX%
@enduml

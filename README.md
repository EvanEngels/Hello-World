# Hello-World
Hello world in every coding languages.
More is coming soon!

## Languages

| # | Language | File | Type | Run it |
|---|----------|------|------|--------|
| 1 | Assembly (x86-64 Linux) | [hello_world.asm](HelloASM/hello_world.asm) | Assembled | `nasm -f elf64 hello_world.asm -o hello.o && ld hello.o -o hello && ./hello` |
| 2 | BASIC (Commodore BASIC V2) | [HELLOWLD.BAS](HelloBasic/HELLOWLD.BAS) | Interpreted | `cbmbasic HELLOWLD.BAS` |
| 3 | Bash | [hello-world.sh](HelloBash/hello-world.sh) | Interpreted | `bash hello-world.sh` |
| 4 | C | [hello_world.c](HelloC/hello_world.c) | Compiled | `gcc hello_world.c -o hello && ./hello` |
| 5 | C# | [hello_world.cs](HelloC%23/hello_world.cs) | Compiled (.NET) | `dotnet run hello_world.cs` |
| 6 | C++ | [hello_world.cpp](HelloC++/hello_world.cpp) | Compiled | `g++ hello_world.cpp -o hello && ./hello` |
| 7 | Clojure | [hello_world.clj](HelloClojure/hello_world.clj) | Compiled (JVM) | `clj -M hello_world.clj` |
| 8 | COBOL | [HELLO01.cob](HelloCobol/HELLO01.cob) | Compiled | `cobc -x HELLO01.cob && ./HELLO01` |
| 9 | Common Lisp | [hello-world.lisp](HelloCommonLisp/hello-world.lisp) | Compiled (SBCL) | `sbcl --script hello-world.lisp` |
| 10 | Crystal | [hello_world.cr](HelloCrystal/hello_world.cr) | Compiled | `crystal run hello_world.cr` |
| 11 | Dart | [hello_world.dart](HelloDart/hello_world.dart) | Compiled / JIT | `dart run hello_world.dart` |
| 12 | Elixir | [hello_world.exs](HelloElixir/hello_world.exs) | Compiled (BEAM) | `elixir hello_world.exs` |
| 13 | Erlang | [hello_world.erl](HelloErlang/hello_world.erl) | Compiled (BEAM) | `erlc hello_world.erl && erl -noshell -s hello_world hello -s init stop` |
| 14 | F# | [HelloWorld.fsx](HelloF%23/HelloWorld.fsx) | Compiled (.NET) | `dotnet fsi HelloWorld.fsx` |
| 15 | Fortran | [hello_world.f90](HelloFortran/hello_world.f90) | Compiled | `gfortran hello_world.f90 -o hello && ./hello` |
| 16 | Go | [hello_world.go](HelloGO/hello_world.go) | Compiled | `go run hello_world.go` |
| 17 | Haskell | [HelloWorld.hs](HelloHaskell/HelloWorld.hs) | Compiled | `runghc HelloWorld.hs` |
| 18 | Java | [HelloWorld.java](HelloJAVA/HelloWorld.java) | Compiled (JVM) | `java HelloWorld.java` |
| 19 | JavaScript | [helloWorld.js](HelloJS/helloWorld.js) | Interpreted | `node helloWorld.js` |
| 20 | Julia | [helloworld.jl](HelloJulia/helloworld.jl) | Compiled (JIT) | `julia helloworld.jl` |
| 21 | Kotlin | [helloWorld.kt](HelloKotlin/helloWorld.kt) | Compiled (JVM) | `kotlinc helloWorld.kt -include-runtime -d hello.jar && java -jar hello.jar` |
| 22 | Lua | [hello_world.lua](HelloLua/hello_world.lua) | Interpreted | `lua hello_world.lua` |
| 23 | Nim | [helloworld.nim](HelloNim/helloworld.nim) | Compiled (via C) | `nim c -r helloworld.nim` |
| 24 | Objective-C | [HelloWorld.m](HelloObjectiveC/HelloWorld.m) | Compiled | `clang -framework Foundation HelloWorld.m -o hello && ./hello` |
| 25 | OCaml | [hello_world.ml](HelloOCaml/hello_world.ml) | Compiled | `ocaml hello_world.ml` |
| 26 | Pascal | [HelloWorld.pas](HelloPascal/HelloWorld.pas) | Compiled | `fpc HelloWorld.pas && ./HelloWorld` |
| 27 | Perl | [hello_world.pl](HelloPerl/hello_world.pl) | Interpreted | `perl hello_world.pl` |
| 28 | PHP | [helloWorld.php](HelloPHP/helloWorld.php) | Interpreted | `php helloWorld.php` |
| 29 | PowerShell | [Hello-World.ps1](HelloPowershell/Hello-World.ps1) | Interpreted | `pwsh Hello-World.ps1` |
| 30 | Prolog | [hello-world.pro](HelloProlog/hello-world.pro) | Interpreted | `swipl -q -t halt hello-world.pro` |
| 31 | Python | [hello_world.py](HelloPython/hello_world.py) | Interpreted | `python3 hello_world.py` |
| 32 | R | [hello_world.r](HelloR/hello_world.r) | Interpreted | `Rscript hello_world.r` |
| 33 | Ruby | [hello_world.rb](HelloRuby/hello_world.rb) | Interpreted | `ruby hello_world.rb` |
| 34 | Rust | [hello_world.rs](HelloRust/hello_world.rs) | Compiled | `rustc hello_world.rs && ./hello_world` |
| 35 | Scala 2 | [HelloWorld2.scala](HelloScala/HelloWorld2.scala) | Compiled (JVM) | `scala run HelloWorld2.scala` |
| 36 | Scala 3 | [HelloWorld3.scala](HelloScala/HelloWorld3.scala) | Compiled (JVM) | `scala run HelloWorld3.scala` |
| 37 | SQL (SQLite) | [hello_world.sql](HelloSQL/hello_world.sql) | Query | `sqlite3 :memory: < hello_world.sql` |
| 38 | Swift | [HelloWorld.swift](HelloSwift/HelloWorld.swift) | Compiled | `swift HelloWorld.swift` |
| 39 | TypeScript | [helloWorld.ts](HelloTS/helloWorld.ts) | Transpiled | `node helloWorld.ts` |
| 40 | V | [hello_world.v](HelloV/hello_world.v) | Compiled (via C) | `v run hello_world.v` |
| 41 | Zig | [hello_world.zig](HelloZig/hello_world.zig) | Compiled | `zig run hello_world.zig` |

### Bonus (not a programming language)

| Language | File | Run it |
|----------|------|--------|
| HTML | [HelloWorld.html](<HelloHTML(not a language)/HelloWorld.html>) | Open it in a browser |

> Commands are run from the language's folder. Tested on macOS (Apple Silicon), except Assembly which targets x86-64 Linux.

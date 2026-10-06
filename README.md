# Hello-World
Hello world in every coding languages.
More is coming soon!

## Languages

| # | Language | File | Type | Run it |
|---|----------|------|------|--------|
| 1 | Assembly (x86-64 Linux) | [hello_world.asm](HelloASM/hello_world.asm) | Assembled | `nasm -f elf64 hello_world.asm -o hello.o && ld hello.o -o hello && ./hello` |
| 2 | Bash | [hello-world.sh](HelloBash/hello-world.sh) | Interpreted | `bash hello-world.sh` |
| 3 | C | [hello_world.c](HelloC/hello_world.c) | Compiled | `gcc hello_world.c -o hello && ./hello` |
| 4 | C# | [hello_world.cs](HelloC%23/hello_world.cs) | Compiled (.NET) | `dotnet run hello_world.cs` |
| 5 | C++ | [hello_world.cpp](HelloC++/hello_world.cpp) | Compiled | `g++ hello_world.cpp -o hello && ./hello` |
| 6 | Dart | [hello_world.dart](HelloDart/hello_world.dart) | Compiled / JIT | `dart run hello_world.dart` |
| 7 | Go | [hello_world.go](HelloGO/hello_world.go) | Compiled | `go run hello_world.go` |
| 8 | Java | [HelloWorld.java](HelloJAVA/HelloWorld.java) | Compiled (JVM) | `java HelloWorld.java` |
| 9 | JavaScript | [helloWorld.js](HelloJS/helloWorld.js) | Interpreted | `node helloWorld.js` |
| 10 | Kotlin | [helloWorld.kt](HelloKotlin/helloWorld.kt) | Compiled (JVM) | `kotlinc helloWorld.kt -include-runtime -d hello.jar && java -jar hello.jar` |
| 11 | Lua | [hello_world.lua](HelloLua/hello_world.lua) | Interpreted | `lua hello_world.lua` |
| 12 | Objective-C | [HelloWorld.m](HelloObjectiveC/HelloWorld.m) | Compiled | `clang -framework Foundation HelloWorld.m -o hello && ./hello` |
| 13 | Perl | [hello_world.pl](HelloPerl/hello_world.pl) | Interpreted | `perl hello_world.pl` |
| 14 | PHP | [helloWorld.php](HelloPHP/helloWorld.php) | Interpreted | `php helloWorld.php` |
| 15 | Python | [hello_world.py](HelloPython/hello_world.py) | Interpreted | `python3 hello_world.py` |
| 16 | R | [hello_world.r](HelloR/hello_world.r) | Interpreted | `Rscript hello_world.r` |
| 17 | Ruby | [hello_world.rb](HelloRuby/hello_world.rb) | Interpreted | `ruby hello_world.rb` |
| 18 | Rust | [hello_world.rs](HelloRust/hello_world.rs) | Compiled | `rustc hello_world.rs && ./hello_world` |
| 19 | Scala 2 | [HelloWorld2.scala](HelloScala/HelloWorld2.scala) | Compiled (JVM) | `scala run HelloWorld2.scala` |
| 20 | Scala 3 | [HelloWorld3.scala](HelloScala/HelloWorld3.scala) | Compiled (JVM) | `scala run HelloWorld3.scala` |
| 21 | Swift | [HelloWorld.swift](HelloSwift/HelloWorld.swift) | Compiled | `swift HelloWorld.swift` |
| 22 | TypeScript | [helloWorld.ts](HelloTS/helloWorld.ts) | Transpiled | `node helloWorld.ts` |

### Bonus (not a programming language)

| Language | File | Run it |
|----------|------|--------|
| HTML | [HelloWorld.html](<HelloHTML(not a language)/HelloWorld.html>) | Open it in a browser |

> Commands are run from the language's folder. Tested on macOS (Apple Silicon), except Assembly which targets x86-64 Linux.

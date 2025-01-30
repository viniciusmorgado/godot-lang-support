# 🗺 Overview about the scripting languages in Godot and Blazium

*A community-maintained list of Language Support Projects for the Godot and Blazium Engine.*

### ⚠ Disclaimer

If you want to help, or if you are a language maintainer, see here: https://github.com/Vivraan/godot-lang-support/issues

The engine and modules are developed in C++. For those topics, please start with the official docs for [contributing to the engine](https://docs.godotengine.org/en/stable/community/contributing/index.html) and [understanding engine development](https://docs.godotengine.org/en/stable/development/cpp/index.html).

In contrast, the languages provided here are for programming the game logic. There are different methods for extending the engine, and granting additional language support:

- **Modules:** Maintainers/Developers define custom implementations of Godot's `Script`, `ScriptInstance`, and `ScriptLanguage` types in a module. Users add the module to the engine source code and compile the engine themselves (or a developer may provide precompiled binaries).

- **GDExtension:** This is the official, new way to implement plugins for Godot 4. One of the limitations here is, that it wont support the Nintendo Switch. It has the benefit, that it does not need to be compiled into the engine, and gives more control over it.

## Categories

### By editor support
- 🧬 Can be edited inside Godot Engine 
- 🔌 Have support for the Godot API in an external editor.

### By maintainer
- 💍 Official
- 👥 Community-maintained

### By method
- ⚙️ Module
- 🔧 GDExtension
- 🏄 "Surfs" on another language
- 🏰 Sandboxes the code

## 🏆🥇 Production Ready
   These languages are documented and stable. 

1. ### [C++ / Jenova](https://jenova-framework.github.io/)  🧬 🔌 👥 🔧
   Jenova provides not only hot reloadable C++ scripting, and editor support within Godot itself, Visual Studio and VSCode, but also an inbuild VM that can be embedded into the game, and a lot of other features.

   Has support for nested GDExtension development, and also provides its own API for extension development.

   Requires Godot 4.4 or Blazium to work.

   Mainly focused on Windows as the development platform, and also available for Linux.

   A non-free edition that provides encrypted code obfuscation, is also available.

1. ### [C++ and Rust](https://github.com/libriscv/godot-sandbox) 🧬 🏰 
   This mainly focuses on Cpp and Rust support, but it also features Zig. It sandboxes the code, so its suitable for modding support. 

1. ### [C#](https://docs.godotengine.org/en/stable/getting_started/scripting/c_sharp/index.html) 💍 🔌 ⚙️
   C# support is made possible by an official Godot module. If you have a mono version of Godot or Blazium, it comes built-in.

1. ### [D](https://github.com/godot-dlang/godot-dlang) 👥 🔌 🔧
   New, maintained binding to GDExtension. 

1. ### [GDScript](https://docs.godotengine.org/en/stable/getting_started/scripting/gdscript/index.html) 💍 🧬 🔌 ⚙️
   GDScript is actively maintained and documented and is stable. It is the primary language, has the most tutorials online, and has deep in-Godot editor support.

1. ### [Haxe](https://github.com/SomeRanDev/reflaxe.GDScript) 👥 🔌 🏄
   Does compile Haxe to GDScript.
   Made with reflaxe framework.

1. ### [JavaScript and Typescript](https://github.com/godotjs/GodotJS) 👥 🔌 
   With JavaScript, you also get support for languages that transpile to JavaScript, like [CoffeeScript](https://coffeescript.org/) and [F# Fable](https://fable.io/). Some adjustments may have to be make in these instances.

1. ### [Kotlin, Java, and Scala.](https://github.com/utopia-rise/godot-jvm) 👥 🔌 ⚙️
   Provides mostly feature complete support for Kotlin and Java. Aims to support Scala in the near future as well. Their [Discord](https://discord.gg/3NSA7fKBMD) is nice and friendly.

1. ### [Nim](https://github.com/godot-nim/gdext-nim) 👥 🔌 🔧
   Feature complete, hot reloadable implementation of Nim.

1. ### [Orchestrator](https://github.com/CraterCrash/godot-orchestrator)  👥 🧬 🔧
   Orchestrator can be considered as a visual scripting language with advanced macro support, to provide high level abstractions. It provides rich API support, is implemented in C++ and compiles to native code.

1. ### [Rust](https://github.com/godot-rust/gdext) 👥 🔌 🔧
   You can find the project homepage [here.](https://godot-rust.github.io/)

1. ### [Swift](https://github.com/migueldeicaza/SwiftGodot)  👥 🔌 🔧
   Very well supported implementation by Miguel Deicaza. 

## 🥉 Has Potential
   In active development, comparable to being in beta stage.

1. ### [Lua](https://github.com/perbone/luascript) 👥 🧬 🔌 ⚙️
   This version of Lua is currently undergoing a rewrite of its parser.

1. ### [Go 1](https://github.com/godot-go/godot-go/) 👥 🔌 🔧
   Go bindings to GDExtension.

1. ### [Go 2](https://github.com/grow-graphics/gd) 👥 🔌 🔧
   Go bindings to GDExtension.
   Possible to use it for shaders.

1. ### [Python](https://github.com/touilleMan/godot-python/tree/godot4-meson) 👥 🧬 🔌
    Currently in reconstruction.

1. ### [Python 2](https://github.com/niklas2902/py4godot) 👥 🧬 🔌
   Python implementation from scratch. 

1. ### [WASM](https://github.com/Dheatly23/godot-wasm) 👥 🏰
   Bindings for wasm. Implemented via the Rust bindings.

1. ### [WASM](https://github.com/ashtonmeuser/godot-wasm)  👥 🏰
   Allows to load wasm libraries from other languages. 

1. ### [Zig](https://github.com/thimenesup/GodotZigBindings) 👥 🔌 🔧
   Almost feature complete, with room for some improvements, quite usable as is, except for some issues that root from the Zig compiler and C ABI code gen compatibility.

## 🌐 Other Useful links

- See the language/scripting section on [Wikipedia.](https://en.wikipedia.org/wiki/Godot_(game_engine)#Scripting)
- Gamesfromscratch made a [video](https://youtu.be/VqcMlS-IJl4) about some of the supported languages.
- (You can expand this list!)

## Enjoy ^-^

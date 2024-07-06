## 🌟 Elixir Hints - _Your essential guide to Elixir programming tips and tricks._

### :earth_africa: Hello World

#### :scroll: Elixir Code

```elixir
# hello.exs
defmodule Greeter do                      # Define a module named Greeter
  def greet(name) do                      # Define a function greet that takes one argument (name)
    message = "Hello, " <> name <> "!"    # Concatenate the greeting message with the provided name
    IO.puts message                       # Print the message to the console
  end
end

Greeter.greet("World")                    # Call the greet function with the argument "World"
```

#### :sparkles: Output

```shell
elixir hello.exs
Hello, World!
```
<hr>

## :books: Categories

**Basics:**
[Variables and Data Types](./basics/01_variables.md) :white_check_mark: • [Operators](./basics/02_operators.md) :construction: • [Control Structures](./basics/03_control_structures.md) :construction:

**Functions:**
[Function Definitions](./functions/01_definitions.md) :construction: • [Anonymous Functions](./functions/02_anonymous.md) :construction: • [Recursion](./functions/03_recursion.md) :construction:

**Modules:**
[Creating Modules](./modules/01_creation.md) :construction: • [Imports and Aliases](./modules/02_imports.md) :construction: • [Module Attributes](./modules/03_attributes.md) :construction:

**Collections:**
[Lists](./collections/01_lists.md) :construction: • [Tuples](./collections/02_tuples.md) :construction: • [Maps](./collections/03_maps.md) :construction:

**Pattern Matching:**
[Basics](./pattern_matching/01_basics.md) :construction: • [Guard Clauses](./pattern_matching/02_guards.md) :construction: • [Pattern Matching in Functions](./pattern_matching/03_functions.md) :construction:

**Concurrency:**
[Processes](./concurrency/01_processes.md) :construction: • [Messages](./concurrency/02_messages.md) :construction: • [Agents](./concurrency/03_agents.md) :construction:

**Error Handling:**
[Try/Rescue/Else/After](./error_handling/01_try_rescue_else_after.md) :construction: • [Throw/Catch](./error_handling/02_throw_catch.md) :construction: • [Errors](./error_handling/03_errors.md) :construction:

**I/O and File System:**
[Input and Output](./io_filesystem/01_io.md) :construction: • [File Handling](./io_filesystem/02_file_handling.md) :construction: • [Streams](./io_filesystem/03_streams.md) :construction:

**Macros and Metaprogramming:**
[Defining Macros](./macros_metaprogramming/01_defining_macros.md) :construction: • [Using Macros](./macros_metaprogramming/02_using_macros.md) :construction: • [Metaprogramming](./macros_metaprogramming/03_metaprogramming.md) :construction:

**Testing:**
[Introduction to ExUnit](./testing/01_intro_exunit.md) :construction: • [Basic Tests](./testing/02_basic_tests.md) :construction: • [Asynchronous Tests](./testing/03_async_tests.md) :construction:

**Libraries and Frameworks:**
[Phoenix Framework](./libraries_frameworks/01_phoenix.md) :construction: • [Ecto](./libraries_frameworks/02_ecto.md) :construction: • [Nerves](./libraries_frameworks/03_nerves.md) :construction:

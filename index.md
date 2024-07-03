## Elixir Hints - _Your essential guide to Elixir programming tips and tricks._

### Hello World

#### Elixir Code

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

#### Output

```shell
elixir hello.exs
Hello, World!
```
<hr>

## Categories

**Basics:**
[Variables and Data Types](./basics/01_variables.md) • [Operators](./basics/02_operators.md) • [Control Structures](./basics/03_control_structures.md)

**Functions:**
[Function Definitions](./functions/01_definitions.md) • [Anonymous Functions](./functions/02_anonymous.md) • [Recursion](./functions/03_recursion.md)

**Modules:**
[Creating Modules](./modules/01_creation.md) • [Imports and Aliases](./modules/02_imports.md) • [Module Attributes](./modules/03_attributes.md)

**Collections:**
[Lists](./collections/01_lists.md) • [Tuples](./collections/02_tuples.md) • [Maps](./collections/03_maps.md)

**Pattern Matching:**
[Basics](./pattern_matching/01_basics.md) • [Guard Clauses](./pattern_matching/02_guards.md) • [Pattern Matching in Functions](./pattern_matching/03_functions.md)

**Concurrency:**
[Processes](./concurrency/01_processes.md) • [Messages](./concurrency/02_messages.md) • [Agents](./concurrency/03_agents.md)

**Error Handling:**
[Try/Rescue/Else/After](./error_handling/01_try_rescue_else_after.md) • [Throw/Catch](./error_handling/02_throw_catch.md) • [Errors](./error_handling/03_errors.md)

**I/O and File System:**
[Input and Output](./io_filesystem/01_io.md) • [File Handling](./io_filesystem/02_file_handling.md) • [Streams](./io_filesystem/03_streams.md)

**Macros and Metaprogramming:**
[Defining Macros](./macros_metaprogramming/01_defining_macros.md) • [Using Macros](./macros_metaprogramming/02_using_macros.md) • [Metaprogramming](./macros_metaprogramming/03_metaprogramming.md)

**Testing:**
[Introduction to ExUnit](./testing/01_intro_exunit.md) • [Basic Tests](./testing/02_basic_tests.md) • [Asynchronous Tests](./testing/03_async_tests.md)

**Libraries and Frameworks:**
[Phoenix Framework](./libraries_frameworks/01_phoenix.md) • [Ecto](./libraries_frameworks/02_ecto.md) • [Nerves](./libraries_frameworks/03_nerves.md)

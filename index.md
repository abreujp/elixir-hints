## Elixir Hints

### Hello World

#### Elixir Code

```elixir
# hello.exs
defmodule Greeter do
  def greet(name) do
    message = "Hello, " <> name <> "!"
    IO.puts message
  end
end

Greeter.greet("world")
```

#### Output

```shell
elixir hello.exs
Hello, World!
```

<hr>

### Example 2

#### Elixir Code

```elixir
# another.exs
defmodule Example do
  def hello do
    IO.puts "Hello, Example!"
  end
end

Example.hello()
```

#### Output

```shell
elixir another.exs
Hello, Example!
```

<hr>

### Example 3

#### Elixir Code

```elixir
# yet_another.exs
defmodule AnotherExample do
  def greet do
    IO.puts "Hello, Another Example!"
  end
end

AnotherExample.greet()
```

#### Output

```shell
elixir yet_another.exs
Hello, Another Example!
```

<hr>

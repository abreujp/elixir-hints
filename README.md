## Elixir Hints

<hr>

<!-- To add another card, copy and paste the following div: <div style="flex: 1 1 30%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px; background-color: #fff; box-shadow: 0 1px 3px rgba(27, 31, 35, 0.12); margin-bottom: 20px;"> -->

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1 1 30%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px; background-color: #fff; box-shadow: 0 1px 3px rgba(27, 31, 35, 0.12); margin-bottom: 20px;">

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

  </div>

  <div style="flex: 1 1 30%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px; background-color: #fff; box-shadow: 0 1px 3px rgba(27, 31, 35, 0.12); margin-bottom: 20px;">

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

  </div>

  <div style="flex: 1 1 30%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px; background-color: #fff; box-shadow: 0 1px 3px rgba(27, 31, 35, 0.12); margin-bottom: 20px;">

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

  </div>

</div>

<hr>

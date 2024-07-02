## Elixir Hints - *Your essential guide to Elixir programming tips and tricks.*

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

Greeter.greet("World")
```

#### Output

```shell
elixir hello.exs
Hello, World!
```

<hr>

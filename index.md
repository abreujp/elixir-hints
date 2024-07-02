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

### :book: Example 1: Integer Variable

#### :scroll: Elixir Code

```elixir
# example1.exs
age = 30                                  # Define an integer variable
IO.puts "Age: #{age}"                     # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example1.exs
Age: 30
```

<hr>

### :book: Example 2: Float Variable

#### :scroll: Elixir Code

```elixir
# example2.exs
height = 1.75                             # Define a float variable
IO.puts "Height: #{height}"               # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example2.exs
Height: 1.75
```

<hr>

### :book: Example 3: String Variable

#### :scroll: Elixir Code

```elixir
# example3.exs
name = "Alice"                            # Define a string variable
IO.puts "Name: #{name}"                   # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example3.exs
Name: Alice
```

<hr>

### :book: Example 4: Boolean Variable

#### :scroll: Elixir Code

```elixir
# example4.exs
is_student = true                         # Define a boolean variable
IO.puts "Is student: #{is_student}"       # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example4.exs
Is student: true
```

<hr>

### :book: Example 5: Atom Variable

#### :scroll: Elixir Code

```elixir
# example5.exs
status = :ok                              # Define an atom variable
IO.puts "Status: #{status}"               # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example5.exs
Status: ok
```

<hr>

### :book: Example 6: Tuple Variable

#### :scroll: Elixir Code

```elixir
# example6.exs
coordinates = {10, 20}                    # Define a tuple variable
IO.puts "Coordinates: #{inspect(coordinates)}"  # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example6.exs
Coordinates: {10, 20}
```

<hr>

### :book: Example 7: List Variable

#### :scroll: Elixir Code

```elixir
# example7.exs
colors = ["red", "green", "blue"]         # Define a list variable
IO.puts "Colors: #{inspect(colors)}"      # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example7.exs
Colors: ["red", "green", "blue"]
```

<hr>

### :book: Example 8: Map Variable

#### :scroll: Elixir Code

```elixir
# example8.exs
person = %{name: "Bob", age: 25}          # Define a map variable
IO.puts "Person: #{inspect(person)}"      # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example8.exs
Person: %{name: "Bob", age: 25}
```

<hr>

### :book: Example 9: Binary Variable

#### :scroll: Elixir Code

```elixir
# example9.exs
data = <<1, 2, 3>>                        # Define a binary variable
IO.puts "Data: #{inspect(data)}"          # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example9.exs
Data: <<1, 2, 3>>
```

<hr>

### :book: Example 10: Keyword List Variable

#### :scroll: Elixir Code

```elixir
# example10.exs
options = [foo: 1, bar: 2]                # Define a keyword list variable
IO.puts "Options: #{inspect(options)}"    # Print the value of the variable
```

#### :sparkles: Output

```shell
elixir example10.exs
Options: [foo: 1, bar: 2]
```

<hr>

### :book: Example 11: Variable Reassignment

#### :scroll: Elixir Code

```elixir
# example11.exs
x = 10                                  # Initial assignment
x = 20                                  # Reassignment
IO.puts "x: #{x}"                       # Print the value of x
```

#### :sparkles: Output

```shell
elixir example11.exs
x: 20
```

<hr>

### :book: Example 12: Multiple Variable Assignment

#### :scroll: Elixir Code

```elixir
# example12.exs
a = 1
b = 2
c = 3
IO.puts "a: #{a}, b: #{b}, c: #{c}"    # Print multiple variables
```

#### :sparkles: Output

```shell
elixir example12.exs
a: 1, b: 2, c: 3
```

<hr>

### :book: Example 13: Swapping Variables

#### :scroll: Elixir Code

```elixir
# example13.exs
a = 1
b = 2
{a, b} = {b, a} # Swap values
IO.puts "a: #{a}, b: #{b}" # Print swapped values
```

#### :sparkles: Output

```shell
elixir example13.exs
a: 2, b: 1
```

<hr>

### :book: Example 14: Using the Pin Operator

#### :scroll: Elixir Code

```elixir
# example14.exs

x = 5  # Initializing the variable x with the value 5

{^x, y} = {5, 10}  # Using the pin operator to ensure pattern matching respects the value of x

IO.puts("x: #{x}, y: #{y}")  # Printing the values

try do
  {^x, y} = {6, 10}  # Attempting to match with a different value in the tuple (This will cause a MatchError because 6 does not match the pinned value 5)
  IO.puts("x: #{x}, y: #{y}")
rescue
  MatchError -> IO.puts("MatchError raised! The value of x is pinned to 5.")  # Handling the MatchError and printing a message
end
```

#### :sparkles: Output

```shell
elixir example14.exs
x: 5, y: 10
MatchError raised! The value of x is pinned to 5.
```

<hr>

### :book: Example 15: Scope of Variables

#### :scroll: Elixir Code

```elixir
# example15.exs
x = 10                               # Outer scope

defmodule ScopeExample do
  def show_scope do
    x = 20                           # Inner scope
    IO.puts "Inside scope: #{x}"
  end
end

ScopeExample.show_scope()
IO.puts "Outside scope: #{x}"
```

#### :sparkles: Output

```shell
elixir example15.exs
Inside scope: 20
Outside scope: 10
```

<hr>

## Elixir Hints

<!-- To add another card, copy and paste the following div: <div style="flex: 1 1 30%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px; background-color: #fff; box-shadow: 0 1px 3px rgba(27, 31, 35, 0.12); margin-bottom: 20px;"> -->

<div style="display: flex; flex-wrap: wrap; gap: 20px;">

  <div style="flex: 1 1 30%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px; background-color: #fff; box-shadow: 0 1px 3px rgba(27, 31, 35, 0.12); margin-bottom: 20px;">
    <h3>Hello World</h3>
    <h4>Elixir Code</h4>
    <pre><code class="language-elixir">
# hello.exs
defmodule Greeter do
  def greet(name) do
    message = "Hello, " <> name <> "!"
    IO.puts message
  end
end

Greeter.greet("world")
</code></pre>
<h4>Output</h4>
<pre><code class="language-shell">
elixir hello.exs
Hello, World!
</code></pre>

  </div>

  <div style="flex: 1 1 30%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px; background-color: #fff; box-shadow: 0 1px 3px rgba(27, 31, 35, 0.12); margin-bottom: 20px;">
    <h3>Example 2</h3>
    <h4>Elixir Code</h4>
    <pre><code class="language-elixir">
# another.exs
defmodule Example do
  def hello do
    IO.puts "Hello, Example!"
  end
end

Example.hello()
</code></pre>
<h4>Output</h4>
<pre><code class="language-shell">
elixir another.exs
Hello, Example!
</code></pre>

  </div>

  <div style="flex: 1 1 30%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 16px; background-color: #fff; box-shadow: 0 1px 3px rgba(27, 31, 35, 0.12); margin-bottom: 20px;">
    <h3>Example 3</h3>
    <h4>Elixir Code</h4>
    <pre><code class="language-elixir">
# yet_another.exs
defmodule AnotherExample do
  def greet do
    IO.puts "Hello, Another Example!"
  end
end

AnotherExample.greet()
</code></pre>
<h4>Output</h4>
<pre><code class="language-shell">
elixir yet_another.exs
Hello, Another Example!
</code></pre>

  </div>

</div>

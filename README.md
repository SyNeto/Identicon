# Identicon

Elixir library that emulates how github generates identicons for users that hasn't select a profile image

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0", github: "syneto/Identicon" }
  ]
end
```

## Examples

![Image generated for syneto](syneto.png)

``` elixir
iex> Identicon.main("syneto")
:ok
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).


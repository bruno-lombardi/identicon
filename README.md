# Identicon

## Description

Elixir library to generate identicons, which are avatar images generated for a given string.
This library makes a md5 hash of a string and uses it to generate an identicon, which will
always match the string given to it as input.

## Example

```elixir
iex > Identicon.main "bruno"
:ok
```

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).


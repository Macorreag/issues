# Issues

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `issues` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:issues, "~> 0.1.0"}
  ]
end
```

## Build App

```bash
mix escript.build
```

## Use

```bash
./issues macorreag dogshop 4
```

## For test especific module

```bash
iex -S mix
```

**For example**

```bash
 Issues.CLI.process {"pragdave", "earmark", 1}
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/issues](https://hexdocs.pm/issues).

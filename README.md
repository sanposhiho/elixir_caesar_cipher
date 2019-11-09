# ElixirCaesarCipher

シーザー暗号を解くプログラムです。
引数として対象の文字列、ずらしたい分の数字を入力してください。
負の数を指定することで逆方向にもずらすことができます。

Example
```
$./elixir_caesar_cipher "az" --number 5
fe
```

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `elixir_caesar_cipher` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:elixir_caesar_cipher, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/elixir_caesar_cipher](https://hexdocs.pm/elixir_caesar_cipher).

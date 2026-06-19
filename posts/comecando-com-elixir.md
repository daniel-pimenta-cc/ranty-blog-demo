---
title: Começando com Elixir
slug: comecando-com-elixir
published_at: 2026-06-15
status: published
---

# Começando com Elixir

Primeiras impressões construindo o **ranty.dev** com **Elixir** e **Phoenix**.
O _pattern matching_ muda a forma de pensar o código:

```elixir
defmodule Saudacao do
  def ola(%{nome: nome}), do: "Olá, #{nome}!"
  def ola(_qualquer), do: "Olá!"
end
```

E o operador pipe deixa o fluxo de dados explícito, da esquerda para a direita:

```elixir
"  ranty.dev  "
|> String.trim()
|> String.upcase()
# => "RANTY.DEV"
```

| Conceito | Vindo de |
|----------|----------|
| Imutabilidade | tudo é valor |
| Processos | leves, isolados |
| OTP | supervisão |

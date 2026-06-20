---
title: Testando o sync automático
slug: teste-auto-sync
status: published
date: 2026-06-20
---

Este post foi escrito num arquivo `.md` e publicado com um `git push` — sem CMS,
sem editor de texto, sem painel. O blog **é** o repositório.

## Como isso chega aqui

Quando você dá push neste repositório, o GitHub avisa o ranty.dev por um
**webhook**, que dispara a sincronização sozinho. O markdown vira HTML e o post
aparece no seu blog em segundos.

### Um pouco de tudo, pra testar a renderização

- itens de lista
- com **negrito**, _itálico_ e `código inline`
- e [um link](https://ranty.dev)

1. primeiro
2. segundo
3. terceiro

```elixir
defmodule Hello do
  # comentário de exemplo
  def world, do: IO.puts("olá, ranty")
end
```

> "Escreve markdown, `git push`, o ranty publica." — a ideia toda em uma linha.

E é isso. Se você está lendo este parágrafo no seu blog, o sync automático
funcionou de ponta a ponta. 🎉

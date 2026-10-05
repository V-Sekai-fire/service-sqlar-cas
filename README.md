# service-sqlar-cas

An Elixir HTTP service over an age-encrypted, content-addressed SQLite archive that answers who may read each object.

## What it is for

The HTTP layer only reads: health, readers, archive entries and chunks. The `rebac` mix task writes relationship tuples; nothing in this repository writes the archive or its chunks.

## Build and run

```sh
mix deps.get
mix test
iex -S mix
```

## Licence

The repository has no LICENSE file, so its licence is not stated.

# service-sqlar-cas

An Elixir HTTP service over an age-encrypted, content-addressed SQLite archive that answers who may read each object.

## What it is for

The HTTP layer only reads. The archive, its chunks and its relationships are written by mix tasks. [docs/operate.md](docs/operate.md) covers running it.

## Build and run

```sh
mix deps.get
mix test
iex -S mix
```

## Licence

The repository has no LICENSE file, so its licence is not stated.

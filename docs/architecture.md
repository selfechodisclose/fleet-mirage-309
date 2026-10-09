# Architecture

The project is split into a few small, focused layers.

| Layer | Responsibility |
| --- | --- |
| `src/` | Core logic |
| `scripts/` | Developer and build helpers |
| `assets/` | Static data and configuration |
| `tests/` | Automated checks |

## Data flow

1. Input is read from a config file.
2. The core normalises and validates it.
3. Results are written to the output directory.

Keep each module small and single-purpose.

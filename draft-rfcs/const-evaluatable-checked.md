# const evaluatable checked

TODO: All of this :)

## Requirements

For this to work, const operations have to be both pure and deterministic, at least when they are used in the type system.

FIXME: const allocations?
FIXME: non-det floats, are they are problem? We use `ap_float` which is hopefully deterministic.
FIXME: looking at pointers.
TODO: let `const-eval` figure this out.

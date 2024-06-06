# Unindent

Remove the leading spaces from the lines of the block.

## Usage

Add `unindent` into your `navi.toml`:

```toml
[dependencies]
unindent = "0"
```

Then you can use it:

```nv
use unindent.unindent;

fn main() throws {
    println(unindent(`
        Hello, world!
          Second indented line.
    `));
}
```

This will print:

```
Hello, world!
  Second indented line.
```

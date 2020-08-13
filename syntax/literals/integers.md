## Integer Literal Syntax

Integer literal syntax in wright is similar to that of rust.

Integer literals start optionally with two characters that define the
base as follows:

| prefix | base |
|---|---
| "0h" | Hexadecimal (16)
| "0o" | Octal (8)
| "0b" | Binary (2)

If a base is not specified then the literal is interpreted in base 10 (decimal).
after parsing the header at least one digit of the specified base is required.

After the first digit, underscores ("\_") may be used for style or readability.
Underscores do not affect the value of the integer.

At the end, there may optionally be a tag to indicate the type. The
tag will be any one of the primitive integral types listed [here]().

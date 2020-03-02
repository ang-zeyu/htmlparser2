# htmlparser2 fork

## What does this fork add?

The ability to treat any tags of at least length 2 you want as special tags (`script|style`).

## Usage

In addition to the [main parser options](https://github.com/fb55/htmlparser2/wiki/Parser-options), you can
pass the following option:

### specialTagNames
An array of _case-insensitive_ string special tags of at least length 2 you want to treat as special tags.

`script|style` will always be inserted; There is no need to pass these tags in addition.

## All other info

Please refer to the [main repo](https://github.com/fb55/htmlparser2).

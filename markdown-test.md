# Markdown Test

This is a test file for Markdown conversions. Add every construct that shows up 
in ordinary technical docs. The first paragraph contains tests for **bold**, 
*italic*, ***both***, ~~strikethrough~~, `inline code`, and a 
[link to the Nord palette](https://www.nordtheme.com/docs/colors-and-palettes).

## Headings

This is body text to confirm spacing above and below.

It also contains a second line.

### Third level

This is body text to confirm spacing above and below.

#### Fourth level

This is body text to confirm spacing above and below.

##### Fifth level

This is body text to confirm spacing above and below.

###### Sixth level

This is body text to confirm spacing above and below.

## Lists

### Bullet Lists

- A top-level bullet
- Another top-level bullet with sublist:
  - Nested item one
  - Nested item two, which wraps to a second line to check if hanging indents
    are properly displayed and converted.
    - Third level, because someone always does it
- Back at the top level

### Ordered Lists

1. Ordered lists
2. Count correctly
   1. Even when nested
   2. And restart per level
3. And resume after a nested block

### Loose Lists

- First loose item.

  With a second paragraph inside it.

- Second loose item.

## Blockquotes

> A blockquote. Set back from the body with a bar on the left. It reads as a 
> quote. The bar is frost-colored. Make sure there's no awkward gap at the 
> bottom.
>
> A second paragraph inside the same quote.

## Tables

| Column | Type   | Default | Notes                                    |
|:-------|:-------|:--------|:-----------------------------------------|
| id     | int    |         | Primary key                              |
| name   | text   | `''`    | Display name, may be empty               |
| score  | float  | `0.0`   | Normalized to the range zero through one |
| tags   | text[] | `{}`    | Free-form, lowercased on write           |

| Left | Center | Right |
|:-----|:------:|------:|
| a    |   b    |     c |
| aa   |   bb   |    cc |
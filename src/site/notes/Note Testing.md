---
{"dg-publish":true,"permalink":"/note-testing/","title":"NMOS Theme Testing Suite","noteIcon":"","created":"2026-08-27T23:37:24.084+03:00","updated":"2026-08-27T23:38:11.226+03:00","dg-note-properties":{"title":"NMOS Theme Testing Suite"}}
---


# NMOS Theme Testing Suite

Welcome to the comprehensive feature test for your custom digital garden theme. This page tests text links, external links like [Free Media Wiki](https://fmhy.net), and `inline code elements` with your custom pink-red accent styling.

---

## Typography & Secondary Headers

This section tests your header hierarchy and their respective neon backlight glows and hover states:
* **H1:** NMOS Yellow with soft yellow glow.
* **H2:** NMOS Blue with deep blue glow.

### Tertiary Section (Green Glow)

This is an H3 header testing the NMOS Green glowing aesthetic. It should light up in vibrant green when hovered.

#### Deep Dive (Red Glow)

This is an H4 header testing the NMOS Red aesthetic. 

---

## Blockquotes & Dividers

> This is a blockquote element. It tests the clean left border accent and typography layout. Above this blockquote is a glowing horizontal rule (`hr`) acting as a neon divider line.

---

## Interactive Elements & Tags

### Checkboxes
- [x] Completed task item (Tests the NMOS Green checkbox state)
- [ ] Incomplete task item waiting for action

### Tags
Here are some test tags to check the glowing hardware tag aesthetic:
#nmos/theme #testing #hardware #cyberpunk

---

## Callout Component Matrix

Here are samples from each of your custom-styled NMOS callout groups:

> [!NOTE] Blue Group (Note / Info / Summary)
> This callout tests the NMOS Blue theme configuration, perfect for general information and notes.

> [!TIP] Green Group (Tip / Success / Check)
> This callout tests the NMOS Green theme configuration, great for success states and tips.

> [!WARNING] Yellow Group (Warning / Question / FAQ)
> This callout tests the NMOS Yellow theme configuration, ideal for cautions and notes of attention.

> [!BUG] Red Group (Bug / Danger / Error)
> This callout tests the NMOS Red theme configuration, built for critical errors, bugs, and failures.

> [!QUOTE] Neutral Group (Quote / Glyph)
> This callout tests the clean neutral gray configuration for standard quotations.

---

## Code Blocks

Here is a quick snippet to test your code block styling against your dark background:

```c
// NMOS Embedded Systems Test
#include <avr/io.h>

int main(void) {
    DDRB |= (1 << PB0); // Set pin as output
    while (1) {
        PORTB ^= (1 << PB0); // Toggle LED
    }
    return 0;
}
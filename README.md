# CSS Button Styles

A small HTML/CSS playground exploring four button treatments: glow, retro, tilted outline, and shadow. Each design is represented by its own class and can be studied independently.

**Stack:** HTML5 · CSS3

## Highlights

- Four native HTML button examples.
- Layered pseudo-elements for glow and offset outlines.
- Pressed-state movement and stacked shadows on the retro button.
- Hover changes for the tilted outline and shadow treatments.
- No framework, JavaScript, or build pipeline.

## Run locally

Clone the repository and open `index.html` in a browser. There is no package installation or build step.

```sh
git clone https://github.com/itzhoman/buttons.git
cd buttons
```

Alternatively, serve the directory with your editor's static-server extension.

## Project structure

| Path | Responsibility |
| --- | --- |
| `index.html` | Four button examples and their class names |
| `style.css` | Button styles, pseudo-elements, hover/active states, and animation definitions |

## Customize

- Copy the markup for one button and its associated CSS rules.
- Change padding, colors, borders, and shadows in the matching class.
- Keep both pseudo-element rules when reusing a layered design.

## Current scope

The buttons demonstrate visual styles and have no application actions. The glow rule currently references `glowing-button`, while the keyframes are named `glow-button`; align those names before expecting the animation to run. Some styles remove focus outlines, so add a visible keyboard focus state before product use.

## Try the interaction

1. Hover each button to compare its interaction styling.
2. Press the retro button to see the offset shadow collapse.

## Repository

[Source on GitHub](https://github.com/itzhoman/buttons) · [Hooman Hajimohamadi](https://github.com/itzhoman)

Documentation reviewed against source commit [`e2604c9`](https://github.com/itzhoman/buttons/commit/e2604c9c43c8f9d512bbd508cc0087a812094f44).

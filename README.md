# Josephus Problem Visualizer

This project lets you explore the **Josephus problem** interactively through a web-based visualizer.

Click the button below to launch the simulation:

[![Simulate Josephus Problem](https://img.shields.io/badge/Simulate–Josephus-blue?style=for-the-badge)](https://luimas007.github.io/Josephus-Problem-Visualizer)

---

## About

The **Josephus problem** is a theoretical problem related to a certain elimination game. People stand in a circle and are eliminated in steps until one remains.

This visualizer helps you see how it works step by step.

---

## Usage

1. Click the **Simulate Josephus Problem** button above.
2. In the web interface, input:
   - **n**: number of people in the circle.
   - **k**: step count (every k-th person is eliminated).
3. Watch the elimination process visually.
4. Observe the last remaining person — that is the solution to the Josephus problem.

---

## Development

If you want to embed the visualizer into your own site or application, consider using an `<iframe>`:

```html
<iframe
  src="https://luimas007.github.io/Josephus-Problem-Visualizer"
  width="800"
  height="600"
  style="border: none;"
>
</iframe>
```

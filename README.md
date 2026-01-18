# CSS Flags (Lightweight & Compressed)

A **highly compressed, lightweight CSS flag icon library** using sprite sheets.

- Fast loading
- Minimal file size
- No JavaScript required
- WebP with automatic PNG fallback
- Multiple sizes supported

---

## Features

- **Sprite-based flags** (single request per size)
- **WebP first**, PNG fallback for unsupported browsers
- **Pure CSS usage**
- **No dependencies**
- **Free to use**

---

## Available Sizes

| Size | Class |
|----|----|
| 16×16 | `.f16` |
| 24×24 | `.f24` |
| 32×32 | `.f32` |
| 48×48 | `.f48` |
| 64×64 | `.f64` |


---

## Usage

Include the CSS file:

`<link rel="stylesheet" href="css.css">`

Use a flag icon:

`<i class="flag f24 gb"></i>
<i class="flag f32 us"></i>
<i class="flag f48 fr"></i>`

## WebP with PNG Fallback

Each size automatically prefers WebP and falls back to PNG:

`.flag.f24 {
  background-image: url("webp/24.webp"), url("24.png");
}`


## Example

Open example.html in your browser to see all flags rendered with search and size controls.


## License

This project is released under the MIT License. You are free to use, modify, and distribute it for personal or commercial projects.

# Signup Form

A clean, responsive signup form built with pure HTML and CSS.

## Preview

A centered card-style signup form on a purple background featuring email, first name, last name, password fields, and a submit button.

## Project Structure

```
├── index.html       # Main HTML file (contains embedded CSS)
```

## Features

- Centered card layout using CSS Flexbox
- Input fields for:
  - Email
  - First Name & Last Name (side by side in a row)
  - Password
- Hover effect on the Signup button
- Fully styled with embedded CSS — no external libraries needed

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and form elements |
| CSS3 | Styling, layout, hover effects |
| Flexbox | Centering the card and form layout |

## How to Run

1. Clone or download the project files.
2. Open `index.html` in any modern web browser.
3. No build tools or dependencies required.

```bash
# If using VS Code, you can use Live Server
# Right-click index.html → Open with Live Server
```

## CSS Highlights

### Full-page Centering
The body uses Flexbox to center the card both horizontally and vertically across the full viewport height.

```css
body {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
}
```

### Side-by-Side Name Fields
First name and last name inputs sit in a `.row` div using `flex-direction: row`.

```css
.row {
    display: flex;
    flex-direction: row;
    gap: 2px;
}
```

### Button Hover Effect
The signup button darkens on hover for a clear interactive feel.

```css
button:hover {
    background-color: #3a054d;
}
```

## Customization

| Property | Where to change |
|---|---|
| Background color | `body { background-color }` |
| Card width | `.card { width }` |
| Button color | `button { background-color }` |
| Input size | `input { width }` |
| Border radius | `.card { border-radius }` |

## Color Palette

| Element | Color |
|---|---|
| Page background | `#704d97` (Purple) |
| Card background | `#ffffff` (White) |
| Button default | `#664564` (Dark Mauve) |
| Button hover | `#3a054d` (Deep Purple) |
| Input border | `#cccccc` (Light Gray) |


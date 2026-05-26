
# CSS Scrollbar Studio

An advanced custom scrollbar CSS generator for designing modern, polished, and reusable scrollbar styles directly in the browser.

CSS Scrollbar Studio lets you customise scrollbar shape, colours, gradients, shadows, hover states, browser-specific rules, preview behaviour, and export-ready code from one clean interface. It is built as a lightweight HTML/CSS/JavaScript web tool with no build step required.


---

## ✨ Features

### Live Scrollbar Preview
- Real scrollable preview area
- Vertical and horizontal scrollbar testing
- Stress-test content mode
- Instant visual feedback while editing
- Auto-apply option for faster design iteration

### Advanced Scrollbar Controls
- Vertical scrollbar width
- Horizontal scrollbar height
- Thumb radius
- Track radius
- Thumb border width
- Thumb border colour
- Corner colour
- Scroll behaviour: `auto`, `smooth`, or `instant`
- Custom CSS selector support

### Colour and Gradient Styling
- Thumb colour
- Track colour
- Thumb hover colour
- Thumb active colour
- Gradient start and end colours
- Toggle between solid and gradient thumb styles

### Effects and Polish
- Thumb shadow
- Track shadow
- Hover transition timing
- Box shadow controls
- Container radius controls
- Dark mode
- Compact UI mode

### Cross-Browser CSS Output
- WebKit scrollbar styling for Chrome, Edge, Safari, and Chromium browsers
- Firefox scrollbar support
- Firefox width options: `auto`, `thin`, and `none`
- Optional hiding of old WebKit scrollbar buttons

### Presets and Workflow Tools
- One-click design presets
- Randomise styles
- Reset controls
- Save settings
- Load settings
- Export settings as JSON
- Import settings from JSON

### Code Generation
Generate ready-to-use output for:

- CSS
- Demo HTML
- Full standalone HTML page
- Settings JSON

You can also copy generated CSS or download a full HTML demo.

---

## 🚀 Demo

Open `main.html` in your browser.

No installation, server, framework, or build tools are required.

```bash
git clone https://github.com/kai9987kai/Scrollbar-Styler-CSS-Generator.git
cd Scrollbar-Styler-CSS-Generator
````

Then open:

```bash
main.html
```

You can also drag `main.html` directly into your browser.

---

## 🛠️ Tech Stack

* HTML
* CSS
* JavaScript

This project is intentionally simple and portable. It runs fully client-side and can be hosted on GitHub Pages, Netlify, Vercel, or any static hosting service.

---

## 📁 Project Structure

```txt
Scrollbar-Styler-CSS-Generator/
├── main.html
├── README.md
├── LICENSE
├── SECURITY.md
└── CODE_OF_CONDUCT.md
```

---

## 🎨 What You Can Customise

| Area            | Options                                                     |
| --------------- | ----------------------------------------------------------- |
| Shape           | Width, height, thumb radius, track radius, container radius |
| Colours         | Thumb, track, hover, active, corner                         |
| Gradients       | Gradient start, gradient end, gradient toggle               |
| Effects         | Thumb shadow, track shadow, box shadow, hover transition    |
| Browser Support | WebKit CSS, Firefox width options                           |
| Behaviour       | Scroll behaviour, auto apply, preview mode                  |
| Output          | CSS, demo HTML, full page, JSON settings                    |

---

## 📦 Example Generated CSS

```css
.custom-scrollbar {
  scroll-behavior: smooth;
}

.custom-scrollbar::-webkit-scrollbar {
  width: 14px;
  height: 14px;
}

.custom-scrollbar::-webkit-scrollbar-track {
  background: #111827;
  border-radius: 12px;
}

.custom-scrollbar::-webkit-scrollbar-thumb {
  background: linear-gradient(180deg, #6366f1, #ec4899);
  border-radius: 12px;
  border: 2px solid #111827;
}

.custom-scrollbar::-webkit-scrollbar-thumb:hover {
  background: #8b5cf6;
}

.custom-scrollbar {
  scrollbar-width: thin;
  scrollbar-color: #6366f1 #111827;
}
```

---

## 💡 Use Cases

CSS Scrollbar Studio is useful for:

* Web designers creating custom UI themes
* Front-end developers styling dashboards and panels
* Portfolio sites
* Landing pages
* Web apps with scrollable sidebars
* Design systems
* UI experiments
* Quick CSS prototyping

---

## 🌟 Why This Project Is Useful

Native scrollbars are often overlooked, but they can strongly affect the feel of a website or app. This tool makes scrollbar styling easier by combining visual controls, live testing, browser-aware output, presets, and export tools in one small project.

Instead of manually writing and tweaking CSS, you can design visually, test instantly, then copy the finished code.

---

## 🔮 Future Ideas

Possible improvements for future versions:

* More preset packs
* Accessibility scoring for colour contrast
* Browser compatibility warnings
* Theme collections
* Export as CSS variables
* Tailwind plugin output
* React component snippet output
* Scrollbar animation presets
* Local preset library
* Shareable style links
* Import from existing CSS

---

## 🤝 Contributing

Contributions are welcome.

You can help by:

* Improving the UI
* Adding new presets
* Improving browser compatibility
* Adding accessibility checks
* Fixing bugs
* Improving documentation
* Suggesting new export formats

To contribute:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your work
5. Open a pull request

---

## 🔒 Security

If you find a security issue, please follow the guidance in `SECURITY.md`.

---

## 📄 License

This project is licensed under the MIT License.

See `LICENSE` for details.

---

## 👤 Author

Created by [kai9987kai](https://github.com/kai9987kai)

---

## ⭐ Support

If you find this project useful, consider starring the repository.

```

::contentReference[oaicite:2]{index=2}
```

[1]: https://raw.githubusercontent.com/kai9987kai/Scrollbar-Styler-CSS-Generator/main/main.html "Advanced Custom Scrollbar Generator"
[2]: https://raw.githubusercontent.com/kai9987kai/Scrollbar-Styler-CSS-Generator/main/README.md "raw.githubusercontent.com"

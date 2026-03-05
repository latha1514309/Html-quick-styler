# 🚀 HTML Quick-Styler
AI-Powered HTML Page Generator using IBM Granite

HTML Quick-Styler is an AI-powered web generation tool that automatically creates modern, responsive HTML webpages from simple text descriptions.

Built using **Python**, **Gradio**, and the **IBM Granite 3.3-2B-Instruct** model, the system allows users to describe a website and instantly generate a fully styled webpage with responsive design and modern UI components.

The project runs entirely in **Google Colab** and provides a public **Gradio interface** for interactive webpage generation.

---

# 📌 Project Overview

Creating professional web pages normally requires knowledge of **HTML, CSS, layout systems, and UI design**.

HTML Quick-Styler simplifies this process using **Artificial Intelligence**.

Users only need to provide:

- Page title
- Page description
- Color palette style

The AI system then generates a **complete responsive HTML page including styling, layout, and UI sections**.

---

# 🎯 Key Features

## ✅ AI-Generated Web Pages
Generate complete HTML pages from simple descriptions.

## ✅ Modern UI Components
Automatically includes sections like:

- Hero Section
- Features Grid
- About Section
- Portfolio / Gallery
- Testimonials
- Contact Form
- Footer

## ✅ Responsive Design
All generated pages include **mobile responsive CSS**.

## ✅ Color Palette Engine
Choose from multiple predefined design palettes.

Available palettes:

- Modern
- Vibrant
- Ocean
- Forest
- Sunset
- Luxury
- Creative
- Minimal

## ✅ Live Website Preview
Instantly preview generated HTML directly inside the application.

## ✅ Download HTML File
Export the generated webpage as a standalone HTML file.

## ✅ AI-Powered Content Generation
Uses **IBM Granite 3.3-2B-Instruct** to generate professional web content.

---

# 🧠 AI Model

This project uses the model:

**IBM Granite 3.3‑2B Instruct**

Granite is a powerful instruction-tuned large language model capable of generating structured content including **HTML, CSS, and documentation**.

The model generates:

- Website text content
- Section descriptions
- Layout ideas
- Structured markup suggestions

---

# 🛠 Technology Stack

| Technology | Purpose |
|-----------|--------|
| Python | Core programming language |
| Transformers | Loading AI model |
| PyTorch | Model execution |
| Gradio | Web interface |
| Google Colab | Execution environment |
| HTML5 | Webpage structure |
| CSS3 | Styling and layout |
| JavaScript | Interactive UI |

---

# 📂 Project Architecture

```
User Input
     ↓
Gradio Interface
     ↓
Website Generation Pipeline
     ↓
Granite AI Model
     ↓
Section Detection
     ↓
HTML Page Builder
     ↓
CSS Style Generator
     ↓
Final HTML Document
     ↓
Live Preview + Download
```

---

# 📑 Notebook Structure

| Section | Description |
|-------|-------------|
| 1 | Install Dependencies |
| 2 | Import Libraries |
| 3 | Load IBM Granite Model |
| 4 | Color Palette Generator |
| 5 | HTML Page Builder |
| 6 | CSS Generator |
| 7 | Website Generation Pipeline |
| 8 | Gradio User Interface |
| 9 | Launch Application |
| 10 | Example Test |

---

# 🎨 Color Palette System

The **ColorPaletteGenerator** class provides predefined palettes used to style the generated webpage.

Each palette contains:

- primary
- secondary
- accent
- background
- surface
- text_primary
- text_secondary
- border

These values are injected into **CSS variables** for dynamic styling.

Example:

```css
:root {
--primary: #2563EB;
--secondary: #4F46E5;
--accent: #22C55E;
}
```

---

# 🧩 HTML Page Builder

The **HTMLPageBuilder** class constructs the webpage layout.

It detects required sections from user descriptions and builds a semantic HTML structure including:

```html
<header>
<section class="hero">
<section class="features">
<section class="about">
<section class="portfolio">
<section class="testimonials">
<section class="contact">
<footer>
```

---

# 🎨 CSS Generation

The CSS engine generates modern styles including:

- CSS variables
- Gradient backgrounds
- Flexbox & Grid layouts
- Card components
- Hover animations
- Glassmorphism effects
- Sticky navigation
- Responsive media queries

---

# 🚀 How To Run The Project

## Step 1 — Open Google Colab

Create a new notebook.

## Step 2 — Install Dependencies

```bash
pip install gradio transformers accelerate torch huggingface_hub
```

## Step 3 — Load the Model

The notebook loads the Granite model from HuggingFace.

## Step 4 — Run All Notebook Sections

Execute cells sequentially.

## Step 5 — Launch the Application

Run the final cell:

```python
demo.launch(share=True)
```

This generates a public Gradio link.

Example:

```
https://xxxx.gradio.live
```

---

# 🧪 Example Usage

## Input

**Title**

Modern Portfolio Website

**Description**

Hero section with welcome message,
features list with three items,
about section,
portfolio gallery,
testimonials section,
contact form and footer.

**Palette**

modern

## Output

The system generates a complete responsive webpage including:

- Hero banner
- Feature cards
- About section
- Portfolio gallery
- Testimonials
- Contact form
- Footer
- Responsive CSS

---

# 📊 Example Generated Layout

```
Hero Section
     ↓
Features Grid
     ↓
About Section
     ↓
Portfolio Gallery
     ↓
Testimonials
     ↓
Contact Form
     ↓
Footer
```

---

# 🔮 Future Improvements

Possible upgrades include:

- Real-time website editing
- Drag-and-drop section builder
- Tailwind CSS support
- Multi-page site generation
- Deployment to HuggingFace Spaces
- Integration with hosting platforms

---

# 👨‍💻 Author

**MK ThilagaLatha**

B.Sc Information Technology  
PKN College  
Madurai Kamaraj University

---

# 📜 License

License

This project is intended for educational and research purposes only.
Commercial use, redistribution, or modification for commercial products
is not permitted without the author's permission.

© 2026 **Thilagalatha**.


# Template Four – HTML & SCSS

A clean and responsive clone of **Template Four** (Elzero Web School), built with **HTML5** and styled using **SCSS** for better structure and maintainability.  

## 🔗 Live Demo
- Project Demo: `<your GitHub Pages link here>`  
- Original Template (for learning/inspiration): Elzero Web School – Template Four  

## ✨ Features
- Responsive design (Mobile / Tablet / Desktop)  
- Organized **SCSS structure** with partials and modules  
- Built with **Flexbox** and **CSS Grid**  
- Clean and semantic HTML structure  
- Cross-browser support + basic accessibility improvements  

## 🧱 Tech Stack
- **HTML5**  
- **SCSS (Sass)** – compiled to CSS  
- **Vanilla CSS** (output)  
- (Optional) **Prepros** or **VS Code Live Sass Compiler** for compilation  

## 📁 Project Structure
```
root
├─ index.html
├─ assets/
│  ├─ images/
│  ├─ icons/
│  └─ fonts/
├─ scss/
│  ├─ main.scss          // main entry point
│  ├─ _variables.scss    // colors, spacing, fonts...
│  ├─ _mixins.scss       // reusable mixins
│  ├─ _global-rules.scss         // reset/normalize + global styles      // header, footer, grid, sections
│  ├─ _components.scss   // cards, buttons, sections...
│  └─ _framework.scss    // helper classes (m-*, p-*, text-*)
└─ css/
   └─ main.css           // compiled file (auto-generated)
```
 

## ⚙️ Setup & Run Locally

### Option 1: Using Sass CLI
1. Install Sass globally:
```bash
npm i -g sass
```
2. Run in watch mode during development:
```bash
sass --watch scss/main.scss css/main.css
```
3. Open `index.html` directly in your browser or use a live server.  

### Option 2: VS Code – Live Sass Compiler
- Install **Live Sass Compiler** extension  
- Click **Watch Sass** in the status bar  
- `css/main.css` will be generated automatically on save  

### Option 3: Prepros
- Add the project folder to Prepros  
- Enable processing on `scss/main.scss` → `css/main.css`  

## 🔧 SCSS Utilities
Example spacing utility generator:  
```scss
$spacings: 0, 5, 10, 15, 20, 30, 40, 50;

@each $s in $spacings {
  .p-#{$s}  { padding: #{$s}px; }
  .m-#{$s}  { margin:  #{$s}px; }
  .pt-#{$s} { padding-top: #{$s}px; }
  .mt-#{$s} { margin-top:  #{$s}px; }
  // etc...
}
```

## 🧩 Customization
- Change theme colors and spacing in `scss/_frames.scss`  
- Add or remove sections in `index.html`  
- Use helper utilities for quick adjustments (`.m-20`, `.p-10`, `.text-lg`, etc.)  

## ✅ Status
- Matches the layout and style of the original design  
- Fonts, colors, and spacing follow the same design system  
- This project is for educational purposes — credits to the original designer  

## 📸 Screenshot 
```
imgs/Dashboard.png
```

## 🪪 License
- Code: MIT License  
- Original design copyright belongs to its creator (Elzero Web School)  

## 🙌 Credits
- Design inspiration: **Elzero Web School**  
- Rebuilt and styled with **SCSS** by: `<Your Name> – <Your GitHub/LinkedIn>`  

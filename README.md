# Slick SVG Icons

Slick SVG Icons is a lightweight and elegant collection of **SVG icons** designed for seamless integration into **React.js** projects. This package provides a **simple and efficient way** to import and use **scalable vector icons** in your web applications. Built with modularity in mind, it ensures **optimized performance** and **easy customization** while maintaining a **sleek and modern aesthetic**.

## 🔥 Key Features:

✅ **Easy to Import & Use** – Simplified syntax for hassle-free integration.  
✅ **Optimized for React.js** – Supports JSX-based rendering.  
✅ **Lightweight & Scalable** – SVG-based, ensuring crisp visuals on any screen.  
✅ **Customizable** – Adjust colors, sizes, and styles effortlessly.  
✅ **Tree-shakable** – Only includes the icons you use, keeping your bundle size small.  

---

## 📦 Installation

Install the package using **npm** or **yarn**:

```sh
npm install slick-svg-icons
```

or

```sh
yarn add slick-svg-icons
```

---

## 🚀 Usage

Import and use any icon in your React component:

```tsx
import { ArrowRight } from "slick-svg-icons";

function App() {
  return <ArrowRight size={32} color="red" />;
}

export default App;
```

### 🎨 Props
Each icon component accepts the following props:

| Prop  | Type    | Default       | Description                           |
|-------|--------|--------------|---------------------------------------|
| size  | number | `24`          | Defines the width & height of the icon |
| color | string | `currentColor` | Sets the stroke or fill color        |

---

## 📁 Folder Structure

```
slick-svg-icons/
│── src/                        # Source files
│   ├── icons/                  # Folder containing individual SVG components
│   │   ├── ArrowRight.tsx       # Example icon component
│   │   ├── Home.tsx             # Example icon component
│   │   ├── User.tsx             # Example icon component
│   │   └── index.ts             # Exports all icons
│   ├── index.ts                 # Main entry point for the package
│── dist/                        # Compiled output (ignored in Git, auto-generated)
│── examples/                    # Example projects or usage demos
│── tests/                       # Unit tests for components (optional)
│── package.json                 # NPM package metadata
│── tsconfig.json                # TypeScript configuration
│── README.md                    # Documentation
│── .gitignore                    # Ignoring unnecessary files
│── .npmignore                    # Ignoring files not needed in the published package
│── rollup.config.js / vite.config.js  # Build configuration (Rollup/Vite for bundling)
```

---

## ⚡ Development & Contribution

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/slick-svg-icons.git
   ```
2. Install dependencies:
   ```sh
   cd slick-svg-icons
   npm install
   ```
3. Start development:
   ```sh
   npm run dev
   ```
4. Run tests:
   ```sh
   npm run test
   ```
5. Submit a pull request with improvements or new icons.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙌 Support

If you find this package helpful, consider **starring the repository** and **sharing it with others**. 🚀


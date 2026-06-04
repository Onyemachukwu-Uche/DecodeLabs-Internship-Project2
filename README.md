# DecodeLabs Internship — Project 2: Fluid Responsive Design

## 📱 About the Project
For my second project with DecodeLabs, the focus is entirely on building smooth, highly responsive layouts that look great on any screen size. Instead of using rigid pixel values or heavy JavaScript libraries, I built this using a **mobile-first mindset** and modern CSS features like Grid, Flexbox, and fluid typography. 

The goal here was clean code, fast performance, and a layout that stretches or shrinks organically depending on what device you're using.

---

##  Key Features & Technical Goals

*   Mobile-First Design:** I started styling for mobile screens first as the baseline, then used clean CSS Media Queries to scale the layout up beautifully for tablets and desktops.
*   CSS Grid & Flexbox Teamwork:** I used CSS Grid to build the main blueprint of the page (the structural rows and columns) and Flexbox inside components (like navbars and cards) to keep individual items neatly aligned.
*   Fluid Layouts with `clamp()`:** No more jerky jumps between screen breakpoints. By using relative units like `rem` and `vw`, along with the `clamp()` function, fonts and spacing scale completely smoothly.
*   Zero JS Overlays (Popover API):** To keep the code lightweight and lightning-fast, I used the browser's native Popover API to handle interactive elements (like popups or toggles) instead of writing extra JavaScript.

The code is live at : https://fluid-core-responsive-webpage.vercel.app/

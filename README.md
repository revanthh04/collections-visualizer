# Java Collections Visualizer

A high-performance, fully interactive web application designed to help developers and students master the Java Collections Framework. By visually simulating the internal mechanics of data structures at the memory level, this tool bridges the gap between theoretical knowledge and practical implementation.

## 🚀 Why This Project?

Every line of code touches a data structure. Choosing the right collection isn't just an interview question—it's the difference between code that scales and code that crashes. This visualizer provides deep, intuitive insights into how Java handles memory, pointers, and internal arrays, empowering you to make better architectural decisions.

## ✨ Features

- **7 Fully Interactive Visualizers:** Supports `ArrayList`, `LinkedList`, `ArrayDeque`, `PriorityQueue`, `TreeSet`, `HashSet`, and `LinkedHashSet`.
- **Real-Time Data Manipulation:** Perform operations like `add()`, `remove()`, `get()`, and `poll()` and watch the data structures react instantly.
- **Internal Mechanics Exposed:** Watch arrays resize (1.5x growth), nodes traverse, heaps sift-up/down, trees rotate, and hash tables linearly probe on collisions.
- **Comprehensive Theory Sections:** Built-in explanations, complexity tables (Big-O), and indexing formulas directly alongside the visualizer.
- **Operation Logs:** A running terminal-style log tracks the step-by-step logic of every operation you perform.
- **Responsive & Dark Theme:** A premium, fully responsive UI built natively without heavy external libraries.

## 🛠️ Tech Stack

- **Frontend Core:** HTML5, Vanilla JavaScript (ES6+), Semantic HTML
- **Styling:** Vanilla CSS3 (Custom Properties, Flexbox, CSS Grid, Advanced Transitions)
- **Visualization:** CSS Transforms, SVG manipulation
- **Architecture:** Zero dependencies, lightweight and extremely fast

## 📁 Folder Structure

```text
/
├── index.html                 # Main landing page & Collection hierarchy
├── style.css                  # Landing page styling
├── visualizer-common.css      # Shared design system for all visualizers
├── ArrayList/                 # Dynamic Resizable Array visualizer
├── LinkedList/                # Doubly-Linked List visualizer
├── ArrayDeque/                # Circular Ring Buffer visualizer
├── PriorityQueue/             # Binary Min/Max-Heap visualizer
├── HashSet/                   # Hash Table (Linear Probing) visualizer
├── LinkedHashSet/             # Hash Table + Insertion Order Chain visualizer
└── TreeSet/                   # Red-Black Tree visualizer
```

## 📸 Screenshots

*(Place your images in the `/assets` folder and uncomment the links below!)*

![Landing Page](./assets/landing.png)
![Priority Queue Visualizer](./assets/priorityqueue.png)
![Hash Set Probing](./assets/hashset.png)

## 💻 Usage & Installation

Because this project is built entirely with Vanilla HTML/JS/CSS and has zero dependencies, you can run it immediately without any build steps!

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/collections-visualizer.git
   cd collections-visualizer
   ```

2. **Run locally:**
   Simply open `index.html` in your web browser. 
   
   Alternatively, if you prefer a local server:
   ```bash
   npx serve .
   ```
   Then navigate to `http://localhost:3000`.

## 🔮 Future Improvements

- Add visualization for `HashMap` and `TreeMap`.
- Introduce a "Step-by-Step Debugger" mode where animations pause and require the user to click "Next Step".
- Include a quiz mode to test time complexity knowledge.

## 👤 Author

Developed by Revanth.

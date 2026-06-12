# Binary-Search-Visualizer
# 🔍 Binary Search Visualizer

An interactive web application designed to visualize how the **Binary Search Algorithm** works in real-time. This tool helps students and developers understand the "divide and conquer" approach by animating the pointers ($Low$, $High$, and $Mid$) as they search through a sorted array.

---

## 🚀 Live Demo
> **[Insert your Live Project Link Here]** *(e.g., GitHub Pages, Netlify, or Vercel link)*

---

## 🧠 What is Binary Search?

Binary Search is an efficient algorithm for finding an item from a **sorted** list of items. It works by repeatedly dividing in half the portion of the list that could contain the item, until you've narrowed down the possible locations to just one.

### Algorithm Complexity
* **Time Complexity:** $\mathcal{O}(\log n)$ — drastically faster than Linear Search $\mathcal{O}(n)$ for large datasets.
* **Space Complexity:** $\mathcal{O}(1)$ — performed in-place.

$$\text{Mid} = \lfloor \frac{\text{Low} + \text{High}}{2} \rfloor$$

---

## 💻 How to Use the Visualizer

1. **Generate Array:** Click to generate a random array (the visualizer automatically sorts it!).
2. **Set Target:** Enter the number you want to find in the input field.
3. **Choose Speed:** Adjust the animation speed slider to follow along comfortably.
4. **Click Search:** Watch the algorithm dynamically shift boundaries:
   * 🟦 **Blue Bars:** Unexplored search space.
   * 🟨 **Yellow/Orange Bars:** Current $Low$ and $High$ pointers.
   * 🟥 **Red Bar:** Current $Mid$ element being checked.
   * 🟩 **Green Bar:** Target found successfully!

---

## ✨ Features

* 📊 **Real-Time Step Animations:** Color-coded bars perfectly illustrate pointer updates.
* 🎛️ **Custom Control Panel:** Generate new arrays, change array sizes, and adjust visualization speeds.
* 💡 **Step-by-Step Logic Logs:** Displays textual explanations of what the algorithm is doing at each step (e.g., *"Target > Mid, shifting Low pointer"*).
* 📱 **Responsive UI:** Clean, minimalist, and responsive dashboard layout built for modern browsers.

---

## 🛠️ Tech Stack

* **HTML5 & CSS3:** Semantic layout, custom UI sliders, and flexbox/grid system for the array bars.
* **JavaScript (ES6):** Core algorithm implementation, asynchronous timing controls (`async/await`, `promises`) for pauses, and dynamic DOM rendering.

---

## ⚙️ Installation & Local Setup

To run this visualizer locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone

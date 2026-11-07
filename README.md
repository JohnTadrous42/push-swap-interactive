# 🎮 Push_Swap Interactive Web Game & Sandbox

An interactive, browser-based visualizer and playable sandbox inspired by the classic `push_swap` algorithmic challenge.

Built as a personal side-project through **vibe coding** (AI-augmented rapid prototyping), I created this tool for myself to manually play through stack operations, test sorting heuristics, and build an intuitive feel for stack manipulation before implementing the actual solver in C.

---

## 🎯 Why I Built This
While preparing to tackle `push_swap` during my studies at **42 Prague**, I didn't want to jump straight into doubly linked lists and pointer manipulation in C without seeing the bigger algorithmic picture first.

I decided to build my own visual sandbox where I could:
1. **Play the game manually** to feel how numbers flow between `Stack A` and `Stack B`.
2. **Test sorting algorithms** (like Turk sort, Chunk sort, or Radix) step-by-step on small and medium stacks.
3. **Experiment and discover new patterns** on my own for minimizing instruction counts.

---

## ✨ Features
- **Full Operation Set:** Interactive controls with tooltips for `sa`, `sb`, `ss`, `pa`, `pb`, `ra`, `rb`, `rr`, `rra`, `rrb`, and `rrr`.
- **Real-Time Move History:** Tracks every operation executed in sequence.
- **Algorithmic Complexity Evaluator:** Automatically benchmarks your move count at the end of each level against theoretical sorting complexities ( $O(n \log n)$, $O(n\sqrt{n})$, and $O(n^2)$ ) .
- **Built-in Frustration Button:** Because sometimes your manual sorting goes way over the limit *(Stay away from the duck 🦆)*.
- **Zero Dependencies:** Pure HTML, Tailwind CSS (CDN), and Vanilla JavaScript in a single portable file.

---

## 🚀 How to Play
Clone the repository and open `index.html` directly in your browser, or play it live via GitHub Pages!

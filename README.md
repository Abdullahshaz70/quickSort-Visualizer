# 🔀 Sorting Algorithm Visualizer

An interactive, single-page visualizer for classic sorting algorithms — step through each one bar-by-bar, watch the pseudocode highlight in sync, and track live stats like comparisons, swaps, and recursion depth.

---

## 📖 Overview

Built entirely in vanilla HTML, CSS, and JavaScript with zero dependencies, this tool lets you pick an algorithm, generate or type in your own array, and watch it sort one operation at a time. Every step is color-coded (pivot, comparing, swapping, sorted) and mirrored in a synced pseudocode panel, so you can see exactly which line of the algorithm is executing at any point.

## ✨ Features

- 🧮 **6 algorithms**: QuickSort, MergeSort, BubbleSort, HeapSort, InsertionSort, SelectionSort
- ▶️ **Step-by-step playback** — play, pause, step forward, and step backward through the sort
- 📝 **Synced pseudocode panel** — the active line highlights in real time, color-matched to the current operation
- 📊 **Live stats panel** — comparisons, swaps/writes, array accesses, and recursion depth
- 📈 **Time complexity reference** for the selected algorithm (best/average/worst/space)
- 🎨 **Color-coded bars** for pivot, comparing, swapping, subarray, merging, and sorted states
- 🎚️ **Adjustable speed and array size** via sliders
- 🎲 **Data presets**: random, sorted, reverse sorted, nearly sorted, many duplicates, few unique values
- ✏️ **Custom array input** — type your own comma-separated values
- 🎯 **Pivot strategy selector** for QuickSort — last element (Lomuto), first element, random, median-of-three
- 🔊 **Sound toggle** — audio tones mapped to comparisons, swaps, and pivot selection
- ⌨️ **Keyboard shortcuts** — Space (play/pause), ←/→ (step back/forward), R (reset), N (new array)

## 🚀 Getting Started

No build steps, no dependencies, no installation.

```bash
git clone https://github.com/Abdullahshaz70/quickSort-Visualizer.git
cd quickSort-Visualizer
```

Then just open `index.html` in any browser — or use a live server for the smoothest experience:

```bash
# Using Python
python -m http.server 8000

# Then visit
http://localhost:8000
```

## 🕹️ How to Use

1. Pick an algorithm from the tabs at the top
2. Choose a data preset, adjust array size/speed, or type a custom array
3. For QuickSort, optionally choose a pivot strategy
4. Hit **Play** to auto-run, or **Step** to move one operation at a time
5. Watch the bars, pseudocode, and live stats update together
6. Toggle sound 🔊 for audio feedback on comparisons and swaps

## 📁 Project Structure
quickSort-Visualizer/
└── index.html     # Full app — markup, styles, and sorting/visualization logic

## 👤 Author

**Abdullah Shahzad** ([@Abdullahshaz70](https://github.com/Abdullahshaz70))

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

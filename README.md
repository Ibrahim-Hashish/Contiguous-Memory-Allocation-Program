# Contiguous Memory Allocation Simulator

A Python-based simulator for **Contiguous Memory Allocation** using First Fit, Best Fit, and Worst Fit strategies. This project provides an interactive command line interface (CLI) and visual representation of memory usage.

---

## Features

- Allocate memory using:
  - First Fit
  - Best Fit
  - Worst Fit
- Deallocate memory blocks by process ID
- Merge adjacent free blocks automatically
- Compact memory to reduce fragmentation
- Simulate random allocations
- Visualize memory layout using Matplotlib

---

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/memory-allocator.git
cd memory-allocator
```

### 2. Install Dependencies
```bash
pip install matplotlib
```

### 3. Run the Program
```bash
python memory_allocator.py
```

---

## Project Structure

```
memory_allocator.py        # Main memory allocator simulator
README.md                  # Project documentation
```

---

## Usage

From the CLI menu, you can:
- Allocate memory to a process
- Deallocate memory
- Visualize memory layout
- Simulate random allocations
- Compact memory

---

## Sample Commands

- **Allocate Process:**
  - Input: `P1`, Size: `25`, Strategy: `best_fit`
- **Deallocate Process:**
  - Input: `P1`
- **Compact Memory:**
  - Choose option 6 from the menu

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contributing

Feel free to fork the repository, open issues, or submit pull requests to improve the simulator.

---

## Contact

Created by **Ibrahim Hashish**  
GitHub: [@Ibrahim-Hashish](https://github.com/Ibrahim-Hashish)  
Email: ibrahimhashish257@gmail.com


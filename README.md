Tower of Hanoi Visual Simulator (Python)

📌 Project Overview

This project implements a Tower of Hanoi Visual Simulator using Python. It demonstrates how disks are moved between rods following specific rules, using recursion and stack operations.
Each rod is represented as a stack, and disk movements are visualized step-by-step using a graphical interface. The simulator helps users clearly understand how the algorithm works internally.


🎯 Objectives

Represent rods using stack data structure
Implement the Tower of Hanoi algorithm using recursion
Visualize disk movements step-by-step
Improve understanding of problem-solving techniques
Learn GUI-based simulation in Python


🧠 Concept

The Tower of Hanoi is a mathematical puzzle where:
There are 3 rods (Source, Auxiliary, Destination)
There are N disks of different sizes

Rules:
Only one disk can be moved at a time
A larger disk cannot be placed on a smaller disk
Only the top disk can be moved


⚙️ Working Principle


The solution uses recursion:

Move (n-1) disks from Source → Auxiliary

Move nth disk from Source → Destination

Move (n-1) disks from Auxiliary → Destination


💻 Technologies Used


Python – Programming language

Tkinter – GUI visualization

Data Structures – Stack (LIFO)

Algorithm – Recursive approach


✨ Features

Graphical visualization of rods and disks

Step-by-step animation

Stack-based implementation

Easy to understand interface


📚 Applications

Teaching recursion concepts

Understanding stack operations

Algorithm visualization

Educational tool for students


✅ Advantages

Makes learning interactive

Simplifies complex concepts

Enhances logical thinking

Visual understanding of recursion


⚠️ Limitations

Slower for large number of disks

Basic user interaction

Requires GUI support


🚀 Future Enhancements

User input for number of disks

Add pause/resume buttons

Improve animation speed

Better UI design


🏁 Conclusion

This project provides a clear and interactive way to understand the Tower of Hanoi algorithm using recursion and stack operations, making it an effective learning tool for students.

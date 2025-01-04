# Doublet Game Solver (Word Ladder)

This project implements an algorithm to solve the **Doublet Game**, also known as **Word Ladder**. The objective of the game is to transform a designated starting word into a designated ending word, one letter at a time, with each intermediate word being valid in a restricted dictionary.

---

## Key Features
- **Algorithm**: Utilizes **A* Search** to find the optimal solution efficiently.
- **Custom Data Structures**: Implements a custom heap for performance optimization.
- **Frontend and Backend Integration**: 
  - **Backend**: Developed in C++ for high-performance computation.
  - **Frontend**: Built using the **Python Django Web Framework** to connect users to the backend logic.

---

## How It Works
1. **Input**: Users specify a starting word, an ending word, and a dictionary.
2. **A* Search**: The algorithm calculates the shortest transformation sequence based on:
   - Word similarity (heuristic).
   - Path cost (number of transformations).
3. **Output**: The optimal sequence of words is presented, satisfying the game's rules.

---

## Live Demo
Check out the live version of the project:  
[**Doublet Game Solver**](https://www.doublet.martinestrin.com/)

---

## Technologies Used
- **C++**: Backend logic, including A* Search and custom heap implementation.
- **Python Django**: Frontend and backend integration.
- **Web Hosting**: The project is deployed and accessible online.

---

## About the Doublet Game (Word Ladder)
The Doublet Game is a word puzzle invented by **Lewis Carroll** in 1878. The challenge is to find the shortest sequence of valid transformations from one word to another by changing only one letter at a time. For example:
- Start: `cat`
- End: `dog`
- Solution: `cat → cot → dot → dog`

---

## Future Improvements
- Expand dictionary options for more extensive word sets.
- Add visualization for the transformation sequence.
- Optimize backend performance for larger dictionaries.

---

Feel free to explore the project, try the live demo, or contribute ideas for improvements!

# Quantum Tic-Tac-Toe (Canvas)

Single-file, offline-friendly implementation of **Quantum Tic-Tac-Toe** using HTML5.  

## Play online
Access to:
https://ManuM2B.github.io/Quantumtictactoe/

## How to play (brief)
- Each turn, tap **two cells** to place quantum marks.  
- If you tap the **same cell twice** (with no prior ghosts there), you place a **classical** mark directly.
- Closing a **cycle** makes the involved cells **glow**; tap any to start the collapse. The **white ray** travels from the first collapsed cell to the next affected ones, collapsing them in sequence.
- **Win condition:** the first player to get **three collapsed (classical) marks in a row**.  
  If both get three-in-a-row after a collapse, the winner is the one with the **smaller sum** of move numbers; if still tied, the player who **triggered the collapse** wins.

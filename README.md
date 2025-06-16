# Solitaire Game

This is a simple text-based solitaire game written in Python.

## How to Play

1.  Run the `solitaire.py` file using Python:
    ```
    python solitaire.py
    ```

2.  The game will start and display the initial board setup.

3.  Enter your moves using the command prompt.

## Commands

*   `draw`: Draws a card from the stock to the waste pile.
*   `move <from> <to>`: Moves a card from one pile to another.
    *   `<from>` and `<to>` can be:
        *   `t<n>`: Tableau pile (e.g., `t1`, `t2`, etc.)
        *   `f<n>`: Foundation pile (e.g., `f1`, `f2`, etc.)
        *   `w`: Waste pile
*   `move <from> <to> <n>`: Moves `<n>` cards from one tableau pile to another.
*   `quit`: Exits the game.

## Example Moves

*   `move t3 f1`: Moves the top card of tableau pile 3 to foundation pile 1.
*   `move w t5`: Moves the top card of the waste pile to tableau pile 5.
*   `move t2 t4 3`: Moves the top 3 cards from tableau pile 2 to tableau pile 4. 
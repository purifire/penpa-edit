# penpa-editor

Universal pencil puzzle editor capable of drawing many different kinds of pencil puzzles. You can also solve problems in the software.

You can save images and text in the form of URLs than be loaded in a browser.

*If the message "Invalid address" is displayed on a supported browser, try clearing the cache.

Depending on the browser you can update the page without using the cache with "Ctrl" + "R", "Ctrl" + "F5", "Shift" + "F5", etc.

## Compatible browsers
* Google Chrome
* Safari
* Firefox
* Microsoft Edge

## Shortcut keys
* Ctrl + z: Undo
* Ctrl + y: Redo
* Ctrl + d: Copy the board
* Ctrl + space: Delete numbers and symbols at the same time
* F2: Problem mode
* F3: Answer mode

## Tips
* Numbers: Back Space can be entered on the panel "1" tab and half-width space can be entered on the "A" tab.
* Number>Arrow: Enter an arrow in the direction you dragged the square.
* Symbol: Input with the numeric keys 1-9,0. When the panel is turned on, a list of symbols that can be entered is displayed, and it corresponds to 1, 2, ... from the upper left. To use the panel place the cursor on the panel symbol and click the board. Erase with two clicks.
* Some symbols such as symbol> figure> cross are onoff input formats. Click the panel to enter directly. Special example: Digital (frame) with the same key. If you press it twice, only the frame will be displayed.
* Special: Delete by clicking the first square of the entered symbol.
* Special: The tip position can be returned to the front by returning to the path that was used during input.

## Current functions
### Surface
* Fill cells. Select a color by style. (Nurekabe, Iceburn, Shakashaka etc.)
* In Dark grey mode only, click twice to get a green square.
* Light grey is used when hiding gray letters and symbols.
* Right click to enter the green square.
### Line
* Normal: A line connecting the center of the square to the horizontal and vertical. (Mashu, bridge over, palindrome Sudoku, etc.)
* Diagonal line: A line connecting the center of the square to the namame. (Zigzag etc.)
* Free line: A line that connects arbitrary squares. (Night tour etc.)
* Midline: A line connecting the center of the square and the center of the side.
* Auxiliary x: An auxiliary cross mark placed on the side.
* Select the color and thickness of the line by style.
### Edge
* Normal: A line that connects the top of the square to the horizontal and vertical. (Heyawake, Slither link etc.)
* Diagonal line: A line connecting the vertices of a square to a namame. (Diagonal Sudoku etc.)
* Free line: A line that connects the vertices of any square. (Sharp and blunt loop etc.)
* Auxiliary x: An auxiliary cross mark placed on the side.
* Border erase: Delete the border of the board.
* Select the color and thickness of the line by style.
### Wall
* A vertical line drawn inside the square. (Vertical and horizontal, slalom etc.)
* Select the color and thickness of the line by style.
### Number
* Normal: Enter numbers, alphabets, and some symbol characters from the keyboard. You can use the panel to input symbols, katakana, hiragana, kanji, etc.\\
.. (Coloring etc.)
* Arrows: Characters with arrows. (Yagirin, CastleWall etc.)
* Tapa: Characters for Tapa. Up to 4 characters.
* 1/4: Characters at the four corners. (Kakuro, Hairyrin, Killer Sudoku etc.)
* Comp: Characters for compass. It is possible to enter small numbers depending on the vertical and horizontal directions.
* Medium/Small: Small size numbers.
* Long sentence: Long sentence. It is possible to create a list such as seekers.
* Candidates: Candidate numbers for Latin Square such as Sudoku. Compatible with 1-9. onoff input.
* White circles and black circles have a circle on the back of the numbers.
* For the white background, draw a white circle behind the numbers. When you can't see the numbers because they are hidden behind the lines.
* When the boundary input is turned on, the character is placed on the side/vertex.
### Frame
* A line that surrounds multiple squares. (Killer Sudoku etc.)
* There are 4 styles: black dotted line, black solid line, gray dotted line, and gray solid line.
* Available in square and regular hexagon.
### Box
* Click to select the square that draws the frame of the board.
### Move
* You can move numbers and symbols by dragging. Originally, you cannot move to a square with a number or sign.
* All can be set to move both numbers and symbols, or either numbers or symbols.
### Composite
* Ability to use multiple input methods simultaneously.
* Composite mode list
1. Black/dot: Drag the black square and dot
2. White/circle Black circle Drag input white circle and black circle
3. Shakashaka pull the triangle to input
4. Line/x line and auxiliary x (Castle wall)
5. Line/OX 〇× (Country road) on line and square
6. Edge/x/inside/outside, auxiliary x, and inside/outside painted yellow and green. (Suririn, Cave)
7. Yajirin: Black square/dot and line
8. Hashi: draw the line again to make a double line
9. Edge/Auxiliary line: An auxiliary line that represents the connection between the edge and the square
10. Battleship: Click twice to change the shape according to the condition of the surrounding ships.
11. Star Battle x Star
12. Tent: A tent and a point, an auxiliary x on the side, and a line that connects the tent and a tree.
13. Numerical flick Input the numerical flick. 123456789 from top left to bottom right.
14. Alphabet flick Enter the alphabet by flick. ABCDEFGH- from top left to bottom right. Enter-in the lower right corner.

### Irregular board shapes
* You can select square, regular hexagon, regular triangle, and pyramid from the "New/Change frame" menu. Functions other than square are limited.
* Adjust the board shape in "mass" mode. From the "Rotate/Move" menu, press the "Move board to center" and "Match screen size to board" buttons to adjust margins.

### Grid
* You can change the border of the board from the "New/Change frame" menu.
* Grid: Border type
* Gridpoints: whether to place points at vertices
* Outside frame: Whether to draw a line around the board
* White space: Used when placing numbers outside the grid on the board. (Sandwich puzzle etc.)
* "Create" button resets the board. The "Change grid" button does not reset the board surface, but updates only display size and frame type.

### Rotation
* You can rotate and flip the board from the "Rotate/Move" menu. Square and pyramid rotate 90°. Regular hexagon, regular triangle Rotate 30° on the board surface.
* Adjust the margin of the board with the "Move the board to the center" and "Match screen size to the board" buttons.

### Save image
* Image quality: The higher the quality, the better the image quality, but the larger the image size.
### Save image (Screenshot button)
* Settings:
1. Image quality: The higher the quality, the better the image quality, but the larger the image size.
2. White Border: Setting NO will remove the extra white space around the grid.
* Options:
1. Open in new window: Opens the image in the new TAB
2. Download: .png image will be downloaded
3. Cancel: close the window

### Share
* URL for editing
1. Complete creating puzzle in Edit mode "Problem".
2. If you need to save your puzzle creation progress and come back later to edit then click on this button

* URL for solving
1. Complete creating puzzle in Edit mode "Problem".
2. If you want to share your puzzle for others to solve then click on this button

* URL for solving with Solution
1. Complete creating puzzle in Edit mode "Problem".
2. Select Edit mode "Solution" and complete the solution.
3. If you want to share your puzzle for others to solve with the ability to verify the solution then click on "Extra options" button. A new small window will appear.
4. Click on "Generate URL with answer check"
5. Click anywhere on the screen outside the small window.

* Options
1. Copy: copies the URL to the clipboard
2. Download: downloads a .txt file with the url
3. Open: opens a new TAB with the same url
4. URL_short:
	1. First create an URL using one of the three methods described above.
	2. Click on "Copy".
	3. Click on "URL_short" (It will open a new TAB).
	4. Paste the URL (CTRL + V on windows).
	5. Click "Shorten"
4. Cancel: close the window

## History
* 2020/01/05 ver2.12 Adjusted mouse judgment.
* 2019/12/21 ver2.11 Implemented composite mode.
* 2019/12/07 ver2.10 Ver.2, which was being developed at another address, is integrated with the old address.
* 2019/09/07 ver2.00 Deformation board support etc.
* 2019/08/16 ver1.05 Microsoft Edge compatible
* 2019/08/04 ver1.04 Changed the specifications of white border and changed the input method of symbols
* 2019/07/29 ver1.03 Fixed drawing of dotted line etc.
* 2019/07/18 ver1.02 iPhone compatible
* 2019/07/14 ver1.01

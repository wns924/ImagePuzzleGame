# Image Puzzle Game
It allows the user to select an image as a puzzle and the user can then play with the selected images.

## Select an image
![filechooser](/filechooser.png)

When JavaPuzzle is executed, a file chooser should be presented to ask for an image file.

## Display the image and randomise the image
![ui](/ui.png)

The image is loaded from the selected file and is divided into blocks of 80*80 pixels in size displayed as shown in above figure. The blocks of the image are randomized so that the user will not see the original image. If the image file fails to load, the program should generate an error message and ask the user to select another image file. Each image block should keep its original position information so that the original image can be
reconstructed.

The image should be resized and scaled to fit into a canvas of 800*800 pixels in size. If the new image fails to load, an error message should be displayed and the old image is retained.

## Drag and Drop the image to the right position
![d&d](/d&d.png)

The movements of image block are controlled manually by pressing and releasing the mouse. If an image block is currently at (i, j), the user has to press the mouse at (i, j) and drag it to the target image block position, then the selected image block and the target image block will be swapped.

![win](/win.png)

If the destination image block is in the correct position, drag and drop another image block to that position will NOT swap their position, and a message should be displayed. The game is finished when all image blocks are in correct position.
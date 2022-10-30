# Guide for optimizing SVG icons for fasteners workbench

This guide is written for INKSCAPE editor version 1.1 or higher.

## 1. Save icons as Optimized SVG file.

Save icons by **"File → Save As..."** menu item. File type select as: **Optimized SVG (*.svg)**

In opened window select next options:

![image](https://user-images.githubusercontent.com/116030160/197383516-2e013546-8a8d-4b92-960b-984350077984.png)

That must decrease size of *.svg file to 40-60%.

## 2. Use one solid contour instead fill instrument.

## 3. Simplify curve paths.

Select curve and press **CTRL+G** or menu item **Path → Simplify** 

## 4. Join paths.

Switch to "Edit paths by nodes" mode by pressing ![image](https://user-images.githubusercontent.com/116030160/198841313-97c477a8-d142-43ae-813f-de114027b559.png)
 button or press **N key** on keyboard.
Select two separated paths. Down CTRL key and select two points where paths are connected.
Press ![image](https://user-images.githubusercontent.com/116030160/198841498-1a7af5a2-24af-495d-aa65-34f2d0ae18ee.png)
 button to join paths.

## 5. Use XML Editor. Remove garbage tags and attributes.

![image](https://user-images.githubusercontent.com/116030160/198841682-7f796d4b-cdee-4a38-b917-e06648cd89ed.png)

Remove unneeded attributes too. Like sodipodi, font attributes etc...

**Next methods needs use XML editor.**

## 6. Get rid of the matrix() and translate() attributes.

Select the subgroup that contains this attribute.
Make Ungroup operation by press SHIFT+CTRL+G keyboard key combination or through **Object → Ungroup** menu item

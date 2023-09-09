# Assignment-2
 
STEP 1:
Wrote basic HTML code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" type="text/css" href="style.css" />
    <title>Assignment 2</title>
  </head>

  <body>
</html

STEP 2:
Inside the <body>, there is a <div> element with the class "first." This <div> acts as a container for organizing and styling a specific section of content on the webpage.

STEP 3:
Inside the "first" div, there are several nested <div> elements with different class names ("firstRow," "SecondRow," "thirdRow," and "forthRow"). These nested <div> elements represent rows inside the main div. Because we have 4 rows in the given task.
STEP 4
The "SecondRow" contains additional nested <div> elements with class names ("R2C1," "R2C2," "R2C3," "R2C4" 
The "thirdRow" contains 4 additional <divs> with class names "R3C1," "R3C2," "R3C3," "R3C4"
STEP 5
The "forthRow" div represents another section at the bottom of the "first" div.

STEP 6:	
Next we have to add CSS to these divs
STEP 7:
body Styles were add to reset default spacing and to ensure proper box sizing we added, padding: 0; margin: 0; box-sizing: border-box..
border: 2px solid #fff;: Adds a white border around the entire page.
STEP 8:
.first div:
background-color: black;: Sets the background color to black.
position: relative;: Establishes a positioning context for child elements.
border: 10px solid black;: Adds a thick black border around the container
STEP 9
.firstRow Styles
width: 100%;: Makes the row span the full width of its container.
height: 90px;: Sets the height of the row to 90 pixels.
background-color: #64a8ff;: Sets the background color to a blue shade.
STEP 10
.secondRow Styles
width: 100%;: Spans the full width.
height: 80px;: Sets the height of the row to 80 pixels.
STEP 11:
.thirdRow Styles
position: absolute;: Positions the row absolutely within its container.
STEP 12:
.R2C1, .R2C2, .R2C3, .R2C4 Styles (Columns in Second Row)
Each column has a width of 25% to evenly distribute them across the row.
height: 50px;: Sets the height of each column to 50 pixels.
background-color: Defines the background color for each column.
position: absolute;: Positions each column absolutely within its parent (SecondRow) to allow for precise placement.
left: 0%, 25%, 50%, 75%, R2C1, R2C2, R2C3, R2C4 respectively, Adjusts the left property to place each column at the desired position within the row.
STEP 13:
.R3C1, .R3C3, .R3C4 Styles (Columns in Third Row)
these columns have specific widths, heights, and background colors.
position: absolute;: Positions each column absolutely within its parent (thirdRow) for precise placement.
top, left, and right properties are used to position these columns as needed.
STEP 14:
.R3C3 Styles (Centered Column)
position: absolute;: Positions the column absolutely within its parent.
top: 50%; left: 50%;: Initially centers the column based on the top-left corner.
transform: translate(-50%, -50%);: Centers the column both horizontally and vertically within its parent by moving it back 50% of its own width and height.
STEP 15:
.forthRow Styles
width: 90%;: Sets the width to 90% of the container.
height: 100px;: Sets the height of the row to 100 pixels.
background-color: #217544;: Defines the background color..

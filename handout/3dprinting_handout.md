Title: 3D printing Workshop 

# Workshop Breakdown
## Opening Lecture/Remarks (20 - 30 Minutes)
    + Introduction of 3D printing generally, different methods, processes and the printers used for the workshop
    + Overview of 3D modeling software
        - Overview of what 3D modeling software is
## Introduction to Autodesk Fusion (40 minutes - 1 hour)
    + Basic 3D modeling
        - A handout will be provide that walks participants through some of features/tools of 123D Design
        - At the end of this section of the workshop the participants will have create 3-4 'base' objects
    + Sandbox/ Introduction to Making your own 3D object on Fusion (1 hour)
        - Using the “base” models created earlier in the workshop participants will create their own models
        - Participants can create their own model if they already have something in mind.
## 3D printing time / More Sandbox (40 minutes – 2 hour)
    + Printing your own 3D object
        - Participants not ready to print are encouraged to continue working on their object
            - If you don’t finish their object in time you can come back to Studio 307 to model and print later!
    + Printing using the Makerbot
        - Using the Makerbot Desktop software participants will set-up and start a 3D print
		
		------

# Introduction
The layout of Autodesk Fusion is comprised of three major parts: The workspace, the toolbar, and the viewing options.
## The Workspace
[comment]: Image of blank workspace
The workspace is where sketches and objects can be created and manipulated. It is represented by a grid, which will scale in size in relation to your project.
## The Toolbar
[comment]: Image of toolbar
The toolbar is at the top of the window and contains various features/tools that will allow you to create 3D objects. This session you will be introduced to several, but not all, of these features.
## Viewing Options
[comment]: Image of viewing bar
The viewing options can be found on the right hand side of the window. These will allow you to move the camera and change the property of the object in order to make modeling easier.

**TIP: Right clicking while over the workspace will allow you to “orbit” objects**
[comment]: Is this still valid? Review viewing hotkeys on the mouse

# Object One – DICE
The first object we will be creating is a dice. The goal of this section is to introduce you to several features of the program (such as the extrude, cut, and fillet) as well as challenging you to think three dimensionally.
## Creating a Base Solid
The first thing we need to do is to create a base solid, a cube, for our dice:

Select the **SKETCH** option in the toolbar and click on the **RECTANGLE** option. Then click on the grid in the workspace.
[comment]: Image of RECTANGLE

This will cause the grid to expand. To begin sketching click on the **ZERO POINT** (marked by a circle) which will now act as your base point for this object.
[comment]: Image of ZERO POINT

Move your mouse out a bit and the outlines of a rectangle will be sketched.
[comment]: Image of basic rectangle

Enter a value of 25mm for both the length and width (using tab to move between the value boxes) and press enter. Your newly created square will change colours indicating you have **CLOSED** the sketch.

Next, go back to the toolbar and select the **CONSTRUCT** option and click on the **EXTRUDE** tool.
[comment]: Image of the tool

Click on your square, input a value of 25mm, and then press enter. You should end up with cube that looks like this:
[comment]: Image 
   
## Modifying the Base Solid
With our base solid now in place we cam start to make it more "dice" like in appearance.

Select the **MODIFY** option and click on the **FILLET** tool
[comment]: Image 

Begin to select the **EDGES** of the cube. They will change in colour once they have been selected.
[comment]: Image 

Once all the edges have been selected input a value of 2mm for the fillet radius and press enter.

**TIP: The edges can be fillet individually if you wish.**

The resulting cube should look like this:
[comment]: Image 

## Making Holes
The final step in making the dice is to assign values to each face.

Selected the **SKETCH** option in the toolbar and click on the **CIRCLE** tool.

To begin your sketch, click one of the faces the dice. This will cause the grid in the workspace to move over top of it.
[comment]: Image 

Move your mouse to the center of the face and click. Move your mouse slightly and the outline of a circle will be project. Input a value of 6mm for the diameter and press enter.
[comment]: Image 

**TIP: Rotating the camera so it is directly pointed at the face will make this process easier.**

Select the **CONSTRUCT** option from the toolbar and click on the **EXTRUDE** tool.
[comment]: Image 

From the dropdown menu that appears select the **SUBTRACT** option.
[comment]: Image 

Then select the circle you just sketched, input a value of -3mm, and press enter. This will result in a cube that looks like this:
[comment]: Image 

## Finishing Up
Using the below template assign, values to each of the dice's faces.
[comment]: Image of dice net

The end result should look similar to this:
[comment]: Image 

**TIP: When subtracting, multiple circles can be selected**
 
# Object Two – CUP
In this section of the tutorial, we will work on line construction, line fillet, and revolving 
## Creating a Base Sketch
Select the **SKETCH** option in the toolbar and click on the POLYLINE tool. Then click on the grid in the workspace.
[comment]: Image 

Click on the **ZERO POINT** to create a starting point, input a value of 25mm for the distance of the line with an angle of 180 degree, and then press enter
[comment]: Image 

Select the **POLYLINE** tool and click on the end of your newly created line. Input a value of 15mm for the distance with an angle of 90 degrees and then press enter.
[comment]: Image 

Re-select the **POLYLINE** tool again as click on the end of the line you created in the previous step. Input a value of 25mm with an angle of 180 degrees and then press enter.
[comment]: Image 

Once again, select the **POLYLINE** tool and click the end of the line you created in the last step. Input a value of 10mm with an angle of 90 degrees and then press enter.
[comment]: Image 

Select the **POLYLINE** tool again and click the end of the previously created line. Input a value of 12.5mm with an angle of 0 degrees and then press enter.
[comment]: Image 

Using the **POLYLINE** tool sketch out enough lines to enclose the base sketch. The end result should look something like this:
[comment]: Image 

**TIP: the POLYLINE tool can be used to draw multiple lines at once**
## Modifying the Base Sketch
Select the **SKETCH** option in the toolbar and click on the **FILLET** tool.
[comment]: Image 

Click out the outer edges and input a value of 2mm for both. (A red outline with be projected to give you a preview of the fillet)
[comment]: Image 

When finished the sketch should look something similar to this:
[comment]: Image 

## Revolving
Select the **CONSTRUCT** option and click on the **REVOLVE** tool.

For a revolve you will need to select both a profile and an axis. For the profile, select the sketch (the shape you have drawn).
[comment]: Image 

For the axis select the line in the top right corner.
[comment]: Image 

Once both the profile and axis have been properly selected, you will be given the option of inputting a value for the revolve. Input 360 degrees and press enter.
[comment]: Image 

The final product should look similar to this:
[comment]: Image 
# Object Three – Dish
In this section of the tutorial the push and shell function will be taught
## Creating a Base Sketch
Select the **SKETCH** option in the toolbar and click on the **ELLIPSE** option. Then click on the grid in the workspace.
[comment]: Image 

Using the Zero Point as your starting point create an input a width of 10 mm and a length of 25 mm.
[comment]: Image 

Select the **CONSTRUCT** option from the toolbar and click on the **EXTRUDE** tool. Click on the Ellipse and input a value of 10mm. **DO NOT PRESS ENTER YET**
[comment]: Image 

Above the preview of the extrude there is a dial that can be moved. This is the push function. Begin to move the wheel and then input a value of 45 degrees and press enter.
[comment]: Image 

The end result should look like this:
[comment]: Image 

## Shelling
Select the **MODIFY** option in the toolbar and click on the SHELL tool.
[comment]: Image 

Click upon the top face of the object. Input a value of 2mm and press enter.
[comment]: Image 

The End result should look like this:
[comment]: Image 

# Finishing your 3D Models
Once you’ve finished your 3D model it needs to be exported as an **STL** if you want to 3D print it. To do this...
[comment]: Image 

Save your file and you’re ready to 3D print!

For the rest of the workshop you are free to design whatever you’d like-- let us know if you'd like to print!


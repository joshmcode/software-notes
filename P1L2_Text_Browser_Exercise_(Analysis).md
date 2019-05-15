# P1L2 Text Browser Exercise (Analysis)

## Introduction
Design is better learned than taught. This video has students actively participate in an exercise where we design a text browser. 

## Text Browser Exercise
The problem space is a tool that allows browsing of text in a computer file, but there is no GUI (at all) to do this. The goal is to build a cleanly structured solution. 

## Quiz: GUI Elements Quiz
What are the bare minimum GUI elements required? 
- Window
- Scroll bar

## FileManager
The text is retrieved through a file manager component. Assume that:
- File contents cannot be held entirely in memory
- There will be line-oriented access to the file at the OS level
- Need a module that can treived a limited length, consecutive subsequence of the file's lines

## ViewPort
The window component is called a view port. Need it to display the contents. Use the following assumptions in order to simplify for the example's sake:
- Display the line numbers as an integer
- Show any number of lines between 1 and 100
- Text will be in the same font and font point size

## ScrollBar
The scroll bar is a way to supply numbers to other parts of an application. Will use a vertical scroll bar. There will be a moveable "handle" that can sit in a "tray." The user can set the position in the file by moving the handle in the tray. The handle's position indicates what text should be displayed. 

The size of the handle in proportion to the size of the tray indicates how much of the file is visible. For example, if the file is very small then a very large (or no handle) will be displayed. 

## Use Cases
How will the user use the application? This is called a "use case."

## Quiz: Use Cases Quiz
Open-ended quiz asking what use cases apply for the text browser application. Here are the one's I entered. 


## Analysis Model

## Quiz: Classes Quiz

## Operations

## Quiz: Operations Quiz

## Quiz: Visible Attributes Quiz

## FileManager

## Relationships

## Quiz: Relationships Quiz

## Quiz: Number of Lines Quiz

## LinesVisible Association

## Quiz: Another Association Quiz

## Explanation

## Displays Diagram

## Quiz: Handle Association Quiz

## HandleProporation

## Subtleties

## Summary

# APPLET_COMMUNICATIONS

Instructions to Run
->Just clone the repository and open it with NetBeans IDE.
->Run the FrontPage.java

The Problem statement is given as follows

In this project, you have to design two applets on the same Webpage that can communicate with each other using applet context. One applet will display different Shapes {Circle, Rectangle and Triangle} randomly and second applet that decide the color of the shapes. Here are some important steps that you have to follow:
1.	Write a class named ShapeColorApplet that extends Applet. Add a field called ShapeSize, and a field of type String called ShapeName.
2.	Add a method called setShapeSize ( ) that has different parameters depending on radius, sides of triangle rectangle (you choose your own).   Use the getShapeSize ( ) method of initialize the ShapeSize field.
3.	Add the start ( ) and stop ( ) methods to the ShapeColorApplet class having them display and stop in change of color in different shapes.
4.	Within the start ( ) method use the showStatus ( ) method of the AppletContext interface to display the text “showing shape_name_size”, where the Shape_size is the value of the field ShapeSize and its color.
5.	Save and Complie the ShapeApplet.
6.	Write a class named EnterShapeApplet that extends JApplet. Add two JButton fields play and Stop. And a TextField field called ShapeName. Also, add a field of type AppletContext.
7.	Within init ( ) method initialize component fields. Also, initialize ApplerContextfield, then instantiate a new ColorListner object, passing the reference of the ShapeName textfiled and the AppletContextField. 
8.	Save your EnterShapeApplet class, and write a new class named ColorListner that implements ActionListener. 
9.	Write an HTML page named shapecolor.html. Add the ShapeColorApplet and EnterShapeApplet applets to the page, using two separate <applet> tags.
10.	View the shapecolor.html page in your Web browser. You should be able to enter a shapename representing a shape, change the color of the shape by clicking the Play button, and stop it by clicking the Stop button.

Specific Technology 
 Java, Applet 
Project Tasks
Use case analysis, Design, Implementation, and User Interface

---
layout: default
title: 
permalink:
---

- [Homework 5 Instructions ](https://youtu.be/c0yvP5hh6EE) [4:17 min.]

<h1> Homework 5</h1>


- You will be integrating CSS with XSLT in this assignment. 
- Download [right-click and save sales_directory.xml](http://www.albany.edu/~mwolfe/ist538/homework/hw5/sales_directory.xml) and 
- Download [right-click and save images.zip folder of images](http://www.albany.edu/~mwolfe/ist538/homework/hw5/images.zip) and retrieve your homework 4 .xsl assignment file. Here's a clean copy of homework4 [sales.xsl](http://www.albany.edu/~mwolfe/ist538/homework/hw5/sales.xsl) file just in case you need it. 
- You will also create a small CSS file that is linked to from your XSL file. It’s suggested that you create a homework 5 directory, and place all files in there. 

- Your final assignment will look like this:  [completed hw5](http://www.albany.edu/~mwolfe/ist538/homework/hw5/hw5.jpg)

**Part 1**

- Update the .xml file for each employee so that  it links to an image. Take this,<span style="font-family:Courier">&lt;photo&gt;  &lt;/photo&gt;</span> and do something like this <span style="font-family:Courier">&lt;photo&gt;</span>stuff/pink_panther.gif<span style="font-family:Courier">&lt;/photo&gt;.</span>
  - Update your homework 4 [sales.xsl](http://www.albany.edu/~mwolfe/ist538/homework/hw5/sales.xsl) file with the following:
   
      - Create a table heading for <span style="font-family:Courier"> “Photo”</span> for both tables
      - Ensure that you add a table data tag to select the image in the for-each loop. Use <span style="font-family:Courier">&lt; img src="{photo}" width="500" height="500"/&gt;</span> to select a photo each time it loops through. Use curly braces in XSLT  to take the value of an XML element and put it inside an HTML attribute, such as <span style="font-family:Courier">src</span>.  Update the height and width so it looks nice. 
      - According to the image of the completed project, you will need to delete code from your .xsl file so it prints the appropriate XML data.
      <p/>
- Create a .css file with the following:
  
    - Link your .css file from your .xsl file, per our exercise for Unit 10 
    - Create selectors for <span style="font-family:Courier">img, strong,</span> and <span style="font-family:Courier">table</span>:
    
      - <span style="font-family:Courier">img </span>set the padding, <span style="font-family:Courier">width</span> and <span style="font-family:Courier">height</span> appropriately. Make rounded corners for your image and a background image. See this link for how-to details: <a href="http://www.w3schools.com/css/css3_borders.asp">http://www.w3schools.com/css/css3_borders.asp</a>
       - <span style="font-family:Courier">table</span> set width and height to <span style="font-family:Courier">&quot;auto&quot;.</span>
       - <span style="font-family:Courier">strong</span> set color to red and margin to the left at 20 pixels.

**Part 2 (1 point of extra credit)**

- Create a way to find the highest and lowest  sellers in the company, and print their last name, image and sales. Since we  only covered this syntax in passing, I will give you some code hints here for finding the highest seller: [code for highest seller.](http://www.albany.edu/~mwolfe/ist538/homework/hw5/highest_seller_code.txt)

<br/>
- You will compress all four items (.css, .xml, .xsl files and the images folder) and email me as **one .zip file.**
- This assignment is worth 10 points. 
- It's due **Monday July 27th**
- You may work on this together on the discussion board, but please send me your own project to my email. 
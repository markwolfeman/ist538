---
layout: default
title: 
permalink:
---

<h1> Homework 1</h1>
- [Final Project video instructions](https://youtu.be/nMLjicS-mVw) [5:34] 

- You been asked to generate various baseball statistics for a popular pub, but with a twist.  You will need to use [BaseX](http://basex.org/) to do initial queries of the XML data, and then you will proceed to  code your project using XSL and CSS. Follow the instructions below to complete the project. To start the project, you will need to download this [.jpg file of Mike Piazza](http://www.albany.edu/~mwolfe/ist538/homework/final_project/piazza.jpg) and the [1998 baseball season roster of players](http://www.albany.edu/~mwolfe/ist538/homework/final_project/baseball_names.xml)
- Your completed final project should look [like this.](http://www.albany.edu/~mwolfe/ist538/homework/final_project/final_project.jpg)

**Part 1 XQuery (5 points)**

- Create an XQuery file using BaseX. 
- Find the top three boy [baby names for 1969](http://www.babycenter.com/popularBabyNames.htm?year=1969)
- Using a FLWOR expression, search and retrieve  those names in <span style="font-family:Courier">baseball_names.xml</span> file. You will need to search for their names and nick names, for example, &quot;Robert&quot; &quot;Bob&quot;.
- For help, you will need to refer to our in-class examples and exercise from Unit 11. Here's a hint for the [<span style="font-family:Courier">if statement</span>](http://www.albany.edu/~mwolfe/ist538/homework/final_project/if_statement.jpg)
- Print out each player, including all of his statistics, and ensure the result is enclosed in a root tag, <span style="font-family:Courier">&lt;BASEBALL_NAMES&gt;&lt;/BASEBALL_NAMES&gt;</span>. Save your newly created .xq file to your project folder.
- Save the newly created .xml file created in BaseX, and call it <span style="font-family:Courier">&quot;baseball_names_new.xml&quot; </span>

**Part 2 XSLT (5 points)**

- Create an .xsl file.
- Link up your .xsl file with your newly created .xml file, which should look like this: [&quot;baseball_names_new.xml&quot;](http://www.albany.edu/~mwolfe/ist538/homework/final_project/baseball_names_new.xml).
- Using code hints from [HW5 part 2,](http://www.albany.edu/~mwolfe/ist538/homework/hw5/highest_seller_code.txt) use XSLT find out who had the highest number of RBIs (Runs Batted In) and display it to the screen.
- Display the photo as well, there's only one: [Mike Piazza.](http://www.albany.edu/~mwolfe/ist538/homework/final_project/piazza.jpg)

**Part 3 CSS (5 points)**


- Link your .css file from your .xsl file, per HW5
- Create selectors for <span style="font-family:Courier">img</span> and <span style="font-family:Courier">strong</span>:
- Add rounded corners: [how-to details](http://www.w3schools.com/css/css3_borders.asp)
- Add drop shadow: [how-to details](http://www.w3schools.com/cssref/css3_pr_box-shadow.asp)
- Once completed, you must individually send me one zip file that includes your ( .jpg, .css, .xsl, .xml, and .xq) files and email them to me. 
- The assignment is **Due Friday, July 31st.**

- **This is a group assignment, so you are free to work together on this!**
---
layout: default
title: 
permalink:
---

- [Homework 4 Video Instruction](https://youtu.be/7ZBAgPQj7aQ) [2:00]


<h1> Homework 4</h1>

Navigate to [this directory](http://www.albany.edu/~mwolfe/ist538/homework/hw4/) [and save the file **sales_directory.xml**]  and style it into HTML using XSLT and XPath. Follow the guidelines below to  complete the assignment. Set up your style sheet in a similar manner as the Unit  7 XSLT group exercise. I have linked what the output file should look like here [http://www.albany.edu/~mwolfe/ist538/homework/hw4/sales_directory.html](http://www.albany.edu/~mwolfe/ist538/homework/hw4/sales_directory.html).

Part 1: **Make Tables (5 points)**

- Create 2 tables of data, and output  only <span class="computer">first_name,  last_name, city, region, salary</span>, and <span style="font-family:Courier">sales</span>. Use an <span style="font-family:Courier">xsl:for-each command</span> (p. 28).
- Round <span style="font-family:Courier">sales</span> using the <span style="font-family:Courier">round()</span> function (p.55).
- One table will display data from the  Washington State region and the other table from the Overseas region using the <span style="font-family:Courier">xsl:if</span> command (p. 30).
- Sort the tables from lowest number of  sales to highest using the <span style="font-family:Courier">xsl:sort()</span> function (p.32).
- Use a color of your choice for the tables.

Part 2: **Print out totals (5 points)**

    
- sales  in dollars. Use the <span style="font-family:Courier">format-number</span> command, use <span style="font-family:Courier">'$###,###'</span> to output only dollars with no  cents.  (p. 54)    
- sales  in British Pounds, which can be computed using  total sales <span style="font-family:Courier">* 0.605913718</span> . Use the <span style="font-family:Courier">format-number</span> command, use <span style="font-family:Courier">'&amp;#163;,###,###'</span> to output only pounds  with no cents.  (p. 54)
- number of total employees using the <span style="font-family:Courier">count()</span>function (p. 53)
- number of Overseas employees using <span style="font-family:Courier">count()</span>
- number  of Washington State employees using <span style="font-family:Courier">count() 
 
- Assignment  is worth 10 points. **Due: Wednesday, July 23rd**
- Zip your .XSL  and .XML files and email it to me.
- Be sure they  are in one folder. I should only receive _one .zip file_.
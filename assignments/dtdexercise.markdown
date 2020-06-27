---
layout: default
title: 
permalink:
---

<h1> Unit 3 Exercise</h1>

<span style="font-family:Courier">      </span>

Download this file: [https://www.albany.edu/~mwolfe/ist538/unit3/sales_directory_ex3.xml](https://www.albany.edu/~mwolfe/ist538/unit3/sales_directory_ex3.xml). You need to create a DTD that validates the .xml file you just downloaded following the directions below. Use the Chapter 6 in Goldberg as well as the videos to assist in your exercise.
- Hint for your DTD, first line:<span style="font-family:Courier"> <!ELEMENT directory (employee+, customer+)></span>
- It might help if you first, define all of the elements and the attributes first before checking validation.
- Note, you will be creating a sequence for the child of <span style="font-family:Courier"> directory</span>, and a sequence for the children of <span style="font-family:Courier">employee</span>
- Define <span style="font-family:Courier">customer</span> as a sequence.
- Define <span style="font-family:Courier">order_info</span> as a sequence.
- Define the elements <span style="font-family:Courier">employee</span> and <span style="font-family:Courier">customer</span> as repeatable one or more times, and address inside of <span style="font-family:Courier">employee</span> will need to be repeatable too (p. 81).
- Make the num and <span style="font-family:Courier">pers_num</span> attributes unique using an ID (p. 89).
- Define <span style="font-family:Courier">purch_num</span> attribute using IDREF so that it references the <span style="font-family:Courier">pers_num</span> (p.89)
- In <span style="font-family:Courier">country</span>, you will need to define an attribute called <span style="font-family:Courier">region</span>. Make <span style="font-family:Courier">region</span> a choice betteen the values <span style="font-family:Courier">overseas</span> or <span style="font-family:Courier">domestic.</span>
- All attributes will be set to <span style="font-family:Courier">REQUIRED</span>.

Updates:

- You will need to update the XML file to ensure a unique number is being used for <span style="font-family:Courier">num</span>, and that attribute value for <span style="font-family:Courier">region</span> is the correct choice.
Notes:
Use Notepad++ or XMLSpear (et al.) in combination with the recommended online validators on the course website to help troubleshoot your DTD document and to validate it against the XML file. The online validators require an embedded DTD inside your .xml file.

- Post to discussion board with subject heading "completed".
- The group exercise **Due Monday, June 29th.** 
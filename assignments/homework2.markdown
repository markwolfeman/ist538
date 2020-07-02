---
layout: default
title: 
permalink:
---

<h1> Homework 2</h1>

You  have been hired by _Johnny&rsquo;s Seed Company_ to create a DTD that will help them gain better control over its [catalog  information](http://www.albany.edu/~mwolfe/ist538/homework/hw2/catalog.pdf).  Create a DTD with the following bulleted constraints and functionality. You will validate your DTD against a downloaded version of [tomato.xml](http://www.albany.edu/~mwolfe/ist538/homework/hw2/tomato.xml) (right click-&gt;&quot;save link as&quot;). The DTD must be defined outside of the XML document, though for troubleshooting purposes, you may want to create it internally to use with online validators (p.106).

Define  all of the elements and attributes as found in the xml document, and make these special considerations:

- Define elements <span style="font-family:Courier"> variety, notes, disease, price, </span>as one or more times.
- Define <span style="font-family:Courier">tom_type, name, cycle, description </span>as one time  only. Be sure that you set up your sequence correctly.
- <span style="font-family:Courier">description</span> may feature <span style="font-family:Courier">#PCDATA</span>  or <span style="font-family:Courier">strong</span> (see p. 82 for  Mixed content) to mark up  bolded type. Make <span style="font-family:Courier">#PCDATA</span> and <span style="font-family:Courier">strong</span> a choice; both  may be used none or more times. <em>Update</em> content in tomato.xml with <span style="font-family:Courier">strong</span> elements in <span style="font-family:Courier">description</span> where text is bold. Look at the PDF for bolded text.
- Define <span style="font-family:Courier">breed</span> as either  <span style="font-family:Courier">&quot;heirloom&quot; or &quot;f1&quot;</span> using  choice (p.87), and make it required. 
- Define <span style="font-family:Courier">currency</span> as either  &quot;US&quot; or &quot;Canadian&quot; using  choice, and make it required.
- Make <span style="font-family:Courier">type</span> and <span style="font-family:Courier">code</span> required  attributes.
- Restrict <span style="font-family:Courier">type</span> to NMTOKEN (p.90) and make  it required, and <em>update</em> tomato.xml so it will  validate.
- Restrict the attribute  <span style="font-family:Courier">num</span> to &ldquo;days&rdquo; using <span style="font-family:Courier">#FIXED</span> and <em>update</em> the  values for <span style="font-family:Courier">num</span> in tomato.xml so it will  validate. 
- Ensure that <span style="font-family:Courier">code</span> contains a  unique value using an <span style="font-family:Courier">ID</span> data type, and <em>update</em> values for <span style="font-family:Courier">code</span> in tomato.xml so it will  validate.
- The elements<span style="font-family:Courier"> notes </span>and <span style="font-family:Courier">disease</span> will  have content inserted into them using &ldquo;shortcuts&rdquo; known as  internal general  entities (p. 92). The content for the notes and disease elements are as such:  &quot;JSS Exclusive&quot;, &quot;Green House&quot;, &quot;Pack Sales&quot;, &quot;Alternaria (Early)  Blight&quot;,  &quot;Late  Blight&quot;,  &quot;Fusarium  Wilt (Races 1 and 2)&quot;, &quot;Fusarium Wilt (Races 0,1,&amp; 2)&quot;,  &quot;Tobacco Mosaic Virus&quot;, &quot;Verticillium  Wilt&quot;.
- Update your DTD using a parameter entity. Create an entity for <span style="font-family:Courier">#FIXED</span>, and reference it using the shortcut. You can use the letter &quot;f&quot; for your shortcut.
- Finally, inside of your .xml file the value of <span style="font-family:Courier">tom_type</span>  (the element) will use a short cut to call an external general entity (from the DTD) . That document has been created as <a href="http://www.albany.edu/~mwolfe/ist538/homework/hw2/details.ent">details.ent </a>(right click->"save link as"). You must  reference that in your DTD, (p. 94-95). 
- Note, you should create your external general entity <u>last</u> if you are using an internal DTD for debugging pursoses. The online validators will not be able to call the <a href="http://www.albany.edu/~mwolfe/ist538/homework/hw2/details.ent">details.ent</a> file. 
- You can only validate external entities using Notepad++'s validator or XMLSpear.

- [Homework 2 Instructions ](https://youtu.be/aa37GLCmwdc) [2:55 min.]
- Your assignment must validate.
- It is worth 10 points
- Email me as an attachment the .xml, .dtd, and .ent documents as one compressed .zip file. 
- **Submit by Saturday, July 4th** (Sooner is better, because Unit 5 is on the way)


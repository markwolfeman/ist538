---
layout: default
title: 
permalink:
---

- [Homework 3 Instructions ](https://youtu.be/cvKim-YiMmQ) [7:27 min.]

<h1> Homework 3</h1>

Create an XML Schema that validates: [http://www.albany.edu/~mwolfe/ist538/homework/hw3/hw3.xml](http://www.albany.edu/~mwolfe/ist538/homework/hw3/hw3.xml). 

In your XML Schema file, do the following to set up your <span style="font-family:Courier">hw3.xml</span> file to enforce correct data entry into the XML document. You must update the <span style="font-family:Courier">hw3.xml</span> document in various places so that it conforms to the rules as defined below. Unless noted, set elements to <span style="font-family:Courier">string</span> data.

1. Set your <span style="font-family:Courier">.xsd</span> file up. Start by defining your *root element* <span style="font-family:Courier">directory</span>, and inside it, define the <span style="font-family:Courier">employee</span> element using a *complex type* setup. <span style="font-family:Courier">employee</span> must reference the *named complex type* “employeeType” (p 142-143). Partial code: 

```
	<span style="font-family:Courier"><?xml version="1.0"?>
		<xs:schema xmlns:xs="http://www.w3.org/2001/XMLSchema">
           	<xs:element name="           ">
			<xs:complexType>
				<xs:sequence>
					<xs:element name="      " type="     "/>
				</xs:sequence>
			</xs:complexType>
		</xs:element>
	…
	</xs:schema></span>
```

2.	Create the *named complex type* <span style="font-family:Courier">employeeType</span> to contain a *sequence* of child elements: <span style="font-family:Courier">last_name, first_name, title, title_of_courtesy, birth_date, hire_date, contact_info, photo, notes, reports_to.</span> 
3.	<span style="font-family:Courier">last_name</span> will reference a *named complex type* called <span style="font-family:Courier">“nameType”</span>.
4.	<span style="font-family:Courier">hire_date</span> and <span style="font-family:Courier">birth_date</span> will reference a *named custom simpleType* called <span style="font-family:Courier">dateType</span>.
5.	Create a *named custom simpleType*, and call it <span style="font-family:Courier">dateType</span>, (p. 127).  Set the *base restriction* to the data type, <span style="font-family:Courier">date</span>, and within restriction, set up a *minInclusive date* of "January 1, 1900" and *maxInclusive date* of January 1, 2050. (p.129 and p. 122) 
6.	<span style="font-family:Courier">contact_info</span> will be reference a named complex type called <span style="font-family:Courier">“contactType”</span>
7.	<span style="font-family:Courier">notes</span> will reference <span style="font-family:Courier">“notesType”</span> 
8.	Create a *named complex type* called <span style="font-family:Courier">notesType</span> you will need to set it <span style="font-family:Courier">“true”</span> for *mixed content*. Inside of <span style="font-family:Courier">notesType</span>,  define an element called <span style="font-family:Courier">major</span> and set it to *string data*. Make it so it must appear at least once, using  <span style="font-family:Courier">minOccurs=”1”</span>(p.148)
9.	Create the *named complex type* for <span style="font-family:Courier">nameType</span> that contains *simple content* (p. 139). Set it to *string data*, and create the attribute <span style="font-family:Courier">id</span>, and set its *type* of <span style="font-family:Courier">integer</span> data, and make it <span style="font-family:Courier">required</span> (p. 155).
10.	Create a *named complex type* for <span style="font-family:Courier">contactType</span>, and create a *sequence* of child elements as listed in <span style="font-family:Courier">directory.xml</span>. Create a *choice* between the elements <span style="font-family:Courier">home_phone</span> and <span style="font-family:Courier">extension</span> or <span style="font-family:Courier">cell_phone</span> inside  <span style="font-family:Courier">contactType</span>
11.	Define <span style="font-family:Courier">postal_code</span> so it references a *named simple type* called <span style="font-family:Courier">postalType</span>
12.	Create a *named simple type* for <span style="font-family:Courier">postalType</span> (p.127). Create a *pattern* that restricts the content to *string data* and to five numbers.
13.	Define <span style="font-family:Courier">time_zone</span> so it references a *named simple type* called <span style="font-family:Courier">timezoneType</span>. 
14.	Create a *named simple type* for <span style="font-family:Courier">timezoneType</span> (p.130). Restrict its content to <span style="font-family:Courier">“Pacific, Mountain, Central, or Eastern”</span> using *enumeration*

This assignment is worth 10 points. **Due Friday July 10th**  


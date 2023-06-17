# SajalTest:- FSD Class test Assignment Submission 
# PART A - (Theory) 

Q1. Mention the working of Internet Website in Terms of Front-end & Back-end Divisions.
Soln. 
A website's front end and back end are two separate components collaborating to produce a usable website. The backend is in charge of data storage and organisation whereas the frontend is what users view and interact with HTML, JavaScript, and CSS are used to build the frontend. On the other hand, the backend, also known as the server-side, is made up of the server, which makes data available upon request, the application, which directs it, and the database, which compiles the data. Through middleware, the frontend communicates with the back end, which safeguards the data and answers the front end's inquiries.


Q2. What are tags in HTML? Explain the each category of tag with an Example.
Soln.
HTML tags are used to define the structure and content of a web page. HTML tags are enclosed in angle brackets, and most come in pairs: an opening tag and a closing tag. The opening tag begins the element, and the closing tag ends it. 

There are Different types of Html tags are as follows 
1. Structural Tags: These tags define the structure of the web page. 
Examples are 
<html>: Defines the beginning and end of an HTML document.
<head>: Contains meta information about the document, such as the title and links to stylesheets.
<body>: Contains the content of the web page, such as text, images, and videos.
  
2. Formatting Tags: These tags define the formatting of the content. 
Examples are 
<h1> - <h6>: Defines headings of different sizes.
<p>: Defines a paragraph.
<strong>: Defines strong emphasis.
  
3. Input Tags: These tags define input elements for forms.  
Examples are 
<input type="text">: Defines a text input field.
<input type="checkbox">: Defines a checkbox input field.
  
4. Link Tags: These tags define links to other web pages or resources. 
Examples are 
<a href="https://www.example.com">: Defines a hyperlink to another web page or resource.
<link rel="stylesheet" href="style.css">: Defines a link to an external stylesheet.
  
5. Image Tags: These tags define images to be displayed on the web page. 
Example are 
<img src="image.jpg/png" alt="alternate text">: Defines an image to be displayed on the web page.
  
  
Q3. Explain the working Procedure of Virtual DOM. 
Soln 
The Virtual DOM is a lightweight copy of the actual DOM that is used in ReactJS to improve performance.
1. Whenever there is a change in the state of an element, a new Virtual DOM tree is created.
2. This new Virtual DOM tree is then compared to the previous Virtual DOM tree to identify the changes.
3. Only the changed elements are updated in the actual DOM, which makes the process faster and more efficient.
4. The Virtual DOM is faster than the actual DOM because it is an abstract representation of the UI that updates only the component that needs to be updated.
5. The Virtual DOM is not faster than the actual DOM, but it provides a mechanism that allows the actual DOM to compute minimal DOM operations when re-rendering the UI.
6. The Virtual DOM is used to optimize performance and speed up the process of updating the UI.

  
Q4. Mention some Differences between MySQL and No SQL
Soln. 
Here are Some differences between Mysql and No Sql 
MySQL
1. SQL is used by the relational database management system known as MySQL.
2. MySQL is a table-based database with a tabular design.
3.  MySQL follows ACID properties (Atomicity, Consistency, Isolation, and Durability)
No SQL 
1. NoSQL is a non-relational database management system that does not use SQL.
2.  It has document-based architecture and can be document-based, key-value pairs, graph databases, or wide-column stores.
3. It Does not follow ACID properties.

  
Q5. Explain any one DBMS Technology in your own words.
Soln.
Mongodb Database 
A NoSQL database management system called MongoDB uses JSON-like forms to store data. It utilises a non-relational, document-oriented data format and an unstructured query language and is extremely scalable, versatile, and distributed.  In comparison to conventional relational databases, MongoDB uses the BSON document storage format to store and manage higher volumes of data. The dynamic schema architecture in MongoDB allows it to operate with unstructured data and storage. The database schema need not be predefined,  and it can be changed dynamically without a disruption in service. MongoDB is used for high-volume data storage, enabling businesses to quickly store massive volumes of data.


# PART B - (Practical)
  Project 1  
  Problem Statement: Create an HTML webpage which calculates the BMI of your body. Use JavaScript to validate the calculation
  Project Attached : BMI- calculator 
  
  Project 2 
  Problem Statement: Create the React app which acts as the Record Form and Collects necessary data of Student for Admission Purpose with mentioned below Requirements- ( a. Title of the Web APP must be “Admission Form”. b. It should have a valid CSS file and the form box must be at centre. c. Use CSS box Model to add relevant padding and other styling content.
  
  Project 3 
  Problem Statement:  Create a git repository using Git Bash and push it on to the Git Hub. Paste the Link of it in the  Google Form for Submission.
  

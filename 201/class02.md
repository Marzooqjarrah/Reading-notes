
HTML
When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.
There are 2 types of markup:
-	Structural markup: the elements that you can use to describe both headings and paragraphs 
-	 Semantic markup: which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on.

•	Headings (<h1> to <h6>):
The contents of an element is the largest, and the contents of an element is the smallest. The exact size at which each browser shows the headings can vary slightly.


•	Paragraphs (<p>):
The browser will show each paragraph on a new line with some space between it and any subsequent paragraphs.

•	Bold & Italic:
            By enclosing words in the tags and we can make characters appear bold.
             By enclosing words in the tags and we can make characters appear italic.

•	Superscript & Subscript:
The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power.
The <sub> element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H2 0.

•	White Space:
In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines.


•	Line Breaks & Horizontal Rules:
As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag <br>.
          To create a break between themes — such as a change of topic in a book or a new scene in a play you 
           Can add a horizontal rule between sections using the tag. <hr/>.

-	There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the pages — they are known as semantic markup.

•	Strong & Emphasis:
 The use of the <strong> element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis.
The <em> element indicates emphasis that subtly changes the meaning of a sentence.

•	Author Details:
The <address> element has quite a specific use: to contain contact details for the author of the page.
								
•	Changes to Content:
The <ins> element can be used to show content that has been inserted into a document, while the <del> element can show text that has been deleted from it.
 The <s> element indicates something that is no longer accurate or relevant (but that should not be deleted).



						
CSS:

CSS allows you to create rules that specify how the content of an element should appear.
CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
Using CSS, you could add a border around any of the boxes, specify its width and height, or add a background color.



CSS works by associating rules with HTML elements:

 

-	CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon.

 


•	Using External CSS:

-	The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page.
<link href="css/styles.css" type="text/css" rel="stylesheet" />  
-	href:
 This specifies the path to the CSS file (which is often placed in a folder called css or styles).
-	rel:
-	 This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.
-	
•	Using Internal CSS:
You can also include CSS rules within an HTML page by placing them inside a <style> element of the page.

 
•	CSS selectors:
There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document.
-	The selectors are:
Universal Selector, Type Selector, Class Selector, ID Selector, Child Selector, Descendant Selector.

CSS selectors are case sensitive, so they must match element names and attribute values exactly.


Why use External Style Sheets?
Once the user has downloaded the CSS stylesheet, the rest of the site will load faster. If you want to make a change to how your site appears, you only need to edit the one CSS file and all of your pages will be updated.


JS:

A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.

•	You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.

 


-	A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.
-	A variable is a good name for this concept because the data stored in a variable can change (or vary) each time a script runs.
-	JavaScript distinguishes between numbers, strings, and true or false values known as Booleans:
1.	NUMERIC DATA TYPE The numeric data type handles numbers. (0.75).
2.	STRING DATA TYPE The strings data type consists of letters and other characters. '(H. 1 ' Ivy! 1).
3.	BOOLEAN DATA TYPE Boolean data types can have one of two values: true or false. True.(true).

-	Note: There are many ways to write content into a page, and several places you can place your script.

-	Programmers sometimes use shorthand to create variables.

 





-	Once you have assigned a value to a variable, you can then change what is stored in the variable later in the same script.
-	Once the variable has been created, you do not need to use the var keyword to assign it a new value. You just use the variable name, the equals sign (also known as the assignment operator), and the new value for that attribute
 



•	ARRAYS:
An array is a special type of variable. It doesn't just store one value; it stores a list of values.
Arrays are especially helpful when you do not know how many items a list will contain because, when you create the array, you do not need to specify how many values it will hold.
 

-	Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).
-	To access a value from an array, after the array name you specify the index number for that value inside square brackets.

 

•	EXPRESSIONS:
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions

•	OPERATORS:
Expressions rely on things called operators; they allow programmers to create a single value from one or more values.
-	ASSIGNMENT OPERATORS: Assign a value to a variable color = 'beige';
-	ARITHMETIC OPERATORS Perform basic math area = 3 * 2;
-	STRING OPERATORS Combine two strings greeting= 'Hi 1 + 'Mol ly';
-	COMPARISON OPERATORS Compare two values and return true or fa 1 se buy = 3 > 5;
-	LOGICAL OPERATORS Combine expressions and return true or fa 1 se buy= (5 > 3) && (2 < 4);


-	Scripts often need to behave differently depending upon how the user interacts with the web page and/or the browser window itself.
-	At the most basic level, you can evaluate two variables using a comparison operator to return a t rue or f al se value.

-	In this example, a user is taking a test, and the script tells the user whether they have passed this round of the test:
 


-	In this example, there are two rounds to the test and the code will check if the user has achieved a new high score, beating the previous record:
-	
 

In the comparison operator, the operand on the left calculates the user's total score. The operand on the right adds together the highest scores for each round. The result is then added to the page.




•	IF STATEMENTS:
In this example, the if statement is checking if the value currently held in a variable called score is 50 or more.

 


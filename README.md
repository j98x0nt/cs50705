java c
CSCI 2720/ESTR2106 – Building Web Applications
Assignment One: Bootstrap Web Page with a Web Form
Released: 2nd October 2024
Due: 23:59, 23rd  October 2024
Synopsis:You are going to build a webpage to introduce a company or an organization. There are specific features that need to be included, as outlined in the following problems. Please note that factual accuracy is not necessary for the content. Your webpage should be written English.Problem 2E and Problem 7E are compulsory questions for ESTR students. For CSCI students, you may also attempt these questions. However, we will only give you feedback without any extra scores.
Problem 0: Usability – look and feel (10%)Your submission should be well-decorated and responsive. This includes responsiveness in layout and clarity of text/color presentation. Overall, you should provide a smooth experience to the user.
Problem 1: Basic contents (5%)
These HTML elements must be included in your HTML5 file:
•   Heading
•   List
•   Table
•   Hyperlink
•   Image / Picture
These HTML semantic elements must be used appropriately:
•   
•   
•   

•   
•   
•   
Problem 2: Styling (10%)
Using Bootstrap and/or CSS, apply the following to your page:
1.   At least one column implemented using bootstrap class
2.   Header background image
3.   Section with background color
4.   Horizonal link items in navbar
5.   Customized font and icons (can be in paragraph or in section header)
Problem 2E: CSS Animation (20%)
Apply a CSS animation triggered by the mouse hovering on the logo (or site name) of the navigation bar.When the mouse hovers over your logo (or site name), the logo should look like it is floating up from the page plane (becomes slightly larger and the shadow occurs under it), as the sample image shows below. The animation duration should be one second.

By default, the logo MySite looks flat.

When your mouse hovers over it, the logo pops up with an animation (1 second).
Remark: Only use CSS to implement this problem. Do not use JavaScript.Hint: Consider alter the box-shadow and transform. CSS properties of the logo. The element of logo or site name should have a border radius to achieve the effect in the sample image.
Problem 3: Dynamic contents (35%)
Task 0: Hide/show buttonInclude a button to hide or show an extra bar of buttons for the following task with their features described below. When the bar is hidden, the button should read “Show”. And while the bar is shown, the button should read “Hide” .
Here is an example.
My site section1s po tights comments show

Task 1: AlignThis is the first button in the hidden bar. It should have the text “Task 1: Align” and change align mode of text in columns once the button is clicked. The align mode should change in the sequence:
Left >> Center >> Right >> Left …
Task 2: SpotlightWhen this button is clicked, a dialog box asks the user to enter a spotlight of the company. If the user entered something, the user input should be added to the spotlight area of your page. If nothing is entered, no new item should be created.
Hence, there should be a spotlight area in your webpage. Here is an example:

This area should always appear on user’s screen,i.e., it should stay in a specific position as the user scrolls.
In this task, use prompt () for the dialog box.
Task 3: Bootstrap ToastWhen this button is clicked,a Bootstrap Toast window should occur at the bottom-right corner of  the  page  (See: https://getbootstrap.com/docs/5.2/components/toasts/).  Inside  the  toast window, there should be a text代 写CSCI 2720/ESTR2106 – Building Web Applications Assignment OneJava
代做程序编程语言 displaying the current time (no need to refresh per second). Here is an example.

Hint: You need JavaScript. to get the current time from the operating system and format it into readable text.
Problem 4: Submit comments (15%)
Add the web form. into your webpage to collect the following information from user:
•     Email address
•     Color: Red/Green/Yellow/Blue
•     CommentYou are recommended to use input boxes for the shorter text for the email address, textarea for the comment paragraph, and a group of radio buttons for the color. You may also decide on your own implementation to achieve a similar user experience.There should be an “Add Comment” button that adds the new comment (together with the email address and the selected color) to the bottom of all existing comments. After the new comment appears, the form. should become blank again.It is okay for your page to come with default comments included and a comment data file in any format.
Problem 5: Form. validation (10%)
When the user clicks “Add Comment”, there could be issues, in particular:
•   Incorrect email format
•   Empty comment/ email
Your task is to avoid both above situations. Implementation is flexible.
Hint: https://www.w3schools.com/js/js_validation_api.asp
Problem 6: Loading and saving comments (15%)
You are required to implement the following features:
•    Save new comments whenever a new comment is added
•   Load comments from the saved file when the page loads
These features can be done using JS Fetch with the Simple Web Server, which is introduced in Lab04. Your comment file can be in text or JSON. Both features should be done automatically when the user performs “Add Comment” in Problem 4.
You must use the Simple Web Server as we will grade your submission with it. See:
https://simplewebserver.org


Problem 7E: TypeScript (15%)TypeScript. is a superset of JavaScript, which compiles to readable, standards-based JavaScript. In this problem, you are asked to implement a timer for duration of stay, at the footer of the page. Here is an example.
Specifically, you need to implement a class using TypeScript. which defineshow to update the element content per second and bind the DOM element in the footer to this class when loading the page. Then you need to compile this your TypeScript. file into JavaScript. and import this compiled JavaScript. file in you HTML file.
You should include both your TypeScript source files and the compiled JavaScript files in your submission. Directly implement this problem in JavaScript. won’t get score.




Submission:
We will only visit your web page submission using Google Chrome (almost-latest versions) with Simple Web Server. We will consider all your files in the same local server directory.
Include the code header for honesty declaration with your full name and student ID on top of your HTML file using comments.
Zip all your files and submit it on BlackBoard. You can have unlimited submissions. We will only grade your latest zip file. Name your zip file as:
(SID)_asg1.zip
Your zip file should only include:
1.   One .html file
2.   One .js file
3.   Optional  .css file
4.   Image files or comment data files (you may organize images in subfolder  ./images)For  ESTR  students:  your  submission  should  include  an  extra  folder  (for  problem  7E) containing a TypeScript. source  .ts file, a complier config  tsconfig.json file, and a compiled  .js file  (you may organize them in  subfolders like  ./src or  ./dist). The compiled .js file should also be imported in your  .html file.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

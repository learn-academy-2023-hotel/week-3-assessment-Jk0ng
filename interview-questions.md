# ASSESSMENT 3: Interview Practice Questions

Answer the following questions.

First, without external resources. Challenge yourself to answer from memory as if you were in a job interview.

Then, research the question to expand on your answer. Even if you feel you have answered the question completely, there is always something more to learn. Write your researched answer in your OWN WORDS.

1. What is JSX? What is one syntax difference between HTML and JSX?

Your answer: JSX is javascript markup language that brings HTML and Javascript logic together. It creates the combination of two languages. 

Researched answer: JSX stands for JavaScript XML, which is a markdown language that is used in JavaScript. It is very similar to HTML other than assigning then use of className. Becasue class is already a protected word in JavaScript, instead of using "class", JSX uses "className". 

2. What is yarn? What file(s) are modified when you run the command yarn in your terminal?

Your answer: yarn is a file manager that mangages all the code snippets necessary for yarn test. Yarn is created by FaceBook, and its intention is to mangange all the code template necessary to run yarn test without having to doing the tedious work of organizing them every single time. 

Researched answer: Yarn is a file manager to download and manage all the dependencies that are needed to run Jest. Because Jest is the testing framework which requires many code snippets that are already made but need to be organzied in the right way, a package manager like yarn does the job of installing and managing the dependencies. 

3. What is the difference between state values and props in React?

Your answer: state values are an JSX hook which is a function that allows to store data and modify the state variable. Props have the same proptery as objects and allows for tranporting data from upstream to downstream nested compoments. The difference between those two other than one is a funtion, the other one an array; props passes data from main.js component to nested componet whereas state values are only specific to the component that it belongs to. For example, const [count, setCound] = useState [number:1,name:Bob] is a state function for count and it sets the initial value of 0. Props can reference the data from main compoment to a nested compoment using prop.name 

Researched answer: state values are constantly being updated by the user interactions, but props don't change. State values are modified based on how the setter function is set to modify the state varibale. Props brings the value that the varible holds to different downstream component like passing user input to a compoment called UserInput to display on the browser in real time. 

4. STRETCH: Which is the difference between a div tag and a span tag?

Researched answer: the main difference between a div and a span tag is their scope. A div tag has the scope of the block, whereas span only has the scope of a single line of code. 

## Looking Ahead: Terms for Next Week

1. DOM: DOM stands for document object model. It is essentially what the code will turn out to look like on the page for users. DOM tree is the model of how elements are organzied in a hierachial structure in HTML.  

2. Object-oriented programming:the birth of OOP is to put codes in objects so that changes made to speicifc code won't affect the entire program. Ruby is an object-oriented programming language that enables programmers to create obejcts, so that changes made to obeject won't jepordize the entire program. 

3. Ruby:Ruby is an object-orientend programmming language that created in 1990s. Ruby is known for its simplicity and nature of being easy to read and write. 

#My Amazing file

- bullety 
- bullety
- bulletto

<h2>My Multiple Choice Question</h2>

### !challenge
* type: multiple-choice
* id: blammo-question
* title: Why it be like it do?

### !question
Why do it be like it do?
### !end-question

### !options
* What's this? An Option?
* It do be like it do be sometimes.
* Hmmmmm
* Just the facts Ma'am
### !end-options

### !answer
* It do be like it do be sometimes.
### !end-answer



### !end-challenge

<!----------------------BEGIN CHALLENGE----------------------------->

### !challenge

* type: checkbox
* id: blammo-checkbox
* title: Example Checkbox Challenge

##### !question

Mark all of the boxes if you are happy.

##### !end-question

##### !options

* I am happy.
* Joyfulness noises.
* Me too
* Woot!

##### !end-options

##### !answer

* I am happy.
* Me too
* Joyfulness noises.
* Woot!

##### !end-answer

### !end-challenge

### !challenge

<!--'type' is required-->
<!--'id' is required, string, must be unique within a single markdown file-->
<!--'title' is required, string, used when displaying results-->

* type: short-answer
* id: 1a3cc34f-ea21-4533-bed4-6da3c8c95a4e
* title: Example Short Answer Challenge

<!--'question' is required, markdown, the question to be answered-->

### !question

What will the following code produce?

```javascript
var myArray = ["Elie", "Janey", "Matt", "Parker", "Tim"];
myArray[3]
```

### !end-question

<!--'placeholder' is optional, the placeholder text in the input box. Removed when the user starts typing-->

#### !placeholder

What does myArray[3] equal?

#### !end-placeholder

<!--'answer' is required, the correct answer to the question.
By default, answers evaluated as case-insensitive exact match. If answer wrapped in '/', evaluated as regex. The answer to this question could have been defined as /\A['"]Parker['"]$/ to allow students to enter single or double quotes. Also supports regex ending in '/i' for case-insensitive regex. To test your regex, you can use http://rubular.com/-->

### !answer
"Parker"
### !end-answer

### !end-challenge


# Is it DRY?

## Learning objectives

- Assess what makes a piece of code DRY or not.

### Estimated time: 0.25h

## Description

## Exercise

When a software system starts to scale, you will inevitably find places where you need to do something very similar to something you've done in the past. Most of the time you want to reuse some of your old code for a similar project you may simply copy and paste and find that your code works without making any changes. But in the long term you'll have a lot of problems trying maintain the same code copied to multiple locations. You will easily forget all the places you need to update, which can lead to a higher likelihood of bugs in your code. Even in small applications you should try to DRY your code from the beginning, to keep it clean, beautiful, understandable and maintainable.

In this exercise you will assess a piece of code and you will try to make it DRY.

*IMPORTANT NOTE: Read **all** instructions before you start this exercise.*

### Instructions

- Check the following examples of code:

Example 1:

```javascript
const pets = ['Cat', 'Dog', 'Bird', 'Fish', 'Frog', 'Hamster', 'Pig', 'Horse', 'Lion', 'Dragon'];
// Print all pets
console.log(pets[0]);
console.log(pets[1]);
console.log(pets[2]);
console.log(pets[3]);
...
```

```css
.cat {
  font-family: "Times New Roman", Times, serif;
  font-size: 1rem;
  color: #FFF;

}
.dog {
  font-family: "Times New Roman", Times, serif;
  font-size: 1rem;
  color: #000;
}
.dragon {
  font-family: "Times New Roman", Times, serif;
  font-size: 1rem;
  color: #009933;
}
```

Example 2:

```javascript
const greet = (message, name) => {
  console.log(`${message}, ${name}!`)
}

greet('Hello', 'John');
greet('Hola', 'Antonio');
greet('Ciao', 'Luigi')
```

```css
.greetings {
  font-family: Arial, sans-serif;
  font-size: 1.5rem;
}

.greetings.english {
  background-color: #000;
  color: #FFF;
}
.greetings.spanish {
  background-color: #FFF;
  color: #000;
}
```

- Create a [gist](https://gist.github.com/) on GitHub.
- Copy code from the "Example 1".
- Answer the question: "Is it DRY?"
  - If it is not DRY, show how you can make it DRY by adding your version of the code.
  - If it is DRY, explain why it is DRY.
- Repeat the process with example 2.
- Create just one gist with two files for the two examples.

### Submit your exercise
[Read this FAQ for a reminder on how to submit your exercise.](https://microverse.zendesk.com/hc/en-us/articles/360061344234)
Now go to your Student Dashboard and submit your exercise.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/git-github/articles/open_issue.md)._
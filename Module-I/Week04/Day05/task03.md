# Debugging and developer tools

## Learning objectives

- Use developer tools to print information to the console.
- Identify how developer tools are used in debugging front-end code.
- Understand the importance of thoughtful, intentional problem-solving.

### Estimated time: 0.5h

## Description

*Debugging* is the process of finding and fixing code errors (also known as *bugs*). *Quality Assurance* (or QA) is a complex discipline that monitors the whole software development process. Debugging is just a small part of QA.

### Why is debugging important?

"*No one in the brief history of computing has ever written a piece of perfect software. It's unlikely that you'll be the first.*" (Andrew Hunt, The Pragmatic Programmer). We should add that no one has written a piece of perfect software *alone* - writing software is a collective and continuous effort.  OK, you can't write perfect code but you can find your errors early, and fix them before they arrive at the final user. And a good way to *debug* your code is by working collaboratively.

### JavaScript debugging

- Read this introduction to [JavaScript debugging](https://www.w3schools.com/js/js_debugging.asp) to learn the JavaScript debugging basics.
- Read the article [Debugging Javascript like a pro](https://blog.bitsrc.io/debugging-javascript-like-a-pro-a2e0f6c53c2e) to learn additional JavaScript debugging techniques. This article is focused on Chrome, but the same techniques can be applied to any browser's developer tools.

A useful yet rudimentary way to debug a web application is by using **console.log()**. It is available in all browsers and you don't need to install anything.

- Look at these [console.log() exercises](https://www.w3schools.com/jsref/met_console_log.asp) from W3Schools, and complete all of their *Try it Yourself* exercises.

### Browser's developer tools

A more robust way to test your applications is with your browser's *developer tools*. Browser tools are included in all modern browsers, with small differences between browsers. With developer tools you can not only print to the console but also stop the execution of the program, change values live, resume your application, etc. Learn more about the most popular browser developer tools available (Hint: for now just look at the browser developer tools for your favorite browser and get familiar with them - do not look at the browser tools for the other browsers.):

- [Firefox Developer Tools](https://developer.mozilla.org/en-US/docs/Tools).
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/).
- [Edge DevTools](https://docs.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/).
- [Safari Web Development Tools](https://developer.apple.com/safari/tools/).
- [Opera DevTools](https://dev.opera.com/extensions/testing/).

Hint: Developer tools are a very broad topic, and mastering them may require some time. You could start with the most useful and common features like:

- The console panel.
- The elements (or inspector) panel.
- The sources (or debugger) panel.

## Additional materials

**These are all optional, but if you're interested in exploring this topic further, here are some resources to help you. Any exploration here should be done outside program time.**

The most common method of the accessing the browser's debugging console is **console.log()**, but it's not the only one. Take a look at the full [**console object**](https://developer.mozilla.org/en-US/docs/Web/API/Console).

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change](https://github.com/microverseinc/curriculum-transversal-skills/blob/main/git-github/articles/open_issue.md)._
# Website Accessibility Tester

### Web app to find website accessibility issues using [Pa11y](https://github.com/pa11y/pa11y)

I was going through the ideas and resources for different projects that I could create. And I ran across this tool called Pa11y, which is an accessibility tester. Basically, you can pass in and URL to a website and it will return the results to an array of issues that have to do with accessibility. Things like: 1) you forgot to put an alt tag on an image or 2) you forgot the for attribute on a label. It returns any errors/issues that have to deal with accessibility.

I am using Pa11y along with Node.js to create a simple back-end API that you can hit to get the results for any website we want. And then create the front-end to display those results. I’m using HTML, CSS, and vanilla JavaScript along with Bootstrap for UI components.

You can enter a website, click Submit, see a little spinner while it checks, and then get a list of all the accessibility issues. For example, you can read an issue 
>*“Img element missing an alt attribute”,*

but you can also see the context or the HTML where that error is, and you have a specific code for each issue as well. 

You may also get a message
>*“This element has insufficient contrast at this conformance level”*. 

It even looks at the color contrast for the visually impaired people.

I am building this using Node.js, along with Pa11y which is the work horse for this application. I’m creating the front-end, using JavaScript to make the request using the Fetch API, get the data back, show it in the DOM. I have a little loading spinner for when it’s checking.

You can use React, Vue or any other framework of your choice but I want everybody to be able to do this regardless of the framework.

___

### Usage
Install dependencies

`npm install`

Run

`npm start`

___

The project is based off this [video](https://youtu.be/MO4vEAu3hKE) by Traversy Media.

# Getting Started with Web Development

## General Terminology

#### Common Phrases

Acroym | Full Name | Description | Difficulty
--- | --- | --- | ---
HTTP | Hyper Text Transfer Protocol | The protocol that is used to transfer data between the client (Browser) and server | Beginner
HTML | Hyper Text Markup Language | The markup language that is used to describe objects within a webpage that will be rendered by the client (Browser) | Beginner
CSS | Cascading Style Sheets | The descriptive language that is used to define styles for the HTML objects | Beginner
JS | Javascript | The programming language that is used to define interactive behaviour within a web page | Beginner
SASS | Syntactically Awesome Stylesheet | Sass is an extension to CSS and a CSS pre-processor. Sass is completely compatible with all versions of CSS and is used to reduce repition and save developer time through the use of variables and other programming practices. | Intermediate
SCSS | Superset of CSS | Sass is the file extension for SASS CSS files. | Intermediate
PHP | Hypertext Preprocessor | Programming language used to serve dynamic content on the web | Intermediate
MVC | Model View Controller | A programming paradigm that is used to describe separation of a web page's model (data structure) from the view (the HTML / CSS / JS representation of the data structure) and the controller which handles the HTTP request for the resource and orchestrates the response to the client. | Intermediate
SPA | Single Page Application | A term that is used to describe having one html web page that dynamically loads and unloads content on the same page to reduce the amount of calls required to the server and to enhance user experience. Some modern examples of such technologies would be Vue.js / React.js / Angular. | Expert

#### Server
A Computer or Device with network capabilities that listens to network requests on a specific port (The internet uses port 80 by default for HTTP). 
![HTTP Request](https://i.imgur.com/S1aOxHs.png "HTTP Request")

#### Front End
This generally refers to what the browser will actually render once the HTML / CSS and JS code has been downloaded from the server (Back End).

#### Back End
As mentioned above, this refers to the server that will be serving the static files and doing any extra processing such as authentication and talking to any 3rd party applications (this can also be done from the front end but is not uncommon for the backend to do also).

#### Middleware
This usually refers to any processes that occur with every request to the back end or the server, such as authorization and logging.

---

## Basics

### Front End

To play around with front end practices, I tend to use JSFiddle. You can find a fiddle [here](https://jsfiddle.net/iDanScott/L74j2qok/6/) that you can fork and play around with.

- HTML (Hyper Text Markup Language)
  - A good basic understanding of HTML Elements 
    - Div `<div>`
    - Span `<span>`
    - Anchor (Link) `<a>`
    - General List `<ul>`
    - Ordered List `<ol>`
    - List Item `<li>`
    - Inputs
      - Textarea
      - Select
      - Button
- CSS (Cascading Style Sheets)
  - Class Selectors `.class-name`
  - Element ID Selectors `#elementId`
  - Basic CSS properties 
    - position
    - display
    - colours
    - overflow
- JS (Javascript)
  - Variables
    - `boolean`
    - `number`
    - `string`
  - Variable scope
    - global scope
    - local scope
  - Event Listeners
    - `click`
    - `change`
  - Functions
  - Loops
    - `for` 
    - `while`
    - `do`
  - Conditional Statements
    - `if`
    - code branching
      - if a condition is met i.e. `1 == 1` then the code block following is executed 

#### Popular Frameworks 
- Bootstrap (CSS / JS) *Made by Twitter*
- Bulma (CSS)
- Material (CSS) *Made by Google*
- Vue (SPA / JS) 
- React (SPA / JS) *Made by Facebook*
- Angular (SPA / JS) *Made by Google*

### Backend
#### PHP
To get a basic server up and running that is used in production environments you can look up how to get started with [LAMPP (Linux)](https://askubuntu.com/questions/863131/installing-lampp) or [XAMPP (Windows)](https://www.apachefriends.org/index.html) which will give you an apache server (this is used in many production environments to serve web pages) which is also typically used to host PHP websites. However, the fact that it can host php websites is not important if you just want to be able to host some html pages.

#### JS
Alternatively, you can look at getting setup with a [nodejs](https://nodejs.org/en/) environment with a basic [expressjs](https://expressjs.com/) application. Nodejs is a runtime that as you may have guessed, uses javascript on the backend. This can have a lot of really great advantages in that if you are profficient with front end development with html / css / js, you can apply your js knowledge in the backend as well as the front end. 

#### C#
Lastly, another alternative that is on the rise is [.net core](https://dotnet.microsoft.com/download) which can be hosted on both linux and windows. There are a few different project types that can be spun up using .net core including MVC and just a basic website that will serve public files such as HTML / CSS / JS content.

#### Summary
Out of all of the above backend services, I would opt to use Nodejs as it's quick to get started and doesn't require much outside knowledge or tooling to get started with.

#### Popular Frameworks 
- [.NET Core](https://dotnet.microsoft.com/download) (C#)
- [.NET Framework](https://dotnet.microsoft.com/download) (C# - Considered Legacy)
- [Laravel](https://laravel.com/) (PHP)
- [Node.js](https://nodejs.org/en/) (JS)
- [Deno](https://deno.land/) (JS)
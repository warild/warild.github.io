# Learning React - a journey

At start I thoutht it would be straight easy. Just buy a book and read along. But no.
React is new and books are getting older by the hour. You wouldnt get the newest features and advices from a book.
So that to do? - Search it up on the net.

And then the journey started

### What is react?
It is something very different from what I thought at start. Here are keypoints from my travel into learning React.

### React is not alone !
Other names continued to pop-up as I was trying to find out what React really was. 
Names like Node, WebPack, Flux, Redux, MaterialUI etc. 
How much noise...

The case is, React is only a part of a system. We need them other parts as well. 

### Searching for a starting point
React is part of a system. What kind of system are we talking of? How is the system made up and how are the parts related? 

### The Single Page Application - SPA
I ended up here, with Single Page Application as the real starting point. 

A Single Page Application is an application running in a single web-page. The page is dynamic and interactive 
and JavaScript is used to make things happen there. With javaScript the layout is changed, data is fetched and 
the user is navitated to new layouts whithin the same web-page.

Traditionally we have a client-server paradigm where the task of the client is to display the pages created and
sent by the server. Not so in this case.

With SPA we need to rethink this consept. Now the client holds the logic and it is the client that makes contact 
with servers and repos - and, yes, there can be more than one server and repo.

The SPA relates so heavily on JavaScript that almost everything is JavaScript based. Serverside-rendering? JavaScript.
Css? JavaScript. Presenting a new page? JavaScript. And tools? coded in JacaScript. Why all JavaScript? 

With javascript an additional layer is put above the traditional code. This extra layer gives flexibility and 
possibilities and simplifies coding. You can do well without React and its friends, but you will do better with them.

Should you know javaScript in advance? yes - certainly. It will help to see the bigger picture when working in details, 
and it will help understanding why things are done in certain ways. 

There is one issue that might have come to your mind. What with links to pages? What if you want to let others reference 
certain places in your app? React takes care of this. To others your one time downloaded, single page app will 
stand forth as a traditional webapplication.

### Developing a Single Page Application
JavaScript is typeless and a script-language, making it easy to create unstrutured code - which we do not want -
espesially as our application grows. Operations on the DOM are not that self-explaining, causing errors and debugging 
in JavaScript can be hard without support. 

Therefore lots of tools are developed.

### SPA with React - The simplest application
The simplest page is a page that loads the React library, defines a React component and then exposes th component. 
I will support an example page later.
This is the start of development with React. 

But others have been down that same road, broaden it. And they share their works. Both tools and code are there 
for you to reuse. Now there are highways increasing the speed of development. 

### On down the road
What we need first of all is a webserver to run our tests and develop against. Then we would like to have tools 
and access to libraries with ready_made code. And - of cause we need the environment where to develop.

### Node.js - our webserver
Node.js is a lightweight and efficient piece of code, serving our development needs. It runs our JavaScript code and 
shows the result in a browser. That is probably all we need to know by now, but one could notice that the effiency 
stems from the fact it runs in a single thread - and is non-blocking. This behavior is achieved by actively 
dispatching tasks - and having the tasks use callbacks when finished. The callbacks are collected in a queue and are 
then treated in order. You may also use Node to run your JavaScript-file. Just type: $ Node your_javascriptfile.js.

### Node Package manager (NPM) - access to a repository with tons of ready made code
Code are shared - some half a million pices of code are shared. NPM takes your list of dependencies, which is written 
in the package.json-file, downloads those files and store them in the 'node_modules' folder. 
Then your code can import from this local library of javaScript-files.

What the packages.jason-file looks like? Mainly a list of dependencies with version number - in the format of a JavaScript
key-value list. 

Now we have the server and the tool to download code. 

### Atom - development environment
Many tools for developing frontend code exists. Atom is one. It is made for frontend development, its free, 
good and very popular. 

Atom is a good starting point for frontend developing with React.

### Development and debugging - Chrome with plugins
Atom might be good for writing the code, but to visualise the code we need a browser. And in the browser dreams get 
distinguished from reality. Or more precisely spoken - it is in the browser we see errors. Chrome has plugins that is
nice to use for this task.

### Webpack - packing all codepieces together into one SPA
Only imported code will end up in the final application. How? Webpack is on the job putting it all together in one single 
final file: bundle.js.

--- And this ends the first read through ---

Next step will be to <a href="https://warild.github.io/P2_setup.html"> set up an environment </a>


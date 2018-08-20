# notmarkdown

The multi-flavored markup language that isn't Markdown.

## What is it?

notmarkdown is self-explanatory in its name: it isn't Markdown.

But, besides that, what's so special about it?
notmarkdown isn't just a markup language, it is a *flavored* markup language. That means that you can choose from a ton of different syntaxes, and all get the job done while supplying a little something extra.

- want clear, defined statements? Try the CAPS library.

- want simplicity in its finest? Try the easy library.

- want syntax so defining it's like a breath of crisp air? Try the minty library.

Besides these, there are many more possibilities, and you'll have to explore and test to find what's best.

## Usage

It's easy to include any notmarkdown library in your project. Simple include the following script tag with your choice of url at *the bottom* of the document *before* your scripts.

``<script src="url"></script>``

And, here are links to all of our different libraries:

- https://cdn.rawgit.com/ntrupin/notmarkdown/d16dea5f/flavors/minty/mintynmd.js

- https://cdn.rawgit.com/ntrupin/notmarkdown/d16dea5f/flavors/easy/easynmd.js

- https://cdn.rawgit.com/ntrupin/notmarkdown/d16dea5f/flavors/CAPS/capsnmd.js

## Contribute

Thanks to GitHub, making a contribution is easy, and we love all the help that we can get. notmarkdown is a fun, quirky project; perfect for beginners or experts who want to have a good time helping to write code. Read on to see how to contribute.

### Familiarize

Before you start writing, it is best to familiarize yourself with the format and code style of the current libraries. Having libraries that are uniform helps developers that come along later, and are just nearer in general. 

The current flavors can be found in the "flavors" directory of the GitHub repository. The base libraries all use .replace and RegExp methods to procedurally parse text, and, though this is the recommended way, you are free to do whatever you want! Just make it as best (and as fun) as you can.

You'll notice that all the libraries have names styled the same way: {name}nmd.js. The name is the title your library will go by in the repo and in the documentation. The "nmd" indicates that it isn't Markdown. The .js is because the libraries are primarily JavaScript files, and that is their file extension. Though the developers at notmarkdown write it in JavaScript (for the web), you can write it in any language you wish. Building a fancy CLI or text editor in Python? Whip up a Python module! Writing a game in Unity and want to add rich text features that aren't Markdown? Feel free to create a C# module.

### Write

You may write you code anywhere you choose, and, though contrary to our recommendation, any way you choose. This is open source, not a dictatorship. We ask that you review the guidelines before you begin. 

When writing your code, you may develop in any language you wish; languages that don't have a module are encouraged the write for.

While writing your code, make sure that you detail each aspect through comments. When you submit a request to merge your files, the repository admins will use these. Besides the formality, it also will help future developers know what is going on!

If you have any problem during your time coding a library, don't be afraid to drop an issue on the repository! It isn't a sign of weakness, but a sign of willing to contribute. Who knows? Your issue may teach someone something!

#### Guidelines

- Code must only edit text, and not interact with the outside page.

- Code must be clearly described via commits.

- Code must be encased in a function titled "parse()".

- parse() May not be called from within the library, it is exclusively for the developer working with the module to call.

- Project may be an npm or cdnjs module. If they are, you **must** provide a link back to the repository. You wrote the module, so you don't need to provide credit to us in the code.

### Submitting 

To submit your code, you must first create a pull request from the repository. This is a you-(and anyone else you let contribute)-independent branch where you can make any changes you want, without it affecting the overall project. 

Once you open the pull, place your code inside a folder inside the flavors directory. ***DO NOT*** change any other files. We will wholeheartedly restrict you from contributing again.

While making your changes, make sure you comment in your code, and that you commit graciously. Your commits will be reviewed by notmarkdown admins when you request to merge your branch with master. If your commit messages are not detailed, your merge will be terminated, though you will be invited to try again.

For your convenience we have including a review cheat sheet to let you know what you should expect when your changes are approved.

#### Review Cheatsheet

- Your code must be commented well enough to be understood be even the newest developer. 

- Your commits must be rich with information of your changes. 

- You must not have modified any code except your own.

- Your library name must be unique.
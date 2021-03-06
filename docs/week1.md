##Getting started with Github

* We're going to be using github in this class. Git is source code management software that allows for [version control](http://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) and we'll be using Github which is one of many code management sites around. In class we will run through how to use github from the command line. But it's also fine to use their desktop client.
* See this tutorial on [getting started with git.](git.md)

To do:

* Fork the class repository to your github site.
* On your computer (or usb), setup the directory you will use for this class.
* In it, clone the class repository '''git clone your-git-url/Drawing-Seeing-Moving-with-Code```
* Add a folder labelled firstnamelastname (all lowercase, no spaces) to the students/ directory in your repository
* Commit the changes back to your online repository.
* Make a pull request to the main class repository.
* Well done! You have done your first pull request!


##Set up p5js
  * Download [latest version of p5js here](http://p5js.org/download/)
  * Download [p5js editor here](http://p5js.org/download/)
  * Setup with a text editor, I recommend [the atom text editor](https://atom.io/) but you can use any that you like. There are some details of the set up here [http://p5js.org/get-started/](http://p5js.org/get-started/) under the environment section.
  * Overview file structure
  * Your first p5 sketch
  * Starting a local server - [see a detailed description and tutorial here.](https://github.com/lmccart/itp-creative-js/wiki/SimpleHTTPServer)

*On a mac:*

  * Open a terminal window (in Applications/Utilities/ and cd to your sketch directory
  * ```python -m SimpleHTTPServer 8000```
  *  In your browser then go to localhost:8000 and this will serve whatever is index.html

*On a pc:*

* Windows doesn't have a built in command line but never fear you can install one for free. [Follow the instructions here (you should already have git bash.)](https://github.com/lmccart/itp-creative-js/wiki/SimpleHTTPServer)
* To start the server. Open up the command line and do the above.
* It is also possible (and gives faster results) to start a server with node. [Instructions are here.](https://github.com/processing/p5.js/wiki/Local-server)

##Introduction to p5js
* Yes it's [Javascript](https://www.instagram.com/p/BA0-Vxvmj5f/)
* Transitioning from Processing: [https://github.com/processing/p5.js/wiki/Processing-transition](https://github.com/processing/p5.js/wiki/Processing-transition)

##Code Examples
* Example 1-1: [No output, check the console](http://codepen.io/tega/pen/mVXZbK?editors=0010)
* Example 1-2: [Mouse moved vs. mouse Dragged](http://codepen.io/tega/pen/zrRVxo?editors=0010)
* Review many more [basic examples here](https://github.com/tegacodes/Drawing-Seeing-Moving-with-Code/blob/gh-pages/docs/basicExamples.md) as prepared by Evelyn Eastmond.

###Javascript objects
* [Javascript literal objects 1](https://www.youtube.com/watch?v=-e5h4IGKZRY&index=7&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
* [Javascript literal objects with functions](https://www.youtube.com/watch?v=QoFWCPVpWUE&index=19&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
* [Javascript Objects with a constructor](https://www.youtube.com/watch?v=F3GeM_KrGjI&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=23)

##Deliverables##
* Review all course documents: [syllabus,](https://github.com/tegacodes/Drawing-Seeing-Moving-with-Code/blob/gh-pages/README.md) [course policies,](https://github.com/tegacodes/Drawing-Seeing-Moving-with-Code/blob/gh-pages/README.md) [assignments,](https://github.com/tegacodes/Drawing-Seeing-Moving-with-Code/blob/gh-pages/README.md) submitting work.
* Get a small notebook for drawing in this class.
* Do the [getting started with git.](git.md) tutorial and do any parts missed in class.
* Do this  Git interactive tutorial. It basically runs you through using Git on the command line and with Github.
* Fork this repo to your git account (as outlined in the git tutorial), and issue a pull request to update your student page - there should be a list of [everyone's folders here](https://github.com/tegacodes/Drawing-Seeing-Moving-with-Code/tree/gh-pages/students) when this is done.
* Download your text editor and get p5js setup. Use the [empty example in the code folder](ttps://github.com/tegacodes/Drawing-Seeing-Moving-with-Code/tree/gh-pages/code/empty-example/) to try your first example.
* Write your first [discovery and research report](https://github.com/tegacodes/Drawing-Seeing-Moving-with-Code/blob/gh-pages/docs/deliverables.md) on a creative programming tool or environment that is used by artists to make experimental technology based work. Explain what the tool is, who created it and what it does, try to include an example of a project (linked) that has been made with it. Issue a pull request to have this post included. If you are stuck for ideas on creative coding tools see the list at the end of [the resources page.](https://github.com/tegacodes/Drawing-Seeing-Moving-with-Code/blob/gh-pages/docs/techResources.md)
* Do [this reading by Zach Lieberman](https://medium.com/@zachlieberman/lessons-for-students-cf1acf200ee#.e3lx0esrf)
*Code exercises:*
* Create an interactive sketch that transforms from chaos to order as the mouse moves across the screen from left to right.
* Using two arrays, create a sketch with 100 flying objects. Make them change when I click the mouse.
* Port one of your old Processing sketches to p5js.
* Start thinking [about ideas for Project 1, come to class next week with some sketches](https://github.com/tegacodes/Drawing-Seeing-Moving-with-Code/blob/gh-pages/docs/project1.md)

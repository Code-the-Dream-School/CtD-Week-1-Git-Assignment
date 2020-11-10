# Week 1 Assignment

Welcome. Assuming you are reading this you are on the right track and on your way to your first successful assignment. To complete it, please meet the following requirements.

Create issues on the link below on the parent repo if you are stuck and want to talk about it. You can paste code, tag people and refer to other issues there. Please use it! It will be helpful for mentors and future students to see where common problems are. Link here: https://github.com/Code-the-Dream-School/CtD-Week-1-Git-Assignment/issues

## Assignment
1. Once you have cloned the repo from the command line (e.g. Git Bash), now you can open up the Assignment1 folder in your text editor (e.g. VS Code or Atom). To open the folder, click on File, Open, and navigate to where your Assignment is stored (you can use Search if you aren’t sure.) 
2. Once you open Assignment1 in your text editor, you should see several files in the sidebar, including index.html. 
3. Open up index.html. Don’t worry about all the text in there; you will soon learn what it all means. For now,  just look for where you see  &lt;body> (around line 12)
4. Underneath &lt;body>, insert a new line.
5. Add a page title with an H1 tag inside of the body of the index.html page. You can use something like this but change what is inside of the tags -
6. &lt;h1>This is my page. &lt;/h1>
7. Underneath that. Create a paragraph/p tag and write a message saying what you are most excited about learning at Code the Dream. Like this -
8. &lt;p>Write something here.&lt;/p>
9. So, when finished, it will look like this: 

```<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>title</title>
  <meta name="author" content="name">
  <meta name="description" content="description here">
  <meta name="keywords" content="keywords,here">
  <link rel="stylesheet" href="styles.css" type="text/css">
  </head>
  <body>
	<h1>This is my page. </h1>
	<p>I’m so excited to be in the class so I can learn…...</p>
  <div id="target-div"></div>
  <script src="index.js" type="text/javascript"></script>
  </body>
</html>
```


10. You just wrote your first batch of HTML! Kudos!
11. Don’t forget to SAVE YOUR WORK!
12. Now, head back to the terminal (e.g. Git Bash) / your command line. Add all of your changes to Git that you made from your terminal based on what you learned in the 'intro to git' class.
13. Commit your changes and write a commit message explaining what changes you made.
14. Push your changes back to your remote branch so that we can see them.


## Additonal Instructions on how to clone/download a repo and get started (ie what you need to do to get up and running). 

Once your repository has been created in github. You will click on the Clone or download button, and then on the clipboard icon to copy the url to the clipboard.

Here is a link to a youtube video walkthrough as well. 

https://www.youtube.com/watch?v=N_AnCnaD44E&feature=youtu.be

Then open a terminal window (or Git Bash window if on Windows). Do:

cd ~

mkdir lessons

cd lessons (this is a folder where you will be keeping all of your code you write for the class)

git clone https://github.com/Code-the-Dream-School/web-basics-1-week-1-YOUR-GIT-USER-NAME.git (you can also just paste the link in here if you clicked on teh green button from your forked github repository)

cd web-basics-1-week-1-johnsmith.git (but replace johnsmit with your git user name, you also should be able to hit tab if you begin typing the begininning of your repository name and it will autocomplete the rest

At this point the repository has been downloaded on your computer in your lessons folder. You should now be able to open the repository by navigating to it inside of your favorite code editor and opening it. Or by navigating to it in your explorer/finder and opening your code editor. 

git checkout -b lesson1

This will create a git branch for your repository called lesson1. Back on github, you will see displayed the instructions for this lesson, which involves editing an HTML file. Make the HTML changes required using your editor and save the file. Try the changes out by opening the HTML file in your web browser. Then close the file in your editor. Do the following:

git status
git add -A
git status
git commit -m "Updated html file"
git status
git checkout master
git merge lesson1
git push
The git push will require that you enter your github ID and password. It will push your revised code back to github. Additional information on git commands is available in a Treehouse class that is part of the first week’s lesson.


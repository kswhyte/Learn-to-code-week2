# Learn-to-code-week2
Last week we signed up for GitHub and the atom text editor!
This week we'll be working with the same code we cloned last week and editing the HTML & CSS.

By the end of today you will have:

1. Forked Cloned another project on github
2. Edited some HTML and CSS
3. Commited and pushed your changes to github!


##Lets fork and clone this repo!
Make sure you're signed in! You're going to want to go to the top of this repository and click the "fork" button. This will create a copy of this repository in your github account!

Next you're going to clone your forked copy of this repository to your local machine!

####Mac
On Github:
- Copy the "SSH clone URL"
In your terminal window:
- Cd into the directory where you cloned your Learn-to-code-week1 repository last week.
- In that directory (but not inside the Learn-to-code-week1 directory) type ```git clone PASTE SSH URL HER```
- Go to atom:
    click file > Add Project Folder >
    then select the Learn-to-code-week2 folder
    atom should open with this repo/project!
- In the left sidebar select the README.md file and continue to the next step!

####Windows
In your github app you installed last week:
- Click "Clone"
- Select Learn-to-code-week2qw


###Lets take a look at some HTML!
Here is the basic structure of an HTML file:

```
<!DOCTYPE html>
<html>
<head>
<title>Lets Build a one page site!</title>
<link href="CSS/style.css" rel="stylesheet" type="text/css">
</head>
<body>
  <div>
    The HTML <div> element (or HTML Document Division Element) is the generic container for flow content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element (such as <article> or <nav>) is appropriate.
  </div>
  <div>
        <ul>
  </div>
</body>


</html>

```

The ```<link>``` tag is referencing the CSS stylesheet that the page is using.

The ```<div>``` tag is a generic container used to apply styles and format to multiple elements!

The  ```<body>``` tag will contain the meat of the page make sure to keep all of the main parts of your code within these body tags!


###How do we check our changes?
If we're making changes to the code on our local machine, how can we check to see if our changes had any affect on our code?

We'll need to open our HTML file in a browser so we can see what it's going to look like!

####Mac users
- Right click on the index.html file and click "show in finder"
- In the finder, right click again and click "open with chrome" (or whatever browser you have)
Tada!!

####Windows users
- Find the index.html file in your directory
- Right click again and click "open with chrome" (or whatever browser you have)
Tada!!



###Fix the link to currently referenced stylesheet
Our website looks lame and boring and Graham is dumb. How do we make it look better?

Can you tell why our inde.html file isn't getting any of the styles in the stylesheet?



###Change the Font to something from Google Fonts
Navigate to google fonts: https://www.google.com/fonts

1. Find a font you like and click "add to collection".

2. On the bottom right side of your screen click "use".

3. On the use page, scroll down to number three and copy the link tag provided.

4. Paste that link tag in your ```index.html``` file with the new link tag
you copied from google fonts. (BONUS: Where should you paste this?)

5. Copy the code under number four.

6. Paste that code into your stylesheet! (BONUS: Where should you paste this?)


###Change the font-size of your h1 tags
First lets change the font size for all the h1 tags on the bottom of your page.

- Look for the h1 tags in the index.html file
- In your Stylesheet look for the place where styles are applied to the h1 tags, it should look like this:

```
h1 {
	font-size: 36px;
	letter-spacing: -1px;
	line-height: 100%;
}
```

Change the font-size to whatever you want.

###Save, Commit and push your changes
Now that we have changed our awesome website it's time to update our github account. It may seem like we haven't changed much but the rule with git is "Commit early commit often"

Lets get started!

####Mac
In the terminal
- Type ```git status``` (This should show all the files you've changed)
- Type ```git add index.html```
- Type ```git add style.css```
- Type ```git status```(You should see the two files you added in green)
- Type ```git commit -m"some commit message"```
- Type ```git push origin master ```

Go to the repo you cloned at the beginning of this class and you should see you changes!

####Windows

?

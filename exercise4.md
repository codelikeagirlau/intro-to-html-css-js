# Exercise 4

So far, we've been working with our website on our local machines, and we're the only ones who can see the pages we're building. If you want to put your website online, you can host it free with GitHub pages.

> GitHub Pages is a static site hosting service designed to host your personal, organization, or project pages directly from a GitHub repository.

In this extra-credit exercise, you'll push your files up to GitHub and publish your website online using Git (a tool most developers use for managing their files).

Read more about **GitHub Pages** here:
https://help.github.com/categories/github-pages-basics/

## Steps

1.  If you don't have a github account yet, start by creating one, then log in.

2.  Let's create a new repository on github, where we will be storing our local files:
    https://github.com/new

3.  Nagivate to your repository and click the green `Clone or download` button, and copy the **HTTPS** link.

4.  Open your terminal on your computer
    * On a Mac, that's `Applications > Utilities > Terminal`
    * On a PC https://www.digitalcitizen.life/7-ways-launch-command-prompt-windows-7-windows-8
    * In your terminal, navigate to where you'd like to store the files for the website on your harddrive
    * To learn some basic instructions like navigating around your computer's directory, read https://www.codecademy.com/articles/command-line-commands
    * A good example might be `~/Projects/My-First-Website`

When you first open your terminal, use 'ls' to list all the files in the directory you're in.
Use 'cd' followed by the file/folder name you'd like to change or go into, to change folders
You can use 'mkdir my-new-folder-name' to create a new folder.

5.  Use 'git clone [your HTTPS repository link]' in the terminal, to copy your repository to your local harddrive.

6.  Once cloned, move your files to the repository folder on your local harddrive.
    _Ask an instructor if you want to discuss this step_

7.  Stage the file for commit to your local repository by running 'git add .' in your terminal. ( the '.' means you're adding all files in the folder!)

8.  Commit the file that you've staged in your local repository by running 'git commit -m "Add existing file"' in your terminal. A 'commit' tracks your changes and prepares them to be pushed to your remote repository on github.com

9.  Push the changes in your local repository to GitHub by running 'git push origin "your-branch"'. The branch is your HTTPS link you used earlier.

🎉 **Congratulations!** 🎉
Your files are now on Github.com!

Now, we need to make them live on Github Pages:

1.  Go to your repo on Github and click on the 'Settings' tab.

2.  Scroll down to 'Github Pages' and in Source, choose 'Master' from the drop down menu.

3.  Once saved, you should get a link to your live website!

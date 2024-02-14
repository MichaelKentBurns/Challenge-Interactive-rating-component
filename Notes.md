# Mike's notes as I do this frontend challenge and capture the process in a Git repository.

## Preface

This is my first FEM challenge.  I'm not a frontend developer so I'm learning that too.
I am experienced in using git repositories within a large professional development team.
My goal with this is to do the two together as an example for those who will follow. 

## My major steps in getting going
1. I joined FEM which also includes getting setup with Discord and joining the FEM community. 

1. Went to FEM challenges page and filtered the challenges to include newbie free simple project.

1. Used Web Github.com to create a new repository:  
<http://github.com/MichaelKentBurns/Challenge-interactive-rating-component>.  
	 - When creating it I elected to create a README.md file wherein I described the purpose of the project with reference to the source of the challenge. 

	 - When commiting the edit of the readme, I elected to commit the change directly to the repository.   

	 - While viewing the formatted README, I clicked on the title of the project "Challenge-Interactive-rating-component" so that I was viewing the list of files (currently only one: README.md).   Prominent above the README preview is a green button "<> Code".   Select that.

	 - That gives me a popup with tabs "Local" and "Codespaces", with Local selected.  That allows me to make a local clone of the new repository on my local machine.   For this first challenge I will use the GitHub Desktop application.  If you have not already done so, download that now and install it.  I already have it installed on my Mac, so I can simply click on the option labeled "Open with GitHub Desktop".  My browser pops up a window asking "Do you want to allow this website to open "GitHub Desktop"?  to which I reply "Always Allow".  

	 - Once GitHub Desktop application is started it cloned the repository into a local directory I have chosen to be the home of my local repositories.  In doing so, it created a new folder.   That new folder contains a hidden directory named ‘.git’ and the README.md file.   

1. Now that I have GitHub Desktop app with a clone of the repository I can now work on my local machine to do the work of building my challenge.  The Desktop app allows me to commit small changes locally and then push them individually or in a logical group.  For now, I will push each commit as it's done. 
	 - In the GitHub Desktop app, I see tabs “Changes” and “History” on the left.  If I pick the History tab the right shows a new pane with the README.md file and the most recent changes.   Lines 1 and 2 were what was written by GitHub to begin the file, and 2-15 are the lines I added in my edit.  Notice line 1 is white because I did not touch it.  Line 2 is red because it was originally there, and I replaced it with a modified form.   All the rest of the lines were my new additions.   

	 - At this point I pushed the existing contents as my initial changes labeled 'Begin README.md' 

1. I also have opened a terminal window on that new repository directory. This allows me to use my usual development tools on the files in the local project as I'm used to do.   

1. The next step was to start writing this process, so using my favorite text editor (vim) on my favorite platform (Mac) I created Notes.md and wrote up the process so far.  Then I pushed that with the label 'Create Notes.md'. 

1. Now, I'm ready to start the challenge proper.  Following the instructions here:
<https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI/hub> 
I noticed in that process that the starter files also contain a README.md file that is used for the instructions on how to complete the challenge.  To avoid loosing my original README.md I renamed it to myREADME.md.  That now looks like a new file and the newly downloaded README.md looks like changes to my original.  No matter, they are both there now.   So with the those files in place I went ahead and pushed everything with the commit label "Download FEM starter files".  

1. My next step is to follow the instructions in the new README.md file and begin work...
 Confession: In an effort to get this writeup done, and since I'm not fluent in CSS and doing interactive JS and HTML, I am cheating on this challenge.  I found a couple of YouTube videos that walk through this process.  So, I'm just copying their work to get started.   Frankly the first one I tried is not terribly helpful.  He uses a fancy IDE that does a lot of the code completion and he tends to cut big chunks into his copy buffer and then invoke a code completion then pastes the copy buffer into it.  He does this quickly without explaining much.  Since I don't have the same IDE setup as he is using I don't get the exact same results.   When I push this code, the GitHub change viewer does not always match the before and after lines. It does not reflect the way I would make the code changes.   But, not a big deal. 
I have now completed the basic editing of the index.html file and creation of index.css and index.js files.
 I pushed that as 'Issue 3 - look interactive'.

1. I then added another issue that I want to demonstrate, and since I have a somewhat changed web page, it is now time to demonstrate 'Issue 4 - publish the current state of the main branch as a Github Page' 
 You can read the instructions of how to do that in the Issue 4 description.  
 The end result is a fully published page that will be kept up to date every time I push more changes:
 <https://michaelkentburns.github.io/Challenge-Interactive-rating-component/>

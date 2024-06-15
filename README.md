# NOTES
 - notes for anyting and eryting

 ## Learning Markdown
    
    Markdown is just HTML! (LOL) and is very similar to how you ("kpatt") already use Obsidian

        html similarities
            - `#` stand for `<h1>`, add more for more headers
            - to start a `<p>` just start typing
            - to do a link ting `<a>`, put text in brackets and then the URL right next to it in parentheses
                - ex: [Google](https://google.com)

        word formatting
            - to *italic*, encase your *"whatever"* in a single `*` asterisk
            - to **bold** encase your **"whatever"** in double `**` asterisks

        other formatting options    
            - code blocks are done with three backticks
                - ```const exFunc = () => {}```
            - lists are done with single `*`
            - numbered lists are done with numbers, you dont even need to use the correct numbers
            - checkboxes are made like seaux -> `- [x]`
            - you can actually draw out a table using `|` and `-`
            - quotes can be done using `>`

 ## Learning Git

    - *git init* : is like adding a memory card to your game console

    - *git add* : is like saving your game to that card
        - *git add .* can be used to save EVERYTHING; 
    - *git commit* : commits those changes to memory
        - *git commit -m* : commits and starts a message to describe the changes
    > you will essentially be using `add .` and then `commit -m` one after another

    - *git log* : allows you to look at, GUESS WHAT? a LOG of the the things you've done! (likely saved changes)

    - if you ever want to go back to a previous commit, you can use *git checkout xxx* and replace 'xxx' with the commit hash code

    - *git remote add origin 'URLexample'* : is how you push to a repo; 
      - the URLexample can be master or a new branch name
    
    - *git branch* : allows you to create a separate branch (i may have got this wrong)
    
    - *git status* : allows you to check the status of changes 
    
    - by default all the code is on a master "branch"
      - but you can actually make changes on a separate branch, like making a separate save
      - these changes don't affect the master
      - you can "merge" the changes into the master branch if you want, it's irrelevant UNTIL it goes into the master
      - if someone wanted to have the person to look at the changes, you can submit a "pull request"

> IMPORTANT: you always want to have your local PC synced to GitHub. 
> when you have changes that you made on your local, you "PUSH" the changes to GitHub. 
> when there are changes that are made on github, you "PULL".


# r_tests

Repository for playing around with R

Just trying out a few things - links with github etc


#### 1. Link to github with Key

a. Get a token to cope with my MFA

b. Apply in command line in the git repo type

   *save the credentials entered*   
   **git config --global credential.helper wincred**
   
   *Change README.md and commit*   
   **echo "adding a line" >> README.md**   
   **git add -A**   
   **git commit -m "A commit from my local computer"**
   
   *Push*   
   **git push -u origin master**   
   **[put in credentials for the last time userid and token]**
   
   *Test*   
   **git push**
      
      
#### 2. A few markdown notes

   #'s for headers (more #'s the smaller it gets)  
   
   * for italics              (open and close)
   ** for bold                (open and close)
   ~~ strikeout               (open and close)
   *** Horizontal rule        (once)
   >[space] for block quote
   *[space] for unordered list
   1.[Space] ordered list
   
   
   ![] (path) for image
   [link] for links
   
   $ for eqautions e.g. $A = \pi*r^{2}$  (open and close)
   
   ```{r} code in R  (open and close)
   
   options in  {}
   
    eval        TRUE      Whether to evaluate the code and include its results
    echo        TRUE      Whether to display code along with its results
    warning     TRUE      Whether to display warnings
    error       FALSE     Whether to display errors
    message     TRUE      Whether to display messages
    tidy        FALSE     Whether to reformat code in a tidy way when displaying it
    results     "markup"  "markup", "asis", "hold", or "hide"
    cache       FALSE     Whether to cache results for future renders
    comment     "##"      Comment character to preface results with
    fig.width   7         Width in inches for plots created in chunk
    fig.height  7         Height in inches for plots created in chunk

   
   
   

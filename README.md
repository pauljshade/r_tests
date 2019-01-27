# r_tests
Repository for playing around with R

Just trying out a few things - links with github etc


1. Link to github with Key

a. Get a token to cope with my MFA
b. apply in command line 
   
     In the git repo type : 
        git config --global credential.helper wincred
     Change README.md and commit with : 
        <b>echo "adding a line" >> README.md
        git add -A
        git commit -m "A commit from my local computer"</b>
     Push :
        git push -u origin master
        [put in credentials for the last time userid and token]
    Test :
        git push
      
      
   
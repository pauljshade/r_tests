# r_tests
Repository for playing around with R

Just trying out a few things - links with github etc


1. Link to github with Key

a. Get a token to cope with my MFA
b. Apply in command line in the git repo type : 
   
     # save the credentials entered
     git config --global credential.helper wincred
     
     # Change README.md and commit 
     echo "adding a line" >> README.md
        git add -A
        git commit -m "A commit from my local computer"</b>
     # Push 
        git push -u origin master
        [put in credentials for the last time userid and token]
     # Test 
        git push
      
      
   

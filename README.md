# Hello-Git
This file is for me, because I usually forget all 'very-simple' git commands and waste time searching for tutorials to get the same thing done again and again

#How to create a new repository and link with you local machine 
  first create a new repository with suitable name 
  then un the following set of commands from the desired path 
      git init
      git remote add origin https://github.com/AyushP851/{repo-name}
      git fetch <origin> <master>
      git pull <origin> <master>
      git add .                            //adds local in queue
      git commit -u "anything"             //commits local file in publish queue
      git push -u <origin> <master>        //publishes local files in the repo


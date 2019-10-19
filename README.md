# DistributedParallel


--------------------------------------git basics------------------------------------------------------
this is for establishing the git hub initially you need to download git onto your machine this is of course 
if you are not operating off the Odin server which already has git installed. for installation go to the 
discord and look at the video or cheat sheet I added which has instructions on installation

-----initialization--------- 
so to start the repository enter: 
git init //this initialized the current directory for git

then you use the command: 
git clone https://github.com/CodyJD/DistributedParallel //include the URL so the git 
                                                        //points to the correct github 
                                                        //once this is done you do not have to do it again
                                                        
-----making changes--------- 
so when you make changes to a file you want to do a few things. 

one is make sure that no one else has changed the code so you enter: 
git pull // this pulls down any changes and 
         // if it say "up to date" then your 
         // fine to push your files
         
to submit your files to git hub you do: 
git add [file] //where file is the name of the 
               //file WITH extension you changed 
               // example: myFile.cpp
               
next you need to commit the changes: 
git add commit -m "made some changes" // this will commit the changes and the -m 
                                      // indicates the message you're including 
                                      // make it more descriptive than mine like 
                                      // what changes you made next nothing has been added yet so you do: git push 
                                      // this pushes up all changes you have committed 
                                      // you will be asked for login name and pass
                                      
this is the very absolute basics of git hub and making changes. watch the video for more in depth look
and to do for the case of conflicts if someone else has changed your code and so on.


-----------------------------------------------end of git basics---------------------------------------------

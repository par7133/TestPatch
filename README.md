# TestPatch

## DOC

   // SETTINGS  
   git config --global user.name "[YourName]"  
   git config --global user.email "[YourEmail]"  
   git config --global core.editor "vi"  

   // CLONING THE PROJECT  
   git clone https://github.com/par7133/TestPatch.git

   // CHECKING THE REMOTE CONFIGURATION  
   git remote

   // CHECKING GIT STATUS  
   git status

   // DOING SOME CODE CHANGES  
   // changes..
   
   // COMMIT OF THE CHANGES  
   git commit -a
   (or git commit -a -m 'message text')

   // PUSHING CHANGES ONLINE  
   git push origin master

   // APPLYING THE PATCH  
   git am ./Dumm.2032-05-27.patch

   // PUSHING CHANGES ONLINE  
   git push origin master
   
   // CHECKING HISTORY  
   git log
   
   // DOING SOME CODE CHANGES #1  
   // changes..
   
   // DOING SOME CODE CHANGES #2  
   // changes..
   
   // PRODUCING PATCHES  
   git format-patch -2 -o /Path/PatchDir
   
   // DOING SOME CODE CHANGES ONLINE, ON THE REMOTE  
   // changes..
   
   // PULLING THE REMOTE CHANGES  
   git pull origin master
   

# How to make contributions on Github

Search **Issues** (second option to the right of the search bar up top).  
Some search queries you can use: 'typos', 'documentation', 'html', etc.  
When you find an Issue you are interested in resolving, click on the repository name and follow the below steps:

1. Fork the repository
2. Find the **ssh** or **https** link on the right-hand side of the repository. 
Copy the link and then type this into your terminal: 
  ```
  $git clone <ssh url>
  ```  
  This will copy all the repository files onto your computer.  
3. ```$cd <repo folder>```
4. ```$git checkout -b <new branch name>```
5. Open the file that contains the error in your text editor.
6. Make changes.
7. Add, commit, and push your changes.    
  ```
  $git add <filename>    
  $git commit -m "<message>" --author-'Ellen<youremail@email.com>'   
  $git push <remote name> <branch name>   
  ```
8. Compare and hit green 'Pull-Request' button.
9. Hit 'Create Pull Request'
10. Finished!

You can also use [Code Triage](http://www.codetriage.com) to search for Github issues.  
Use their 'Filter list by Language' to see PHP specific issues.   
![alt text](http://i.imgur.com/FXrjDnh.png "Code Triage")

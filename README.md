# GUIDE TO GITHUB

Step 1: open cmd and go to the folder you want to push to GitHub
+ Use cd to go to next folder
+ Use dir to see all directories

Step 2: Type:  git clone https://github.com/DieppDiepp/hi.git example_repo2
+ Link is : the link of the repository
+ example_repo2 : the name of the folder in your computer that you want to connect to GitHub

Step 3: 
+ git status : to see the currently status (what file was add in to Git, what file was not, what files have been modified, ..)
+ git add test.py : add file test.py to the git (Now this file is still only your local computer)
+ git commit -m "First commit" : Package all the file that have been added to Git and put it in "First commit"
+ git push origin main : Push the "First commit" to the GitHub (Now you can see it in Github website)

NOTE: with this way, each folder you assign to a repository. 
So when you move to the different folder you have the different repository' aceess

# GUIDE TO MODIFY FILE

Step 1: Change the code, file as your expectation
 + Step 2: Like the above Step 3
 + Step 3: end!

 Khi bạn sử dụng lệnh `git checkout <commit_hash> -- <file>` để khôi phục một tệp từ một commit cụ thể, tệp đó sẽ được khôi phục về trạng thái mà nó có tại thời điểm của commit đó. 

Khi bạn chạy lệnh `git log`, Git sẽ hiển thị danh sách các commit, mỗi commit sẽ có một mã hash duy nhất. Để xác định lần commit cụ thể mà bạn muốn khôi phục từ, bạn cần biết mã hash của commit đó.

Ví dụ, nếu bạn muốn khôi phục một tệp từ commit thứ 4 trong lịch sử commit của dự án, bạn cần biết mã hash của commit thứ 4 và sử dụng lệnh `git checkout <commit_hash> -- <file>` với commit đó. 

Tóm lại, bạn cần xác định mã hash của commit mà bạn muốn khôi phục từ để biết được tệp sẽ được khôi phục về trạng thái tại lần commit đó.
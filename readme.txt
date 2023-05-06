git config --global user.name "your_username"

git config --global user.email "your_email_id@gmail.com"

touch .gitignore

git init //Initialising empty git respository

git add .

git commit -m "Initial commit"

git status //for checking 

git remote add origin git@shh link

git push origin master
gitgit 

//for generating ssh key(if you want to upload privately)

ssh-keygen -t rsa -b 4096 -C "your_email@example.com" //public key generated//

cat "public key location" // Copy the key generated here to github account

git push origin master // Project will be uploaded


How to update new file in existing repository

git add .

git commit -m "write message what you want to do"

git push origin master
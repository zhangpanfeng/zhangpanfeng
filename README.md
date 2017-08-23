How to create a repository


git init

git add README.md

git commit -m "first commit"

git remote add origin git@github.com:zhangpanfeng/darren-hadoop.git

git push -u origin master

OR

git remote add origin git@github.com:zhangpanfeng/darren-hadoop.git

git push -u origin master

if the repository has beed added, you can remove it first, and then add it again

For example:

git remote add origin https://github.com/zhangpanfeng/darren-hadoop.git

fatal: remote origin already exists.

you can do this as below:

git remote rm origin

then:

git remote add origin git@github.com:zhangpanfeng/darren-hadoop.git

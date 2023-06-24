# test-git

#เริ่มต้นการสร้่าง
#1. เข้าไปสร้าง repositoryname ใน git จะได้คำสั่ง

echo "# test-git" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/project2you/test-git.git

<br>
#เพิ่มตรงนี้เข้าไป<br><br>
git remote set-url origin https://<key อย่างลืมเปลี่ยน>@github.com/project2you/test-git.git
<br><br>
#หากมีการเพิ่มไฟล์เข้าไปใหม่ ให้ทำการ Add ไฟล์ลงไปใน git<br>
git reset --mixed origin/main

git add .

git commit -m "This is comment"

git push -u origin main

<br>
#2. ให้ทำการ
git init

#git remote set-url origin https://<githubtoken>@github.com/<username>/<repositoryname>.git

git remote set-url origin https://<key อย่างลืมเปลี่ยน>@github.com/project2you/nginx-docker-jupyter-v2.git

git remote -v (for checking current repository)

git add -A(add all files)

git commit -m 'Added my project'

git pull --rebase origin master

git push  origin master



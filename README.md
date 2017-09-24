# Creating your own git repository

echo "# test-git" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/majid198x/test-git.git
git push -u origin master


# generating ssh key and adding ssh key to your github account

ssh-keygen -t rsa

# copy the ssh key generated to your git repository

cat ~/.ssh/id_rsa.pub

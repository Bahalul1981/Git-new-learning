How to work with Git-hub

১. প্রথমে  Visual studio  এ গিয়ে নতুন ফাইল এ ঢুকে টার্মিনাল খুলে নিউ টার্মিনাল এ গিয়ে লিখতে হবে  git init (নতুন repository জন্য VS cod এ নতুন ফাইল খুলতে হবে)

2.  তার পর : git add . 
# git add index.html (নির্দিষ্ট কোনো ফাইল স্টেজ এ তোলার জন্য)
# git rm --cached index.html (নির্দিষ্ট কোনো ফাইল unstage করার  জন্য)
# git rm -r –-cached . (সব ফাইল unstage করার  জন্য)

3.  git commit -m “any cganged name”

4. এবার যেতে হবে গিটহাব একাউন্ট এ। সেখানে গিয়ে নিউ রেপেজটারি খুলতে হবে। এবার রেপেজটারি এর ইউআরএল(https://github.com/Bahalul1981/learning-github.git) কপি করে সেটাকে ঠিক এভাবে পেস্ট করতে হবে।

git remote add origin https://github.com/Bahalul1981/learning-github.git (দ্বিতীয় কোড  টা …or push an existing repository from the command line এটা  গিটহাব এর সাথে লোকাল কড কে কানেক্ট করার জন্য।)

৬. git push -u origin master প্রথম বারের জন্য।
দ্বিতীয় বার git push এটা লিখলেই হবে


আফলোড  এর খেলা শেষ। .......
** git clone (https://github.com/Bahalul1981/Inla-mningsuppgift-3.git (github link যে  গিটহাব থেকে cod ডাউনলোড করতে চাই।)
git fetch (গিট্ হাব এ কোনো ফাইল এ পরিবর্তন করলে সেটা VS cod এ জানানোর জন্য।)
git pull (Download same file in same VS cod)
git branch (new branch name) নতুন ব্রাঞ্চ তৈরী করতে
git branch (কোন ব্রাঞ্চ এ কাজ করছে সেটা দেখার জন্য। )
git checkout(যে ব্রাঞ্চ এ যেতে চাই সে ব্রাঞ্চ এর নাম)
git merge(name of branch) (কোনো ব্রাঞ্চ এর সাথে কোনো ব্রাঞ্চ কে এডজাস্ট করার জন্য)
git branch -D(যে ব্রাঞ্চ কে ডিলিট করতে চাই ,তার নাম।)

VS কোডে  যেকোনো পরিবর্তন করলে বা "commit " করলে শুধু 
1.	git add .  
2.	git commit -m “commit massage”
3.	git push   
 লিখলেই হবে।
•	git log ( commit এ কি কি পরিবর্তন হয়েছে সেটা দেখার জন্য।)/
git log --oneline 
•	git pull/git clone ( Github থেকে লোকাল কম্পিউটার এ কোড আনার জন্য)
•	git diff ( Local directory and stage area cod পার্থক্য দেখার জন্য)
•	git diff HEAD (local directory(local cod) and local repository cod পার্থক্য দেখার জন্য)
•	git merge ( to add local repository cod with local computer cod)
•	git checkout ( To bring back cod from local repository to local cod)
•	git checkout master ( to go back in master branch)









For More details : Git and Github in One Video (Theory + Practical) | A 2 Z in Bangla (youtube vedio)


Git-hub with anisul Islam 

Open terminal then type 
Cmd+space butten: then write terminal.

pwd : where you actually wright now
ls : how many file you have in present position?
cd (desktop): to move your terminal to any file with that’s file name(cd (then file name)

ctrl+L : to clear terminal.

mkdir (file name): To creat a new foder.

cd (file name): To move in that file .
cd .. : to go back in begeineng(like desktop)

ls -a: To se hidden file in present position.

touch (mydoc.txt/ mydoc.html/mydoc.html): touch space then weite your file name to make a new file.

open (file name): to open a that file

git status: to see present position of git.

git add . : to put your file on stage

git add -A : to bring all fils on stage

git restore (file name): to go back that file without adding/putting on stage anything.

git rm --cached (file name):to bring back any staged file to unstage.

git diff: to see what changed has done.

git commit -m “massage”: to put local repository.

git remote : to see is that already connected with local to remote(if show origin its means cod is connected)

git remote u -v: to see details where actually connected local cod with which URL

git remote add origin (https cod of remote repository) example(https://github.com/Bahalul1981/group4.git): to adda local to remote.

git clone https://github.com/Bahalul1981/group4.git: To bring any cod from remote repository to local without making any file in local.

git log : to see commit history

git log --oneline: to see commit in short or oneline

git show (commit id): To check exactly what happened in that particular commit.

git branch : to check branch which ¨branch you are right now.

git branch (branch name): to create a branch 

git checkout (branch name ): to change branch

git branch -D(branch name): to delete a branch(I need to stay in main branch if I want to delete a another branch.

git checkout -b(branch name): to create and switch I n another branch at the same time.

git checkout(commit id): to hide that commit.

Git checkout master: to bring back checkout commit.

git add . && git commit -m “any massage” : to add and commit tighter.

git reset --soft HEAD^ : get beck from commit to stage area.

git reset HEAD^ : to go back working directory.

git reset --hard HEAD^ : go back previous commit.

Git remote add origin (HTTPS link): to link with github

Git push -u origin master: to push cod from vs cod to github

Git push : to push for second time.


GIT  MERGE

First have to come back in origine branch and then …

git merge (branch name): to merge any file with main.

git pull:

git push:


	
















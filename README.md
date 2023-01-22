Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga (main)
$ git clone https://github.com/szabopeter92/git-vizsga0104
Cloning into 'git-vizsga0104'...
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (15/15), done.
remote: Total 15 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (15/15), 14.06 MiB | 3.02 MiB/s, done.


Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git init
Reinitialized existing Git repository in C:/Users/Daniel/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104/.git/

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git commit -m "readme.md és .gitignore létrehozása"
[main 5c3de99] readme.md és .gitignore létrehozása
 2 files changed, 4 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git branch console

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git checkout console
Switched to branch 'console'

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git commit -m "üzenet hozzáadása a konzol-hoz"
[console f714270] üzenet hozzáadása a konzol-hoz
 1 file changed, 4 insertions(+)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git commit -m "oldal háttérszínének változtatása css-ben"
[console 706f1bf] oldal háttérszínének változtatása css-ben
 1 file changed, 1 insertion(+), 1 deletion(-)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git branch
  console
* main

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git commit -m "parancsok hozzáadása README-md-hez"
[main 77ada5f] parancsok hozzáadása README-md-hez
 1 file changed, 59 insertions(+)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git remote add origin https://github.com/DanielAmbrus/vizsga-git-daniel-ambrus.git
error: remote origin already exists.

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git checkout console
error: pathspec 'console' did not match any file(s) known to git

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git init
Initialized empty Git repository in C:/Users/Daniel/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104/.git/

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git commit -m "újra inicializálás és elemek commitolása"
[main (root-commit) 14756d6] újra inicializálás és elemek commitolása
 13 files changed, 340 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 app.js
 create mode 100644 images/hey.jpg
 create mode 100644 images/river.jpg
 create mode 100644 images/summer.jpg
 create mode 100644 images/ukulele.jpg
 create mode 100644 index.html
 create mode 100644 music/hey.mp3
 create mode 100644 music/river.mp3
 create mode 100644 music/summer.mp3
 create mode 100644 music/ukulele.mp3
 create mode 100644 style.css

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git branch console

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git checkout console
Switched to branch 'console'

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git commit -m "üzenet hozzáadása konzolhoz app.js-ben"
[console 60dc42c] üzenet hozzáadása konzolhoz app.js-ben
 1 file changed, 4 insertions(+)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git add .

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git commit -m "háttér módosítása css-ben"
[console 0b5556a] háttér módosítása css-ben
 1 file changed, 1 insertion(+), 1 deletion(-)

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (console)
$ git checkout main
Switched to branch 'main'

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$ git branch
  console
* main

Daniel@LAPTOP-RL3GRC5C MINGW64 ~/Desktop/FRONTEND/04. VERZIÓKEZELÉS/vizsga/git-vizsga0104 (main)
$
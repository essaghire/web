# web

said@HP-Elitebook MINGW64 /d/downloads
$ cd h5bp/

said@HP-Elitebook MINGW64 /d/downloads/h5bp
$ ls
404.html           css/  favicon.ico  icon.png  index.html  LICENSE.txt  site.webmanifest  tile-wide.png
browserconfig.xml  doc/  humans.txt   img/      js/         robots.txt   tile.png

said@HP-Elitebook MINGW64 /d/downloads/h5bp
$ git init
Initialized empty Git repository in D:/downloads/h5bp/.git/

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git add .
warning: LF will be replaced by CRLF in .editorconfig.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in .gitattributes.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in .htaccess.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in 404.html.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in LICENSE.txt.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in browserconfig.xml.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in css/main.css.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in css/normalize.css.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in doc/TOC.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in doc/css.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in doc/extend.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in doc/faq.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in doc/html.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in doc/js.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in doc/misc.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in doc/usage.md.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in humans.txt.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in js/plugins.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in js/vendor/jquery-3.2.1.min.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in js/vendor/modernizr-3.5.0.min.js.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in robots.txt.
The file will have its original line endings in your working directory.
warning: LF will be replaced by CRLF in site.webmanifest.
The file will have its original line endings in your working directory.

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git commit -m "Initial commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'said@HP-Elitebook.(none)')

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git config --global
Display all 322 possibilities? (y or n)

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git config --global user.
user.email        user.name         user.signingkey

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git config --global user.name essaghir.e@gmail.com

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git commit -m "Initial commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'said@HP-Elitebook.(none)')

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git config --global user.email essaghir.e@gmail.com

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git commit -m "Initial commit"
[master (root-commit) d040c2d] Initial commit
 30 files changed, 3630 insertions(+)
 create mode 100644 .editorconfig
 create mode 100644 .gitattributes
 create mode 100644 .gitignore
 create mode 100644 .htaccess
 create mode 100644 404.html
 create mode 100644 LICENSE.txt
 create mode 100644 browserconfig.xml
 create mode 100644 css/main.css
 create mode 100644 css/normalize.css
 create mode 100644 doc/TOC.md
 create mode 100644 doc/css.md
 create mode 100644 doc/extend.md
 create mode 100644 doc/faq.md
 create mode 100644 doc/html.md
 create mode 100644 doc/js.md
 create mode 100644 doc/misc.md
 create mode 100644 doc/usage.md
 create mode 100644 favicon.ico
 create mode 100644 humans.txt
 create mode 100644 icon.png
 create mode 100644 img/.gitignore
 create mode 100644 index.html
 create mode 100644 js/main.js
 create mode 100644 js/plugins.js
 create mode 100644 js/vendor/jquery-3.2.1.min.js
 create mode 100644 js/vendor/modernizr-3.5.0.min.js
 create mode 100644 robots.txt
 create mode 100644 site.webmanifest
 create mode 100644 tile-wide.png
 create mode 100644 tile.png

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git log
commit d040c2db10c986043dcbd5435953728b3032cb00 (HEAD -> master)
Author: essaghir.e@gmail.com <essaghir.e@gmail.com>
Date:   Sat Oct 7 23:52:01 2017 +0100

    Initial commit

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git diff

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git status
On branch master
nothing to commit, working tree clean

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git branch g1r0c0

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git status
On branch master
nothing to commit, working tree clean

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git diff

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git branch
  g1r0c0
* master

said@HP-Elitebook MINGW64 /d/downloads/h5bp (master)
$ git checkout g1r0c0
Switched to branch 'g1r0c0'

said@HP-Elitebook MINGW64 /d/downloads/h5bp (g1r0c0)
$ git branch
* g1r0c0
  master

said@HP-Elitebook MINGW64 /d/downloads/h5bp (g1r0c0)
$ git push https://github.com/essaghire/web.git g1r0c0
Username for 'https://github.com': essaghir.e@gmail.com
Counting objects: 36, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (34/34), done.
Writing objects: 100% (36/36), 85.90 KiB | 4.09 MiB/s, done.
Total 36 (delta 0), reused 0 (delta 0)
To https://github.com/essaghire/web.git
 * [new branch]      g1r0c0 -> g1r0c0

said@HP-Elitebook MINGW64 /d/downloads/h5bp (g1r0c0)

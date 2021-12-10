Published GitHub Pages sites may be no larger than 1 GB. 

need .nojekyll file

to server dll files
$ vim .gitattributes
* binary

//===
$ git branch gh-pages
fatal: Not a valid object name: 'master'.
--> must git commit master branch first ?
-->
$ git add readme.txt
$ git commit -m "master branch readme.txt"
$ git branch gh-pages

 


//===
https://git.3hdeng.me/pubBlasmEx1/GameofLife 
work in debug mode by "dotnet run"
but not work in release mode publish as stand-alone deployment???


//===
$ git init
$ git branch gh-pages
$ git checkout gh-pages
$ git branch -vv
$ touch .nojekyll 
$ git add .nojekyll 
$ git commit -m "need .nojekyll to serve files whose name begins with _, such as _framework, _css, ..."

$ git push origin gh-pages


//=== 
$ vim index.html
change base href 

$ git commit -m "cp from publish/wwwroot/, index.html: change base href to /pubBlasmEx1/ "

//===


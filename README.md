# washington-canyons

config order:
1) create new repo
2) >>>git clone html 
3) add file contents to cloned folder (do NOT push yet)
4) >>>bundle install
5) >>>bundle exec jekyll build
6) >>>bundle exec jekyll
7) >>>bundle lock --add-platform x86_64-linux
8) >>>git add --all
   >>>git commit -m 'add files'
   >>>git push
9) Go to github repo -> settings -> pages -> github actions -> configure
10) check progress in actions tab

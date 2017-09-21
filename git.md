git init
#lisame repository (nt github või bitbucket)
git remote add origin github.com/KevinPitsenko/laraveltest.git
#olukorra ülevaade (ka konflikti lahenduse nägemiseks)
git status
#failide lisamiseks commit jaoks
git add .gitignore
git add *.txt
git add all
#muudetud failide pakendamine
git commit -m "kommentaar"
#failide laadimseks serverisse (origin ehk server ja master ehk branch)
git push -u origin master
#kuvab commit ajaloo
git log

https://github.com/KevinPitsenko/laraveltest.git
#võtab serverist viimase versiooni (nt kui muudetud on mujal kui teie arvutis)
git pull origin master --allow-unrelated-histories

git add * //et trackida muutetud faile
git commit -m "kommentaar" //kommentaar muutatuse kohta
git push //et üleslaadida muutatused


git remote --help
git remote add --help
#kasutaja konfigureerimine
git config --global user.email kevin.pitsenko@vikk.ee
#uue branchi loomine
git checkout -b v001
#branchi vahetamine
git checkout master


git checkout v001
git add git.md
git commit -m "lisatud git readme fail"
git push
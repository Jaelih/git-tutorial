# git-tutorial
pano mag github

1. Getting a local copy

Hello, and 'git-tutorial' ay tinatawag na repository (ata).
para makakuha ng local copy ng repository at makapag edit
ng files, pumunta sa directory kung saan ilalagay ang
files ng repository.

ex. "C:\Users\goober\Documents\projects\MP4"

pagkatapos ay buksan ang Git Bash at pumunta sa tinutukoy
na directory.

itype ang mga sumusunod sa command:
- git init
- git pull URL
	(makikita ang url pag cinlick ang berdeng "<> Code" 
	button sa github.)

maari ka nang mag edit ng files.

1.1 setting the remote

baka di pa naka set ung origin so yea.

itype and sumusunod na command:
- git remote add origin URL
	(same url as kanina)

2. Making commits
 
Pagkatapos mag edit ng files maari na itong ilagay sa
'working directory'.

itype ang command:
- git add sample.txt

kapag sigurado nang iuupdate ang mga inadd na files,
pwede na ito icommit

itype and command:
- git commit

Ito ay magbubukas ng text editor kung saan ilalagay
ang mga detalye ng inedit na files. Pagkatapos itype
ang mga detalye, isave ito sa iclose ng text editor.

nice.

3. pushing to repository

Para iupdate and repository, 
itype ang sumusunod na command:
- git push origin main

congrats

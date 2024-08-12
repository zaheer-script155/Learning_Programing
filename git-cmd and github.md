git configuration
git config --global user.name "name"
git config --global user.email "name@gmail.com"
git config --global core.editor "code --wait"
git config --global core.autocrlf "input"
git config --global -e (show usear name, email, etc)
git config --list

U-untracked 
A-added
C-commited
git log --oneline (to know current status of saved points)
git log --oneline --graph (show graph rasta kase kase toota he)
git log (to know current status of saved points)
.gitignore file create karin aos me ja kr ham jus file ka nam laikhy ga woo file untrace ho jye ge
git reset --hard HEAD~1 (as se ak step pechy ja sakhty ha)
git status -s (check file ktne add he)
git status  (check file ktne add he)
git branch koibe name/navbar create branch
git switch main ye command main branch me jye ga aor jis branch me jana chie whn ham bajha sakhty he
git merge branch name (note phle apko main branch me switch hona hoga)
git branch -d branch name (jis ka name likhana he wo delete ho jye ga)
git switch -C branch name(branch be create hogi aor ap aos branch me switch be kar jao ga)
git stash (ye ham jab kasi be branch me kasi be file pr kuch new lakhty ha aor save ni karty hee to fir ham swithch karty he kase aor branch me fir ye waala stash kr ka ham kase be branch me jaa sakhty he fir ham waps aa kar wo he cheze dobra wps kar sakhty he)
git stash apply (get kar sakhty he aor code dekh sakhty he)
git stash clear as se ham stash delete kar sakhty he

echo "# testingtest" >> README.md (as se ham new file create karty he)
git init se ham initialze karty he apni repo ko
git add . jtne file hogi sare add ho jye ha
git ad file name likhty he to serf wo he add hogi
git commit -m "write any commit"
git branch -M main (ham main pr aa jye ga aor name change kar sakhty he)

git remote add origin paste link jahn apko add karna ha
git push -u origin main as se apka code upload hoga
git switch -C name of branch(im note fir ham kase dosre bandy ka code dekha sakhty ha aor aos pr kam kar sakhty ha)
git branch and git add . git commit  push kar da ga as ko 2sra brnach wala banda mrg ni kar sakkhta wo main bnda kary ga
git fetch kar ka ham dosre wla code apni laptop me mrg karne kely dekh sakhty ha 
git pull
git clone write url(gitjub se ham apni laptop me file ko lana chahty he asle)
ls lisit of file normal file
ls -a all file aa jye ga

cd .. jis directry se bahir jane kaely use hota ha
mkdir name of folder create a folder
cd name of folder ja ham ne jaana ha
git remote -v ham verffiy kar sakhyt ha kis rep pr ha
git push origin main (asme ham code push to kary ga lkn bar bar ye likhna pary ga as se bachany kely)
git push -u origin main(asme ham ne akk bar btaa dia fr dobra onley git push karty rahe ga aos he ak repo pr)
git branch (to cheak branch ham kis branch ppr ha)
git branch -M main (to rename branch)
git checkout aor doosre branch ka name (as se ham dosre branch me ja sakhty he)
git checkout -b new brach name(to create new branch )
git branch -d branch name (delete branch)
git diff main (ye branches ka differce chek karwa daty ha main se)
git pull origin main (as se ye hoga ham apni github ki merge repo ko apni local laptop me lana chaty ha)

1 staged changes add karty he
git reset file name (serf wo file hgi jis ka nam likh lain gain)
git reset (ye sare file reset kar da ga)
2 committed and change (one commit)
git reset HEAD~1
3 commited changes(for many commits)
git reset commit hash(hash kele ham git log kar sakhty he hash mill jye ga)
git reset --hard hash 
(sare commit pechy chaly jye ga)

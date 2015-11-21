# GameJam2015

## Git & GitHub

#### Perustoiminnot

- **Hae projekti koneelle**  
  `git clone https://github.com/paavonelimarkka/GameJam2015.git`


- **Hae päivitykset**  
  `git pull`


- **Näytä muuttuneet**  
  `git status`


- **Näytä muutokset** (poistu painamalla Q)  
  `git diff`  
  `git diff {filename-with-path}`  
  `git diff -- **{filename}`


- **Lisää yksittäisiä muutoksia kommittiiin**  
  `git add {filename-with-path}`  
  `git add **{filename}`  
  `git rm {filename-with-path}`  
  `git rm **{filename}`


- **Lisää kaikki muuttuneet tyylit kommittiiin**  
  `git add **less **css **.css.map`


- **Lisää kaikki muutokset kommittiiin**  
  `git add --all`


- **Palauta kaikki muutokset**  
  `git reset --hard`


- **Palauta tiedoston muutokset**  
  `git checkout -- {filename}`


- **Kommitoi muutokset**  
  `git commit -m "Commit message in english"`


- **Muokkaa kommitin viestiä ennen pushia**  
  `git commit --amend -m "New commit message"`


- **Vie muutokset GitHubiin**  
  `git push origin master`


- **Luo uusi branch**  
  `git branch {branch-name}`
  
  
- **Vaihda aktiivista branchia**  
  `git checkout {branch-name}`
  
  
- **Näytä branchit (aktiivinen on merkitty tähdellä)**  
  `git branch`
  
  
- **Vie uusi branch GitHubiin**  
  `git push -u origin {branch-name}`
  
  
- **Mergeä branch masteriin**  
  `git checkout master`  
  `git pull origin master`  
  `git merge {branch-name}`  
  `git push origin master`
  

- **Poista branch lokaalisti**  
  `git branch -d {branch-name}`


- **Poista remote branch** (ole varovainen)  
  `git push origin :{branch-name}`

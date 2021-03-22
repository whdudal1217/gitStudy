
How To Use GIT in CommandLine 
===

<br />

## I was download some programs for useing git

- sourctree : it's program that makes git visualization
- cmder : for better command line (you can use Linux commands in window)

> ##### Link1 : [Download Github][Download Github]  /  Link2 : [Mark down Grammer][Mark down Grammer] / Link3 : [Download Cmder][Download Cmder]

[Download Github]: https://steady-coding.tistory.com/275 "Download Github"
[Mark down Grammer]: https://gist.github.com/ihoneymon/652be052a0727ad59601 "Mark down Grammer"
[Download Cmder]: https://cmder.net/ "download cmder "

<br />

-----

<br />

# git basics (how save data)

## <span style="color:#FE73FE"> 1. workflow </span>
 + working directory

	+ untracked
	 : a new files
	+ tracked 
	 : git already know this files 
		+ unModified
		 : files are not modify In comparison with before version files
		+ Modified
		 : files are modify In comparison with before version files, only modified files are commit and move to staging area
         <br/>
         <br/>

```
↓ $ git add
```
<br />

------

<br />

## <span style="color:#FE73FE"> 2. staging area </span>


 - git repository (.git directory) -> it says history
	##### If you use vi editor you have to know 'a', ' i ', 'o' it help you edit text <br />
    ##### and press 'esc' exit vi edit mode <br />
    ##### and put in ':wq' -> it means write and quit, then your commit will finish  
    ##### don't commit all files tied package, 
    ##### because git have function that usefull and easy to manage version 
    ##### but if you all files tied to package and commit all files together 
    ##### then the function is no use managing
    ##### ※※ git commit message is verb and present continuous

<br/>

<br/>

	↓ $ git commit / ↑ git pull

<br/>

------
## <span style="color:#FE73FE"> 3. server </span>

each commits has identifier hashcode based snapshot info that are be version info

<br/>

-----

# Use command & Save data on GIT 

1. Make repository (only First) (or Pull or Fetch)
2. Remote (only First)
3. Add
4. Commit
5. Push

## <span style="color:#FE73FE"> 1. Make Repository </span>

### Make your own Repository 

<img src="/img/makeRep.png" width="800px" height="500px" title="image1" alt="make Repository1"></img>

<br />

<img src="/img/makeRep2.png" width="800px" height="500px" title="image1" alt="make Repository1"></img>

## 2. Add Remote

```
	->  git remote add 'remote name' 'your git addr'
```

## 3. Add 

```
	-> git add * 
	// add all files

	-> git add *.txt
	// add all files extension name is .txt

	-> git add a.txt
	// add a.txt
```

## 4. Commit

```
	-> git commit 
``` 
then your cmd become a vi editor mode
1. press 'o' or 'i' or 'e' 
2. typing any comment about your commit 
3. press 'esc'
4. typing ':wq' it means 'write and quit vi mode'

## 5. Push

```
	-> git push 'remote name' 'branch name'
```
you can check your branch name on your github repository <br />
or typing this on cmd
```
	-> git status
```
if you not edit any names, then default name is 'master'

## 6. etc

- git status
```
	-> git status
```
 ### explain about your git status

<br />

- git branch
```
	-> git branch 'branch name'
```
 ### make one branch

<br />

 - git check out
```
	-> git checkout 'branch name'
```
 ### move to branch name

<br />

 - git branch -d
```
	-> git branch -d 'branch name'
```
 ### delete branch name
# testing-inventyv
testing-inventyv Github training By Aman Sir 

Here is the list of topics that we will cover in this training:

#### 1) Create Git Account In Github Website

#### 2) Install Git and Setup a Email and Username as Global
```bash
git config --global user.name "Your Name"
git config --global user.email "yourname@example.com"
```

#### 3) Verify the Git Configuration
```bash
git config --get user.name
git config --get user.email
```

#### 4) Go for Github Account Settings in the Emails Section here end of the page you will find the keep my email address private checkbox to click on it.

#### 5) Go for Github Account Settings in the Developer Settings Section here you will find the Personal Access Tokens to generate a new token. 90 days validity. Token added to the local machine.
``` 
git credential approve <<< $'url=https://github.com\nusername=codervirugama\npassword=ghu_sjsjajsjsjsjasjjajsjsjsjsjsjsjs'`
```

#### 6) Create a Repository in Github

#### 7) Git Remote add Repository in the local machine
```bash
git remote add origin 
```

#### 8) Any File add In the Github = Git Add, Git Commit, Git Push
```bash
git add .
git commit -m "Initial Commit"
git push origin main
```


<br>
<br>

## testing-inventyv Repo 

### main branch

![alt text](image.png)

#### 1) Here Create first hello_world.txt file 
#### 2) commit in the main branch
#### 3) Any Change in the Hello World File
#### 4) commit in the main branch
#### 5) Push in the main branch

<br>
<br>

### feature1 branch

![alt text](image-1.png)

#### 1) Here Create a Different Branch feature1
##### Create Branch
```
git branch feature1 
```

##### Switch Branch
```
git checkout feature1
```

##### Create & Checkout Branch
```
git checkout -b feature1
```

<br>
<br>

## website-flow

![alt text](image-3.png)

#### 1) Here Create a Different Branch Name is feature1

#### 2) Merge the feature1 branch into the main branch

``` 
git checkout main
git merge feature1
```

<br>
<br>

## website-flow/git-merge-test 

![alt text](image-4.png)

<br>
<br>

## Visualizing-git 

![alt text](image-5.png)

#### 1) Here Create a Different Branch
```
git branch branch_name
```

#### 2) hotfix to create a separate branch to solve the issue
```
git checkout -b hotfix
git commit -m "hotfix"
```


#### 3) hotfix merge purpose to create a separate branch release_main_hotfix
```
git checkout -b release_main_hotfix
```

#### 4) release_main_hotfix inside merge hotfix branch
``` 
git checkout release_main_hotfix
git merge hotfix
```

#### 5) main branch merge release_main_hotfix branch
```
git checkout main
git merge release_main_hotfix
```




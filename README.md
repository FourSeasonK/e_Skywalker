# CSIS 3275-070 Software Engineering

## Objectives

This repository contains a RESTful web service developed in Java with the Spring Boot framework, applying various concepts covered in class. The project focuses on an e-commerce system offering features such as:

- Store and retrieve images using AWS S3
- Utilize Gmail SMTP service for email handling
- Implement browser data caching with Redis
- Provide product recommendations
- Handle authentication and authorization with JWT
- Cart tracking functionality
- Process payments

---

## Contributors

- Leandro Machado
- Mariana Magalhães
- Sebastian Gonzalez
- Sung Ah Kim

---


# se_project_frontend


## Project setup
```
yarn install

### Compiles and hot-reloads for development
```
yarn serve
```
### Compiles and minifies for production
```
yarn build
```
### Lints and fixes files
```
yarn lint
```
### Customize configuration
```
Reference (https://cli.vuejs.org/config/)

<br/>

<h2> <strong>Github Best Practices</strong></h2>

<strong>Clone the repository:</strong>

```javascript
$ git clone https://github.com/leandrofahur/se_project_backend.git
```

<strong>Create your own branch:</strong>

```javascript
$ git checkout -b  <branch_name>
```

If you are in the main branch, this command will copy the main one and create a new branch named <branch_name>.

<strong>Staging, commiting and pushing:</strong>

```javascript
$ git add .
```

```javascript
$ git commit -m "a comment describing what this commit is about"
```

```javascript
$ git push
```

If you are pushing for the first time, git will ask you to execute the command

```javascript
$ git push --set-upstream origin <branch_name>
```

Where the <branch_name> tag is the name of your local branch that is going to be created on the remote repository.

<strong>Always keep things up to date:</strong>

```javascript
$ git pull
```

If you are pulling for the first time, git will ask you to execute a command similar to the one listed for push.

<strong>Wrapping up:</strong>

After finishing your work, and the branch is ready to merge with master, execute the following:

```javascript
$ git checkout master
```

and then

```javascript
$ git merge <branch_name>
```

<strong>Delete branch locally</strong>

```javascript
$ git branch -d localBranchName
```

<strong>Delete branch remotely</strong>

```javascript
$ git push origin --delete remoteBranchName
```
<br/>

<h2><strong>References</strong></h2>
<ol>    
  <li>
    <a href="https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository">
        Github - Configuring branches and merges in your repository
    </a>
  </li>
</ol>
<br/>

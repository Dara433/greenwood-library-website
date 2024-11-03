# greenwood-library-website

## Objectives 

The purpose of this project is to enhance the Greenwood Community Library website to make it more engaging and informative by adding 2 sections to the website, the Book Review section and Events page. 

Using git as a version control system. All files in this repository (including the webpage basic sections) were created on local repository and pushed to remote repository, the main branch. 

Morgan and Jamie were responsible for creating the new 2 sections of the website, with Morgan working on the adding the Book review section, while Jamie was responsible for updating the Events page.

[Github link](https://github.com/Dara433/greenwood-library-website)


## Setup

A new remote repository was created and initialized with a readme.md file. This remote repository was then configured on the local terminal using `git clone`



![git clone](./img/1.git%20clone.png)

## Webpage basic sections 
The website contains basic webpage files which includes the following.

    - Home
    - about us
    - events
    - contact us 

each files of the webpage were staged using the command `git add`, committed `git commit -m` and pushed `git push origin main` to the git remote repository as the main branch as shown below

![git add](./img/2.%20git%20add.png)

![git commit -m](./img/3.%20git%20commit.png)

![git push  origin main](./img/3.%20git%20push.png)


## Morgan's Work: Adding Book Reviews

### Creating a new branch 

A separate branch called "add-book-reviews" was created on the local terminal. The following commands were used: 
`git branch` and `git checkout -b`. **This branch is separate from the main branch**. 

![git checkout -b](./img/4.%20git%20branch%20and%20checkout.png)


A new file is added to this branch and named "book_reviews.html". This file on the local terminal was staged using the command `git add`, committed `git commit` and then pushed `git push` to the remote git repository as shown below 

![git add](./img/5.%20git%20add.png)

![git commit -m](./img/6.%20git%20commit%20add%20book%20review.png)

![git push](./img/7.%20git%20push.png)

Created and approved a pull request on github to merge changes to the master branch

## Jamie Work: Updating Events page. 

### Fetching updated file changes 

In other to use the most most recent update from the main branch, the command `git pull` is used. It fetches and merge updated file changes (if any) from the remote repository 

![git pull](./img/8.%20git%20pull.png)

As seen in the code above, the main branch on the remote repository is up to date.


###  Creating a separate branch for Jamie's work and pushing changes

A similar workflow for was used for updating the events page on a separate branch called 'update-events' .

![git checkout](./img/9.%20git%20checkout.png)

 The events webpage was updated with Jamie's work added on the webpage file "events.html" 

 ![vim](./img/10.%20vim%20events.png)
 
 The changes made to the events file were staged and committed, then merged with the main branch and then pushed to the remote repository

![git commit -m](./img/11.%20git%20commit.png)

![git merge](./img/12.%20git%20merge.png)

![git push](./img/13.%20git%20push.png)


Created and approved a pull request on github to merge changes to the master branch
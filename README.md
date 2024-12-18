# CapStone Project: Enhancing a Community Library Website

## Introduction

Enhancing the website for the Greenwood Community Library which aims to be more engaging and informative for visitors. Which includes basic sections: Home, About Us, Events, and Contact Us.

### Scope of Work

My team will be in charge of adding a “Book Review” section and update the “Events” page to feature upcoming community events.
Morgan and Jamie will carry out the task. Morgan will handle the “Book Review” section, while Jamie will update the “Event” page with new Community events.

## Setup

* Creating a Repository on Github
* Naming it grrenwood-library-website
* Initializing it with a README.md file and cloning it to my local machine.

`git clone https://github.com/bolajidevops/greenwood-library-website.git`

### See images below:

![alt text](images/image1.png)
![alt text](images/image2.png)
![alt text](images/image3.png)
![alt text](images/image4.png)

The images above shows the steps on how i created my repository and named it greenwood-library-website, also further to initializing it with a README.md file and lastly cloning it to my local machine.

### Task

In my main branch using the Visual Code Editor i created the following files for each of the web page needed for this project.

* home.html
* about_us.html
* events.html
* contact_us.html

I was able to achive the above files using the command "Vim" on my local terminal on Visual code editor.

- `vim home.html`
- `vim about_us.html`
- `vim events.html`
- `contact_us.html`

See image representation below. 

![alt text](images/image5.png)

After creating the above files, I proceeded to staging, adding and commiting. This will allow Git to be aware of the files created and the modifications made to them at any point in time.

- `git add .`
- `git commit -m "word added"`
- `git push`

![alt text](images/image6.png)
![alt text](images/image7.png)
![alt text](images/image8.png)

The above images shows the staging, comitting and pushing process of the files to the github.

### Morgan's Task: Adding Book Reviews

A branch was created for morgan named "add-book-Reviews" and a new file called *book_reviews.html* was created to represent the book reviews section of the project.
This file (*book_reviews.html*) contains Morgan's codes in building the **Book-Reviews** Section of the project.

Creating branch **add-book-reviews** for Morgan, Creating a file (book_reviews.html) under this branch and also pushing Morgan work to the online Repo.

- `git checkout -b add-book-reviews"`
- `vim book_reviews.html`
- `git push --set-upstream origin add-book-reviews`


![alt text](images/image9.png)
![alt text](images/image10.png)
![alt text](images/image11.png)

- The above images shows how the file (book_review.html) was created.
- How it was stage and committed. 
- Also it shows how the new  branch created for morgan named (add-book-review) was created and switched to from the default brach.

A pull request will be raised for Morgan's work (add-book-review) and will be merged with the main branch to bring it up to date.

`git pull`

![alt text](images/image12.png)
![alt text](images/image13.png)
![alt text](images/image14.png)
![alt text](images/images15.png)

Images above shows how a pull request was raised for Morgan's work and how it was merge to the main branch to keep the project updated.

### Jamie's Task: Updating Events Page

 A branch was created for Jamie named "update-events" and a new file called *update-events.html* was created to represent the book reviews section of the project.
This file (*update-events.html*) contains Morgan's codes in building the **Update-Events** Section of the project.

Creating a branch **Update-Events** for jamie and creating a file (update-events.html) under this branch.

- `git checkout -b update-events`
- `vim update-events.html`
- `git push -u origin update-events`

![alt text](images/image16.png)
![alt text](images/image17.png)
![alt text](images/image18.png)

- The above images shows how the Jamie's file (update-events.html) was created.
- It shows how it was stage and committed.
- It shows how the new  branch created for Jamie named (update-events) was created and switched to from the default brach.
- It also shows how it was pushed from the local system to the remote online.


A pull was raised from the main branch to Jamie's branch (update-events) so Jamie can have access to all the file and add his own part of the project after which a pull request was raised to merge all Jamie's work to the main branch.

![alt text](images/image19.png)
![alt text](images/image20.png)
![alt text](images/image21.png)

The images above explains how Jamies task of the project was completed and merge with the main project.
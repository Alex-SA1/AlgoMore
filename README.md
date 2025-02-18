
# AlgoMore - Website Presentation







### Starting Page 

On this page you will find introductive information about the platform and also the register and login buttons.

![starting-page-1](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/1.png)

![starting-page-2](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/2.png)

![starting-page-3](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/3.png)

The menu has three options: create an account, log in your account, enter in platform (if you are logged in, otherwise you will be redirected to the login page) 

![starting-page-menu](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/4.png)

### Create an account 

On this page you will find a form which is asking for some information about you that are required for creating an account on the platform.

![create-an-account](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/5.png)

### Log in

Here is the place where you have to enter the credentials used for account creation so that you log in the platform.

![log-in](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/6.png)

### Home Page

In this section you will find a menu which lets you navigate through the platform.

![home-page](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/7.png)

### Algorithms Menu

This page contains all algorithms that were added to the platform (separated pages with explanations and implementations for each algorithm).

![algorithms-menu-page](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/8.png)

Also, here is a search bar which allows you to search for some algorithms (if there are algorithms that are containing in the title the word(s) that you entered in the search bar, they will pop up on the top of the page, otherwise the method won't make a change to the page).

![search-bar](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/9.png)

### Algorithms Page (example page: the greatest common divisor)

All algorithms pages are beginning with the title of the algorithm, the author of the article and a detailed explanation of the algorithm with some implementations writen by the author.

![gcd-page](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/10.png)

Also, the users can add implementations for a certain algorithm and they will appear on the page only if the algorithm that was uploaded by them is passing all tests (the algorithm submitted will be run on some input data and the output data will be compared with the expected output data).

![add-implementation](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/11.png)

If an implementation passes all tests, it will be added on the algorithm page and will look like this (when the source code section is toggled on):

![implementation](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/12.png)

If a submitted implementation failed a test, the following messages will be shown to the user:

- first message prints the input data on which the solution failed
![error-1](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/13.png)

- the second message says that the solution will not be added on the page because of the failed tests
![error-2](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/14.png)

If the submitted implementation passes all tests, a success message will be shown to the user and the solution will be added on the page:

![succes-message](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/15.png)

![new-implementation](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/16.png)


### Suggest an algorithm

On this page users can submit new algorithms to be added on the platform.  
They have to write the name of the algorithm, an explanation and an implementation (C++ code). After sending, the algorithm details will be shown on this page until the admin team verifies the scientific correctness of the algorithm and if everything is alright, the algorithm page will be created by admin team and will appear on the algorithms menu.

![new-algorithm-page](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/17.png)

![new-algorithm](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/18.png)


### Forum

This section is a classic forum where users can discuss about different topics related to computer science.

![forum-page-1](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/19.png)

![forum-page-2](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/20.png)

Also, on this page is a search bar where users can search for posts from forum after some keywords.  
If on the forum is a certain post where the word(s) introduced by the user in search bar are found, this post(s) will be pop up on the top of the page. Otherwise, the search method will not modify the page.

![search-bar](https://raw.githubusercontent.com/Alex-SA1/AlgoMore/refs/heads/main/images/21.png)

### 





## If you want to run locally my project

You must have installed: nodejs (I use nodejs v18.16.0), npm (I use v9.6.7), mingw (I use g++ (MinGW.org GCC-6.3.0-1) 6.3.0) and Microsoft visual C++ Redistributable.

- Install this repository on your computer
- Delete package-lock.json
- Open terminal and run next commands

```bash
npm cache clean --force
npm install
npm run dev
```

- Go on localhost to see the website
    
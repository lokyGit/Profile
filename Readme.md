
# Software Engineer/Data/Cloud Engineer Port Folio - Lokesh Palacharla

One of the ways of scaling up as a developer is building a portfolio. Basically, a portfolio is a way of showcasing work samples and skills stated in your resume.

One of the ways of creating a simple portfolio is using GitHub pages. This is a site hosting service that takes HTML, CSS and JavaScript files directly from a repo on GitHub. The good thing about GitHub pages is the fact that it is free as it supports custom domains, with deploys straight from Git.

Getting Started
Make sure you have a GitHub account.
Have basic knowledge of how Git and GitHub Works.
Lets do this 💪🏻
Login to your GitHub account

Creating a project site.

With project sites, you get to use templates downloaded online or pick a theme from the settings on the repository.
create a new repository named username.github.io. Say if you name is carolyne, your repository name will be carolyne.github.io. This will be your homepage. PS: You can add a description if you like.

Check out the following websites to download free portfolio website templates from colorlib, Start Bootstrap, Themezy, BootStrap zero or Bootstrap made. You can as well use this link (https://github.com/evanca/quick-portfolio) to create one by forking the repo.
Go to repository Settings and scroll down to the “GitHub Pages” section. Select “master branch” under the “Source”.

Add a theme to the portfolio to changeits look and feel


Choose the theme you want and then , Select Theme


You may be asked to edit your site`s README.md file
Your chosen theme will automatically apply to files in your repo.

Steps to create personal or organization site
You can work with the repo already created or create a new one.

Clone the repository.
create a folder where you want to store the project on your desktop and clone the new repository

~ $ git clone https://github.com/carolmusyoka18/carolmusyoka18.github.io

add index.html file
You can now create an index.html file in the project folder


~ $ cd carolmusyoka18.github.io
~ $ echo "Hello World" > index.html

Push the Repo
Add commit and push all your changes

`~ $ git add --all

~ $ git commit -m "Initial commit"

~ $ git push -u origin master
`

And you are good to go 😎🎉🎉

Check out your website https://username.github.io.

If you are deploying Github pages for the first time, you might need to wait for a while before you see the actual site. If you need to make any change to your portfolio, you can make them locally and push the changes as shown above. It is not advisable to make changes directly on the portfolio.

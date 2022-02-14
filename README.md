# Ruby on Rails Ecommerce
An E-commerce Web Application built using Ruby on Rails framework with MongoDB as database and Bcrypt for the user authentication.\

This simple e-commerce application demonstrates CRUD operations using mongoDB and a simple implementation of a cookie based user authentication using Bcrypt. I specifically built this application to serve as a default template for building medium to large-scaled e-commerce applications.

## Getting Setup:
1. Download or clone the project from Github
2. Open your terminal then navigate to where you installed mongoDB. In my case it’s located under C:/mongodb/
3. From the root directory of your mongodb installation, go to bin folder then run: mongod.exe to initialize the Mongodb database server
4. Open another terminal then navigate to where you extracted the project files.
5. Run bundle install to install all project dependencies.
6. Finally run: rails server to start the Web Server. rails server -> rails server -b 0.0.0.0
7. Open up your favorite browser then go to http://127.0.0.1:3000


## Pages Included:
- Home
- Login
- Register
- Account
- Add Product
- Edit Product
- Manage Products
- Product List
- Single Product View

## Contribution guidelines
If you are a developer and you would like to contribute to this project, please follow my guidelines bellow:
- ALWAYS start a new branch before making changes to the codes
- Pull requests directly to the master branch will be ignored!
- Use a git client, preferably Source Tree or you can use git commands from your terminal, your choice!
- Many smaller commits are better than one large commit. Edit your file(s), if the edit does not break the code with things like syntax errors, commit. It is easier to reconcile many smaller commits than one large commit.
- When your feature or bug fix is ready, perform a pull request and notify kwislawrencekwis@gmail.com that your code is ready for review on Github.
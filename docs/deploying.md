# Deploying

You will need two accounts to deploy your new webiste. They are both free:
* [Github](https://github.com/)
* [Netlify](https://netlify.com/)

## Pushing to Github
Once you have created your github account. You will need to create a new respository.

### Create a new repository
Click the plus icon in the navigation bar and select New Repository

![New Repo](/newRepo.png)

* Give your repository a new
* Select private
* Make sure Initialize this repository with a README is unchecked

![Repo Details](/repoDetails.png)

### Push to new repository

Open your terminal and navigate to your project folder.

Type the following commands:
```bash
git add .

git commit -m"Initial Commit"
```

Now follow type the commands for `..or push an existing repository from the command line`

![Git Add Remote & Push](/pushGit.png)

## Connecting & Deploying to Netlify
Since there is already fantastic documenation for deploying to netlify I will link to that:
[Deploy to netlify](https://www.netlify.com/blog/2016/02/24/a-step-by-step-guide-gatsby-on-netlify/#connecting-to-netlify)

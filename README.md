# opensource-contribution


## How to Contribute?

<img align="right" width="300" src="https://media.discordapp.net/attachments/716523839634407436/762003277553336360/1.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button 
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://media.discordapp.net/attachments/716523839634407436/762005779947323412/aaaaa.PNG" alt="clone this repository" />

open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

<img align="right" width="300" src="https://media.discordapp.net/attachments/716523839634407436/762003278317355038/2.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/Your-Username/opensource-contribution.git
```

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd opensource-contribution
```

Now create a branch using the `git checkout` command:

```
git checkout -b Your-Branch-Name
```

For example:

```
git checkout -b add-Henzo-Dev
```

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it.

<img align="right" width="450" src="https://raw.githubusercontent.com/firstcontributions/first-contributions/master/assets/git-status.png" alt="git status" />

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <your-name> to Contributors list"
```

replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://media.discordapp.net/attachments/716523839634407436/762003279882092584/3.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://media.discordapp.net/attachments/716523839634407436/762003285455405166/4.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!

Celebrate your contribution and share it with your friends and followers , also with who are participating in hacktoberfest .

<h3>Join Our <a href="https://discord.gg/aEaYpYG" target="_blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/discord.svg" alt="NerdGang" height="30" width="30" /> Discord</a> </h3>

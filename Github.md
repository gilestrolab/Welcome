Gitub
====================


What is Github ?
--------------------
[Gitub](https://en.wikipedia.org/wiki/GitHub) is a free web service designed to host software projects.

When to use Github ?
--------------------

* If your project involves writing some code.
* If you are doing some scripting of any kind (e.g. using `R` statistical software).
* If you are writing LaTeX report/papers.


When **not** to use Github ?
--------------------
Do not use github to store large data typically, you do **not** want to put on github:

* Videos (very bad)
* Sound
* Many/large images
* Any sort of large data (>10M) that a program could output


Requesting access to our organisation
---------------------
We share an organisation, `gilestrolab` on github. 
You can just ask any lab member to invite you.


Public or private repository?
---------------------
If you start a new project, and you want to create a repository,
consider/discuss beforehand whether you would like to make it public or private.


HOW TO: Sunchronize your files to github (Anne's dummy guide) ?
--------------------
1. Log in to github and make a repository for your project of choice
2. On the github page of your new repo, copy the clone URL
3. Open terminal and cd in the directory where you want to have your github files
4. Enter "git clone (copy of clone URL) (YourDirName)", in the clone URL, add your github username and an "@" in front of "github", i.e. "https://username@github.com/gilestrolab..."
5. cd to the new directory and make subdirectories of your choice (mkdir YourSubdirectory)
6. make dummy files in the subdirectories as github won't push empty directories by, e.g., "touch YourSubdirectory/dummy"
7. Add all to git by "git add ."
8. Comment what you just did " git commit -m "YourComment" "
9. git push
10. If your repo is private, you will have to enter your password now.

Happy coding

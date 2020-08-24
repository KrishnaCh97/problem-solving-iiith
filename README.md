A fork is a copy of a repository. Using a forked repository, we can make our own changes to the code or content of the files
without involving the original repository.

To fork a repository,click on the "Fork" button on the top-right corner of the page.
By clicking the button, a copy of the repository will be created in our github account.
We can work on the necessary changes in our github account to make the code more efficient.


Syncing the fork with the original repository is necessary to propose changes to the upstream repository.
First, create a local clone of the fork. This is done by copying the url from the "clone with HTTPS" button 
under code dropdown. Use git clone <url> in the terminal from the directory where we want to clone the fork.
Here the url is the copied url from the forked repo.

Next, to sync with original repository,in the same terminal,copy the url from "clone with HTTPS" button under code dropdown
and use git remote add upstream <url>.
Here the url is the copied url from the original repo.


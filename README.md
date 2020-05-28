# Rules
The system by which we tell stories together

I am a warlock who stands on the shoulders of those magic wielding stewards who came before me.

I am not one of the sorcerers who put the lighting in the rocks to make them think.

While I often employ their techniques, I am not one of the wizards who who shapes thoughts to put in the rocks.

Instead I'm a steward of rocks and their thoughts. I teach magi of rock care and feeding.  I help their rocks speak and show them how to listen.

I mention these things to show that the artifacts of my trade _are_ thoughts and I have tools to share with fellow shapers of thoughts.

The main tool I will introduce you to is called git. Git is a version control system. Version control systems exist to help groups collaborate together. Some of the things mentioned in document I'm calling "The Rules" far have very similar counterparts in git (an entry's name and the first line in a commit message solve the same problem), while other things (like version numbers) become non-issues and will vanish.

The basic flow for this is to first "clone" the repository (usually shortened to repo, https://github.com/Quillcosm/rules is where this repo is hosted on github), this copies all the files in the remote repo to a local repo on your computer. Then you can make the changes that you would like to the documents inside and "add" them to your "commit". Then you'll "push" your commit up to the remote repo. This is how incremental changes are made to documents and each commit is kept in the repos history.

The real advantages in collaboration come with the introduction of "branches" and "pull requests". The default main branch is called "master" and is usually the regaurded as the official version of the work (not work in progress). Lets say that you want to add a rule "All entry names must be limericks", but you're not sure that this rule is a good one and you want others input before you add it to the official document (on the "master" branch). To do this you'll make a new branch (lets call the branch limrick_comment), make your changes and push limrick_comment up to the remote repo. Then you'll create a "pull request" (PR) and ask other members of the project to review your changes. If they approve your changes, you can "merge" limrick_comment with the master branch. This is functionally the same as adding the commits in limrick_comment to the master branch. Usually at this point you'll delete the limrick_comment branch.


# Resources:
git for ages 4 and up" is kind of a long watch, but pretty approachable for folks who are new to this kinda thing: https://www.youtube.com/watch?v=1ffBJ4sVUb4

If videos are not your thing, http://think-like-a-git.net/ is also a pretty good resource.

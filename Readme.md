#GIT

PART 0:
Create a git projet
Create a file Readme.txt and first.txt
Commit and push it on your repo

PART 1:
You have worked hard and the result is beautiful.
But somehow there's a bug.

It's late, your partner wants you to go home.

Hell, maybe a good night sleep (or a good night something else)
will help you find that stupid bug.

So you want to go home, but you don't want to leave the work unsaved,
that would be unprofessional. And you're a pro.

So, as the code cannot be merged into master yet, you decide to create a branch

    Create a file second.txt with the text "A B C D F G"
    Create and checkout a new branch named "second"
    Commit the current state
    Push itv

PART 2:
Your mind is clear and ready to tackle that nasty bug.
As you march to your desk like the conquerant you are, your boss stops you.

There's an urgent fix that needs to go out in prod just. right. now.

    Checkout the branch master
    Pull it to get the last version
    Add a "three" to the file first.txt
    Commit and push the changes to that new file

PART 3:
Now is the time to tackle the problem, let's get back to your work.

    Checkout the branch second

PART 4:
Of couuuuurse !
You found it, the 'E' is missing between 'D' and 'F'

After fixing the bug, the awesomeness can be merged into master.

    Modify the file so that it's beauty is complete
    Commit the difference
    Push it
    Merge it into master
    Push master

PART 5:
You are a good citizen (or at least in this story we assume you are).
You are not working anymore on the branch file-second

    Delete the branch fsecond both localy and on github

PART 6:
Now, you work on a new evolution.

    Create a branch "three"
    Create a file three.txt
    Commit and push it
    Create a file four.txt
    Commit and push it

PART 7:
There is a urgent fix (again), we need the file four.txt only on prod

    Cherry pick this file on master
    Add the text "G H I J K M"
    Commit and Push it

PART 8:
You have a time to work on the branch three

    Add "G H I J K L M" on the four.txt
    Commit and Push it

PART 9:
You want to merge the four.txt on your master

    Merge it
    if there is some conflict, correct it
    Commit and Push it

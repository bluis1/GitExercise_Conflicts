MERGED EX1

# GitExercise_Conflicts

```
----*----*[main]
     \
      \----*[ex1]
```

We will do two seperate git operations 
- [Part 1] add a new change to branch main, thus introducing a second difference with ex1 branch
- [Part 2] then we will merge the changes from branch ex1 into main

Thus after Part 1 the new graph will look like

```
----*----*----*[main]
     \
      \----*[ex1]
```

And after Part 2 the new graph will look like

```
----*----*----*----*[main]
     \             /
      \----*------/
```

Another common project workflow is if there's a red dot on pull (down arrow) that means someone else made changes to the remote that you don't have.  Pull operations need to be done before push operations... so if someone changed the remote after your clone but before your push you will have to pull first, merge, and resolve any conflicts before you are allowed to push your changes to remote.  We didn't have to do that here, but its a very normal workflow for your projects.

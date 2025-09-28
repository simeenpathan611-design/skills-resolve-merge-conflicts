# skills-resolve-merge-conflicts
Step 2: Resolve a merge conflict
Good start! Now let's look deeper at a merge conflict! 🔍

This can be intimidating, but have no fear, Git is smart when it comes to merging! Git only needs a human to decide how to resolve the conflict. Sometimes, the best way to resolve a merge conflict is to add content that's from both branches, or even something that isn't on either! This is why Git needs a human to look at the code and make the proper fixes.

⌨️ Activity: Resolve a merge conflict
Open the pull request that you just created, we created a conflict for you. Have no fear!
At the bottom of the page, under "This branch has conflicts that must be resolved", click the Resolve conflicts button.
Look for the highlighted sections that begins with <<<<<<< my-resume and ends with >>>>>>> main. These markers are added by Git to show you the content that is in conflict.
Remove the changes made on the main branch by deleting all of the content below the ======= and above >>>>>>> main.
Next, remove the merge conflict markers by deleting the following lines:
<<<<<<< my-resume
=======
>>>>>>> main
With the merge conflict markers removed, click Mark as resolved.
Finally, click Commit merge.
Wait about 20 seconds then refresh this page (the one you're following instructions from). GitHub Actions will automatically update to the next step.

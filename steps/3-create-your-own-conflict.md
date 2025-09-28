Step 3: Create your own conflict
Good job! You've solved a merge conflict! 🎉

Resolving a conflict doesn't automatically merge the pull request in GitHub. Instead, it stores the resolution of the conflict in a merge commit and allows you and your team to keep working. To resolve a conflict, GitHub performs what is known as a reverse merge. This means that the changes from the main branch were merged into your my-resume branch. With a reverse merge, only the my-resume branch is updated. This allows you to test the resolved changes on your branch before you merge it into main.

Now, let's get a little evil. (It's for educational purposes!)

⌨️ Activity: Create your own conflict
We went ahead and added a new file called references.md and pushed that change to main, without updating your my-resume branch.

Browse to the my-resume branch.
Click the Add file dropdown menu and then on Create new file.
Create a file named references.md.
Enter some text that conflicts with what we added for references.md in the main branch.
Scroll to the bottom of the page and enter a commit message for your change.
Click the Commit new file button, making sure the "Commit directly to the my-resume branch" option is selected.
Wait about 20 seconds then refresh this page (the one you're following instructions from). GitHub Actions will automatically update to the next step.

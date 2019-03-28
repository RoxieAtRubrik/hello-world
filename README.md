# Hello World! 

No coding necessary to complete this tutorial, just a GitHub account. You don’t need to use the command line, or install Git (the version control software GitHub is built on) unless you want to.

> Tip: Open this guide in a separate browser window (or tab) so you can see it while you complete the steps in the tutorial.

# Step 1. Create an Issue
Issues are used to track ideas, enhancements, tasks, or bugs for work on GitHub. Rubrik Build uses issues to collect user feedback, report software bugs, and organize tasks we'd like to accomplish within a repository. Issues can act as more than just a place to report software bugs. You can also watch an issue to receive notifications about the latest comments.

Take a look through the folder structure and find the `.md` file that corresponds to your city. For example if the workshop is taking place in New Orleans, then there should be a `New-Orleans.md` file located in the `/North America/` directory. Note the sections for what to see/do and where to eat/drink; what is missing? Tell us by creating an issue!

To create an issue:

1. Go to the **Issues** tab at the top of the repository. Select **New Issue**. 

![New Issue](https://user-images.githubusercontent.com/29388592/54911357-43b99500-4f29-11e9-9d96-dfc16e7ec642.png)

2. Select **Get started** next to **Bug Report** to begin creating an issue. This will bring up an Issue template similar to the following image. 

![Filing a Bug Report](https://user-images.githubusercontent.com/29388592/54917938-e6791000-4f37-11e9-84bb-eec9d27a5217.png)

3. Under **Title** type "Your name - Issue", for example `RFitzhugh - Issue`. In the **Write** pane, describe the issue. For example:

```
The `New-Orleans.md` is missing Shaya under the "To Eat/Drink" section. This is an oversight because Shaya is a James Beard award winning restaurant serving delicious Mediterranean food. 
```

Under Assignees, choose [`RoxieAtRubrik`](https://github.com/RoxieAtRubrik). Label should auto-populate as `good first issue`. 

Rubrik Build uses a series of labels, two of which are particularly important to pay attention:

* `good first issue` - indicates a good issue for first-time contributors
* `help wanted` - indicates that a maintainer wants help on an issue or pull request

Click **Submit new issue**. 

You should now see this issue listed under the **Issues** tab. 

# Step 2. Fork the Repository

A fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.

Most commonly, forks are used to either propose changes to someone else's project or to use someone else's project as a starting point for your own idea.

You will fork this repository to your account to make and propose changes. 

To fork: 

1. At the top of the repository, click the **Fork** button. 

![Fork the repo](https://user-images.githubusercontent.com/29388592/54977736-322fc600-4fd9-11e9-8c04-057acbf2d355.png)

2. A dialog will appear to confirm the fork, select your account. 

![Confirm the fork](https://user-images.githubusercontent.com/29388592/54977838-74f19e00-4fd9-11e9-8b27-00c02d4c30ae.png)

You should now this this repository forked to your account and available for you to freely edit. 

![Successful fork](https://user-images.githubusercontent.com/29388592/54978131-55a74080-4fda-11e9-8dd2-b80876e070c9.png)

# Step 3. Create a Branch
Branching is the way to work on different versions of a repository at one time.

By default your repository has one branch named `master` which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to master.

When you create a branch off the `master` branch, you’re making a copy, or snapshot, of `master` as it was at that point in time. If someone else made changes to the master branch while you were working on your branch, you could pull in those updates.

Rubrik Build uses branches for keeping bug fixes and feature work separate from the `master` (production) branch. When a change is ready, a maintainer or admin will merge the branch into `master`.

To create a new branch:

1. Go to your forked copy of the repository called `hello-world`.
2. Click the drop down at the top of the file list that says branch: master.
3. Type a branch name, `name-edits` (i.e. rfitzhugh-edits), into the new branch text box.
4. Select the blue Create branch box or hit “Enter” on your keyboard.

![Create a branch](https://user-images.githubusercontent.com/29388592/54919262-491fdb00-4f3b-11e9-800e-0368ca7a75f5.gif)

Now you have two branches, `master` and `name-edits`. They look exactly the same, but not for long! Next we’ll add our changes to the new branch.

# Step 4. Make and commit changes
Bravo! Now, you’re on the code view for your `name-edits` branch, which is a copy of master. Let’s make some edits.

On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.

Make and commit changes:
1. Navigate to the `.md` file for your city.
2. Click the :pencil: pencil icon in the upper right corner of the file view to edit.
3. In the editor, add a new recommendation for the city.
4. Write a commit message that describes your changes.
5. Click Commit changes button.

![Commit](https://user-images.githubusercontent.com/29388592/54920124-5e960480-4f3d-11e9-956f-be45493e78d0.png)

These changes will be made to just the city `.md` file on your `name-edits` branch, so now this branch contains content that’s different from master. Time to merge into the master!

# Step 5. Open a Pull Request
Nice edits! Now that you have changes in a branch off of `master`, you can open a pull request.

Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub’s @mention system in your pull request message, you can ask for feedback from specific people or teams, regardless of location.

You can even open pull requests in your own repository and merge them yourself. It’s a great way to learn the GitHub flow before working on larger projects.

Open a Pull Request for changes:

1. Click the **Pull Request** tab, then from the Pull Request page, click the green **New pull request** button.

![New PR](https://user-images.githubusercontent.com/29388592/54980022-9eadc380-4fdf-11e9-8abf-44f943cbd6c5.png)

2. In the Example Comparisons box, select the branch you made, `name-edits`, to compare with master (the original).

![PR Review](https://user-images.githubusercontent.com/29388592/54980053-b127fd00-4fdf-11e9-8d92-8196972c017f.png)

3. Look over your changes in the diffs on the Compare page, make sure they’re what you want to submit.

4. When you’re satisfied that these are the changes you want to submit, click the big green Create Pull Request button.

5. Give your pull request a title and write a brief description of your changes. When you’re done with your message, click Create pull request!

![Submit PR](https://user-images.githubusercontent.com/29388592/54978848-6b1d6a00-4fdc-11e9-82dd-972060096470.png)

| Tip: You can use emoji and drag and drop images and gifs onto comments and Pull Requests. |
| --- |

With proper access you will be able to merge your own branch. In this instance, a project maintainer is required to do the merge. 

Celebrate! By completing this tutorial, you’ve learned to contribute to a project and make a pull request on GitHub!

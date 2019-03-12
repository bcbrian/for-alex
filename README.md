______________________________________________________________________________________________
ACTICITY 1 10min
______________________________________________________________________________________________

# Partner Do: Recap git/GitHub

* In this activity you will recap the concepts covered last class. This includes initializing a new repo, adding collaborators, creating branches, and opening a pull request.

## Instructions

* New branches should ALWAYS be made off of the updated master branch.

* Refer to the accompanying PDF for help if needed.

* One partner should create a new repository on GitHub. Name it anything you like. Don't forget to click "initialize this repository with a README".

* Add the other partner as a collaborator, by going to `Settings > Collaborators` and adding their GitHub username.

* Under the `Branches` tab in settings, choose master from the drop down under `Branch protection rules` 

* Check all of the following: 

  * Protect this branch
  * Require pull request reviews before merging
  * Include administrators

* Clone the repository to your local machine using `git clone`.

* Create and checkout a new branch using `git checkout -b` followed by a branch name. Remember that branch names should describe the feature that will be created on that branch.

* Open the project in your editor and make some changes.

* Add and commit the changes using:

```
git add -A 
```
```
git commit -m "descriptive message here"
```

* Push these changes back up to GitHub using `git push origin` followed by your branch name.

* Navigate to your repository in GitHub and there will be a prompt to open a pull request (you may need to refresh).

* Click the green button to "create a pull request"

* Assign a collaborator to review your pull request and merge it.

* On your local machine, checkout the master branch using `git checkout master` and then update the branch to show the latest changes using `git pull origin master`
______________________________________________________________________________________________
ACTICITY 2 10min
______________________________________________________________________________________________
 # Group Do: Designing your MVP

## Instructions
* With your group, answer each of the following questions:
  1. Who is your target audience?
  2. What is the problem that the product will address?
  3. What is the primary goal of the product?
  4. Identify and prioritize essential user stories (limit this to 3 or fewer)?

* Remember, your MVP should be the absolute *minimum* product that you need to pitch your idea to investors (or your classmates). Think bare essentials.

* As an example, the essential features of an instagram-like application might look like:

  1. As a user, I want to post pictures so that I can share my life.
  2. As a user, I want to be able to search for other users so that I can find their list of images.
  3. As a user, I want to be able to view other people's images so that I can keep up with what's happening in their lives. 

* Things like liking photos, sending photos to friends, making instagram stories, etc are cool, but they aren't essential. They should **not** be part of the MVP.

______________________________________________________________________________________________
ACTICITY 3 10min
______________________________________________________________________________________________
 # Student Do: GitHub Issues

* In this activity you will create an Issue on GitHub utilizing the template provided.

## Instructions

* Start by listing the tasks involved in completing each of your user stories.

* Once you have 1-5 tasks written up for each user story, open a GitHub issue for each task by clicking on `Issues` and the green `New Issue` button.

Use the template below, replacing the user stories and acceptance criteria with your own.

```
## User Story
As a user, I want to be able to input search queries so that I can search Stack Overflow when I'm stuck.

## Acceptance Criteria
- [ ] index.html has a text input
- [ ] index.html has a search button
```

* **This is a critical task.** Don't be afraid to ask instructional staff for help during this part. Make sure that each task is clear and everyone on the team understands how to implement each one. 

As an example:

In a dating website application...

**User Story**: As a user I want to see my closest match, so that I can meet someone with whom I share interests.

* **BAD TASK**: 
1. On new member form submit, find and display best match.

* **GOOD TASKS**: 
1. build a form that captures user scores (1-5) to ten questions. 
2. On submit, save the ten numerical answers to as an array.
3. Compare the user array to each existing user array and find the closest match.
4. Display the closest match to the user.

______________________________________________________________________________________________
ACTICITY 4 10min
______________________________________________________________________________________________
 # Student Do: Create a Kanban Board

* In this activity you will create your own Kanban Board for managing your project and add some cards.

## Instructions

* Use the `Projects` tab in GitHub to create a new project (use the automated kanban template).

* Add a new column called Icebox (You will need to exit the "add card" pop-up to access the "add column" area on the right side).

* Click "+ Add Cards" and dragging each issue into the correct column, To Do or Icebox.

### Bonus

* If you have extra time, let each team member add some additional features to the Icebox. This is a great place to hold future enhancement ideas. Remember that each feature may need to be broken down into smaller tasks in the future before you open issues and start building them.  

______________________________________________________________________________________________
ACTICITY 5 10min
______________________________________________________________________________________________
 ## Students Do: First Stand-up

* In this activity you will take part in your first stand-up with your group mates. This will make sure everyone is on the same page with what they are working on and everyone gets help they might need.

## Instructions

* Before your first stand-up, each member of the team should go through the To Do column of the Project Board and self-assign at least one issue. 

  * To do this, click on the issue and on the right choose "self-assign".

* Everyone should have a clear idea of what they intend to accomplish today. Now it's time for your first stand-up!

* Stand if you are able - yep, stand-ups take place standing; this helps to ensure that the meetings are short and to the point. 

* Each member of the team should say what they did yesterday, what they plan to do today, and what, if anything, is blocking their progress. 

* Stand-ups should be held **daily** from this point forward - yes even days that you don't have class (use Slack).
______________________________________________________________________________________________
LETS WORK ON PROJECTS
______________________________________________________________________________________________

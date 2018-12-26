Assignment
========================

In the professional world, you'll often be working on an existing codebase. What to do when you find yourself with someone else's code as part of your own job duties? How can you improve it?

Taking over projects seamlessly and quickly is a skill that will come in handy!

Executing a project from start to finish is "easy" (well, relatively speaking). You end up with intimate knowledge of the project and all its quirks. However, it can be much more difficult to take over someone else's work, especially when there are no existing tests — but there are existing bugs. 🐛

Here's the scenario. You just joined a small team that believes all of the world's problems are due to people being disorganized, and that more focus would solve everything. That's why they've built what they claim to be the world's best to-do app. Maybe the app itself is cool, but the code behind it is a total mess! They've brought you in to add tests to the codebase and to fix a couple lingering bugs.

In order to improve the project, you'll first need to download the project code:

[Download project](https://github.com/amuntasim/todo)


Check out how it's structured, and try to understand how it works. You'll be 
##### fixing bugs, 
##### adding new feature.

### Step 1: Setup
`bundle install`
`rails db:create`
`rails db:seed`
`rails s`  to run and visit `localhost:3000`

### Step 2: Fix the bugs
There are 2 bugs in the code, and it's your job to find them! Here are some hints:

One bug is a simple typo (Task show page).
One of the bugs is severe enough that to-do items can't even be added! (Strong parameter)😮

You'll need to go hunting in the code for these bugs like they're Waldo! Once you find them, you'll fix them because they're preventing the code from functioning properly.

### Step 1: Improve the project

Now it's time to improve the project. Here are the features that you should add: 

1. Upon clicking on the title in the listing page, it should be marked as completed (Ajax request recommended)
2. It shows Yes/No or icons for Completed column in the listing page.

To make these changes, you must understand the code you inherited.


###Files to provide:

Updated code with improvements


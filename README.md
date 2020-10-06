# Autograding Example: Python
This example project is written in Python, and tested with pytest.

### The assignment
The tests are failing right now because the function isn't outputting the correct string. Fixing this up will make the tests green.


- Contents:
    + [The assignment](#the-assignment)
    + [Requirements](#requirements)
    + [Accepting the assignment](#accepting-the-assignment)
    + [Working on the assignment](#working-on-the-assignment)
    + [Testing your assignment](#testing-your-assignment)
    + [Submitting the assignment](#submitting-the-assignment)
    + [Working on the assignment (Repl.it)](#working-on-the-assignment--replit-)
    + [Submitting the assignment (Repl.it)](#submitting-the-assignment--replit-)
    + [Feedback](#feedback)
    + [Setup command](#setup-command) (for teacher)
    + [Run command](#run-command) (for teacher)
    + [Notes](#notes) (for teacher)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

### Requirements
- GitHub Account

### Accepting the assignment
- Use the given link to accept the assignment.
- You will need to log-in with your GitHub Account
- Click "Accept this assignment"
    - This will create a private assignment repo just for you. Be sure the repo name ends with your GitHub username. e.g., `some-repo-yourusername`
- Click the link to open your assignment GitHub repository.

### Working on the assignment
You have the option to work on the assignment using Repl.it. If this is the case, follow the instructions in the [Working in Repl.it](#working-in-replit) section. Otherwise, you can work in any environment you wish.

### Testing your assignment
1. Open the terminal
        - In repl.it: `ctrl + shift + s`.
2. Type `pytest` in the terminal.

### Submitting the assignment
You can also simply work on your code wherever and paste it into `main.py` right in GitHub.
- Click on `main.py`.
- Click the edit icon on the top-right of the code file box.
- Click in the editor box and press `ctrl + a` (select all).
- Paste in your code with `ctrl + v`.
- Scroll down on the GitHub edit page, and click "Commit changes".

You can skip to the [feedback](#feedback) section below.

### Working on the assignment (Repl.it)
- Click "Work in Repl.it"
    - In the "Code" tab, if you look down a bit you will see a button that says "Work in Repl.it"

- **TODO: Need to get better student POV to allow Repl.it as third party app.**

- Make your changes in `main.py`
- Run your code using the "Run" button at the top. Verify your code works.
- Optional: If there is a test-suite, you can run `pytest` in the console.

### Submitting the assignment (Repl.it)
- Go to the "Version Control" tab on the right of the Repl.it window. It looks like a fork.
- If there is a green button that says "Pull", it would be a good idea to click it.
- Regardless, you need to fill in a message in the box that says "What did you change?" and then hit "commit & push".

When you do this, it will automatically upload your code to your assignment's GitHub repo. Go to GitHub to check it out.
If all the tests pass perfectly, you will see a green checkmark near the top of the file table.

### Feedback
In your assignment's GitHub repo, if you go to the Pull Requests tab, you will see a "Feedback" PR. Again, a green checkmark there means all the auto-grading tests passed. A red `x` means that at least one test failed.

### Setup command
*For teacher*

`sudo -H pip3 install pytest`

### Run command
*For teacher*

`pytest`

### Notes
*For teacher*

- pip's install path is not included in the PATH var by default, so without installing via `sudo -H`, pytest would be unaccessible.

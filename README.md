GitHub Actions – Hello World Workflow:-
This repository demonstrates a basic GitHub Actions workflow that runs automatically whenever code is pushed to the repository.
It is designed to understand:
What GitHub Actions is
How a workflow is triggered
How jobs and steps work

Workflow Overview:
Trigger: On every push event
Runner: ubuntu-latest
Job Name: my-job
Step: Prints Hello World! to the console

How It Works:
A push is made to the GitHub repository
GitHub Actions automatically starts the workflow
A virtual Ubuntu machine is created
The job my-job runs
The step my-step executes the command:
echo "Hello World!"
The output is displayed in the Actions logs


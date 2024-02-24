# This is a GitHub Actions Practice Project

This project is a sandbox for learning and practicing GitHub Actions workflows. It follows a tutorial to get familiar with the basic functionalities and configurations.

## Technology 
The project is a Vite React project provided by Maximilian Schwarzmüller of Academind. However, all **WORKFLOWS** were written by me.

## Learning Resources

**This project is based on the following tutorial:**
- **Name**: Learn how to build automated CI / CD workflows with GitHub's DevOps service.
- **Instructor**: Academind by Maximilian Schwarzmüller
- **Platform**: Udemy

https://www.udemy.com/course/github-actions-the-complete-guide/learn/lecture/34120940

## Running Workflows

This project includes example workflows in the .github/workflows directory. You can trigger them manually or automatically based on events like pushes, pull requests, or scheduled times.

### Manually:

Go to your repository's "Actions" tab.
Select the desired workflow.
Click "Run workflow".
### Automatically:

Edit the workflow file to define triggers under the on section.
Push your changes to the repository. The workflow will run automatically based on the defined triggers.
### Workflow Examples

- build.yml: This workflow builds the project and runs tests.
- deploy.yml: This workflow deploys the project to a staging or production environment. (This is just an example, you might not have a deployment workflow in this practice project.)




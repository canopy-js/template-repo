# Template Repo #

This is a template repository for a Canopy JS project. You can create a new project using this repo as a template and begin building and publishing your Canopy project without ever using the command line.

Here are the steps for using this repo:

1. Press the green "Use this template" button above. (You may get emails telling you about a "failing build," this is because upon creating the new repo, certain automatic "workflow" tasks will run, but they don't have the permissions they need until you complete step 2.)

2. Go to Repository Settings > Actions > General and find the section titled "Workflow permissions" and select "Read and Write Permissions." This will allow Github Actions to automatically generate a new website every time you edit your project.

3. Click the `README.md` file.

4. Edit the text with a description specific to your project and press the green "Commit Changes" button at the bottom of the screen. This will trigger automatic processes that set up your project to be edited via the online Github interface.

5. Go to the top left corner of the page and find the link to the repo you created and click the name to navigate back to the project directory.

6. Find the branch drop-down that currently say "Main" on the left side of the page under the navigation bar and click it to select `online-edit`

7. Click the `EDIT_ME` file to open it in the Github web interface.

8. Click the pencil button on the top right-hand side of the file contents box. Change the words "Example Project" everywhere they appear with your preferred project name. Make sure the second row of text begins with `**`, this tells Canopy what your default topic is, which affects where users begin when they navigate to your site.

9. Repeat steps 6-8 any time you want to change your website's contents. You should now have a `build` branch that is automatically updated when you make changes. That folder contains a static website that can be displayed using any hosting service. For a free and easy way of making a Canopy website available online, you can use Netlify.com, a free hosting provider. Follow the steps below to publish your project online.

## Publishing with Netlify ##

1. Log in to Netlify.com using your Github credentials.

2. Choose the "Add new site" option under the "Sites" tab.

3. Pick your user or organization, then pick your repo. For the "Branch to deploy" option, select the build branch.

4. Now your Netlify website should deploy on any change to the build branch, which should update on any change to the topics files on the `main` or `online-edit` branches.

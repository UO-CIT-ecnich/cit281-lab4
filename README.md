# Description
In this lab, my goal was to create a Fastify Node.js web server and complete several tasks related to initializing the project, adding Fastify using npm, setting up git, fixing a MIME error, and adding a second route with query parameters. Here's an overview of my experience and the outcomes of each part:

Part 1: Create initial Fastify Node.js web server
I started by creating a folder called "lab-04" in my cit281/p3 folder. Inside this folder, I created a file called "lab-04.js" and copied the provided code into it. The code set up a basic Fastify server with a route for the "/" endpoint, which returned a simple HTML response. However, I couldn't run the code yet because I needed to add the Fastify module to the project.

Part 2: Initialize as a Node.js project folder using Node Package Manager (npm)
To initialize the folder as a Node.js project, I executed the command "npm init -y" in the terminal within the cit281/p3/lab-04 folder. This command created a default package.json file, which would be updated with package dependencies.

Part 3: Add Fastify to project using npm
To add the Fastify package to the project, I used the command "npm install fastify --save" in the terminal within the cit281/p3/lab-04 folder. This command installed Fastify and updated the dependencies section of the package.json file. After installing Fastify, I used the Run and Debug section in Visual Studio Code (VSCode) to start the web server. I then opened Chrome and navigated to http://127.0.0.1:8080 to ensure that the default content was displayed. However, I noticed that the HTML tags were being displayed as plain text, which I needed to fix.

Part 4: Add git repo, exclude node_modules folder from git, make commits
I wanted to version control my project using git. So, I initialized a git repository using the command "git init" in the lab folder. Since the node_modules folder was automatically created when adding Fastify and should not be included in version control, I created a .gitignore file in the lab folder and added "node_modules" as the only line in the file. I also committed the changes using the commands "git add *" to add the files to git and "git commit -m 'First commit'" to make the initial commit.

Part 5: Fix MIME error, test, and commit
I researched MIME types to understand the issue with the HTML tags being displayed as plain text. After identifying the problem, I fixed the bug in the code to ensure that the browser would interpret the content as HTML. I tested the code and confirmed that the browser displayed the returned web content correctly. I then committed the changes with the documentation message "Fixed MIME type."

Part 6: Add a second route with query parameters, test, and commit
I added a second route to the web server to handle a URL with query parameters for the first name and last name. I updated the code to extract the query parameters and use them to display a personalized message. I tested the new route to ensure that the web server correctly handled the URL and returned the expected output. Finally, I committed the changes with the documentation message "Added name route."

Throughout the lab, I gained hands-on experience in setting up a Fastify Node.js web server, initializing a project using npm, managing dependencies, working with git, fixing coding errors, and implementing routes with query parameters. These tasks helped me become more familiar with web server development and reinforced my understanding of JavaScript and Node.js concepts.

By completing this lab, I achieved the desired outcomes and made progress toward completing Project 3.

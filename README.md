# Scrum Quick Guide Website
Epic User Story: As a visitor to the website, I want to learn the basics about Scrum so I can run my own Scrum teams. 

There will be nine web pages of varying topics. The topics will include the following. 
1.	What is product backlog grooming?
2.	What is Daily Scrum, who participates, and what is the objective? What is not Daily Scrum?
3.	What is a Sprint Review activity?
4.	What is a Sprint Review activity?
5.	What is the difference between a Sprint backlog and a Product Backlog?
6.	What is Sprint execution?
7.	Who is Kenneth S. Rubin? What does he know about Scrum?
8.	What are the responsibilities of a DevOps professional?

https://docs.google.com/document/d/1YMbYiFMRTpzn8cPg19BASfNYkNy6FCDrAdUwOc2FBGo/edit?tab=t.0  

## Common Git Commands: 
Only clone the main branch once when you start a new project.   
```
git clone repoURL
```

How to list all the available branches?   
```
git branch -a
```
Each time you create a new branch, use these two commands to switch to the new branch:   
```
git pull
git switch branchname
```

Each time you are ready to commit code:   
```
git add -A
git commit -m ’what did I accomplish message’
git push
```

How to undo an accidental edit to main instead of to a branch. Ask your favorite AI this question for many options depending on how far along you are. 

If you have not used git add or git commit yet, use
```
git checkout -- <filename>
```

Create the GitHub Issues and Pull Requests in the repo’s GitHub interface.
   
Consider the VS Code extension Live Server by Ritwick Dey to let you preview the static HTML pages.   
To preview your html file, right click and choose "Open in Live Server" or press "Go Live" on the status bar.   

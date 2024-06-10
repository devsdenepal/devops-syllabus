**What is Docker Compose?**  
If you want to run multiple Docker containers, you can create a Docker Compose file and type the command `docker-compose up`. This will run all the containers mentioned in the Docker Compose file.

**What is Scrum?**  
Scrum is used to divide complex software and product development tasks into smaller chunks using iterations and incremental practices. Each iteration lasts two weeks. Scrum consists of three roles: Product Owner, Scrum Master, and Team.

**What does the commit object contain?**  
A commit object contains the following components:
- A set of files representing the state of a project at a given point in time.
- Reference to parent commit objects.
- An SHA-1 name, a 40-character string that uniquely identifies the commit object (also called a hash).

**Explain the difference between git pull and git fetch?**  
- `git pull`: Pulls new changes or commits from a branch from your central repository and updates your target branch in your local repository.
- `git fetch`: Pulls all new commits from the desired branch and stores them in a new branch in your local repository. To update your target branch, `git fetch` must be followed by `git merge`. 

Remember the equation:
```
git pull = git fetch + git merge
```


**How do we know in Git if a branch has already been merged into master?**  
- `git branch --merged`: Lists the branches that have been merged into the current branch.
- `git branch --no-merged`: Lists the branches that have not been merged.

**What is ‘Staging Area’ or ‘Index’ in GIT?**  
Before committing a file, it must be formatted and reviewed in an intermediate area known as the ‘Staging Area’ or ‘Indexing Area’.

```
git add <file_name>
```

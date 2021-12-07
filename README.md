## Creating a New Rails Project with a PostgreSQL Database

- create folder `mkdir project-name-here`
- cd into that folder `cd project-name-here`
- make sure your Rails version is up to date
- For the hell of it, make sure your Rails version is up to date before creating a new Rails app. This seems like a good best practice, so why not.<br>
`rails -v`<br>
`gem update rails`
- create new rails API with a PostgreSQL database<br>
`rails new project-name-here --database=postgresql`<br>
This will create a Rails project directory named `project-name-here`
- cd into your new Rails folder
`cd super-awesome-api`
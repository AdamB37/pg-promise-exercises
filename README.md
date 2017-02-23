## PG-PROMISE-EXERCISES

## Installation Instructions

### 1. Initialize the database
Run the following commands in a terminal window
```bash
createdb pg-promise-exercises
psql -d pg-promise-exercises -f schema.sql
```

### 2. Fix `user` in the `postgresConfig` in the file `exercises.js`


## Specifications

- [ ] Complete all the exercises in the file `exercises.js`
- [ ] There are assert functions for all the exercises


## Quality Rubric

**Well formatted code**
- Code uses a linter, which can be invoked with a command (e.g. `npm run lint`). [50 points]
- Running the linter on all source code files generates no linting errors. [50 points]

**Proper dependency management**
- There is a command to install dependencies (e.g. `npm install`) and it is specified in the installation and setup instructions of the README. [50 points]

**Good project management**
- Commit messages are concise and descriptive. [25 points]
- All features are added via pull requests. [25 points]
- Every pull request has a description summarizing the changes made. [25 points]
- Every pull request has been reviewed by at least one other person. [25 points]

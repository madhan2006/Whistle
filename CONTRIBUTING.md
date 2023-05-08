## contributing

This is the specification on how to contribute to the project.

### pull requests

- Naming of branch connected with PR:
  - up to you; but recommend having a branch titled the same way as the PR itself

- Naming of PR:
  - Recommend we follow [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)


  - ```
    <type>[optional scope]: <description>
  
    [optional body]
  
    [optional footer(s)]
    ```
  - The following is adapted from the guidelines:
    - `fix` refers to a bugfix; something minor
    - `feat` refers to a new feature
    - `docs` refers to a change in documentation/comments. code changes should not be in this PR
    - `refactor` refers to refactoring of code that may allow for better scalability/performance
    - `(!)` appended to a PR means it is a breaking change -- this includes major changes to code/db infrastructure that makes it incompatible with previous versions



- peer code review
  - merge only when one(1) other person has looked through (and perhaps given recommendations)
  - should take into account performance/edge cases/potential bugs when reviewing code




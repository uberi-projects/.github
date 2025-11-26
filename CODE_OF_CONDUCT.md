# Code of Conduct

Welcome to uberi-projects! Your contributions are greatly appreciated. To ensure consistency and best practices across UB-ERI coding projects, please ensure you read the following guidelines, and adhere to the best of your abilities.

## Styling

### General Guidelines

Code should be clear, tidy, and concise where possible, with meaningful variable names and inline notes to explain code where necessary. Sections of a file should be indicated by meaningful section titles. Personal notes should not be included in project files, but should be written in a file labelled notes.txt. notes.txt will only be accessible on your personal computer and will not appear to other contributors or in the project codebase on GitHub. 

### R

When performing statistical analyses, creating visualizations for outputs or internal reports, or creating a Shiny app, R should be preferably used. R code should be formatted in scripts (.R) according to the [tidyverse style guide](https://style.tidyverse.org/index.html), established by Hadley Wickham. To make this process easier, the packages [styler](https://styler.r-lib.org/) and [lintr](https://github.com/r-lib/lintr) may be used to automatically style according to this standard. Please read the tidyverse style guide to familiarize with conventions for file names, variable and function names, syntax, formatting, and more. 

### Python

Python code should be formatted according to [PEP 8 style guide standards](https://peps.python.org/pep-0008/). To make this process easier, the extension [Pylint](https://www.pylint.org/) may be used to automatically style according to this standard.

### Git

Git branches should be titled all lowercase, with words separated by dashes. Where possible, standard sub-directory and file names should be used, for example .server and .ui R files for creating a shiny app, instead of project-specific names. Title commits, issues, and pull requests in present tense. Refer to [GitHub's best practices](https://docs.github.com/en/contributing/writing-for-github-docs/best-practices-for-github-docs) for more details.

### CSS

CSS styling should be contained within .css stylesheets. Elements should be named using kebab-case. Rules within a ruleset should be organized alphabetically, and rulesets should be logically ordered within a stylesheet with headers. 


## Team Practices

### Project Quality

Please test all code changes locally before commiting. Do not create a pull request with code that breaks other project features. If you are unable to solve an issue, add the label `Help Wanted` onto the issue, explain the problem in a comment on the issue page, and clearly state the branch name. A supervisor or other  collaborator will follow up.

If you notice a bug or otherwise unsatisfactory feature on a project, feel free to open an issue. Clearly explain the issue in the description and with a descriptive issue title, and tag the issue appropriately. Please include enough detail so that others are able to reproduce the issue, which will be necessary to resolve the problem. 

All contributors are expected to do their best to ensure any code submitted through a pull request is of high quality, and follows the standards of this document. Supervisors are expected to validate CSS and HTML code using [w3](https://validator.w3.org/) prior to merging in major frontend changes. Supervisors are also excepted to communicate with project clients to ensure that the project quality is in line with established expectations between the parties at regular intervals.

### AI Use

While contributors are encouraged to write original code or incorporate code snippets from reliable sources online, the use of AI tools to assist with coding and development in this project is acceptable, provided that any significant use of AI tools for coding is clearly acknowledged with inline comments. Inline acknowledgement is not required for proofreading or basic editing, such as finding missing commas, correcting typos, or identifying styling mismatches. Inline acknowledgement is also not required for menial tasks such as recalling function names, syntax, or arguments. Where it *is* required is when AI is used for tasks such as conceptualization, code formulation, or interpretation. By contributing to this project, you take responsibility for ensuring the quality and appropriateness of any AI-generated code.  Example acknowledgement comments include:

      ```
      # The contributors acknowledge the use of ChatGPT to help select an appropriate formula for this model.
      # The contributors acknowledge the use of Copilot to generate the base code for this plot, which was later modified and adapted for use in this project.
      ```

### Code Confidentiality

Some projects may be part of a private repository. As a contributor, you are expected to maintain the confidentiality and integrity of the code. Do not share any part of the private codebase, including files or screenshots, to anyone outside of team members or the client. Do not grant repository access to others without supervisor approval. By contributing to a private repository, you agree to respect and uphold these privacy guidelines. If you have any questions or concerns about confidentiality, please reach out to the project supervisor.

### Data Privacy

Every dataset will have its individual considerations regarding privacy and sharing. It is the responsibility of each contributor to ensure no data is included in the repository that is restricted from public release. Please carefully review any DSAs for your data before deciding whether or not to include the data directly in the repository. If the data cannot be appropriately shared, you may still use the data locally, but place the datafile names inside the .Gitignore file to ensure they are ignored by version control. Clearly state this is the case in that repository's README.md. 

### Kindness and Respect

All team members are expected to do their best to treat other team members and clients with respect, using polite and professional language in inline code comments, in GitHub discussions, and in office where applicable.  Team members are also expected to treat the project itself with respect, and write code with the intention of bettering the project, and not harming its quality.

<br>

<img src='www/images/fish.png' height="350" />
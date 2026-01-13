# CI/CD Static website pipeline

This project was used to demonstrate a Continuous Integration(CI) pipeline built by using Github Action to automate validation of a static website on every code push.

# What this project does

- Automatically triggers a CI workflow on every push to the 'main' branch
- Checks out the repository code
- Verifies required files like (index.html) exist
- Fails the pipeline if validation checks do not pass

  # Tech Used

  - Git & Github
  - Github Actions
  - Linux Ubuntu
  - Html & CSS
 
  # CI workflow overview

  1. Developer pushes code to Github
  2. Github Actions workflow is triggered
  3. Code is checked out on Github-hosted runner
  4. Validation checks are then executed
  5. Pipeline passes or fail automatically
 
  # How The trigger happens

  - Git add .
  - git commit -m "Test CI Pipeline"
  - git push
 
    # What I learned

    - How to initialize and manage a Git repository
    - How to configure Github Actions Workflows
    - Understanding CI concepts and automated checks


## Summary (Summarize the bug encountered concisely)

If you want to create an new blank project, there is an field to click where the word "blank" is written wrong. Instead of "blank", it shows "black".
Create new project link: https://gitlab.com/projects/new
Picture of the bug: ![Bug](../Image/Bug_Project_create_blank.png)

## Steps to reproduce     

Step 1: User is logged in GitHub
Step 2: Open the page https://gitlab.com/projects/new
Step 3: Maneuver up to the left up field "Create a blank project" 
Step 4: On this field you can see a missspelling ("black" instead of "blank")
   
## What is the current bug behavior?

The spelling in the described field is not correct. It shows "Create a black project"
     

## What is the expected correct behavior?

The left-up field should show "Create a blank project"
    
## Relevant logs and/or screenshots

Old "new projects" page: ![Old](../Image/Bug_Project_create_blank.png)

New "new projects" page: ![New](../Image/Bug_Screenshot.png)

## Possible fixes

Make changes in the websites HTML Code from for example:

<h3 class="gl-font-size-h2 gl-reset-color">Create black project</h3> to <h3 class="gl-font-size-h2 gl-reset-color">Create blank project</h3>

## Whom do you report/ Assign To/ Tags

/label ~bug ~reproduced ~needs-investigation 
/cc @project-manager 
/assign @qa-tester

## Priority

Trivial

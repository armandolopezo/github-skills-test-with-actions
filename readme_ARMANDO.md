13-02-2025
ALO

### <ins>I began learning WORKFLOW of GITHUB ACTIONS with the course TEST WITH ACTIONS from GITHUB SKILLS</ins>
###
##### I made some mistakes while I was learning and I discovered that is important INDENTATION OF 2 SPACES in the .YML files
##### in different sections like the following elements: 
##### 
```diff
! EXAMPLE:
+ Workflow name: , on: , permissions: , jobs: (first level before indentation of 2 spaces)
+ workflow_dispatch: , push: , contents: , get_current_step: , on_start: (second level - 2 spaces)
+ branches: [after push] , name: runs-on: steps: outputs [after get_current_step:]   (third level - 4 spaces after beginning)
+ - name: , - id: [after steps:]    (fourth level - 6 spaces after beginning)
```
##### I also invest some or a lot of time correcting a file related with a STEP in the course
##### TEST WITH ACTIONS from GITHUB SKILLS . The STEPS of the course were followed in the following PATH: 
##### github-skills-test-with-actions/.github/steps/   and I had to correct the code in the STEP 7 in the file
##### 1-add-a-test-workflow.md  with the following content:
#####
```diff
- - name: Run markdown lint
-   run: |
-     npm install remark-cli remark-preset-lint-consistent
-     npx remark . --use remark-preset-lint-consistent --frail
```
#####
##### I made some corrections with the followinfg changes or something similar:
#####
```diff
@@ - name: Run markdown lint                                                                       @@
@@   run:  |                                                                                       @@  
@@     npm install remark-cli remark-preset-lint-markdown-style-guide                              @@ 
@@     npx remark . --use remark-preset-lint-markdown-style-guide --frail                          @@
```
#####
##### For other STEPS and corrected files, please see CI.YML workflow file in tee MAIN and CI branches.
#####

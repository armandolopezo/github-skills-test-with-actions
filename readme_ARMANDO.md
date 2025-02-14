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
##### TEST WITH ACTIONS from GITHUB SKILLS 

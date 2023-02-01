# Lab Report: Continuous Integration
___
**Course:** CIS 411, Spring 2023  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Michael Shoul  
**GitHub Handle:** [m-shoul](https://github.com/m-shoul)  
**Repository:** [m-shoul / cis411_lab1_CI](https://github.com/m-shoul/cis411_lab1_CI) 
___

# Step 1: Fork this repository
- The URL of my forked repository: https://github.com/m-shoul/cis411_lab1_CI
- Diagram representation of [Trevor Bunch's](https://github.com/trevordbunch/cis411_lab1_CI) repository and my newly [forked repository](https://github.com/m-shoul/cis411_lab1_CI):

![Forked Repository](/assets/ForkLab1.svg)  


# Step 2: Clone your forked repository from the command line  
- **My local file directory is:** C:\Users\17177\Desktop\Junior\Spring2023\CIS411\GitHub\Lab00\cis411_lab1_CI

- **The command to navigate to the directory when I open up the command line is:** 
```
cd C:\Users\17177\Desktop\Junior\Spring2023\CIS411\GitHub\Lab00\cis411_lab1_CI
```

# Step 3: Run the application locally
- My GraphQL response from adding myself as an account on the test project:
``` json
{
  "data": {
    "mutateAccount": {
      "id": "720f4b18-8630-40c2-972a-b81cc5769335",
      "name": "MICHAEL SHOUL",
      "email": "ms1822@messiah.edu"
    }
  }
}
```

# Step 4: Creating a feature branch
- The output of my git commit log
```
Insert the logs here.
```
- The accompanying diagram of what my feature branch precisely and conceptually represents...

# Step 5: Setup a Continuous Integration configuration
- What is the .circleci/config.yml doing?  


- What do the various sections on the config file do?  
   

- When a CI build is successful, what does that philosophically and practically/precisely indicate about the build?  
   

- If you were to take the next step and ready this project for Continuous Delivery, what additional changes might you make in this configuration (conceptual, not code)?  
   

# Step 6: Merging the feature branch
* The output of my git commit log
```
Trevors-MBP:cis411_lab0 trevorbunch$ git log --oneline
dbf826a (HEAD -> labreport, origin/labreport) Answer Step 4
a9c1de6 Complete Step 1, 2 and 3 of LAB_TREVORDBUNCH
1ead543 remove LAB.md
8c38613 Initial commit of labreport with @tangollama
dabceca (upstream/main, origin/main, origin/HEAD, main) Merge pull request #24 from tangollama/circleci
a4096db Create README.md
...
44ce6ae Initial commit
(END)
```

* A screenshot of the _Jobs_ list in CircleCI
![CircleCI Success](../assets/circleci_success.png)

# Step 7: Submitting a Pull Request
_Remember to reference at least one other student in the PR content via their GitHub handle._



# Step 8: [EXTRA CREDIT] Augment the core project
PR reference in the report to one of the following:
1. Add one or more unit tests to the core assignment project. 
2. Configure the CircleCI config.yml to automatically build a Docker image of the project.
3. Configure an automatic deployment of the successful CircleCI build to an Amazon EC2 instance.

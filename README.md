# CSC510-HW5
### Name: 
Navjot Singh
### Student Id: 
200154743
### Unity Id: 
nsingh9@ncsu.edu

#### How to run playbooks:
To run setup commands type:
```
ansible-playbook -i inventory setup.yml
```
To run tasks commands type:
```
ansible-playbook -i inventory tasks.yml
```

#### Link to the setup file
[Setup.yml](https://github.ncsu.edu/nsingh9/CSC510-HW5/blob/master/setup.yml)

#### Link to the tasks file tasks.yml
[Tasks.yml](https://github.ncsu.edu/nsingh9/CSC510-HW5/blob/master/tasks.yml)


#### Link to the video
[Screencast of running tasks, setup and app](https://youtu.be/JoNGObOk8lI)


* Why should developers use configuration management tools to manage their software programs? What can go wrong?
    * Configuration Management focuses on establishing, and maintaining the consistency of a system or product throughout its lifetime. CM is a collection of competencies, techniques and tools whose purpose is to ensure the consistency of the system’s requirements, functional attributes and physical properties. Configuration management tools help in keeping track of the older versions of the system configurations and makes the transition smooth. If we don't use these we will have to tackle situations like the following which are costly in terms of time and money:
        * Figuring out which system components to change when requirements change.
        * Making changes to an older version of the application that was released a couple of years ago. A CM might be able to take the system back to the older configuration easily
        * Re-doing an implementation because you implemented to meet requirements that had changed and you didn’t communicate that to all parties.
        * Losing productivity when you replace a component with a flawed new version and can’t quickly revert to a working state.
        * Replacing the wrong component because you couldn’t accurately determine which component needed replacing.

* Explain the difference between continuous integration, continuous delivery, and continuous deployment, in your own words.  
    * Continuous integration: In this developers merge their code changes to the shared mainline several times a day to avoid the problem of 'integration hell'. The code being merged is automatically tested, analyzed, and verified by an automated build to detect early problems. On the contrary, if the checkout branch is long worked on without being integrated continuously, then it starts to differ tremendously from the mainline branch and gives rise to merging problems.
    * Continuous delivery: In this the main idea is to produce softwares in short cycles to make sure that the software can be released faster and more frequently by testing in production-like environments. This reduces the risk involved with delivering big changes in terms of cost and time by aiming for smaller incremental changes in production-like environments. The companies can then be sure that a software that since a software has been pushed to a staging environment through complete automation, it is safe to be deployed in production.
    * Continuous deployment: In this practice the software produced in short cycles is automatically tested and those that pass the tests are then deployed to production environments.

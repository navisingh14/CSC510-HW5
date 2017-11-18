# CSC510-HW5

* Why should developers use configuration management tools to manage their software programs? What can go wrong?
    * Because
* Explain the difference between continuous integration, continuous delivery, and continuous deployment, in your own words.  
    * Continuous integration: In this developers merge their code changes to the shared mainline several times a day to avoid the problem of 'integration hell'. The code being merged is automatically tested, analyzed, and verified by an automated build to detect early problems. On the contrary, if the checkout branch is long worked on without being integrated continuously, then it starts to differ tremendously from the mainline branch and gives rise to merging problems.
    * Continuous delivery: In this the main idea is to produce softwares in short cycles which makes sure that the software can be released faster and more frequently by testing in production-like environments. This reduces the risk involved with delivery big changes in terms of cost and time by aiming for smaller incremental changes in production.
    * Continuous deployment: A practice where incremental software changes are automatically tested, vetted, and deployed to production environments.

You have been Hired as a Devops Engineer in xyz software company. They want to implement CI/CD pipeline in their company. You have been asked to implement this lifecycle as fast as possible. As this is a product-based company, their product is available on this GitHub link.
https://github.com/hshar/website.git Following are the specifications of the Continuous integration:
1. Git Workflow has to be implemented
2. Code Build should automatically be triggered once commit is made to master branch or develop branch.
If commit is made to master branch, build and publish website on port 82. If commit is made to develop branch, just build the product, do not publish.
3. Create a pipeline for the above tasks.
4. Create a container with Ubuntu and apache installed in it and use that container to build the code and the code should be on ‘/var/www/html’.

# merck-snb-integrations
dev is the primary branch for approved changes that have not yet been deployed to the customer environment.
Before developing code, create a branch from dev and make your changes in that branch. Then, when ready, create a pull request to merge the changes into dev.
When preparing a build to deliver to the customer, create a release candidate branch from dev that contains the source code to be delivered.
When the build is deployed in the customer production environment, merge the release candidate branch into main.

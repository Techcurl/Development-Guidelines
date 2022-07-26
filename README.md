# Development Guidelines

## Branching
### ``feature``
Feature branches are the branches where dev commits their code and push to github, in order to make a pull request. A feature branch naming can be like ``feature/<ticket-number>-<feature-name>``.<br>For eg. ``feature/102-login-form``
### ``bug-fix``
Bug Fix branches are the branches where dev commits their code in order to fix a reported bug. A bug fix branch naming can be like ``bug-fix/<ticket-number>-<bug-name>``.<br>For eg. ``bug-fix/105-login-fix``
### ``develop``
Develop branch is the branch where all the devs code gets merged, and then deployed on the dev site.
### ``master``
Master branch is the main production branch, which is used for the production deployment.

## Code Flow
**``feature/bug-fix ``** -> Code is initially pushed on the feature / bug fix branch. Then, A Pull Request is submitted to merge the code on the ``develop`` branch. The code is merged on the ``develop`` branch after the code review is completed.<br><br>
**``develop``** -> After the code is merged on the ``develop`` branch. The QA is done on the dev site. If the QA gives a go ahead for the changes. A Pull Request is submitted to merge the code on the ``master`` branch.<br><br>
**``master``** -> The ``master`` branch is the main production branch. After the code is merged here, a deployment is done on the production site.

## Code commit
Commit messages should be short but should explain what the commit is all about.<br>
For eg. <br>
![Commit message](/images/commit_message.png)

## Code Reviews
### PR workflow
You need to create a PR to the develop branch.<br><br>
![New PR](/images/new_pr.png)
<br>
![Create PR](/images/create_pr.png)
<br><br>
The code reviewer will review the Pull Request, and then based on the review, either the Pull Request will be merged, or you will be asked to update the Pull Request with the required changes.

## Responsive frontend
### Mobile, desktops
### Browser support

##Error logging

##New Project

* Estimate meeting
* Setup Git
	* Create branch `dev`
	* Create branch `master`
* Setup Project
	* Folder structs
	* Basic architecture
* Setup Jenkins
	* Create job for `dev`
	* Create job for `master`	 
* Divide the stories
* Determine the interface between app and backend

##New Story

* Create branch for story
* Implement
* Push branch to remote
* Create pullRequest
* Write implementation detail(See detail form)

##New PullRequest

@Reviewer

* Confirm changes
* Merge branch to `dev`
* Delete remote branch
  
@Requester (when branch has been merged)

* Delete local branch 
* Update story tracker
  
##Hotfix

* Stash or push current branch
* Create hotfix branch
* Implement
* Push branch to remote
* Create pullRequest
* Write implementation detai
* Notify reporter

##Detail Form

	Purpose:
		/* To help reviewer get brief of this story. */
	Description:
		/* Describe implementation to make code-review easier. */
	Todo:
		/* List todo or improving points. */
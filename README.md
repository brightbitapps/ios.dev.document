#Code Style

[@NYTimes/objective-c-style-guide](https://github.com/NYTimes/objective-c-style-guide)

===

#Git
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

* `pivotaltracker`Update Story to `Start`
* Create branch for story
* Implement
* Push branch to remote
* Merge latest `dev` to your current branch, make sure no conflict.
* Create pullRequest
* Write implementation detail(See detail form)
* `pivotaltracker`Update Story to `Finish`

##New PullRequest

@Reviewer

* Confirm changes
* Merge branch to `dev`
* Delete remote branch
* `pivotaltracker`Update Story to `Deliver`
  
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
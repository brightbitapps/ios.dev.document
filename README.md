#Code Style

[Coding Guidelines for Cocoa](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/CodingGuidelines/Articles/NamingBasics.html#//apple_ref/doc/uid/20001281-BBCHBFAH) - **Apple**

[Google Objective-C Style Guide](https://google-styleguide.googlecode.com/svn/trunk/objcguide.xml) - **Google**

[Objective-c-style-guide](https://github.com/NYTimes/objective-c-style-guide) - **NYTimes**

##Good to pratice

###Less warnning, less bugs.
As a responsibly developer, We should not allow any warning in our codes.

###Writting skills
>The best document is no documents.

The method name and comment should tell you the informations you need.

###Methods should be declared.
* Those methods or properties you wish others to use should be declared at headerfile`.h`.
* Those methods you don't want others know should declared at Class extension in implementfile`.m`.

===

#Git
##New Project

* Setup Git
	* Create remote branch `dev`
	* Create remote branch `master`
* Setup Project
	* Folder structs
	* Basic architecture
* Setup Jenkins
	* Create job for `dev`
	* Create job for `master`	 

##New Story

* Press `Start` on `pivotaltracker`
* Create local branch for the story
* Implement the story
* Push branch to remote
* Merge latest `dev` to the local branch of the story, make sure no conflicts.
* Create pullRequest
* Write implementation detail(See detail form)
* Press `Finish` on `pivotaltracker`

##New PullRequest

@Reviewer

* Confirm changes
* Write comments
* Merge branch to `dev`
* Delete local/remote branch
* Press `Deliver` on `pivotaltracker`
  
@Requester (when branch has been merged)

* Delete local branch
  
##Hotfix

* Stash or push current branch
* Checkout dev
* Create hotfix branch
* fix the bug
* Push branch to remote
* Create pullRequest
* Write implementation detail
* Notify reporter

##Detail Form

	Purpose:
		/* To help reviewer get brief of this story. */
	Description:
		/* Describe implementation to make code-review easier. */
	Todo:
		/* List todo or enhancement points. */
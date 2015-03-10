# gitformanifestos



Examples: https://github.com/showcases/policies


* Manifestos, policies and processes are code on which organisations run
** These documents should not simply be changed on a whim
** Many people are afraid to edit a wiki because they never know if they are allowed to, or if their edit is "important" enough, so there are invisible barriers to collective edits
** It should be easy and safe to propose and share changes
** if must be possible to know exactly which version of a policy is currently active 


* When editing documents in version control all changes are recorded as differences between versions
* Each change can be "blamed" on an individual



Merging



In an open organisation, these documents should be shareable, allowing others to build new organisations based on the same "code"

* Use the tools developers use to manage their code
** Version control is the key tool for collaboration
*** Thousands of people can work on the same programme
** Git is probably the most popular open source tool for 



Collaborative editing environments, like google docs and wikis offer a way to edit documents collectively. However, when a document is a collective declaration, a manifesto or shared process, these should not simply be changed on a whim. 






#BASIC GIT FUNCTIONALITY

##Function: Share change with someone else
Dev Method: git push, git pull
Normal Method: Open email client, navigate to file on C:\ drive, add as an attachment, enter emails of people who need the file, then send the email.
##Function: Work out what has changed
Dev Method: git diff
Normal Method: Open two documents at the same time, look through to work out what the differences are.
##Function: Integrate the changes from one file to another
Dev Method: git merge
Masses Method: Copy and paste paragraphs, slides, cells etc., from one file to another.
##Function: Tracking versions
Dev method: git commit
Masses method: Save file as DocumentNamev[1-n]


##Branching
* When someone would like to suggest some changes to a document, they are able to create a branch 
* This branch can be edited just like the original "master"
* At any point, changes from the master can be "merged" into the branch so that the two are kept in-sync
* if all the changes in the branch are accepted, they can be merged into the "master"

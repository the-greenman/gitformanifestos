# gitformanifestos


# Lessons in collaboration from the world of software

## Work like coders
Software is written with words. The languages used are rather specific so that their meaning can be exact and unambiguous, but they are not that far removed from any other language. The fact that software must be exact, that not a single word can be out of place, makes it very hard for programmers to work together on the same document. One small comma out of place and it all falls down. __Yet, how come the same piece of software could have thousands of contributors? More than that, thousands of people working on the same text - and no central plan or project management?__

Programmers have had one very significant advantage over other wordsmiths, they know when what they have written is correct (or at least works). Being able to detect problems in code quickly, and the need for intense, unambiguous communication has forced software developers to find new techniques for collaboration at a level very rarely required in any other field. Now, as sofware begins to influence almost every aspect of our lives, these techniques and tools are becomming available in many other fields. 

The foundation of most, if not all, collaboration techniques developed within the software industry is __version control__. Version control tools allow different people to work on the same text, and for their changes to be tracked and (generally) safely combined. Different people are able to safely edit and save their own copy of a file, while integrating just the changes they want from others. 

__Version control systems, distributed version control systems in particular are non-hierarchical, decentralised tools for collaboration and decision making that will form the foundation of most collaborative organisations in the years to come. It's time you learned how to use them.__ 

## What would a programmer do?
Every organisation has it's own source code. Often this code is unwritten, and in most cases, locked away in the minds of "management" so that they can stay in control. If we want to create an organisation that is less heirarchical and more open, these rules need to be made clear, they need to be extracted from the minds of those involved and turned into words - turned into a program that will allow the organisation to work. 

Extracting and writing the rules is hard. It involves time and difficult decisions. Once you get the first draft out "onto paper" however, the tools that programmers use to manage their source code come into play. These tools are free and getting easier and easier to use every day. 

## Empower the individuals
Collaborative editing environments, like google docs and wikis offer a way to edit documents collectively. However, many people are afraid to edit a wiki because they never know if they are allowed to, or if their edit is "important" enough. It can be very difficult to create an environment where everyone within and organisation feels confident enough to make changes that might be important. 

Version control makes it possible to safely create a concurrent version of a document, make any proposed changes, and then share their changes in a way that will allow them to be included - if they are agreed on. Changes are safe, and anyone is free to make changes safely. 



---------------------------------


Examples: 
* http://www.hastac.org/blogs/harrisonm/2013/10/12/github-academia-and-collaborative-writing
* https://github.com/showcases/policies
* http://openpolitics.org.uk/contributing.html


* Manifestos, policies and processes are code on which organisations run
* These documents should not simply be changed on a whim so there are invisible barriers to collective edits
* It should be easy and safe to propose and share changes
* if must be possible to know exactly which version of a policy is currently active 


##Version control
* Use the tools developers use to manage their code
* Version control is the key tool for collaboration
* Thousands of people can work on the same file
* Git is probably the most popular open source tool for managing versions
* When editing documents in version control all changes are recorded as differences between versions
* Each change can be "attributed" on an individual
* Changes can be added and removed easily
* 


## Github
* Github is the biggest online tool for managing git repositories
* Github allows easy, online editing 
* Markdown allows simple formatting (http://daringfireball.net/projects/markdown/). Using markdown keeps simple formating as plain text, so that it is easy to compare and manage changes. 
* http://Prose.io is a good way to make editing easier.



In an open organisation, these documents should be shareable, allowing others to build new organisations based on the same "code".








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

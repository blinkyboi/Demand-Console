# Contributing to DMD  
---
The Demand Console Project is a community-driven project, and we are always delighted to welcome new contributors!  
  
There are lots of ways you can contribute for full details see the [Contributing Guide](https://github.com/blinkyboi/Demand/blob/main/contribute/contribute.md).  
  
## Got a Question or Problem?  
---
If you have a question or problem relating to using DMD then the first thing to do is to check the website's [Frequently Asked Questions](https://demand.pythonanywhere.com/faq)[^1] page.  

If the FAQ doesn't help then please ask on the [Discord Server](https://discord.gg/nSHPMG8zsH) or the [Q&A discussion board](https://github.com/blinkyboi/Demand/discussions/categories/q-a).  
  
## Found an Issue?  
---
If you have found a bug then raise an [issue](https://github.com/blinkyboi/Demand/issues).  
  
Its worth checking to see if its already been reported, and including as much information as you can to help us diagnose your problem.  
  
This [guide](https://github.com/blinkyboi/Demand/blob/main/contribute/contribute.md) explains some useful steps you can follow.  
  
## Found a Vulnerability?  
---
If you think you have found a vulnerability in DMD then please report it via our designated [Vulnerability reporting Discord Channel](https://discord.com/channels/1186333713395617823/1235026033774694410).  
  
We are always very grateful to researchers who report vulnerabilities responsibly and will be very happy to give credit for the valuable assistance they provide.  
  
## Have a Feature Request? 
---
If you have a suggestion for new functionality then you can submit a ticket in the Discord, or create an [issue](https://github.com/blinkyboi/Demand/issues) marked as `New Feature` on the repo.  
  
Its worth checking to see if its already been requested, and including as much information as you can so that we can fully understand your requirements.  
  
## Help Improve the Documentation  
---
Wanna help make the docs more helpful? We encourage and welcome all document-related Pull Requests titled as `Docs: Your Change Here` or opening [issues](https://github.com/blinkyboi/Demand/issues) using the `docs` tag.  
  
## Coding  
---
All code should follow the [Development Rules and Guidelines](https://github.com/blinkyboi/Demand/blob/main/contribute/DevGuidelines.md). 
  
Other helpful resources for DMD Developers:  
* The [Discord Server](https://discord.gg/nSHPMG8zsH)  
* The [Discussions Board[^2]](https://github.com/blinkyboi/Demand/discussions)
  
If you are interested in working on any of the code then the Discord is the best place to ask questions.  
  
### Improve Existing Functions or Write New Ones 
---
The functions define how useful DMD can get. When there are more assorted and useful commands, DMD would be used more frequently especially if the added/existing functions are easy to use.  
  
We are always looking to improve existing ones and add new ones, so this is a great place to start helping with the DMD code base.  
  
### Improve Existing Plugins or Write New Ones  
---
Want to write add-ons (Plugins) that add functionality to DMD? Usually Plugins are coded as add-ons to DMD and can be found in the [DMD Plugin Releases](https://github.com/blinkyboi/Demand/blob/main/Plugin-Releases/).  
  
Add-ons are a great way to extend DMD and can be ideal for personal projects.  
  
### Improve DMD and `/bin/`  
---
The DMD `/bin/~` directory underpins all of the other DMD features, such as plugins loader or other helper files, and so ensuring its contents are as robust as possible is very important.  
  
Fixing [issues](https://github.com/blinkyboi/Demand/issues) is very valuable (ones flagged as [Ideal First Bug](https://github.com/blinkyboi/Demand/issues?q=is%3Aissue+is%3Aopen+label%3A%22Ideal+First+Issue%22) are good ones to start on) and there are always many core improvements we want to make.  
  
#### Guidelines for Pull Request (PR) submission and processing: 
---
  
##### Contributor License Agreement  
---  
You will need to sign the [Contributor Licensing Agreement](/contribute/CLA.md).  
If you have not yet done this then you will be prompted to sign it when you submit a PR.  
The comment prompting you to sign it will explain how this can be done.  
If you would like to sign it for past PRs then just submit a dummy one to the [cla](https://github.com/blinkyboi/cla) repo and follow the prompt.  
The PR does not have to be merged so we can just close it.  
  
##### Developer Certificate of Origin  
---
The Git commits must be [signed off] to indicate your agreement with [Developer Certificate of Origin].  
  
##### Format/Style Python Code  
---
The Python code is formatted using the standard python formatting (2 indent spaces between functions) and includes detailed comments and explanations of code snippets and all functions.  
  
##### What should you, the author of a pull request, expect from us (DMD Team)? 
---
* How much time (maximum) until the first feedback? 1 week.  
* And following iterations? 1 week.  
* This is a guideline we should normally be able to hit. If it's been more than a week and you haven't heard then please feel free to add a comment to your PR and @ mention the team (@team12runners/blinkyboi).  
  
##### What we (DMD Team), expect from you?  
---
  * "Atomic commits" (logical changes to be in a single commit). Please don't group disjointed changes into a single commit/PR.  
  * Descriptive commits (subject and message):  
    * For example: https://git-scm.com/book/en/v2/Distributed-Git-Contributing-to-a-Project#_commit_guidelines  
  * Please, leave a comment after force pushing changes. It allows everyone to know that new changes are available.  
  * Discussion about the changes:  
    * Should be done in/on the PR or via the Discord and a link to that Discord thread added to the PR comments. (i.e.: Shared information is important, if something happens via IRC or private email please ensure a summary makes it to the PR.)  
    * Discussion will be kept in the pull request unless off topic.  
  * No merge commits. Please, rebase.  
  * Rebase if the branch has conflicts.  
  * How much time will a pull request be left open?  
    * This isn't static, one or more members of the DMD Team will reach out (using @ mentions in PR comments) once or twice in order to get things back on track. If no input is received after a month or two then the PR will be closed. Total stale time will likely be 2 to 3 months.  
    * Close with a message such as: "The pull request was closed because of lack of activity (as per CONTRIBUTING guidelines)". Labeled as `Stale`.  
    * If the contribution is deemed important or still valuable the code may be:  
      * Manually merged (if possible).  
      * Retrieved by another member of the team, fixed up and resubmitted. In which case the commit message (PR message) should contain a reference to the original submission.  
  
##### Approval process:  
---
* All PRs must be approved by a minimum of 2 members of the DMD Team (other than the author) and anyone who is flagged as a reviewer or assignee on the PR.  
* The PR author can optionally specify any reviewer they would like to review their PR and any member of the Team can add themselves as a reviewer. This will effectively prevent the PR from being merged until they approve it.  
* Any member of the Team can merge a PR as long as the above conditions are met.  
* Reviews by people outside of the Team are still appreciated and welcomed :)  
  
---
[signed off]: https://git-scm.com/docs/git-commit#Documentation/git-commit.txt--s  
[Developer Certificate of Origin]: https://developercertificate.org/  
  
[^1]: FAQ page is currently being worked upon and more topics will be added soon. If you'd like to help with the [docs](https://demand.pythonanywhere.com/docs.html), we welcome and encourage you to open a pull request.

[^2]: For accepted developers only; see [Contributing Guide](https://github.com/blinkyboi/Demand/blob/main/contribute/contribute.md).

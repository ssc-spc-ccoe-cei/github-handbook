# GitHub
GitHub is a widely used platform for source code management. It allows teams to collaboratively work on code and documentation, with both internal and external partners.

## Setup

If you don't already have a GitHub account, please visit github.com and sign-up. 

1. Send a message to Steve or Jun to add you to the organization.
2. You'll probably want to tweak your [notification settings](https://github.com/settings/notifications), specifically the `Automatically watch repositories` option.  
3. You'll want to become familiar with a `git` client.  Some options include:

* [GitHub Desktop](https://desktop.github.com/)
* [VS Code](https://code.visualstudio.com/) 
  * See VS Code's [Working with Git](https://code.visualstudio.com/docs/editor/versioncontrol) for more information.



## Rules and Guidance

* Do not store private or sensitive data in GitHub. This includes passwords, keys, personal data, private configuration data.  If you think you pushed anything private to GitHub,
consider it compromised and notify your manager.

* Repositories should be public unless there is a compelling reason to keep it private.  Starting with a public repo and making the source code open from the beginning is _much_ easier than starting as a closed source project are then attempting to open source it when it's "ready".  If you're unsure, ask your manager.

* The Government of Canada position on Open Source is to open source code by default when possible: 
   - [Open First Whitepaper](https://github.com/canada-ca/Open_First_Whitepaper/blob/master/en/4_Open_Source_Software_Contribution.md) 
   - [Guide for Publishing Open Source Code](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/open-source-software/guide-for-publishing-open-source-code.html)

* Projects that are no longer maintained should be [Archived](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/archiving-repositories) instead of deleted. 

* Do not commit code directly to the main branch. The recommended practice is to create a feature branch and a pull request when your code is ready to be merged.  Please read [GitFlow](https://guides.github.com/introduction/flow/) for more detailed information.

* Repositories should be given a useful name that decribes the project. For example, `terraform-module-eks-cluster` is more appropriate than `eks`.  

* Repository names should be all lower case and use `-` instead of `_`



# GitHub-case-study<br>

CSA case study</br>

<b>Customer scenario</b></br>
Our security team is asking for help ensuring proper reviews are being done to code being added into our repositories. We have hundreds of repositories in our organization.</br>
- What is the best way we can achieve at scale?</br>
- We are new to some of the out-of-the-box settings and the GitHub API.</br>

Can you please help us create a solution that will accomplish this for our security team?</br>


The Challenge</br>
The technical solution to accomplish this is to listen for organization events to know when a repository has been created. When the repository is created, please automate the protection of the default &main; branch.</br>
Notify yourself with an @mention in an issue within the repository that outlines the protections that were added.</br>


Assumptions</br>


Proposed Solution</br>



Reference Links

Docs: https://docs.github.com/en</br>
API: https://docs.github.com/en/developers/overview/about-githubs-apis</br>
Webhooks: https://docs.github.com/en/developers/webhooks-and-events/webhooks/about-webhooks#events</br>

====
https://docs.github.com/en/rest
https://github.com/cbrgm/githubevents
https://docs.github.com/en/developers/webhooks-and-events/webhooks/creating-webhooks


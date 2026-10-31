# Developer handoff notes

## What I delivered
The customer support portal page (index.html, styles.css) is where our clients can go for assistance whenever they have any issues with their account and orders. We put an email to reach out to our team directly and support hours listed so they know when to reach out and expect a response. We also implemented an FAQ where commonly asked questions or issues can be quickly resolved without having to wait on a customer support response. Implemented .gitignore and updated project README.md

## How I verified the page
Verified everything locally by opening index.html in google chrome to make sure styles.css were correct, making sure title is visible, contact email is correctly displayed, and support hours included the proper time zone. Used git status after every commit to make sure we had a clean tree each time. 

## Remote change I received
Synchronized with remote team documentation updates by running git pull origin main to pull down shared repository changes into the local working tree without conflicts and ran git status to verify there were no issues. 

## Git workflow explanation
Git commit alone won't update GitHub because it takes snapshots to the local repository databse on your machine not online. A separate push operation (git push origin main) is required to translate that to the remote GitHub server so team members can see them. 
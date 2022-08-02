## Git – Group activity

**Activity name:** Git Collaboration – Basic (Working with .txt files)

**Team size:** 3

**Purpose of the activity:** To understand how to collaborate and contribute files to a common git repository using git within a team.

**Requirements:** GitHub account, Git installed in local.

**Scenario:** The team is preparing for a formal presentation in front of the client about their project. The presenters are getting ready with a plan for the presentation.

Let’s call the team members (presenters) as Member1, Member2, Member3 and let Member1 be the person responsible for managing/creating/merging the files remote repository in GitHub.

-   Member1 – Responsible to maintain a list of emails to whom invites have to be sent for the presentation.
-   Member2 – Responsible to create a checklist to make sure everything is in place before the presentation starts.
-   Member3 – Responsible to create the agenda for the presentation.

    Note – Please work with .txt files here.

## How to execute:

1.  First, Member1 should create an organization called git-exercises in his/her GitHub account.
2.  Next, Member1 should create a remote repository (can be private or public) called practice-git-with-files in the organization git-exercises.

    Note: Do not forget to add a README.md file to the repository and fill it with what/why this repository was created.

3.  Member1 should now add Member2 and Member3 as members to this repository practice-git-with-files. By doing so Member1 and Member2 will be able to contribute files to the repository created in this organization. And Member1 by default will be able to contribute to the repository as he/she will be the owner.
4.  Now Member1 should share the repository link with Member2 and Member3.
5.  Now all the members should clone the remote repository to his/her local repository.
6.  Next let any member, say Member3 should create a .txt file in the cloned folder (local) with the contents specified above.
7.  Next Member3 should push the file from his/her local repository to remote repository.
8.  Now all the members can see the file completed by Member3 in the remote repository but the local repository of Member2 and Member1 does not reflect the changes pushed to remote repository by Member3. For this, Member2 and Member1 should pull the files from the remote repository to bring it to their local repository. Now in Member2 and Member1’s local repository folder, the file (completed by Member3) will be visible.
9.  Likewise, the other 2 members (Member2 and Member1) can repeat the same steps one after the other.
10. Finally, we should be able to see 3 .txt files completed by the 3 team members in the remote repository. So now we can say that all the team members have contributed files to the same remote repository.

## Further exploration:

1.  What if all the team members work with their own files simultaneously and push the code? Will it be successful? Or will it show an error? If so how do we fix it?
2.  The git commands required for the above steps would have been completed in GitBash. How would it be if we do in through GithHub Desktop or any other Git UI client ? Easy? Difficult? Same?
3.  What if Member1 did not add Member2 and Member3 as members? Will they still be able to contribute code to the remote repository created by Member1? Hint: Should learn about pull request in git.

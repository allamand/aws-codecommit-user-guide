# Working with Repositories in AWS CodeCommit<a name="repositories"></a>

A repository is the fundamental version control object in CodeCommit\. It's where you securely store code and files for your project\. It also stores your project history, from the first commit through the latest changes\. You can share your repository with other users so you can work together on a project\. If you add AWS tags to repositories, you can set up notifications so that repository users receive email about events \(for example, another user commenting on code\)\. You can also change the default settings for your repository, browse its contents, and more\. You can create triggers for your repository so that code pushes or other events trigger actions, such as emails or code functions\. You can even configure a repository on your local computer \(a local repo\) to push your changes to more than one repository\. 

![\[A view of the contents of a repository\]](http://docs.aws.amazon.com/codecommit/latest/userguide/images/codecommit-code-browse.png)

Before you can push changes to a CodeCommit repository, you must configure your IAM user in your AWS account\. For more information, see [Step 1: Initial Configuration for CodeCommit](setting-up-gc.md#setting-up-gc-account)\. 

For information about working with other aspects of your repository in CodeCommit, see [Working with Files](files.md), [Working with Pull Requests](pull-requests.md) , [Working with Commits](commits.md), [Working with Branches](branches.md), and [Working with User Preferences](user-preferences.md)\. For information about migrating to CodeCommit, see [Migrate to CodeCommit](how-to-migrate-repository.md)\.

**Topics**
+ [Create an AWS CodeCommit Repository](how-to-create-repository.md)
+ [Connect to an AWS CodeCommit Repository](how-to-connect.md)
+ [Share a AWS CodeCommit Repository](how-to-share-repository.md)
+ [Configuring Notifications for Events in an AWS CodeCommit Repository](how-to-repository-email.md)
+ [Tagging Repositories in AWS CodeCommit](how-to-tag-repository.md)
+ [Manage Triggers for an AWS CodeCommit Repository](how-to-notify.md)
+ [View CodeCommit Repository Details](how-to-view-repository-details.md)
+ [Change AWS CodeCommit Repository Settings](how-to-change-repository.md)
+ [Synchronize Changes Between a Local Repo and an AWS CodeCommit Repository](how-to-sync-changes.md)
+ [Push Commits to an Additional Git Repository](how-to-mirror-repo-pushes.md)
+ [Configure Cross\-Account Access to an AWS CodeCommit Repository](cross-account.md)
+ [Delete an AWS CodeCommit Repository](how-to-delete-repository.md)
The purpose of this article is to provide guidance and best practices for utilizing the default JIRA workflow.

##Workflow Diagram

![default_diagram](img/workflows/default_diagram.png)

##1. Open

When an issue is created, it is automatically set to the Open state.  As a rule, you should only make changes to the issue's attributes (description, priority, labels, user assignment, etc.) when it is in the Open state.

##2. In Progress

Once an issue has been assigned to you and you begin working on it, you should advance the workflow state to In Progress using the appropriate workflow button.  When an issue is In Progress, you may upload documents, leave comments, etc.  If you need to reassign the issue to another user, you should move it back to the Open state before changing the assignment.

##3. Resolved

If you have completed all necessary work on an issue, advance it to the Resolved state.  In the "Resolution" field, enter a summary of the work that has been completed on the issue.  Once an issue has been marked as Resolved, no changes should be made.  If you need to make changes to a Resolved issue, please move it to the Reopened state and advance it to In Progress before doing so.

##4. Closed

Once an issue is marked as Resolved, project administrators should review the issue to ensure that no further work is required.  If all work has in fact been completed, the project administrator should take the following steps:

  * Move all output documents to the "Final Documents" category within the issue.
  * Download a copy of all final documents.
  * Navigate to the Documents layer for the project and create a folder under the appropriate component (+ ISSEC, if applicable) folder for the task using the following naming convention:

```ruby
<Project Slug>-<Issue Number>: <Issue Summary>

Example:

JIRA-6: Cold Store Symlink is Misconfigured
```

  * Upload the final documents to the folder.
  * Close the issue.

After an issue has been closed, it cannot be modified unless a project administrator advances it to the Reopened state.

##5. Reopened

The Reopened state indicates that an issue was previously either Resolved or Closed, but further work is required.  The Reopened state is analogous to the Open state in its function and associated conventions.  

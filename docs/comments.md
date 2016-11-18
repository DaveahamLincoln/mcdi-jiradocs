The purpose of this guide is to outline best-practice for the usage of JIRA's  comment functionality.

##Atlassian Documentation

[You can view an overview of JIRA's comment functionality here.](https://confluence.atlassian.com/jira064/commenting-on-an-issue-720416302.html)

[You can view an overview of JIRA's @mention functionality here.](https://confluence.atlassian.com/jira064/emailing-an-issue-720416419.html#EmailinganIssue-mentions)

-----

##Best-Practice

JIRA's comment system is incredibly powerful, but to quote Uncle Ben, ["With great power comes great responsibility."](https://www.youtube.com/watch?v=b23wrRfy7SM)

It is important to develop good habits for interacting with JIRA from the beginning, so that things don't spiral out of control and cause problems down the line.  

-----

###Good Habit #1: Simplicity is Elegance

- Try to limit your comments to under 300 words.  This will make it easier for future users to scan through a given issue and get up to speed quickly.
- If you need to include a lot of text, it is usually better to upload the text to the issue as a document and refer to that document in a comment instead.

-----

###Good Habit #2: @Mention Is Your Friend

- When you need to get a user's attention, type the "@"" sign in a comment and select the name of the user you need to notify.  This will /always/ send them an email and HipChat notification, regardless of whether or not they have been added as a Watcher to the issue.  
- If you need a user to do something, please use *active* language in your comment- be explicit about what you need from the user.

This is an example of a very poorly-written comment:

```ruby
"We need to order 10 widgets Joe."

Since Joe was not @mentioned, he will not receive an email or other notifications, and the 10 widgets will
not be ordered.
```

Another example of a poorly-written comment:

```ruby
"We need to order 10 widgets.  @Joe @Steve."

This comment is not clear enough- while Joe and Steve will receive notifications, the comment does not indicate
what they are supposed to do.
```

This is an example of a well-written comment:

```ruby
@Steve, we need 10 widgets, could you put together a PRF and send it to @Joe?  
@Joe, once you receive it, please start the procurement process.

This comment makes good use of the @mention functionality, and is clear on what is needed from each @mentioned user.
```

- If you're ever in doubt about whether or not to @mention a user, you should probably @mention the user.

-----

###Good Habit #3: Edit for Clarity, Not for Content

- You should only modify a comment that you've left to make it clearer or to fix typos.  
- You **should not** edit comments to change their overall meaning or add additional information.
- If you feel the need to add additional information to a comment or change the content, create a new comment instead.

-----

###Good Habit #4: Say What You Mean, Mean What You Say

- You cannot delete comments.  This is by design.
- This means that whatever you write will be saved forever.
- Don't say anything that you don't want to be saved forever.  There are no takebacks.

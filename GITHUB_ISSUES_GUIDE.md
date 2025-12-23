# GitHub Issues: A Complete Beginner's Guide

Welcome! This guide will walk you through everything you need to know about using GitHub Issues.

## What are GitHub Issues?

GitHub Issues are like a to-do list for your project. They help you:
- Track bugs (things that are broken)
- Request new features
- Ask questions
- Organize tasks
- Discuss ideas with your team

Think of Issues as conversation threads where you can discuss work that needs to be done on your project.

## How to Access Issues

1. Go to your repository on GitHub (the main page)
2. Click on the **"Issues"** tab at the top of the page
3. You'll see a list of all open issues (if any exist)

## Creating Your First Issue

### Step-by-Step:

1. **Click the green "New issue" button** (top right of the Issues page)

2. **Write a clear title**
   - Good: "Add contact form to homepage"
   - Bad: "fix stuff"
   - The title should briefly describe what the issue is about

3. **Add a description**
   - Explain the problem or feature in detail
   - If it's a bug, describe:
     - What you expected to happen
     - What actually happened
     - Steps to reproduce the problem
   - If it's a feature request, explain:
     - What you want to add
     - Why it would be useful
     - How it might work

4. **Add labels (optional but helpful)**
   - Labels are like tags that categorize your issue
   - Common labels:
     - `bug` - Something isn't working
     - `enhancement` - New feature request
     - `documentation` - Improvements to docs
     - `question` - Questions about the project
     - `help wanted` - Looking for help
     - `good first issue` - Easy for beginners

5. **Assign the issue (optional)**
   - You can assign the issue to yourself or someone else
   - This shows who is responsible for working on it

6. **Add it to a Project or Milestone (optional)**
   - Projects help organize multiple related issues
   - Milestones are goals with deadlines

7. **Click "Submit new issue"**

## Example Issue

Here's what a well-written bug report looks like:

```
Title: Button on homepage doesn't work when clicked

Description:
When I click the "Sign Up" button on the homepage, nothing happens.

Expected behavior: Should take me to the registration page
Actual behavior: Button does nothing

Steps to reproduce:
1. Go to www.example.com
2. Click the blue "Sign Up" button in the top right
3. Notice nothing happens

Browser: Chrome Version 120
Operating System: Windows 11

Labels: bug
```

## Commenting on Issues

Once an issue is created, you and others can comment on it:

1. Scroll to the bottom of any issue
2. Type your comment in the text box
3. Click "Comment"

You can use comments to:
- Ask for more information
- Suggest solutions
- Report progress
- Share related links or screenshots

## Using Markdown in Issues

GitHub Issues support Markdown formatting:

- `**bold text**` makes **bold text**
- `*italic text*` makes *italic text*
- `` `code` `` makes `code`
- Create lists with `-` or `*`
- Add links: `[text](url)`
- Add images: `![description](image-url)`

### Code Blocks
Use three backticks for code:
````
```
your code here
```
````

### Checklists
Create task lists:
```
- [ ] Task 1
- [x] Completed task
- [ ] Task 3
```

## Managing Issues

### Closing Issues
When an issue is resolved:
1. Scroll to the bottom of the issue
2. Click "Close issue"
3. Optionally add a comment explaining the resolution

### Reopening Issues
If a closed issue needs more work:
1. Open the closed issue
2. Click "Reopen issue"

### Editing Issues
- Click the "..." menu (top right of the issue)
- Select "Edit"
- Make your changes
- Click "Update comment"

## Linking Issues to Code

When you make a commit or pull request, you can reference issues:

- `#123` - Links to issue #123
- `fixes #123` - Automatically closes issue #123 when merged
- `closes #123` - Same as above
- `resolves #123` - Same as above

Example commit message:
```
Add contact form, fixes #42
```

## Searching Issues

Use the search bar at the top of the Issues page:

- `is:open` - Show only open issues
- `is:closed` - Show only closed issues
- `label:bug` - Show only issues with the "bug" label
- `assignee:username` - Show issues assigned to a user
- `author:username` - Show issues created by a user

You can combine filters:
```
is:open label:bug assignee:@me
```

## Issue Templates (Advanced)

You can create templates to help others write better issues. Templates are markdown files stored in `.github/ISSUE_TEMPLATE/` directory.

## Notifications

You'll get notified when:
- Someone comments on your issue
- Someone mentions you with `@username`
- You're assigned to an issue
- An issue you're watching has activity

Configure notifications in your GitHub settings.

## Best Practices

1. **Search first** - Check if someone already reported the same issue
2. **Be specific** - Clear titles and detailed descriptions help
3. **Be respectful** - Remember there are real people reading your issues
4. **One issue per topic** - Don't combine multiple unrelated problems
5. **Follow up** - If someone asks for more info, respond promptly
6. **Close resolved issues** - Keep the issue list clean and up-to-date

## Quick Reference

| Action | How to do it |
|--------|-------------|
| Create issue | Click "New issue" button |
| Comment on issue | Type in comment box, click "Comment" |
| Close issue | Click "Close issue" button |
| Add label | Click gear icon next to "Labels" |
| Assign someone | Click gear icon next to "Assignees" |
| Link to issue | Type `#` followed by issue number |
| Mention someone | Type `@` followed by username |

## Common Questions

**Q: Can I delete an issue?**
A: Only repository owners can delete issues. Usually it's better to close them instead.

**Q: Who can see my issues?**
A: On public repositories, anyone can see issues. On private repositories, only collaborators can see them.

**Q: Can I convert an issue to a discussion?**
A: Yes! Click the "..." menu and select "Convert to discussion" (if discussions are enabled).

**Q: What's the difference between issues and pull requests?**
A: Issues are for discussion and planning. Pull requests are for submitting actual code changes.

## Getting Help

If you're stuck:
1. Check the [GitHub Docs](https://docs.github.com/en/issues)
2. Ask in your project's discussions or issues
3. Search on Stack Overflow
4. Watch GitHub tutorials on YouTube

## Next Steps

Now that you know the basics:
1. Try creating a test issue in this repository
2. Practice adding labels and comments
3. Close the issue when you're done practicing
4. Start using issues to track real work in your projects!

Remember: Everyone was a beginner once. Don't be afraid to experiment and ask questions. The GitHub community is here to help! 🚀

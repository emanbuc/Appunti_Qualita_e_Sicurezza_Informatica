## Introduction

This commit message style guide acts as the guideline to follow in all projects. There are many opinions on the "ideal" style in the world of development. Therefore, in order to reduce the confusion, improve the maintainability of the code and help the future user of the code (yourself included!)  all developers must to this style guide for their projects.

## Commit Messages

### Message Structure

A commit messages consists of three distinct parts separated by a blank line: 

- the title [***Required***]
- body [*Optional*]
-  footer [*Optional*]

The title consists of the type of the message and subject. Please note that the blank line separating three parts are mandatory. Various tools such as  `log`, `shortlog`and `rebase` can get confused if you run the two together. Always put a blank line between title, body an footer.

The layout looks like this:

```
type: subject

body

footer
```

### The Type

The type is contained within the title and can be one of these types:

- **feat:** a new feature
- **fix:** a bug fix
- **docs:** changes to documentation
- **style:** formatting, missing semi colons, etc; no code change
- **refactor:** refactoring production code
- **test:** adding tests, refactoring test; no production code change
- **chore:** updating build tasks, package manager configs, etc; no production code change

### The Subject

Subjects should be no greater than 50 characters, should begin with a capital letter and do not end with a period.

Use an imperative tone to describe what a commit does, rather than what it did. *For example, use **change**;  not changed or changes*.

### The Body

Not all commits are complex enough to warrant a body, therefore it is optional and only used when a commit requires a bit of explanation and context. Use the body to explain the **what** and **why** of a commit, not the how.

When writing a body, the blank line between the title and the body is required and you should limit the length of each line to no more than 72 characters.

### The Footer

The footer is optional and is used to reference issue tracker IDs. Typical usage are:

```
Resolves: #123`
See also: #456, #789
```

### Example Commit Message

```
feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequenses of this
change? Here's the place to explain them.

Resolves: #123
See also: #456, #789
```
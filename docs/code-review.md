# Code Review

Reviewing code can often be more challenging than writing it yourself and it is far better to catch any issues now than before it reaches QA or even worse, production. A [pull request template](https://github.com/Exygy/exygy-base/blob/main/docs/pull-request-template.md) can be used to help certain steps are taken.

Some steps you can take to provde a quality review are:
- When you are reviewing a PR, first look at the issue to ensure you understand the acceptance criteria
- Check that all the test suites passed (yes, there should be tests)
- Check the “did you remember” checkboxes
- Make sure you actually boot up the code and test locally to ensure that it is meeting the acceptance criteria
- Ensure automated tests have been written if possible
- If you don't understand something in the code, please ask. This can often lead to a better solution or at the very least highlight that there should be better comments in the code

As a reviewer on a PR, try not to leave only comments. If the PR requires further discussion or changes, mark it with Requested Changes. If a PR looks good to you or even if there are smaller changes requested that won't require an additional review, mark it with Approved and comment on the last few changes needed. This helps other reviewers better understand the state of PRs at the list view.

The more people who review a PR, the better and try to have at least two people review your work.

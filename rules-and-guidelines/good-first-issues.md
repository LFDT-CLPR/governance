# 🐣 Good First Issue Guidelines

This guide explains what qualifies as a “Good First Issue” and how to create one for new contributors.
All our good first issues are labeled with the `good first issue` label.
An overview of all open good first issues can be found [here](https://github.com/issues?q=is%3Aopen%20is%3Aissue%20org%3ALFDT-CLPR%20archived%3Afalse%20label%3A%22good%20first%20issue%22%20sort%3Aupdated-desc).

## What is a Good First Issue?

A Good First Issue is a task that is suitable for newcomers to the project. It should be:

- **Well-defined**: The issue should have a clear goal and scope.
- **Manageable**: The task should be small enough to be completed in a reasonable amount of time (typically a few hours).
- **Educational**: The issue should help the newcomer learn about the project and its codebase.
- **Non-critical**: The issue should not involve critical functionality or complex dependencies.
- **Documented**: The issue should include all necessary information, such as links to relevant documentation, code examples, and any prerequisites.
- **Welcoming:** The issue should be phrased in a friendly and encouraging way, explicitly inviting newcomers to contribute and making it clear that questions and guidance are welcome.

Examples of Good First Issues:

- Documentation updates (typos, broken links, clarifying setup steps).
- Adding or improving tests for small, isolated components.
- Code style or linting improvements.
- Simple bug fixes with clear reproduction steps.
- Small feature enhancements (e.g., adding a config flag, improving log messages).

## How to Create a Good First Issue

When creating a Good First Issue, the best is to follow our template:

```markdown
## 🆕🐥 First Timers Only

This issue is reserved for people who have never contributed or have made minimal contributions to LFDT-CLPR or any open source project in general.
We know that creating a pull request (PR) is a major barrier for new contributors.
The goal of this issue and all other issues labeled by [**'good first issue'**](https://github.com/issues?q=is%3Aopen+is%3Aissue+org%3ALFDT-CLPR+archived%3Afalse+label%3A%22good+first+issue%22+) is to help you make your first contribution to CLPR.

## 👾 Description of the issue

AT THIS SECTION YOU NEED TO DESCRIBE THE ISSUE IN A WAY THAT IS UNDERSTANDABLE TO NEW CONTRIBUTORS.
YOU MUST NOT ASSUME THAT SUCH CONTRIBUTORS HAVE ANY KNOWLEDGE ABOUT THE CODEBASE OR CLPR.
IT IS HELPFUL TO ADD LINKS TO THE RELEVANT DOCUMENTATION AND/OR CODE SECTIONS.

## 💡 Solution

AT THIS SECTION YOU NEED TO DESCRIBE THE STEPS NEEDED TO SOLVE THE ISSUE.
PLEASE BREAK DOWN THE STEPS AS MUCH AS POSSIBLE AND MAKE SURE THAT THEY ARE EASY TO FOLLOW.
IF POSSIBLE, ADD LINKS TO THE RELEVANT DOCUMENTATION AND/OR CODE SECTIONS.

### 👩‍💻 Implementation

AT THIS SECTION YOU NEED TO DESCRIBE THE TECHNICAL STEPS NEEDED TO SOLVE THE ISSUE.
PLEASE BREAK DOWN THE STEPS AS MUCH AS POSSIBLE AND MAKE SURE THAT THEY ARE EASY TO FOLLOW.
IF POSSIBLE, ADD LINKS TO THE RELEVANT DOCUMENTATION AND/OR CODE.

## 📋 Step by step guide to do a contribution

If you have never contributed to an open source project at GitHub, the following step-by-step guide will introduce you to the workflow.
More information and concrete samples for shell commands for each step can be found in our [CONTRIBUTING.md](https://github.com/LFDT-CLPR/.github/blob/main/CONTRIBUTING.md) file.
A more detailed general documentation of the GitHub PR workflow can be found [here](https://github.com/firstcontributions/first-contributions/blob/master/README.md).

- [ ] **Claim this issue:** Comment below that you are interested in working on the issue
- [ ] **Wait for assignment:** A community member with the given rights will add you as an assignee of the issue
- [ ] **Meanwhile, review:** How [DCO works](https://github.com/cncf/dco2) and how to create signed commits 
- [ ] **Work on the issue:** Follow the detailed description in our [CONTRIBUTING.md](https://github.com/LFDT-CLPR/.github/blob/main/CONTRIBUTING.md) file.
- [ ] **Track:** Test failues, comments and reviews. Make sure to rebase your change to the main branch and resolve any conflicts.
- [ ] **You did it 🎉:** If approved, we will merge the fix in the main branch. Thanks for being part of the CLPR community as an open-source contributor ❤️

***IMPORTANT*** Your pull request CANNOT BE MERGED until you add a changelog entry AND sign your commits each with `git commit -S -s -m "chore: your commit message"` and a GPG key***

## 🤔 Additional Information

If you have any questions about the topic of this issue, please ask us directly by adding a comment below.

A general manual about open-source contributions can be found [here](https://github.com/firstcontributions/first-contributions/blob/master/README.md).
```

Once you created the issue, please make sure to add the `good first issue candidate` label to it.
Please do not add the `good first issue` label directly, as we want to review all issues before adding that label.

## Reviewing Good First Issues Candidates

All candidates for good first issues can be found [here](https://github.com/issues?q=is%3Aopen%20is%3Aissue%20org%3ALFDT-CLPR%20archived%3Afalse%20label%3A%22good%20first%20issue%20candidate%22%20sort%3Aupdated-desc).

The review process for good first issues candidates is as follows:

1. **Verify Issue Completeness:** Ensure the issue contains a clear description, expected outcome, relevant links, and any necessary context or prerequisites.
2. **Check Scope and Complexity:** Confirm that the issue is well-defined, manageable, educational, non-critical, and documented, as outlined above.
3. **Assess Suitability for Newcomers:** Make sure the issue does not require deep project knowledge or access to sensitive resources.
4. **Provide Feedback:** If the issue is missing information or does not meet the criteria, leave a comment with suggestions for improvement.
5. **Label Appropriately:** Once the issue meets all requirements, remove the `good first issue candidate` label and add the `good first issue` label.
6. **Encourage Discussion:** Invite the original author and other contributors to ask questions or clarify details as needed.

By following these steps, maintainers help ensure that good first issues are welcoming and accessible to new contributors.

## Reviewing Pull Requests based on Good First Issues

Please follow these tips when reviewing a PR based on a Good First Issues label:

- **Be welcoming and constructive** – remember many contributors are making their very first PR. Encourage, don’t discourage.
- **Check for clarity** – if something is missing in the PR (tests, docs, formatting), explain why it matters and guide the contributor.
- **Keep scope small** – if the PR goes beyond the intended “good first issue,” help contributors refocus rather than rejecting outright.
- **Celebrate success** – acknowledge even small improvements; positive feedback keeps new contributors engaged.

## Definition of Good First Issue related GitHub labels

The following issues should be part of every repository since they are used in the "Good First Issue" process.

| Label Name | Description | Color |
| :--- | :--- | :--- |
| Good First Issue Candidate | Issues that can become a “good first issue” but need more description/context. | #d6d651 |
| Good First Issue | Issues which are ideal for a first time or new project contributor. | #097023 |
| Non-Code | Issues that can be solved without coding like documentation. | #0ca4a5 |
| Spam | Irrelevant, low-quality, or malicious, created solely for self-promotion, credit, or deception. | #a50104 |

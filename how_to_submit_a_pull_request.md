# How to submit a pull request?

[GitHub has their own guide on how to submit one](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request?tool=webui).

The rest of the document is to guide you on how we handle pull requests for the committee's existing projects.

## Branch and pull request naming

This is how we name branches and their corresponding pull requests: `[label]/[title]`

The label names should be linked to the dominating label of the issue. Usually an issue is dominated either as a:

- `feature`
- `bug`
- `documetation` or `docs`
- `refactor` 

Examples may look like this:

- `feature/new-feature-name`
- `bug/fix-something`
- `docs/ammend-doc`
- `refactor/refactor-something`

![A sample image at the pull requests tab containing closed pull requests that have titles such as "Refactor/footer" or "Feature/create-footer-section".](assets/how_to_submit_a_pull_request/closed_pull_requests.png)

> [!NOTE]
> The first letter of the branch name is capitalized for the pull request title.

## An issue must exist before the pull request

If the issue does not exist, [create one](how_to_create_an_issue.md). Each issue should have one person assigned and one branch should be created for that specific issue.

> [!WARNING]
> We will reject pull requests without binding issues. What you want to push to the main branch should be discussed first and approved by the members of the committee.

![The issues tab should display all issues that are open for contribution. Each issue has one person assigned and one branch is created for that specific issue.](assets/how_to_submit_a_pull_request/issues_tab.png)

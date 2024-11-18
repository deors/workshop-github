# workshop-github

Workshop about GitHub: working with repositories, issues, pull requests, codespaces and actions.

## Introduction

This workshop was first done for dotnetMalaga conference on 2024 Nov 23rd.

The purpose of this workshop is to provide participants with the basic knowledge to work with GitHub repositories and the GitHub Flow, work with Codespaces, and some more advanced topics such as repository custom properties and merge queues. During the workshop, GitHub Actions and workflows will be used but it is not the purpose of the workshop to know how to build them or to understand them in detail.

## How this workshop is structured

This workshop is not intended as a step-by-step guide, but more like a do-it-yourself with the guidance of workshop facilitators and the extensive and fantastic GitHub documentation to help participants to find what they need to complete every step.

The repository will also contain a simple yet exemplar .Net Core application with some basic CI workflows to help participants to review pull requests and to assess whether the code keeps working after changes. It will also contain some exemplar issue forms for typical contributions such as reporting a bug or contributing with code (e.g., for external collaborators).

## Workshop Step 1: General description of GitHub

Contents:

- What is GitHub.
- Brief description of differences between GitHub.com (personal and organizations) and GitHub Enterprise.
- How to work with GitHub: GitHub.com web interface, Git CLI, GitHub CLI, GitHub Mobile app, GitHub Desktop.
- ```Roleplay 1.1```: Navigate through GitHub.com and locate the workshop repository.
- ```Roleplay 1.2 (Optional)```: Install GitHub Mobile app on your phone and/or GitHub Desktop on your workstation/laptop.

Links:

- https://docs.github.com/en/get-started/start-your-journey/about-github-and-git
- https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account
- https://docs.github.com/en/enterprise-cloud@latest/admin/overview/about-github-enterprise-cloud
- https://github.com
- https://git-scm.com/docs
- https://docs.github.com/en/github-cli/github-cli/about-github-cli
- https://docs.github.com/en/get-started/using-github/github-mobile
- https://docs.github.com/en/desktop/overview/about-github-desktop

## Workshop Step 2: Introduction to repositories and issues

Contents:

- Introduction to repositories and issues.
- ```Roleplay 2.1```: Create repositories from scratch and from a template.
- ```Roleplay 2.2```: Create issues from scratch and from issue templates.
- ```Roleplay 2.3```: Distribute participants in groups of 4-5 people. Each group will discuss about the collaborative workflow that will be used for the rest of the workflow.
- ```Roleplay 2.4```: Invite collaborators to repositories. From now Each group of 4-5 people will work on the same repository (from now on it will be refered as the 'group repository').

Links:

- https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories

## Workshop Step 3: Introduction to Codespaces

Contents:

- Introduction to Codespaces.
- ```Roleplay 3.1```: Create and/or open a Codespace for the group repository (it will be configured already).
- ```Roleplay 3.2```: Review the Codespace configuration, access the terminal, and verify that the Codespace is ready for work with the post create command.

Links:

- https://docs.github.com/en/codespaces/overview

### Workshop Step 4: Introduction to GitHub Flow and working with pull requests

Contents:

- Introduction to GitHub Flow and pull requests.
- Introduction to custom properties to decorate repositories with useful metadata.
- Configure customized workflows based on branch protection and rulesets.
- ```Roleplay 4.1```: Create a change and promote it to the default main branch with vanilla configuration (not protected), without and with PRs.
- ```Roleplay 4.2```: Configure a simple GitHub Flow based on a protected main branch and feature branches, and repeat steps done in ```4.1```.
- ```Roleplay 4.3```: Configure a more complex GitHub Flow with an intermediate development branch, and repeat steps done in ```4.1/4.2```.
- ```Roleplay 4.4 (Optional)```: Create a CODEOWNERS file to force approvals from certain teams or individuals depending on the files being changed and/or the target branch.
- ```Roleplay 4.5 (Optional)```: Configure a GitHub Flow supporting two speeds with an intermediate release branch.
- ```Roleplay 4.6 (Optional)```: Configure a GitHub Flow supporting multiple releases (in development or being supported).
- ```Roleplay 4.7```: Add custom properties to the repositories created in ```2.1```, e.g. team name, department (fictitious), target platform (fictitious).
- ```Roleplay 4.8```: Add rulesets at the organization level based on custom properties and validate whether they are propagated as expected to the repositories (repositories would no longer need rulesets at least for the generally agreed workflow rules).
- ```Roleplay 4.9```: Resolving conflicts. Different collaborators will make changes on the same files and they will work through different scenarios to resolve conflicts at the review time.
- ```Roleplay 4.10 (Optional)```: How to undo a change approved and merged by mistake.

Links:

- https://docs.github.com/en/get-started/using-github/github-flow
- https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches
- https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets
- https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
- https://docs.github.com/en/enterprise-cloud@latest/organizations/managing-organization-settings/managing-custom-properties-for-repositories-in-your-organization
- https://github.blog/open-source/git/how-to-undo-almost-anything-with-git/

## Workshop Step 5: Introduction to merge queues

Contents:

- Introduction to merge queues.
- ```Roleplay 5.1```: Use merge queues to manage larger batches of changes. Members of each group will prepare multiple changes and submit PRs simultaneously to understand how merge queues work.

Links:

- https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/configuring-pull-request-merges/managing-a-merge-queue
- https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request-with-a-merge-queue

--- EOF ---

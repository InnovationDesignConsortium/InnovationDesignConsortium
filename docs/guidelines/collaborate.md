---
title: Collaborate
layout: support-page
description: Code collaboration and review are built into the development process with GitHub. Check out our steps for getting started so you can share work, discuss changes, and get feedback in one place.
permalink: /guidelines/collaborate/
---

# **Code Contribution** `</>`

In the realm of the IDC, code contribution is not just about software, but also about the seamless integration of design, construction, and operations. Our codebase represents the culmination of the collective expertise of multiple firms. To ensure efficient collaboration, we follow a systematic workflow. Here's a step-by-step guide to understanding our process of collaboration using pull requests (PRs) and issues:

## **1. Raise an Issue** 📝

Before diving into coding, it's crucial to discuss new features, bugs, or improvements. 

- **Why?** To avoid redundant work, clarify doubts, and set clear objectives.
- **How?** Use the 'New Issue' button in the repository. Clearly describe the problem, the proposed solution, or the new feature you wish to work on. Attach any relevant references or sketches.

## **2. Fork & Clone** 🍴

Once an issue is acknowledged, you can start working on it. But first, create your own copy of the codebase.

- **Why?** To ensure that everyone works on their own versions without affecting the main codebase.
- **How?** Use the 'Fork' button on the top right of the repository. Once forked, clone it to your local machine.

## **3. Create a Feature Branch** 🌿

Always create a new branch for every feature or bugfix. This keeps things organized.

- **Why?** To avoid mixing up different features or fixes in the same branch.
- **How?** Use `git checkout -b your-branch-name`.

## **4. Make Your Changes** ✏️

Now, you're ready to code. Make your changes, ensuring you follow the consortium's coding standards.

- **Why?** Consistent coding practices make collaborative work smoother.
- **How?** After making changes, commit them with a descriptive message using `git commit`.

## **5. Sync and Push** 🔄

Ensure your local branch is updated with the latest main branch. Push your changes to your GitHub fork.

- **Why?** To avoid merge conflicts and ensure smooth integration.
- **How?** First, sync with the upstream: 
  ```bash
  git fetch upstream
  git rebase upstream/main
  ```
  Then, push your branch: `git push origin your-branch-name`.

## **6. Create a Pull Request (PR)** 🚀

Once you're satisfied with your contributions, it's time to integrate them into the main codebase.

- **Why?** To propose your changes to the consortium and get feedback.
- **How?** Go to your forked repo on GitHub, and you'll see a 'New Pull Request' button. Use it to create a PR against the main repository. Link the PR to the issue you initially raised.

## **7. Review & Feedback** 🔍

Your PR will be reviewed by members of the consortium.

- **Why?** To ensure quality, adherence to standards, and compatibility.
- **How?** Engage in the conversation. Address any feedback or changes suggested.

## **8. Merge & Celebrate** 🎉

Once your PR is approved, it will be merged into the main codebase.

- **Why?** Your contribution is valuable and now part of the collective effort.
- **How?** Celebrate your success, and perhaps start on the next issue!


Remember, collaborative coding in the AEC industry is about integrating varied expertise into a unified codebase. Respect, patience, and clear communication are the pillars of our collaborative success.




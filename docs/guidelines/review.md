---
title: Review
layout: support-page
description: Quality is paramount. Get acquainted with our rigorous code review process and understand the criteria that every contribution needs to meet.
permalink: /guidelines/review/
---


# **Code Review Process** `🔍`

Ensuring code quality and consistent standards across our projects is crucial, especially in a consortium where multiple Architecture and Engineering firms collaborate. Our code review process is designed to facilitate collaboration, maintain high coding standards, and enable knowledge sharing.

## **Why Code Reviews Matter**

A rigorous code review process:
- **Upholds Code Quality**: Identifies bugs, inconsistencies, and potential issues early.
- **Promotes Collaboration**: Encourages diverse input and team involvement in code decisions.
- **Facilitates Learning**: Allows members to learn from each other, promoting best practices.

## **Our Review Guidelines**

### **1. Pull Request (PR) Basics**

- **Descriptive Titles**: PR titles should summarize the change effectively.
- **Link to Issue**: Always connect the PR to a related issue for context.
- **Clear Description**: Explain the 'what', 'why', and 'how' of your changes.

### **2. Writing Reviewable Code**

- **Small Changes**: Break down your PRs into smaller, logical chunks. Each PR should have a specific focus.
- **Comment Code**: Add comments to clarify complex sections or decisions.
- **Run Tests**: Ensure all tests pass before requesting a review.

### **3. Reviewer Responsibilities**

- **Timeliness**: Aim to complete reviews within a set time frame (e.g., 48 hours).
- **Constructive Feedback**: Provide clear, actionable feedback. Avoid vague criticisms.
- **Ask Questions**: If something is unclear, ask the author to clarify. It may reveal areas that need more comments or refactoring.

### **4. Handling Feedback**

- **Be Receptive**: Remember, feedback is about the code, not the coder. It's an opportunity to learn and improve.
- **Respond Promptly**: Address review comments, and push your changes or clarify with further comments.
- **Merge Conditions**: Ensure that a certain number of approvals are secured before merging, and all discussions are resolved.

## **Tools We Use**

Our consortium utilizes various tools to facilitate the code review process:

- **[GitHub](https://github.com/)**: For hosting our repositories, raising PRs, and conducting reviews.
- **[Github Actions](https://github.com/features/actions)**: To run tests and deploy code automatically when PRs are raised. For example, [the page you are reading](https://github.com/InnovationDesignConsortium/InnovationDesignConsortium/actions/workflows/pages/pages-build-deployment) is deployed through a github action. Check it out for an example!
- **[Static Code Analysis Tool]**: To automatically check code quality. *(Replace with the tool we pan to use)*

---

## **Conclusion**

The code review process is a team effort. It requires patience, open-mindedness, and a commitment to learning and collaboration. Together, we'll continue to maintain high coding standards and produce outstanding projects.


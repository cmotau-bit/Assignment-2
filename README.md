# Assignment-2

## Explain the fundamental concepts of version control and why GitHub is a popular tool for managing versions of code. How does version control help in maintaining project integrity?
Fundamental Concepts of Version Control
Repositories (Repos): A repository is a storage space where your project lives. It can either be local (on your computer) or remote (on a server). A version control system keeps track of all the changes made to the files in the repository.

Commits: A commit is like a snapshot of your project at a particular point in time. Every time you make a change to the code, you "commit" those changes to the repository, along with a message describing what was changed.

Branches: Branches allow multiple people or teams to work on different features or bug fixes independently without affecting the main codebase (usually called the "main" or "master" branch). You can create a branch, make changes, and then merge it back into the main branch when ready.

Merging: After working on a branch, you can merge your changes back into the main project. If multiple people have edited the same file in different ways, version control systems help merge these changes together, highlighting conflicts to resolve.

Tags: Tags are used to mark specific points in the project history, like release versions (e.g., v1.0, v2.0). This helps track important milestones in the project.

History: Every commit creates a history of changes that can be revisited. This is crucial for understanding what was changed, why it was changed, and how the project evolved over time.
GitHub is one of the most popular tools for managing versions of code, particularly because it builds on Git, a distributed version control system. GitHub adds a web-based interface and collaboration features on top of Git. Here’s why GitHub is so widely used:

Collaboration: GitHub makes it easy for multiple developers to collaborate on a single project. It has features like pull requests, which allow team members to propose changes and have them reviewed before being merged into the main codebase.

Remote Repositories: GitHub hosts remote repositories in the cloud, meaning the project’s code is accessible from anywhere. Developers can clone a repository, work locally, and then push changes back to GitHub for others to access.

Branching and Merging: GitHub makes it easy to manage branches and merge them. This feature is key for managing multiple versions of a project or working on separate features simultaneously.

Version History: GitHub provides a clear and visual representation of the entire project history, including commits, branches, and merges. This makes it easy to track changes over time and see who made what changes.

Issue Tracking: GitHub has an integrated issue tracker, so teams can log bugs, features, and improvements. This helps prioritize work and ensures tasks are tracked alongside the code.

Pull Requests and Code Review: GitHub’s pull request system facilitates code reviews, allowing others to comment on your code before it's merged. This ensures that the code meets the team’s quality standards.

Integration with Other Tools: GitHub integrates with many tools like continuous integration systems, project management apps, and deployment pipelines, streamlining development processes.
How Version Control Helps Maintain Project Integrity
Backup and Recovery: Version control acts as an automatic backup. If something goes wrong, you can roll back to a previous version of the codebase. This is crucial for preventing the loss of work.

Collaboration Without Conflicts: When working in a team, version control allows different team members to work on separate parts of the project without stepping on each other's toes. Changes can be made in parallel, and version control tools handle merging changes when necessary.

Audit Trail: Every change is recorded with a commit history. This creates an audit trail, so if something breaks, you can track exactly what was changed, who made the change, and why. This makes debugging much easier.

Branching for Features and Bug Fixes: Teams can work on features or bug fixes independently using branches. This ensures that the main project remains stable while developers work on new features, without introducing bugs or breaking existing functionality.

Versioning and Releases: Version control allows teams to manage versions and releases. You can track when new versions were created, what features were added, and which bugs were fixed, all of which ensures stability and progress over time.

Conflict Resolution: When two developers change the same line of code, version control helps identify conflicts and lets developers resolve them before merging. This ensures that the final codebase is consistent and functional.

## Describe the process of setting up a new repository on GitHub. What are the key steps involved, and what are some of the important decisions you need to make during this process?
Sign in to GitHub and go to the New repository page.
Fill in your repository name, description, and visibility settings.
Choose whether to initialize with a README, .gitignore, and/or a license.
Create the repository.
Clone the repository to your local machine.
Start adding and committing files to the repository.
Key Decisions and Considerations
Visibility (Public vs. Private):

Public repositories are great for open-source projects and sharing code with the community.
Private repositories are useful when you want to keep the code confidential, for personal or team-based work.
Initializing with a README:

It's a good practice to initialize the repository with a README.md file. It gives the project a starting point, and you can always edit this file later to include more information about the project.
Choosing a License:

If you're making your project public, you need to decide on a license. The choice of license can affect how others can use your code. Open-source licenses (like MIT, Apache, or GPL) encourage collaboration and sharing, while proprietary licenses limit usage to specific parties.
.gitignore:

You should consider what files or directories to ignore (such as dependencies, IDE configurations, etc.). GitHub provides templates for many popular languages, but you can customize it further based on your needs.

## Discuss the importance of the README file in a GitHub repository. What should be included in a well-written README, and how does it contribute to effective collaboration?
The README file is one of the most important documents in a GitHub repository because it serves as the first point of contact for anyone interacting with the project—whether they are contributors, users, or collaborators. A well-written README helps users and developers understand the purpose, functionality, and setup process of the project. It also contributes significantly to effective collaboration by providing clear guidelines and context for everyone involved.

Importance of the README File
Provides Context and Understanding: The README gives a concise explanation of the project’s purpose, functionality, and scope. This context is crucial for new developers or contributors who are exploring the project for the first time.

Guides Setup and Installation: It offers instructions on how to install, configure, and run the project. Without this, collaborators or users may struggle to get the project up and running, especially if they are unfamiliar with the setup process.

Facilitates Contribution: A good README provides guidance on how people can contribute to the project, what the contribution process is, and any specific guidelines for submitting issues or pull requests. This is crucial for open-source projects or collaborative development.

Acts as Documentation for Users: For users of your project, the README serves as the main source of documentation. It explains how to use the software, what its features are, and how to troubleshoot common problems.

Encourages Open-Source Participation: A well-structured README encourages others to contribute to the project. By laying out clear instructions and project goals, you increase the likelihood of others feeling confident in getting involved.

Helps with Discoverability: When others search for repositories, a clear README can make your project stand out. If the README is well-organized, it’s easier for people to quickly determine if your project is relevant to them.
What Should Be Included in a Well-Written README?
A well-written README typically includes the following key sections:

Project Title and Description:

The title should be clear and concise, reflecting the project’s purpose.
A brief description of what the project does and what problem it solves. This is where you "sell" your project and explain why it exists.
Installation Instructions:

Detailed, step-by-step instructions on how to install the project locally or on a server. This should include prerequisites (e.g., software, libraries, dependencies) and commands or steps needed to set up the project.
License Information:

Include information about the licensing of the project. This explains how others can legally use, modify, and distribute the code. Most open-source projects use licenses like MIT, GPL, or Apache 2.0.
Contact Information:

Provide details on how to contact the project maintainers for support or feedback (email, GitHub issues, etc.). This fosters communication and ensures that users and collaborators know how to get in touch with questions or problems.
Project Roadmap or Future Plans (Optional):

If applicable, mention what features or improvements you plan to implement in the future. This helps contributors understand the direction of the project and can attract contributors who are interested in specific areas.
Acknowledgements (Optional):

Recognize contributors, libraries, or tools that helped with the project. This fosters a sense of community and gives credit where it’s due.
How the README Contributes to Effective Collaboration
Clear Communication: The README acts as a centralized place for project details. By documenting how the project works, how to use it, and how to contribute, it minimizes confusion and ensures that everyone is on the same page. This is especially important in collaborative, multi-developer environments.

Onboarding New Contributors: When new contributors come on board, the README gives them the context they need to understand the project quickly. Without this, they would have to ask the existing team for every detail, slowing down the collaboration process.

Reducing Redundancy: By providing clear instructions, common questions, and guidelines in the README, you reduce the number of times team members have to explain the same thing. It ensures consistency in how people set up and interact with the project.

Encouraging Consistent Practices: When the README clearly outlines processes for code contributions, formatting, and testing, it helps set standards for everyone involved in the project. This consistency reduces errors and makes collaboration more efficient.

Improving Project Adoption: A thorough README that makes the project easy to understand and use increases the likelihood of others adopting it or contributing to it. This can lead to a larger, more active community and faster development.

## Compare and contrast the differences between a public repository and a private repository on GitHub. What are the advantages and disadvantages of each, particularly in the context of collaborative projects?
In the context of collaborative projects, a public repository is better if you want to encourage open contributions from a large community and make the project available for anyone to use. A private repository is more appropriate for internal, sensitive, or business-critical projects where you want to manage access strictly and avoid sharing the code with the public.
Public Repository
Visibility - Open to everyone, public access to code
Collaboration- Open collaboration, anyone can contribute
Security- Exposed code, potential for misuse or exploitation
Cost- Free, no cost for public repos
Private Repository
Visibility - Restricted to invited collaborators, not searchable
Collaboration- Controlled collaboration, only authorized users can access
Security- More secure, code is only visible to authorized users
Cost- Can be free or paid, depending on the plan and collaborators

## Detail the steps involved in making your first commit to a GitHub repository. What are commits, and how do they help in tracking changes and managing different versions of your project?
Commit: A snapshot of changes in the project. Each commit is identified by a unique ID and includes a commit message.
Commit Message: A short description of the changes made in the commit.
Tracking Changes: Commits provide a history of the project, allowing you to track progress, understand changes, and revert if necessary.
Version Control: Commits allow you to manage and navigate different versions of your project. You can roll back to previous states if something breaks.
Collaboration: Commits help manage collaboration, allowing multiple contributors to work on a project without overwriting each other's work.
What Is a Commit?
A commit is a snapshot of changes to your files at a specific point in time. When you commit, Git records which files were changed, added, or deleted, along with a message describing the change. Each commit is given a unique identifier (commit hash), which allows you to track and reference the history of changes made to the project.
Why Are Commits Important?
Tracking Changes:
Commits act like a timeline of your project. They allow you to track how your project has evolved over time, see who made which changes, and understand why certain decisions were made (based on the commit messages).
Version Control:
Git keeps track of all changes and allows you to revert to a previous commit if something goes wrong. This version control system ensures that you never lose work, and you can always go back to a stable state.
Collaboration:
In collaborative projects, commits help multiple contributors work together without overwriting each other's work. When working with branches and pull requests, commits allow you to isolate and test new features before merging them into the main codebase.
Auditability:
Commit messages provide a historical record of changes. This is important for debugging, understanding the evolution of features, or reviewing the reasons behind specific changes. A good commit history makes it easier to diagnose and fix bugs and ensure that contributions are well-documented.
Branching and Merging:
Git allows you to create branches to work on separate tasks without affecting the main project. Each commit is tied to a branch, and when branches are merged, the history of commits is preserved. This ensures a clean workflow when multiple people are working on different parts of the codebase.


## How does branching work in Git, and why is it an important feature for collaborative development on GitHub? Discuss the process of creating, using, and merging branches in a typical workflow.
Branching in Git is a key feature for efficient, collaborative development, especially in environments like GitHub where teams of developers often work on different features simultaneously. It allows developers to work independently, track changes separately, and merge their contributions back into the main project with minimal conflicts. By creating, using, and merging branches, teams can maintain a clean, stable codebase while continuing to innovate and develop new features.

Benefits of Branching in GitHub for Collaboration
Isolated Development:
Branching allows developers to work on new features or bug fixes in isolation, without worrying about breaking the main codebase.
Collaboration Without Conflict:
Each developer works on their own branch, and Git’s merging system ensures that changes are brought together without overwriting anyone’s work. Conflicts can be resolved when merging.
Code Reviews:
Branching enables easy pull requests, which facilitate code reviews, testing, and validation before merging changes into the main codebase.
Parallel Workflows:
Multiple developers can work in parallel on different branches, speeding up development and allowing for task-based workflows.
Easy Rollback:
If something goes wrong with a branch, you can simply delete it, roll back changes, or revert to a previous commit, without affecting the main codebase.

Important feature for collaborative development on GitHub:
Clone the repository: Each collaborator clones the repository to their local machine using git clone.
Create a new branch: Collaborators create a new branch for each task (feature, bug fix, etc.) using git checkout -b.
Make changes and commit: Developers make changes, stage them (git add), and commit them (git commit).
Push the branch: The branch is pushed to GitHub using git push origin <branch-name>.
Create a pull request (PR): Once the changes are pushed, the developer creates a PR on GitHub to merge the branch into the main branch.
Review and merge: Other team members review the PR, suggest changes, and approve it. Once approved, the branch is merged into the main branch.
Sync with the main branch: After merging, collaborators can update their local main branch with the latest changes.

## Explore the role of pull requests in the GitHub workflow. How do they facilitate code review and collaboration, and what are the typical steps involved in creating and merging a pull request?
Pull requests are essential to the GitHub workflow and serve as the cornerstone for collaboration, code review, and quality assurance in software development. They provide a structured way to propose, discuss, review, and merge changes, making them an indispensable tool for maintaining code quality and promoting collaboration, especially in teams working on shared projects. Through the pull request process, developers can ensure that new code integrates smoothly with the existing codebase, enhancing the overall integrity and maintainability of the project.
Steps
1. Create a New Branch for Your Changes
2. Create a Pull Request
3. Code Review and Discussion
4. Continuous Integration and Testing
5. Approve and Merge the Pull Request
6. Clean Up After the Merge
7. 
## Discuss the concept of "forking" a repository on GitHub. How does forking differ from cloning, and what are some scenarios where forking would be particularly useful?
The Concept of "Forking" a Repository on GitHub
Forking a repository on GitHub is a process that creates a personal copy of someone else's repository. This copy lives in your GitHub account and is independent of the original repository, meaning you can make changes without affecting the original project.
When you fork a repository, GitHub creates a new copy under your account, which you can modify as you wish. This is especially useful in open-source projects or when collaborating with other developers. After making changes to the forked repository, you can later submit a pull request to the original repository, proposing the changes you made.
Forking vs. Cloning
While both forking and cloning create copies of a repository, they serve different purposes and are used in different contexts. Here's how they differ:

1. Forking
Purpose: Forking is primarily used to contribute to an existing project, especially in the context of open-source development. It creates a personal copy of a repository under your GitHub account.
Where it's done: Forking is done on GitHub's website, and it creates a separate copy of the repository that you control.
Collaboration: After forking a repository, you can make changes and propose them back to the original repository through a pull request.
Repository Ownership: The forked repository is fully under your GitHub account, and you have complete control over it. The original repository remains unchanged unless you create a pull request that is merged.
2. Cloning
Purpose: Cloning is used to create a local copy of a repository on your computer so you can work with it directly from your development environment.
Where it's done: Cloning is done on your local machine using Git commands like git clone to download the repository from GitHub (or any other Git hosting service).
Collaboration: After cloning, you can modify the files locally, commit the changes, and push them back to the original repository or to a forked repository (if you have one).
Repository Ownership: Cloning doesn't change ownership; you're simply copying the project to your local machine. You can’t push changes directly to the original repository unless you have write access.

Forking is especially useful in the following scenarios:
1.Contributing to projects that you don’t own: If you want to contribute to an open-source project, but you don’t have write access to the repository, forking is the way to go. Once you fork the repository, you can make your changes in the forked version, and then propose your changes via a pull request to the original repository.
2.Experimenting with a Repository
Isolated testing and experimentation: Forking is useful when you want to experiment with new ideas, features, or changes without affecting the original codebase. Forking gives you a full version of the project that you can work on, make mistakes in, and try out new things.
3.Developing a Personal Version of a Repository
Creating a personal version of a project: If you like a repository but need to customize it for your personal use, forking is a great way to create your own version of the repository that you can modify freely. You can make changes that are specific to your needs without worrying about conflicting with the original project.
4.Maintaining a Long-Term Independent Version
Creating long-term custom versions: In some cases, you might fork a project to maintain a long-term, custom version of the repository, especially if the project has evolved in a direction you don’t want to follow. This can be particularly useful in enterprise environments where a project might need to be tailored to specific business needs.

## Examine the importance of issues and project boards on GitHub. How can they be used to track bugs, manage tasks, and improve project organization? Provide examples of how these tools can enhance collaborative efforts.
GitHub's Issues and Project Boards are essential tools for managing project tasks, tracking bugs, organizing work, and enhancing collaboration among developers. These tools are used for tracking bugs, assigning tasks, prioritizing work, and ensuring that a project is well-organized. Together, they streamline project management, improve communication, and facilitate better collaboration among team members.
 Issues: Tracking Bugs and Managing Tasks
What are Issues?
Issues on GitHub are used to track bugs, feature requests, task assignments, and other actionable items within a project. They can be used by developers to communicate problems or tasks that need to be addressed, and they allow project maintainers to track progress over time.
Each issue can include:
A title and description outlining the problem or task.
Labels to categorize or prioritize the issue (e.g., "bug," "enhancement," "help wanted").
Assignees to assign team members responsible for addressing the issue.
Milestones to associate the issue with a specific project goal or deadline.
Comments for discussions, clarifications, and updates on the issue.
References to commits, pull requests, or other issues, allowing for easy tracking of related work.
How Issues Help with Tracking Bugs and Managing Tasks
Bug Tracking:

Issues provide a centralized place for tracking bugs or problems within the project. A team can assign issues to specific developers, add details, and follow the progress until the issue is resolved.
Example: If a user reports that a button is broken in a web application, an issue can be created to track the bug. The issue can be tagged as "bug," assigned to a developer, and updated with progress as the bug is fixed.
Task Management:
Issues can represent tasks that need to be completed in the project. For example, you can create an issue to implement a new feature or update documentation, then assign it to the appropriate developer or team member.
Example: For a feature like "Add user authentication," a task is created as an issue and assigned to the developer working on that functionality. As the work progresses, the issue is updated with comments and links to pull requests or commits.
Discussion and Collaboration:
Issues provide a space for team members to discuss bugs, features, or any other concerns. This enables collaborative problem-solving and ensures that everyone on the team has visibility into what’s being worked on.
Example: If a developer is unsure about the best way to implement a feature, they can use the issue comments to ask for advice or clarification from the team.
Progress Tracking:
Each issue can be linked to specific milestones or labels to track its status or priority. Milestones are particularly useful for setting project timelines and tracking progress toward major project goals or releases.
Example: You might have a "v1.0 release" milestone, with several issues grouped under that milestone to track progress toward completing version 1.0 of the project.
Benefits of Issues and Project Boards for Collaborative Efforts
Enhanced Communication:

Issues provide a place for team members to discuss bugs, tasks, or features, fostering transparent communication about the project's status.
Project boards visually show the progress of work, ensuring that everyone on the team is aware of the current state of the project.
Task Ownership:

By assigning issues and pull requests to specific team members, GitHub makes it clear who is responsible for each task, reducing ambiguity and ensuring accountability.
Prioritization:

Teams can prioritize tasks based on importance, deadlines, or project needs, ensuring that critical work gets done first.
Using labels like “high priority” or “critical” helps identify which issues require immediate attention.
Tracking Progress:

Project boards allow teams to visually track progress in real time, helping to prevent bottlenecks and keeping the project moving forward.
With the ability to associate issues with milestones, teams can ensure that they’re on track to meet release goals.
Seamless Collaboration:

Issues and project boards enhance collaboration by allowing multiple developers to work on different tasks simultaneously. Team members can check the status of other tasks, discuss potential conflicts, and provide feedback on each other's work.

## Reflect on common challenges and best practices associated with using GitHub for version control. What are some common pitfalls new users might encounter, and what strategies can be employed to overcome them and ensure smooth collaboration?
Common Challenges for New Users
1. Confusing Git Concepts
Challenge: Git, and by extension GitHub, relies on concepts like commits, branches, merges, and rebases, which can be confusing for newcomers. Understanding the difference between git clone, git pull, and git fetch, or how to resolve merge conflicts, can be a steep learning curve.

Strategy:

Educate Yourself: Take the time to understand basic Git concepts. GitHub offers resources, and there are many tutorials available to explain concepts like branching, merging, and commits. Resources like Git documentation or interactive tutorials (e.g., GitHub Learning Lab) are extremely helpful.
Start Simple: Begin by using Git for basic tasks, like cloning a repo, making commits, and pushing changes. Gradually introduce more advanced workflows like branching and pull requests as you get comfortable.
Use Git GUIs: If the command line feels overwhelming, consider using Git GUI tools (like SourceTree, GitHub Desktop, or Visual Studio Code’s Git integration) to visualize actions like commits and branches.
2. Merge Conflicts
Challenge: Merge conflicts occur when two or more developers modify the same lines of code in a file. Resolving merge conflicts can be time-consuming and tricky, especially for users unfamiliar with Git’s merge tools.

Strategy:

Commit Frequently: Small, frequent commits reduce the risk of conflicts by limiting the number of changes in any one commit.
Pull Frequently: Regularly pull changes from the main branch to keep your branch up to date. This reduces the likelihood of conflicts when it’s time to merge.
Use Git's Merge Tools: Git provides built-in merge tools to resolve conflicts. Tools like git mergetool or GUI-based merge conflict resolvers can help you manually choose between competing changes.
3. Not Using Branches Properly
Challenge: New users may either avoid branching or use it improperly, which can lead to issues like accidental commits to the wrong branch or difficulty tracking which features have been completed.

Strategy:

Use Feature Branches: Create a new branch for each feature or bug fix. This keeps the main branch clean and reduces the chance of conflicting changes.
Example: git checkout -b feature/login-system to work on the login feature. Once completed, you can submit a pull request to merge it back into the main branch.
Stay Organized: Use clear and consistent naming conventions for branches (e.g., feature/, bugfix/, or hotfix/).
Merge Frequently: Regularly merge your feature branches back into the main branch (after review) to ensure that your branch doesn’t diverge too far from the latest changes.
4. Not Using Commit Messages Effectively
Challenge: New users may write vague or unclear commit messages, making it hard for others (or even themselves) to understand what a particular commit does. Poor commit messages lead to confusion and difficulty in tracking project history.

Strategy:

Write Clear, Descriptive Commit Messages: Each commit message should explain why the change was made, not just what was changed. This is useful for code review and future reference.
Example of a good message: "Fix bug where user login failed when entering incorrect password format."
Example of a bad message: "Fixed stuff."
Follow a Commit Message Convention: You can follow established guidelines like Conventional Commits or simply agree with your team on a consistent style.
5. Not Properly Managing Permissions (for Collaborators)
Challenge: Teams might encounter issues with access control and permissions when working on private repositories. Confusion about who can commit, who can review pull requests, and who has administrative control can slow down progress.

Strategy:

Use Teams and Roles: For organizations, GitHub provides the ability to create teams with different access levels. Ensure that you assign appropriate roles (Admin, Write, Read) based on the level of involvement each user has with the project.
Use Pull Requests for Code Review: Only give write access to trusted collaborators. Otherwise, rely on pull requests (PRs) for code review before merging contributions to the main branch.
Best Practices for Smooth Collaboration on GitHub
1. Embrace the Pull Request (PR) Workflow
Strategy:

Use pull requests to propose changes rather than pushing directly to the main branch. This ensures code is reviewed and tested before integration, and it maintains the integrity of the main codebase.
Code Reviews: Always request reviews from team members to ensure the quality of code and foster collaboration.
PR Templates: Use pull request templates to ensure contributors provide relevant context for their changes, making the review process smoother.
2. Use Issues for Task Management
Strategy:

Track Bugs and Features with Issues: Use GitHub issues to track bugs, feature requests, or tasks that need to be done. Issues can be assigned to team members, labeled for priority, and linked to pull requests.
Create Milestones: Group related issues into milestones to track progress towards specific goals (e.g., a feature release or a sprint).
Use Labels: Label issues with categories like bug, enhancement, wontfix, help wanted, and question to help organize and prioritize tasks.
3. Maintain a Clear Branching Strategy
Strategy:

Follow a structured branching strategy, such as Git Flow or GitHub Flow, depending on the complexity of your project. This helps organize your work and avoid conflicts.
GitHub Flow: For simple projects, use GitHub Flow, where all feature development happens in branches, and every change is made through pull requests.
Git Flow: For more complex projects, Git Flow involves multiple long-lived branches (e.g., develop, master, feature, release, hotfix) to manage releases, bug fixes, and features.
4. Keep Repositories Clean
Strategy:

Use .gitignore: Ensure you include a .gitignore file in your repository to avoid committing unnecessary files (e.g., IDE configurations, temporary build files).
Archive Old Branches: After merging, delete old branches to keep the repository organized. This prevents clutter and keeps the focus on active work.
Refactor and Organize Files: As the project grows, periodically refactor the codebase to ensure it remains clean and well-organized. This can be tracked through issues and pull requests.
5. Communicate Effectively
Strategy:

Use Descriptive Commit and Issue Messages: Clear communication is key. Commit messages should be descriptive, and issues should include enough information for others to understand the task or bug.
Document the Process: Use README files, wikis, and issue templates to document the process, project requirements, and workflow. This helps onboard new collaborators and ensures consistency across contributions.
6. Regularly Sync Your Forks (for Open Source Projects)
Strategy:

If you’re contributing to an open-source project by forking it, regularly pull updates from the original repository to keep your fork in sync. This ensures that you’re working with the latest code, reducing the risk of conflicts.
Example: Use git remote add upstream to add the original repository as a remote, and git fetch upstream to pull changes.


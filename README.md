Agile Methodology and Development
Overview of Version Control System Using GIT
Overview of Version Control Systems (VC)
A Version Control System (VCS) is a tool that helps manage changes to source code and other collections of information over time. It tracks the history of changes, enabling multiple developers to collaborate efficiently on a project. A VCS allows you to revert files back to a previous state, compare changes over time, and see who last modified something that might be causing a problem.

Why is Version Control Needed?
Collaboration: VCS enables multiple developers to work on the same project without interfering with each other's work. Changes made by different team members can be integrated seamlessly.
History Tracking: Every change made to the project is logged, providing a detailed history of modifications. This is crucial for understanding the evolution of the project and for debugging.
Backup and Recovery: VCS acts as a backup system. If something goes wrong, you can revert to a previous stable version of the project.
Branching and Merging: VCS allows developers to create branches for new features or bug fixes. These branches can be merged back into the main codebase once they are stable, ensuring that the main codebase remains functional.
Audit Trail: A VCS provides an audit trail of changes, including who made each change and why. This can be useful for project management and accountability.
Introduction to Git
Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Unlike centralized version control systems (CVCS), Git does not rely on a central server. Instead, every developer has a complete copy of the entire project history on their own machine, enabling them to work offline or remotely with the same efficiency as if they were connected to the main server.

Centralized vs. Distributed Version Control Systems
Centralized Version Control Systems (CVCS):

A single server contains all the versioned files, and clients check out files from this central place.
Examples: Subversion (SVN), Perforce.
Pros: Simple to understand, single source of truth.
Cons: Single point of failure, slower for distributed teams, limited offline work.
Distributed Version Control Systems (DVCS):

Every developer has a local copy of the entire project history.
Examples: Git, Mercurial.
Pros: Enhanced redundancy, better performance for distributed teams, supports offline work, easier branching and merging.
Cons: More complex to understand initially, larger disk usage.

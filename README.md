git-mikado
==========

Not ready for use!!!

A git extension to help when using the Mikado Method.

usage: git mikado subcommand

Available subcommands are:
   * new       Create a Mikado Goal, the root of the restructuring, represented by a new branch.

Planned subcommands are:
   * prereq    Create a new prerequisite branch for the current. Stashes all changes in this branch, creates new branch and switches to it.
   * done      Mark the current node as done. Will merge it back to its origin and any node marking it as a prerequisite
   * cancel    Remove the current branch, and all of its prerequisites.
   * prune     Delete all branches marked as done.
   * graph     Create a graph (png) representing your Mikado graph.
   * depend    Make current goal depend on a prerequisite that this goal didn't originate. 



# node-project-runner

A project runner that listens for any changes on a directory.

Changes include: Changes to a file, deleting a file or adding a file.

When in the directory where you want to listen to changes - use the command: watchit [filename]

[filename] = the file that will be executed after any change has been detected in the directory.

If no [filename] is given, the runner will look to run index.js in the directory


tmc-universal-template
======================

This is the exercise template for universal TMC projects. The main curiosity in this template is the .universal folder. Most of that folder's content are actually not visible to the student.

The student sees:
- Whatever lies inside the root folder (other than .universal)
  - However, note that some of those files might be overwritten by files in .universal/exercise-stubs
- .universal/controls is also visible

The control scripts are quite simple in nature. In most cases they just use a project management tool like maven or rake, and are kept quite small. A small parser is required for each new project type, however, to be able to obtain points.

Scripts
=======

# get-points
This script should produce the following:
testname1 p1 p2 p3 p4 ...
testname2 p1 p5 p2 p8 ...
...
Here p stands for pointname. Any number of pointsnames can follow a test's name.

![Lab Tests](../../actions/workflows/cc-lab-passing.yml/badge.svg)

# Instructions

Each sub-directory has an exercise for you to complete. Each exercise subdirectory is prefixed with the string `part-`. The subdirectory contains a README.md which explains the requirements for the exercise.

Start with `part-1` and move through the problems in numerical order. Only move on to the next part when you have completed the current part you are working on.

In order for your instructors to know who worked on the project, there is a file in your repository named `AUTHORS.md` which shall contain each student's name, CSU email address, and GitHub user name. This file is located at the root level of your repository.

The file `AUTHORS.md` is empty so you and your partner will fill it in. Let's imagine your name is Tuffy Titan and your partner's name is Peter Anteater. Tuffy's email address is tuffy@csu.fullerton.edu and Peter's email address is peter@csu.fullerton.edu. Peter's GitHub user name is `anteater` and Tuffy's GitHub user name is `tuffytitan`. With this information, the contents of the `AUTHORS.md` file will look like the following example:

```
Tuffy Titan
tuffy@csu.fullerton.edu
@tuffytitan
Peter Anteater
peter@csu.fullerton.edu
@anteater
```

The order matters and it is part of your grade. Please make your `AUTHORS.md` file match the same pattern as the one given here.

Please adhere to the [Google C++ coding style](https://google.github.io/styleguide/cppguide.html).

When writing git log comments, please make them descriptive and meaningful. For example, "Fixed my typo that stopped it from compiling." or "Smashed the bug in my main function." are descriptive. Log comments such as "Done" or "upload" are of poor quality.

Each exercise subdirectory has its own [Makefile](https://en.wikipedia.org/wiki/Makefile) which you may use to build and test your progress. Each Makefile has the following targets:

* all: builds the project
* clean: removes object and dependency files
* spotless: removes everything the clean target removes and all binaries
* format: outputs a [`diff`](https://en.wikipedia.org/wiki/Diff) showing where your formatting differes from the [Google C++ style guide](https://google.github.io/styleguide/cppguide.html)
* lint: output of the [linter](https://en.wikipedia.org/wiki/Lint_(software)) to give you tips on how to improve your code
* authors: check to make sure your AUTHORS.md file exists and is formatted properly
* test: run tests to help you verify your program is meeting the assignment's requirements. This does not grade your assignment.

To build the program use the `make` command. The Makefile's default target is to build `all`.

# Rubric

Each exercise is worth 15 points. There are 2 parts so there is a total of 30 points possible. Each program must compile before it is graded. _Submissions that do not compile shall be assigned a zero grade._

A detailed rubric is assigned to each lab in Canvas. The rubric in Canvas will specify points and criteria.

Generally, each lab part is assessed on at least two dimensions. A detailed rubric is assigned to each lab in Canvas. The descriptions below serve as a general reminder of how labs are assessed.

* Functionality (approximately 9 points): Your submission shall be assessed for the appropriate constructs and strategies to address the exercise. A program the passes the instructor's tests completely receives full marks for this dimension. A program that partially passes the instructors tests receives partial-marks. A program that fails the majority or all the tests receives no marks.

* Format & Readability (approximately 6 points): Your submission shall be assessed by checking whether your code passess the style and format check, as well as how well it follows the proper naming conventions, and internal documentation guidelines. Git log messages are an integral part of how readable your project is. _Failure to include a complete `AUTHORS.md` file forfeits all marks._

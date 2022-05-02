# Recursion Exercise

A little dive into understanding recursion in Java.

## Instructions

Choose one of the two given fractal generating programs and document it thoroughly, explaining how it works.

### Javadoc comments

Documentation must include full Javadoc comments, including:

- the `author` tag should indicate "`@author Foo Barstein, with comments by Baz Bumberger (bf1234)`". Replace `"Baz Bumberger`" with your own name, and replace "`bf1234`" with your own NYU Net ID.
- a description of the the entire program, and complete descriptions of all instance and class variables and methods.
- for instance or class variables, be sure to explain how that variable is used throughout the rest of the program.
- for each method, be sure to include a plain description of the method's purpose, and a detailed description of the process by which achieves that purpose.
- for each method, also include a plain description of any parameters that the method accepts as well as a description of its return value, if any.

### Additional comments

- add a comment above any while or for loops describing the high-level purpose of the loop
- add a comment above any recursive elements describing the high-level purpose of the recursion.
- indicate any flags and state their purpose.
- for any variable that is incremented or decremented, explain why.
- for any method calls, please explain the purpose of the method call and any arguments passed to the method.
- if the program inherits from another class, be sure to point out in comments any parent class methods or data fields that the code references.
  - also, be sure to point out any overridden methods

### Folder structure

This project has several important directories:

- `src` - contains the Java source code for the project (i.e. `.java` files)
- `test` - contains code that will help us determine whether the code you have written works correctly. Do not touch this directory!
- `bin` - contains the compiled code (i.e. `.class` files)
- `lib` - contains any dependencies (other libraries of code that the project depends upon to work)

If your project has no dependencies and has not been compiled, you may not see the `lib` or `bin` directories.

### How to test your work

Automated tests that can help determine whether you have done the work correctly have been included within the `test` directory. Use them as follows. A [video tutorial](https://www.youtube.com/watch?v=Af6Ka0Bmflo) shows how to do this and overcome any problems:

- Click the Run and Debug icon in the Visual Studio Code activity bar, then click the play button to run your code without using the automated tests. Do this prior to running the tests to make sure your program seems to behave correctly yourself.
- Open the relevant test file, located within the `test` directory.
- Click the Test icon (a beaker) in the Visual Studio Code activity bar and click the play button to run those tests. Tests that pass will be marked with a green checkmark, while those that fail will be marked with a red "X".
- Each test that fails will show a message with some indication of what went wrong - these messages may help you pinpoint the source of the error.

If you have trouble running the tests from within Visual Studio Code, you can do them from within a Terminal window, assuming the project directory is the current working directory (change `TestClassName` to the relevant name fo the test class.)

```bash
java -cp "bin:lib/*" org.junit.runner.JUnitCore edu.nyu.cs.TestClassName
```

Windows users should replace the `:` in `"bin:lib/*"` with a semi-colon, `;`, i.e. `"bin;lib/*"`

## How to submit this assignment

Once you have completed the changes to th assignment, you are ready to submit it. Do this from within Visual Studio Code.

1. Click on the `Source Control` icon in the left activity bar in Visual Studio Code.
1. In the Source Control side bar, you will see a field named `Message` - type in a unique message about what you have done, e.g. "_Finished assignment!_" or whatever you want to write as a short note to yourself.
1. Hover over the words `Source Control`. You will see a `...` icon appear - click it to see a menu. In that menu, click `Commit`->`Commit`. This logs the changes you've made to the Git project - remember Git is used to keep track of changes.
1. Go to the same menu and click `Push` to submit your assignment - this uploads your updated files to the copy of your respository on GitHub.

![Push changes to GitHub](./images/how_to_push_changes_to_github_from_vscode.png)

That's it... you're done.

## Double-check your submission

Prove to yourself that you have correctly submitted by viewing your repository on the GitHub website - you should see your completed README.md file there.

## Resubmit as many times as you want

You can re-submit as many times as you want before the deadline. Just make changes to the files on your own computer and repeat the process outlined above to upload them to GitHub.

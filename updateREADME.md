# ITSC-1213: Summer 2025

# Problem Solve 19
Name: Ashley Reynoso Marmolejos  
Email: areynoso@charlotte.edu
UNC Charlotte ID: 801133223
- Your GutHub user name.: areynosowatch
- The name of this activity: itsc1213
- `RectangleTest.java` program is this class describes a system where user inputs width and length.
- `Circle.java` program is this class describes a solution to problem solve 19 with a given radius and color and area.


## Original source

The original files for thos assignment are provided at https://github.com/Charlotte-CCI-ICC/1213-problem-solve19.git (by [nanajjar](https://github.com/nanajjar), last accessed on July 14, 2025).

## Contents

- `README.md`: Empty Markdown file.

- `RectangleTest.java`: Template for a Java program that will do some geometric calculations using rectangles.

- `Circle.java`: This class describes a circle with a given radius and color.


## Set up a new GitHub project

### Basic reading

We are assuming you read the following sections on the Runestone book:

- **12.7 What are Git and GitHub?** ([click here](https://runestone.academy/ns/books/published/UNCCharlotte_ITSC1213_Sumer25/sec-git-github-concepts.html)). 
- **12.8 Getting the Project Code: Cloning** ([click here](https://runestone.academy/ns/books/published/UNCCharlotte_ITSC1213_Sumer25/sec-git-cloning.html). 
- **12.9 Working with Versions: Branches and Checkout** ([click here](https://runestone.academy/ns/books/published/UNCCharlotte_ITSC1213_Sumer25/sec-git-branches-checkout.html))
- **12.10 Project Setup, Branches, and Tooling Context** ([click here](https://runestone.academy/ns/books/published/UNCCharlotte_ITSC1213_Sumer25/sec-arraylist-setup-tooling_scope.html))

### Soft tips about Git from the Phyloinformatics Lab
- [What is Git?](https://www.notion.so/What-is-Git-117514596f29807cba1bc9148b5e6b3e?pvs=21)

- EXTRA: [Set up Git to handle GitLab projects (command line solutions for Linux)](https://www.notion.so/Set-up-Git-to-handle-GitLab-projects-command-line-solutions-for-Linux-b2a3843ac20a4751955540e892df940d?pvs=21)

- EXTRA: [Using GitHub Desktop with GitLab](https://www.notion.so/Using-GitHub-Desktop-with-GitLab-68600607967b43eda1609a35387b87c7?pvs=21)

### Additional resources

- **Git, GitHub, & GitHub Desktop for beginners**, by Code Coder. Available from [YouTube](https://youtu.be/8Dd7KRpKeaE?si=b6XUc2ojTc9rs3h3) (last accessed on July 14, 2025).
- **A step-by-step guide to Git installation: How to install Git on macOS, Windows and Linux**, by Kyryl Sidak. Available from [codefinity](https://codefinity.com/blog/A-step-by-step-guide-to-Git-installation?utm_source=google&utm_medium=cpc&utm_campaign=21144377223&utm_content=&utm_term=&dki=&gad_source=2&gad_campaignid=21151281995&gbraid=0AAAAABTeUgSvz2V3IX7fTCkWYogwr27oO&gclid=CjwKCAjw1dLDBhBoEiwAQNRiQeJhMogCHqcBkhpWda_7iAwRHDRoBKx-p2iyw9i0q8QljeX7ZGSM8xoCch4QAvD_BwE) (last accessed on July 14, 2025).

### Setting up

Make sure you have a GitHub account.

Download and install the GitHub desktop app.

On GitHub's website, in your account, create a new GitHub project for this activity. Call it `ITSC1213_ProblemSolve19`.

Clone that empty project locally. Add the contents of https://github.com/Charlotte-CCI-ICC/1213-problem-solve19.git in there. Update your project.

## Modify the RectangleTest.java program

At the top of  `RectangleTest.java` , add:

```java
import java.util.Scanner;
```

Let us modify the program to read width and height from the user. Inside the `main` method, add the following code:

```java
// Inside main() 
Scanner input = new Scanner(System.in);
System.out.print("Enter width: "); 
int width = input.nextInt();
System.out.print("Enter height: "); 
int height = input.nextInt();
```

Once your program runs correctly and calculates the area based on user input, you’re ready to move on to the next part. Be prepared to show how this program runs to the instructional team during the review.

## Document your code with JavaDoc

In this part we will work on document your code with JavaDoc comments and generate documentation.

1. Open the `Circle.java` file and review its content. Then, replace the basic comments with proper JavaDoc-style comments.
	1.1. Above the class: purpose + @author
	1.2. Above methods/constructors: summary, @param, @return

2. Generate the documentation by running the following command in the terminal:

```bash
javadoc -d docs Circle.java
```

The command above creates a folder named docs and fills it with HTML files that contain your JavaDoc comments, formatted as a browsable website.

> **Help! Command not found on Windows:**
> If you run into this error:
> ```javadoc : The term 'javadoc' is not recognized as the name of a cmdlet, function, script file, or operable program.```
> you will need to ensure your system knows where to find Java is installed in your machine. On Windows, it’s usually:  `C:\Program Files\Java\jdk-<version>`
> You want the path that contains folders like bin, lib, etc. Use your File Explorer to locate it.
> Once you've located it, scroll up to the top of this assignment page and expand the "**Fixing JavaDoc on Windows**" section of the Background. Follow the steps and screenshots posted there.
> Relaunch VS Code and all terminal windows (including those in VS Code) to ensure these changes are in effect and verify Java was added to the PATH by running `javadoc --version` in your terminal. 



3. To verify the generated documentation, open `docs/index.html` in a web browser and review the JavaDoc you created.

4. If you notice anything that needs fixing, update your JavaDoc comments and re-run the command to regenerate the documentation.

5.  Now, save your changes using Git. Be sure to track both the `Circle.java` file and the generated documentation.

6. Once everything looks good, you're ready to show your work to the instructional team for review.

## Modify the README file

Add the following details to your README file using Markdown language:

- Your full name
- Your UNC Charlotte's email address
- Your UNC Charlotte's ID number
- Your GutHub user name.
- The name of this activity
- An explanation of the `RectangleTest.java` program, in plain English. This should be a complete and detailed explanation of the code and what it does.
- An explanation of the `Circle.java` program, in plain English. This should be a complete and detailed explanation of the code and what it does.
- The URL for your private project in GitHub.

## Deliverables

Download your complete project from GitHub and upload it here as a compressed (`.zip`) file. Your compressed file should contain the following:

- `README.md`: Your README file, with the requested information on it.

- `RectangleTest.java`: Your working rectangle program after you implemented and tested the requested modifications.

- `Circle.java`: Your circle program.

- `docs/`: The documentation that you created.

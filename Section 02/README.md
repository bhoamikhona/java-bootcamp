# Section 02: Programming Tools Setup

**About:**

## Table of Content

- [Section 02: Programming Tools Setup](#section-02-programming-tools-setup)
  - [Table of Content](#table-of-content)
  - [Software Tools Introduction](#software-tools-introduction)
    - [JShell](#jshell)
  - [Author](#author)

## Software Tools Introduction

- Java Development Kit (JDK) version 17
  - It is the software that is used to create and run Java programs.
- We will also use IntelliJ IDEA for an IDE. It is a very powerful piece of software, packed with lots of features for both, beginners and pro developers.
- The great thing about IntelliJ is that it is extremely beginner friendly and there is a free community edition or a paid ultimate edition.
- In this section, we are going to get the JDK and IntelliJ setup.
- Other IDEs for Java: Eclipse and Netbeans.

### JShell

- JShell became a standard component of the Java Developers Kit in Java 9.
- It is what is known as Read-Eval-Print-Loop interactive program (REPL for short) which means it does pretty much just that:
  - It reads the command or code segment we type in.
  - It evaluates and executes code, and often allows short cuts to be used.
  - It prints out the results of the evaluation or execution, without making the developer write code to output the results.
  - Lastly, it loops right back for more input (more code segments or commands).
- JShell runs in a terminal (or on the command line for Windows) and is useful for quickly trying out new ideas.
- JShell is a kind of sandbox, or playground, that let's us experiment with code, in a simple, safe, and fun way.
- It does this with instant feedback which, for brand-new developers, is very rewarding.
- Note that although JShell is interactive (because it is a REPL), it is not the same thing as an IDE.
- JShell does not replace the need for an IDE. It is just a handy tool to quickly get started with Java.
- We will be transitioning to an IDE later in the course.
- We will use JShell for the first part of this course, both to introduce it to you, and to explore some basic concepts in Java.
- For the rest of this lesson, we will look at some of JShell's built-in features, and try to get comfortable with some simple commands.
- First, let's take a look at some online documentation for JShell: [Docs](https://docs.oracle.com/en/java/javase/17/jshell/introduction-jshell.html)
- As you can see in the docs, it starts with a simple introduction and is divided into various sections such as "Snippets", "Commands", etc.
- We are not going to explore this documentation in detail but, be aware that it is here and it can be very useful if you get stuck with a problem, or simply want to learn more on your own.
- In general, be curious and take advantage of the many online resources available to you.
- We will also be looking at many such Java online resources together as we progress through the course.
- For now, let's switch over to JShell and learn a bit about it.
- To launch JShell in the terminal, you can type `jshell`.
- `/help intro` - This command will give us a simple introduction to JShell and a couple more hints.
- `/help` - This command will give us the JShell help.
  - As you can see, there are several commands available with a brief description of each.
  - We won't be going through all of those commands, just a few common ones.
  - There are options to save and open files, reset JShell to its initial launch state, and even review the history of what you have typed, etc.
  - Let's take a look at the top command which is the list command.
- `/list [<name or id>|-all|-start]`
  - As you can see, the list command is followed by some options, contained within left and right square brackets.
  - Those brackets indicate the options for the command.
  - We can also see that the list command is used to list the source you have typed.
  - Since we have not yet typed any source (code), let's use the `-all` option: `/list -all`.
  - What we see in the output is a list of libraries of built-in code that JShell includes in its enviornment.
  - One of the great thing about Java is, it has been around a long time, and there is a lot of code already written that we can take advantage of.
  - We don't have to re-invent the wheel because, we will be able to find and use existing code to do things like, connect to the internet, solve math problems, or get input from a user.
  - Note, if had typed in some code already, it would also be listed along with the list of libraries.
  - So, the list command shows us the history of Java code run in JShell.
  - Although we didn't execute the import statements that you see when you get the list, JShell executed them, when it started up.
- In addition to seeing the history of the Java code executed, we can use the up and down arrow keys to scroll through whatever we ourselves typed in JShell.
- The up and down arrow keys will be very useful to us, as we execute one line of code, then want to change something about it, and execute it again.
- Once we have the previous code on our current prompt, we can edit that code, then execute it with our new changes, by hitting enter again.
- One other useful thing in JShell is when you want to write a couple lines of code in Java, but you don't want them to be all on the same line, you can do that with the use of braces.
- If you enter the braces prompt by mistake, to exit it, you can press `ctrl + c`.
- To exit out of JShell, you can type in `/exit` and then you will be back at the regular command prompt.

## Author

- [@bhoamikhona](https://github.com/bhoamikhona)

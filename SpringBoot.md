# Welcome to the SpringBoot for Java!

This tutorial will help teach you how to build Java web applications using
SpringBoot 3.0.

Before you get started, you will need to install [java](https://www.oracle.com/java/technologies/downloads/) and [git](https://git-scm.com/downloads).

I recommend installing Java 21, as it's the latest LTS (Long Term Support)
release version of Java as of the time this file was created, which should
be valid throughout the entire semester.

These installs may require you to update your PATH, which is done differently
in Windows or the Mac. Those details are not provided in this tutorial.

Test that the `java` command works by running:

    java -version

You should see text displaying the version of java installed. If you do not,
ensure you have java installed and referenced in your PATH.

Optionally, you can also install/use an IDE such as [Eclipse](https://eclipseide.org/)
or [IntelliJ](https://www.jetbrains.com/idea/download/) to provide an more
robust programming environment. Note, I recommend the Ultimate version of the
latter, which is use by many commercial developers, but is free for
students/teachers, see [here](https://www.jetbrains.com/community/education/#students)
for details on obtaining an educational license.

Alright! You are ready to go!


Create a new project
--------------------

This documentation is heavily influenced by the following [site](https://spring.io/quickstart), which you can use OR follow this documentation.

Create a new Spring Boot Project by going to <https://start.spring.io/>

* Project - Gradle - Groovy
* Language - Java
* Spring Boot - 3.3.2
* Project Metadata
  - Group: edu.carroll
  - Artifact: cs341-demo
  - Name: cs341
  - Description: CS341 project for Spring Boot
  - Package name: edu.carroll.cs341
  - Packaging: Jar
  - Java: 21

Next, in the upper-left corner of the screen, Click on the 'Add dependencies'
button, and scroll down until you see 'Spring Web', and then click to add it.

Finally, click the 'GENERATE' button at the bottom of the page, which should
create and then download the file cs341-demo.zip onto your laptop.

Bring up a command line window and browse to the directory for projects
in this class) (either create a new directory or use an existing directory).

Once in that directory, unpack the file in the top-level directory, which
should create a new folder named cs341-demo containing the basic configuration
for your demo project.

In the newly created `cs341-demo` directory create a new git repository by running:

    cd cs341-demo
    git init

```sh
git add .
git commit -m "Initial commit"
```

At this point, I would *HIGHLY* recommend creating a new Github repository
associated with your personal Github account, and then upload this project
to github before proceeding. Instructions on how to accomplish this are
not included in this tutorial.

Throughout this tutorial you will be able to check your progress against the
official tutorial.  To do this add the official tutorial as a new git remote
named `upstream` by running:

    git remote add upstream https://github.com/YogoGit/SpringBootTutorial.git


Fetch the remote repository:

    git fetch upstream --tags



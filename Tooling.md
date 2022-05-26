## TOOLING

**TOOLS**

You don't have to be conversant with all the tools there are a few that every software developer must be.

**SOUCE CODE CONTROL**

the open source tools are usually your best option because they are written by developers, for developers.

- AN "ENTERPRISE" SOURCE CONTROL SYSTEM: If your company is using a "enterprise" source code control system, you can use both. You can check your source code into the “enterprise” system at the end of each
iteration (once every two weeks or so) and use one of the open source systems.
- PESSIMISTIC VERSUS OPTIMISTIC LOCKING: Thanks to new systems, this strategy of locking files is outdated and not very useful.
- CVS / SVN: The old standby source control system is CVS. It was very good at dealing with individual files and directories, but it's not very good renaming files or deleting directories. Subversion, works very nicely, it allows you to check out the whole system in a single operation, and easily update merge and commit. However, it's not very good branching.
- Branching: SVN is a good option, but there are better options like git.
- git: Git is a game changer for developers and should be a must using it.

**IDE/EDITOR**

As developers we read and edit a lot of code. The tools to do it should be good.

- VI: It's an outdated editor but it can be used for little things.
- EMACS: As a
general-purpose editing tool, nothing else even comes close. On the other hand,
I think that Emacs cannot really compete with the specific-purpose IDEs that
now dominate. IntelliJ is a better option.
- ECLIPSE/INTELLIJ: Both are very good options as IDE, Eclipse is similar in power and scope to IntelliJ. However, the learning curve is high, and project
set-up time is not insignificant. These tools are not lightweight. They take a lot of computing resources to run.
- TEXTMATE: Tt's powerful and lightweight. It can't do wonderful manipulations that IntelliJ and Eclipse can do, it's not as fast as VI and doesn't have the powerful lisp engine and library of Emacs but it's easy to use and intuitive.

**ISSUE TRACKING**

There are some of them, like Pivotal Tracker, which is simple to use and fits nicely with the Agile/iterative approach. For small project you can use Lighthouse, which is quick and easy to use. 
You can just use a wiki. Wikis are easy to understand and use and you're not forced into a certain process or a rigid structure.
Before use one of them you can start with a manual system, like a bulletin board.

- BUG COUNTS: This type of issue tracking systems should be for no more than 100 problems, the moment you have a thousand problems they become a dump of problems.

**CONTINUOUS BUILD**

An example of these systems is Jenkins. You should hook it up to your source code control system and whenever anybody checks in code, it should automatically
build and then report status to the team.

**UNIT TESTING TOOLS**

Each language has it’s own particular unit testing tool. For example: JUnit, NUnit, RSPEC, etc...

A unit testing tool should support these features:

1. It should be quick and easy to run the tests.
2. The tool should give you a clear visual pass/fail indication.
3. The tool should give you a clear visual indication of progress.
4. The tool should discourage individual test cases from communicating with
each other.
5. The tool should make it very easy to write tests.

**COMPONENT TESTING TOOLS**

These tools are for testing components at the API level. Their role is to make sure that the behavior of a component is specified in a language that the business and QA people can understand.

- THE DEFINITION OF DONE: Using this tool we can indicate or not if a job is done or not. That's what it means to pass or not the tests.
- FITNESSE: FitNesse is a wiki-based system that allows business analysts and QA specialists to write tests in a very simple tabular format.
- OTHER TOOLS: There are others like RobotFX, Green Pepper, Cucumber or JBehave. They are all similar but with some differences.

**INTEGRATION TESTING TOOLS**

Component testing tools can also be used for many integration tests, but are less than appropriate for tests that are driven through the UI. In general, we don’t want to drive very many tests through the UI because UIs are notoriously volatile. Some examples of UI testing tools are Selenium and Watir. They are very important tools to define the structure of the code, but they are not everything. The code for a complete program is also needed.

**UML/MDA**

They are very important tools to define the structure of the code, but they are not everything. The code for a complete program is also needed.

- THE DETAILS: Programmers are detail managers. We specify the behavior of systems in the minutest detail and it can't be done with a UML system.
- NO HOPE, NO CHANGE: The hope that diagram systems will replace code is an unreachable dream. As much as the diagrams are a tiny abstract form of code, it is still code, since these diagrams have their own coding, and coding requires programmers. Then these diagrams are nothing more than a new image of coding.


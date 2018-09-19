# Questions
Q1: What is gitflow ?

Q2: Why i should break my code ?

Q3: What is Django explain it and Give 3 examples program that is similar ?   

Q4: Explain the waterfall model ?

Q5: How to test and find bugs ?
# Answers
A1: GitFlow is a branching model for Git, created by Vincent Driessen. It has attracted a lot of attention because it is very well suited to collaboration and scaling the development team.


A2: A common mistake very early programmers make is to write it, then only run it once or against the most simple scenario. A great way to deepen your abilities is to purposefully try to break your own code.


Find unexpected ways to run your code, test on different machines, disable the internet, etc. Ask yourself:

Does it still work, or does it just crash? (If it crashes, see the next section.)
If it runs, does it report errors?
Can you find a way to handle those errors without stopping the program? As an example, if it fails due to the internet being down, maybe you could try the request again later, and only stop if several requests fail.


A3.2: Django is a free and open source web application framework, written in Python. A web framework is a set of components that helps you to develop websites faster and easier.

When you're building a website, you always need a similar set of components: a way to handle user authentication (signing up, signing in, signing out), a management panel for your website, forms, a way to upload files, etc.

Luckily for you, other people long ago noticed that web developers face similar problems when building a new site, so they teamed up and created frameworks (Django being one of them) that give you ready-made components to use.

Frameworks exist to save you from having to reinvent the wheel and to help alleviate some of the overhead when you’re building a new site.


A3.2: 1) xampp
      2) netbeans
      3) Visual Studio Code

A4: The waterfall model is a design process often used in software development. This model takes its name from the cascading “flow” of its life cycle, which moves downward (akin to a waterfall) through the stages of development. In the waterfall model, the phases of development do not overlap

A5: This is a deeper topic than can easily be covered here, but every language has some way of debugging. This is another reason why you should make mistakes every day: you want a reason to dive down under the surface of your code and understand what’s happening at a deeper level.

Most debugging will let you step through your program — jumping deeper into the lower layers and learning what really happens when you call a method, or set a value, or make a network request.

The goal with debugging — from a learning standpoint — is to build up that muscle memory about how the parts of a program are glued together. The deeper this knowledge, the easier it will be to predict, find, and fix bugs in the future.
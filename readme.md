# Errata

This repo contains errata and improvement proposals for books.

## Goal

To have a common repository where we can share fixes or suggestions to books. We will be able to keep our books up to date with the last fixes, even before a new version is released (if that happens at all).

## Index

- [*M. van Steen and A.S. Tanenbaum, Distributed Systems*](books/distributed-systems-978-1543057386.md)
- [*Essential Computer Science: A Programmer’s Guide to Foundational Concepts*](books/essential-computer-science-978-1484271070.md)
- [*Math for Programmers: 3D graphics, machine learning, and simulations with Python*](books/math-for-programmers-978-1-61729-535-5.md)

## Structure

Each book will have a separate file containing information about the book (eg: link to amazon or goodreads) and errata for the (possible) different versions of it.

The name of the file should not overlap with other books with the same name, so please use the [slugified](https://en.wikipedia.org/wiki/Clean_URL#Slug) name of the book, suffixed by the [ISBN-13](https://en.wikipedia.org/wiki/International_Standard_Book_Number) (if existent).

Example:

This is the file which contains information about [*M. van Steen and A.S. Tanenbaum, Distributed Systems*](https://www.distributed-systems.net/):

> ./books/distributed-systems-978-1543057386.md

## Conventions

- Be specific on the version of the book where the errors were found and add a comment if the error was fixed in a subsequent version
- Be as specific as possible to spot the section where the error is found
- If you are telling in which paragraph the error was found, consider also a paragraph the one which started in the previous page and finishes in the referred page

## PR

Feel free to submit a PR adding errors/improvements to any book (existent in the repo or new ones).

Feel also free to provide contact information for the authors, and to provide links to this repo to the authors so they can see the latest errors found by the community and luckily provide feedback through discussion in Issues or PRs.

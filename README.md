# elixir
Integration
Elixir Logo
HOME INSTALL GUIDES LEARNING CASES DEVELOPMENT DOCS BLOG
News: Elixir v1.11 released
Search...
GETTING STARTED
Introduction
Basic types
Basic operators
Pattern matching
case, cond, and if
Binaries, strings, and charlists
Keyword lists and maps
Modules and Functions
Recursion
Enumerables and streams
Processes
IO and the file system
alias, require, and import
Module attributes
Structs
Protocols
Comprehensions
Sigils
try, catch, and rescue
Typespecs and behaviours
Debugging
Erlang libraries
Where to go next
MIX AND OTP
Introduction to Mix
Agent
GenServer
Supervisor and Application
Dynamic supervisors
ETS
Dependencies and umbrella projects
Task and gen_tcp
Doctests, patterns and with
Distributed tasks and tags
Configuration and releases
META-PROGRAMMING IN ELIXIR
Quote and unquote
Macros
Domain-specific languages
Getting Started
Introduction
Installation
Interactive mode
Running scripts
Asking questions
Welcome!

In this tutorial, we are going to teach you about Elixir fundamentals - the language syntax, how to define modules, how to manipulate the characteristics of common data structures, and more. This chapter will focus on ensuring that Elixir is installed and that you can successfully run Elixir’s Interactive Shell, called IEx.

Our requirements are (see elixir -v):

Elixir 1.5.0 onwards
Erlang/OTP 19 onwards
Let’s get started!

If you find any errors in the tutorial or on the website, please report a bug or send a pull request to our issue tracker.

The Elixir guides are also available in EPUB format:

Getting started guide
Mix and OTP guide
Meta-programming guide
Installation
If you haven’t yet installed Elixir, visit our installation page. Once you are done, you can run elixir --version to get the current Elixir version.

Interactive mode
When you install Elixir, you will have three new executables: iex, elixir and elixirc. If you compiled Elixir from source or are using a packaged version, you can find these inside the bin directory.

For now, let’s start by running iex (or iex.bat if you are on Windows PowerShell, where iex is a PowerShell command) which stands for Interactive Elixir. In interactive mode, we can type any Elixir expression and get its result. Let’s warm up with some basic expressions.

Open up iex and type the following expressions:

Erlang/OTP 21.0 [64-bit] [smp:2:2] [...]

Interactive Elixir (1.11.2) - press Ctrl+C to exit
iex(1)> 40 + 2
42
iex(2)> "hello" <> " world"
"hello world"
Please note that some details like version numbers may differ a bit in your session; that’s not important. From now on iex sessions will be stripped down to focus on the code. To exit iex press Ctrl+C twice.

It seems we are ready to go! We will use the interactive shell quite a lot in the next chapters to get a bit more familiar with the language constructs and basic types, starting in the next chapter.

Note: if you are on Windows, you can also try iex --werl (iex.bat --werl on PowerShell) which may provide a better experience depending on which console you are using.

Running scripts
After getting familiar with the basics of the language you may want to try writing simple programs. This can be accomplished by putting the following Elixir code into a file:

IO.puts "Hello world from Elixir"
Save it as simple.exs and execute it with elixir:

$ elixir simple.exs
Hello world from Elixir
Later on we will learn how to compile Elixir code (in Chapter 8) and how to use the Mix build tool (in the Mix & OTP guide). For now, let’s move on to Chapter 2.

Asking questions
When going through this getting started guide, it is common to have questions; after all, that is part of the learning process! There are many places where you can ask questions, here are some of them:

Official #elixir-lang on freenode IRC
Elixir Forum
Elixir on Slack
Elixir on Discord
elixir tag on StackOverflow
When asking questions, remember these two tips:

Instead of asking “how to do X in Elixir”, ask “how to solve Y in Elixir”. In other words, don’t ask how to implement a particular solution, instead describe the problem at hand. Stating the problem gives more context and less bias for a correct answer.

In case things are not working as expected, please include as much information as you can in your report, for example: your Elixir version, the code snippet and the error message alongside the error stacktrace. Use sites like Gist to paste this information.

Is something wrong? Edit this page on GitHub.
Top Next →
© 2012–2020 The Elixir Team. All rights reserved.

# Ruby Console & Object Oriented Ruby

## The Plan

This pairing lab does not have a designated place to switch drivers. Instead, every 30 minutes the pair's responsibilities should swap. The driver becomes the navigator, and vice versa.

To minimize extra cloning and forking, this project should be completed in only one person's Github account, on one computer.

## What is a `console`

A programming console is a coding environment to run text based code. `console`s give developers a way to interact with their domain. Similar to adding a breakpoint in your code ( `binding.pry` ), `console`s have access to all the Ruby classes and objects you have created in your program.

This lesson contains a console that you can use. To enter the console session, run `ruby tools/console.rb`. You'll be able to test out the methods that you write here.

## Domain mapping

Before you start building the domain outlined below, read over the application interface ("Deliverables") and discuss what the relationship of these objects are. What belongs to what? What has many of another? What links objects together? What object serves as a source of truth for connecting two other objects?

## Instructions

*After discussing your domain*, your goal is to build out all of the methods listed in "Deliverables". Do your best to follow Ruby best practices. For example, use higher-level array methods such as `map`, `select`, and `find` when appropriate in place of `each`.

  --  Make sure you are testing your code as you go! --

Look at the contents of the `console.rb` file and use the commented out code to guide writing your API. Comment out a line or section at a time and verify that 1. your code executes without error and 2. your code returns the expected data.

## Deliverables

Implement all of the methods described below

### `Course`

* Course.all
  * returns **all** of the course instances
* Course.find_by_subject(subject)
  * given a string of the subject, returns the **first course** whose subject matches


### `Enrollment`

* Enrollment.all
  * returns all enrollment instances
* Enrollment#course
  * returns the course object for that given enrollment
* Enrollment#student
  * returns the student object for that given enrollment

### `Student`

* Student.all
  * returns **all** of the student instances

### `SchoolSupply`

* SchoolSupply.all
  * returns all the school_supply instances

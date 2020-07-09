<p align="center">
  <a href="https://sqlzoo.net/">
      <img width="40%" src="_images/sqlzoo-logo.png">
  </a>
</p>

## What is SQLzoo?

[SQLzoo](https://sqlzoo.net/) provides various exercises for writing SQL queries.
Topics range from simple `SELECT` statements, to aggregate functions and `GROUP BY`,
to various `JOIN` operations. Difficulties range from trivial to genuinely tricky.

## What is this repository?

This is a collection of my solutions to each of SQLzoo's exercises. Many existing public
solutions aren't as clear or simple as they could be. I'd like this repository to serve
as a reference of clean, readable solutions for anyone working through the tutorials.

## Tutorials

|  #  | Tutorial Topic                                                                |                 Solved/Total                  |
| :-: | ----------------------------------------------------------------------------- | :-------------------------------------------: |
|  0  | [SELECT basics](https://sqlzoo.net/wiki/SELECT_basics)                        |     [3/3](tutorials/0_SELECT_basics.sql)      |
|  1  | [SELECT name](https://sqlzoo.net/wiki/SELECT_names)                           |     [15/15](tutorials/1_SELECT_name.sql)      |
|  2  | [SELECT from World](https://sqlzoo.net/wiki/SELECT_from_WORLD_Tutorial)       |  [13/13](tutorials/2_SELECT_from_world.sql)   |
|  3  | [SELECT from Nobel](https://sqlzoo.net/wiki/SELECT_from_Nobel_Tutorial)       |  [14/14](tutorials/3_SELECT_from_nobel.sql)   |
|  4  | [SELECT within SELECT](https://sqlzoo.net/wiki/SELECT_within_SELECT_Tutorial) | [10/10](tutorials/4_SELECT_within_SELECT.sql) |
|  5  | [SUM and COUNT](https://sqlzoo.net/wiki/SUM_and_COUNT)                        |     [8/8](tutorials/5_SUM_and_COUNT.sql)      |
|  6  | [JOIN](https://sqlzoo.net/wiki/The_JOIN_operation)                            |        [13/13 ]tTutorials/6_JOIN.sql)         |
|  7  | [More JOIN operations](https://sqlzoo.net/wiki/More_JOIN_operations)          | [15/15](tutorials/7_More_JOIN_operations.sql) |
|  8  | [Using Null](https://sqlzoo.net/wiki/Using_Null)                              |      [10/10](tutorials/8_Using_NULL.sql)      |
| 8+  | [Numeric Examples](https://sqlzoo.net/wiki/NSS_Tutorial)                      |  [8/8](tutorials/8%2B_numeric_examples.sql)   |
|  9  | [Self join](https://sqlzoo.net/wiki/Self_join)                                |      [10/10](tutorials/9_Self_join.sql)       |

### Notes on Style

I mostly followed the [SQL style guide by Simon Holywell](http://www.sqlstyle.guide/).
I found this to be a clean, highly-readable way of formatting queries. Table and column
names are dependent on SQLzoo's chosen names.

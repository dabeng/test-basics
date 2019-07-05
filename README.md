# Code Coverage - Istanbul
There are a number of coverage criteria, the main ones being:

Function coverage Has each function (or subroutine) in the program been called?
Statement coverage Has each statement in the program been executed?
Branch coverage Has each branch (also called DD-path) of each control structure (such as in if and case statements) been executed? For example, given an if statement, have both the true and false branches been executed? Another way of saying this is, has every edge in the program been executed?
Line coverage has each executable line in the source file been executed?
For each case, the percentage represents executed code vs not-executed code, which equals each fraction in percent format (e.g: 50% branches, 1/2).

It can only be different of you have more than one statement on one line. Statement coverage is a more accurate indicator of coverage - line coverage is to support existing coverage tools that rely on line level info

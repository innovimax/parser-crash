# parser-crash
A test suite for Crashing Parsers

## What is a parser?
A parser is simply a program that reads data and create a data representation in memory.

## Isn't there already tools for that?
There is hundreds of way to crash a parser.
 * Some are smart like [AFL](http://lcamtuf.coredump.cx/afl/)
 * Some are less smart like this attempt, to find the corner cases **related to the size**.

## Which parsers?
 * HTML
 * XML
 * JSON
 * YAML

for a start and let's see where get

## How?
 # Well there is java codes that generates the data files
 # And then you just run them through your favorite parser
 # and then you share the results so we can improve the parser generator

## Why?
It started by a discussion around node density about HTML, XML and JSON (the usual suspects about being to verbose)



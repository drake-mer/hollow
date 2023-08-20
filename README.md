# Hollow 👻

A *nix tool to keep track of your filesystem content

## Description

This is a tool designed for personal use, it might or might not suit your needs.

The aim of this tool is to identify what is the content of your hard drive and make an 
index out of it.

The problem we are solving nowadays for a personal computer with a very long lifetime (talking about > 5 years)
is that it gets incredibly difficult to have a consistent backup policy for your own files.

Probably most of the time, you copy and forget, and you have a ton of duplicated files everywhere. Maybe some of the
files you want to keep are somewhere in one of your computers, but you can't really be sure about it, and it would
force you to go across all your USB sticks (once again 🙄).

This is totally a personal project, made for me with the hope that it could be useful for someone at some point.

## Solution

So how do we organize all of this?

The initial proposal is simple

1. have an index of your files somewhere (a PG database, or even better, an elastic search instance).
2. have a script that can run on your computer and create some metadata
3. build a nice UI to display and query all of this

## Example of query one might want to run

- Give me all mp3 files created between 2010 and 2014 on a hard drive with the brand Seamaster
- Find all PDFs larger than 3 pages that look like paper research
- Find all successive iterations of my resume, ie all files similar to the example I give you

## The project in short

So, the idea, you guess it, is to be your ultimate archive tool, a search engine for your computer.

Why is this project especially interesting to me?

- it will help me have a data-analytics approach
- it will help me master elastic search
- it will help me master the go programming language



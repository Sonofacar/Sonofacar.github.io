---
title: "A Simple Guide to Vim"
date: 2023-01-27
tags:
  - Vim
  - Programming
draft: true
---

# Why Vim?

At its base, Vim is a text editor. 
It has many features and is considered one of, if not the most efficient text editors.
Beyond that, it is highly configurable and can be used for almost anything you can think of.
I personally use it for taking notes, for programming, and for writing this site.
But I could do the same things with other text editors: why does Vim matter?
Here are a few reasons:
- It is very fast
- You can configure it in many ways
- It has incredible functionality
- You do not have to touch a mouse at all
- It is light-weight on your computer
- Easy to add plugins and use for many purposes
- I like the aesthetic

While I could get into why it is great at what it does, that is not the purpose of this post.
I want to make a guide on how to get started using it.
To start with, I would like to talk about the primary concept called modularity.


# Modularity

Vim is what is called a _modal_ text editor. By that, I mean that it has several modes which are:
- Normal
- Insert
- Visual
- Command
- Replace
- etc.

Each of these modes have specific purposes, and they all have several features that make them each very useful.
There are many functions you can use in each mode, but there are so many that learning it all at once is very difficult.
I feel like I don't know even a quarter of the possibilities, but the basics offer quite a bit.
I will go through a few of the important ones and give some understanding about the modes.

## Normal Mode

Normal mode is what you start out in with Vim.
If you are in any other mode, all you have to do is press the `Esc` key, and you will return to it.
The primary purpose of Normal mode is movement.
The most simple way to move in vim is the `h`, `j`, `k`, and `l` keys.
Here is what they do:
- `h`: move left
- `j`: move down
- `k`: move up
- `l`: move right

This is a simple use that takes a bit to get used to, but why is this a good system.
What is nice about it is that all of those keys are on the home row of your keyboard.
Because of that, it makes it really easy to shift your right hand over to these keys and start moving around.
To me, this makes sense, but there is so much more to movement.
Here are some of my favorite keys to use for movement:
- `gg`: move to the top of the document
- `G`: move to the bottom of the document
- `w`: move to the beginning of the next word
- `e`: move to the next end of a word
- `0`: move to the start of the current line
- `$`: move to the end of the current line

Despite the main purpose of this mode being movement, it is not the only thing it can do.
Another major tool is searching through the current text.
This is done by pressing the `/` key and typing the text you want to search for.
It will highlight all of the matches and move your cursor to the next occurance.
In the case of multiple occurances, you can press the `n` key to go to the next one and `N` to go to the previous one.

There are also delete, copy and paste functions that are very feature rich in this mode.
I will just give the basics of how to do these things:
- `dd`: delete the current line
- `yy`: copy the current line
- `p`: paste the last copied/deleted selection to the line below the current line

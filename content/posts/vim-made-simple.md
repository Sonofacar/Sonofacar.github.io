---
title: "Vim Made Simple"
date: 2023-02-08
image: "/images/post-pics/vim.webp"
alt: "Vim logo"
tags:
  - vim
  - coding
  - tutorial
  - workflow
draft: false
---

You are trying to edit a file.
It might be a some code, a markdown file, a configuration file, or any number of text files.
You remember a tool called `vi` which you remember is used to do just that,
and you use it to open up your file.
Once you are in,
you realize you can't type or move your cursor around.
You likely would have given up, used something else and wondered "why would anyone use this?"
That is what I am here to answer.
`vi` is a whole world all on its own,
and, in my opinion, once you understand it, there is no going back.

# What is vi or vim?
`vi` is a text editor, so all you do is use it to open up a file and edit some text.
It is packed with functionality, and it is pretty old.
So, people later came along and created what is called `vim` or 'vi improved.'
Vim really is the main tool people use today,
but vi is still found natively on servers and many other computers.
Vim and all of its variations have been continuously developed until the present day,
and it has become a very powerful tool in that time.

But what about it is so great?
The key is that you can use it entirely with the keyboard
and work faster than you ever could while using your mouse.
While it may be a bit of a learning curve,
there is a huge return on the time you spend to learn it.

# Basics of Vim
The key to understanding vim is that it is built off of modes.
There is a mode for inserting text,
there is a mode for moving your cursor around,
there is a mode for selecting text,
and there are even more modes out there.

### Normal Mode
When you first open up vim,
you enter normal mode.
This mode is all about moving around, switching between modes, and executing commands.
To get to this mode from any other mode,
all you need to do is press the `Esc` key.
You can also write the file by typing in `:``w` and `Enter`,
and if you wanted to write the file and quit at the same time, type `:``w``q` and `Enter`.
There is a whole host of commands that make your workflow much quicker,
and you can access the prompt for these commands by just pressing `:` from normal mode.

Movement works with the following keys:
- `h` (left)
- `j` (down)
- `k` (up)
- `l` (right)
This might seem like an odd choice,
but this was specifically chosen because of its nearness to the home row.
This makes it very easy to transition to moving your cursor around from inserting text. 

It is important to know that there is a lot more you can do to move around quickly,
it is just hard to cover in such a short guide.

### Insert mode
This one is a little easier to understand.
While in normal mode, press `i`,
and you will enter insert mode with your cursor right before the space you were currently on.
This will also let you delete,
although there are some very effective ways to do that in other modes.
You can still move around with arrow keys,
but it is much quicker to just press the `Esc` key and move around with basic movement keys.

### Other modes
It is important to know that there are other modes that each have their own unique functionalities.
Some of these include:
- visual
- visual-block
- replace

I can't cover all of these in enough depth,
but I want you to understand that these other modes
and all the previous ones have much much more to them than I could speak about.
I would only point you to a program that is generally installed alongside vim called `vimtutor`.
It will walk you through the basics of vim in a lesson format
that generally doesn't take long and will get you on your feet quickly.

# Why Vim?
I previously said that it can make things much faster at editing your text,
but why is it useful for us as data scientists to know?
It is particularly great in its code capabilites and customization.

For example, on my setup, I have a few plugins installed
that allow me to open up an `R`, `Python`, or `bash` terminal and execute code from my current file.
I also have a file explorer set up, a note taking plugin, 
and other plugins that deal with syntax highlighting.

It would be easy for me to open up a tab, work on this blog post,
then switch over to another to work on some `R` or `Python` coding,
and then search through another file for a specific occurrence of a certain word.
All of this is sped up considering the fact that all of this is done without ever touching the mouse.

# Conclusion
Although it certainly is not something everyone will want or need to do,
it can be a very powerful tool or even a fun tool to tinker with.
It is something that has made me much quicker at performing simple tasks,
expanded my horizons of what is possible with working with code,
and gave me a lot of enjoyment is learning something new.

I would just encourage those of you who are interested to
install vim and test out the `vimtutor` command and see if you like it.
If you do, try it out a little and try learning new things about it.

# SBB

> Simple Bash Blog

Blogging system designed using Bash.
Should work on any Linux machine. (Let me know if it doesn't.)

Depends on:
- *Bash*
- *markdown*

Install using your distro's package manager.

### Install

Place entire *blog/* folder in the root of your webhost. Move *bin/post* to
somewhere within your *$PATH*.

### Configuration

Open the post script and change the top variables to whatever paths you use.

### Usage

Run post and enter your blog post title. The *post* script will call up
*$EDITOR* (*nano* if *$EDITOR* is not set) and allow you to type in the body
of your blog post using markdown. When done, save and close.

Currently, to edit blog posts, you'll have to change the HTML itself.
Might be changed in the future, but it's not my priority to implement yet.

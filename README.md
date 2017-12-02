# SBB

> Simple Bash Blog

Blogging system designed using Bash.
Should work on any Linux machine. (Let me know if it doesn't.)

Depends on:

- Bash
- markdown

Install using your distro's package manager.

### Installation

Place entire blog/ directory in the root of your webhost. Move bin/post to
somewhere within your $PATH.

### Configuration

Running post will first create a config file in either $XDG_CONFIG_HOME or the
default .config directory. Currently the only variable is path. Set it to the
root of your webhost. *(Do not put a leading slash there.)*

### Usage

Run `post` and enter your blog post title. The script will call up
$EDITOR (nano if $EDITOR is not set) and allow you to type in the body
of your blog post using markdown. When done, save and close.

Currently, to edit blog posts, you'll have to change the HTML itself.
Might be changed in the future, but it's not my priority to implement yet.

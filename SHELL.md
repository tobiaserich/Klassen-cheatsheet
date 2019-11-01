# SHELL

A computer's Shell is basically a direct way to access an OS's functions through a text-interface, often called the "command line." Think of it this way: you often navigate folders by double-clicking on icons. This is using a graphical user interface, or GUI, since you've got visuals to guide you.

A Shell lets you do all the normal things, but only with text commands - no icons to view, click through, or drag around.

# Why is the Shell Useful?

1. **Shells can do many things GUI's can't.** Want to run a site locally and see live-updates based on changes? Install needed packages for a repo? Run a Gulp or NPM workflow? Develop a prototype app on your computer? All these things require the Shell. Some functions do have GUI counterparts - for example, you can use Git source control via the Shell or apps like SourceTree. But those GUI's never give you the full range of functions you'll need. Remember git rebasing? It's a lot harder, even impossible, to do on any GUI.

2. **Shells let you automate otherwise time-consuming tasks.** As a coder, you'll have lots of repetitive computer tasks that take away your time and productivity. Shells let you condense complex tasks into simple commands that do all the work.

# Some Basic Commands

A good starting command is **ls**. It shows all the files in your current directory, or the computer folder you're in. If you're in a folder full of text files, you'll see each file's name.

Most commands also accept flags, which modify their functionality slightly. They're used by adding a **-** paired with a character to the command. For example, using ls with a flag could look like **ls -1**. This command also shows all items in your directory, but on separate lines.

Want to see all the flags? Use the man command for the ls command by running **man ls**. You'll see everything you need to know about ls, what it does, and all its flags! **This is perhaps the most important command, since it gives you useful info about all commands. Use it often!**

- **pwd** - see your current directory
- **cd** - navigate to different directories
- **cd** **~** - go to your root directory
- **mkdir** - make a new directory
- **touch** - make a new file
- **cat** - show a file's contents
- **cp** - copy a file
- **rm** - delete files or directories
- **wc** - get the number of words, characters, or lines
- **echo** - show text, or the compiled text of other commands. Great for testing commands out.

There's also some slightly more advanced ones you should take the time to learn.

- **Curl** - download or transfer data from a server. You'll see it a lot when installing new things!
- **Grep** - filter results line-by-line based on different patterns, or regular expressions (aka a regex)
- **Pipe (|)** - take one command's output and use it as the input for another
- **Awk** - lets you process text files different ways
- **Sed** - manipulates texts in files using a regex

[Link](https://dev.to/maxwell_dev/the-shell-introduction-i-wish-i-had-551k) to article to read more about Schell.

[Another Useful Link](https://dev.to/milkstarz/helpful-terminal-commands-for-beginners-5cjh) to article to read more about Schell.

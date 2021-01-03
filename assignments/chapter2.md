## Chapter 2 Assignment

The aim of this week's exercises are to get your shell environments customized and have you practice a little bit of scripting and debugging.

You will modify this file with your answers and submit your assignment in an email to `xix2007@med.cornell.edu`. The file should be saved as `{first}-{last}-assignment{#}.md`, and your email should be titled `datascibasics assignment {#}`.

Follow chapter 2's [exercise module](https://axiezai.github.io/wcm_datasci_basics_02environment/04-assignment/) steps and answer the following questions:

#### Q1:
While creating aliases for your most used commands, you used the `awk` program and one of its built-in functions `substr`. Try running the `history | awk '{$1="";print substr($0,2)}' | sort | uniq -c | sort -n | tail -n 10` command step by step, and explain in your own words, how did your command history change with each piped (`|`) step?

#### Q2:
After completing your dotfiles directory, and testing that your installation script works for all your dotfiles, use the `tree` program to show the contents of your `dotfiles` directory. 

The `tree` program does not come attached to Linux or macOS distributions, so you can install it quickly with `sudo apt-get install tree` on Linux or `brew install tree` on macOS.

Read up on what `tree` does with `tree --help`, `man tree`, or `tldr tree` (remember to install tldr). Use `tree` to display the contents of your dotfiles directory with the size of all files attached in human readable format, copy and paste the output tree structure here:

```bash
# Your dotfile directory tree structure here
```

#### Q3:
Now instead of tree, follow Part 2 step 1, print the `ls` command you used and its outputs for the dotfile directory here:

```bash
# Your command and output here
```

#### Q4:
Write your <em> working</em> `marco` and `polo` bash functions here:

```bash
# Your functions here
```

#### Q5:
Report the following:

```bash
# Your debugging script:

# The standard output stream:

# The output error stream:

# (BONUS) How many runs did it take for the script to fail?
```
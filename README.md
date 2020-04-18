# Shell Notebooks

Sweet, and super low-tech shell notebooks!

Write a (simple) [Markdown](https://daringfireball.net/projects/markdown/) document, then automatically convert it to a runnable shell script and get back a shiny new Markdown document with all of the results!

If you've used an [R Markdown](https://rmarkdown.rstudio.com) notebook before, you know what I mean!

## Installation

You'll need to have [Ruby](https://www.ruby-lang.org/en/documentation/installation/) installed on your computer.

Then download the `run_bash_notebook` script and put it somewhere convenient!  That particular script will use `bash` so you'll want to have that as well.

## Usage

Try it out!

```
./run_bash_notebook test_files/test.md
```

I've only tested it with some pretty basic Markdown so far (see `test_files/test.md`).  Who knows how well it'll work with super complicated and spiffier Markdown files `¯\_(ツ)_/¯`!

## Inspiration

- [bash-notebook](https://github.com/roblabs/bash-notebook) -- another option for bash notebooks
- [R Markdown](https://rmarkdown.rstudio.com) -- 💖 it, but not so smooth for shell focused notebooks!
# Testing out bash_notebook

Hi there!  I'm a cool "bash notebook".

## Do something

Let's run some commands.

```{bash}
echo 'hi "bob"'
echo "hi 'ryan'"
```

This code block will not be run!

```
i'm just a "little" code block!
```

## Saving variables!

Yep, you can use variables.  First, here's a `codeblock` where we set some.

```{bash}
apple="apples are good"
pie='pie is good'
sentence="apple: ${apple}, pie: ${pie}"
```

And then, in another codeblock, we can use them again!

```{bash}
echo "the sentence was: ${sentence}"
```

## Subshells

Subshells can be a lot of fun.

```{bash}
wc -w <(printf "hi\tbob\n" | cut -f1)
```

## Backticks

You can also do backtick type things!

```{bash}
wc -w <(`printf "echo 'hi ryan moore'"`)
```

Granted, that's a little weird!

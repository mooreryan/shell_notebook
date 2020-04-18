# Disable Exit Code Checking

By default, the error code of the last command in the bash block will be checked for success (i.e.,  it will check that `$? == 0`).  (That's why it's normally better to have a single command or multiple commands joined by `&&`s in a single bash block.)

For example, this code block would normally cause the notebook to exit with an error.

```{bash check=false}
ls im-a-file-that-doesnt-exist
```

However, since I added `{bash check=false}` instead of just `{bash}`, the notebook will keep going!

```{bash}
echo 'still truckin!'
```

Try to remove the `check=false` bit and re-run the notebook.
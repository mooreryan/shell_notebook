# Multiple commands per code block

If you use multiple commands in a code block, it will work fine, but the notebook won't stop after the second command (which will fail).

Depending on what you're trying to do, that may be a feature.

```{bash}
echo 'hi'

ls arosietnarosient

echo 'bye'
```
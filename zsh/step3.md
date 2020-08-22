# 3.Set up the plugins

Now use the editor(nano,vim,etc.) to open the ``~/.zshrc`` file.

## use vim editor

`vi ~/.zshrc`{{execute}}
run this to open the file. **Then PRESS letter "i" before you input your plugin name.**
there's a line like this:

```text
plugins=(git)
```

Note that the plugins are separated by whitespace (spaces, tabs, new lines...). Do not use commas between them or it will
break.
These are rignt:

```text
plugins=(git ruby)
plugins=(git
         ruby
         rake
)
```

More plugins located at repository readme file.

## After typing

press esc first.then enter(directly!!!): ":wq"
DON'T ENTER JUST ":q" OR ":q!" ! IT WILL DON'T SAVE ALL FILES!

### Editor nano - usage was all printed on the editor

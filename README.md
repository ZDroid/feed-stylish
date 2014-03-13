# Feedstyl

> Script for displaying stylish feeds

Uses [feedparser](http://code.google.com/p/feedparser/).

For more info about content parsing, read
[sanitization article](http://pythonhosted.org/feedparser/html-sanitization.html)
at feedparser documentation.

## Command line

```bash
$ ./feedstyl.py URL
```

## API

Feedstyl is meant to be used only in the command line as **distinct command**.
However, you can import Feedstyl in the another script. You have to import it
locally.

```py
import feedstyl
```

### .feed()

**Usage:** `feedparser.feed()`

Displays feed properties.

### .entries()

**Usage:** `feedparser.entries()`

Displays entries properties.

### .run()

**Usage:** `feedparser.run()`

Displays both feed and entries properties.

## Configuration

Configuration values:

- `indent_lenght`
- `feed_trunc`
- `entry_trunc`

## License

MIT &copy; [Zlatan Vasović](https://github.com/ZDroid)

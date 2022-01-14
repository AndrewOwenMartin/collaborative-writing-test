# Intro

A Markdown file is any file ending in `.md`.
You can put one sentence per line in the file.
It will render as a normal paragraph unless you actually leave a blank line.

This is a new paragraph because I left a blank line. Here's how to do a few other things. Headings are when a line starts with a #, subheadings are lines that start with ## and you can go up to ######.

# Markdown features

Here are some features

## Lists

There are two types of lists

### Numbered lists

The first type of list is the numebred list

1. Numbered lists
2. Bulleted lists

### Bulleted lists

There is also the bulleted list

- Numbered lists need lines that start with `1.` or `2.` etc.
- The actual number doesn't matter, markdown will correctly number the lines, but you might want to number them for your own benefot while reading.
- Bulleted lists are lines that start with a `-`
- You can also have paragraphs in the list, just indent a bit
  If I wanted to go into more detail I'd do it here
- Lists can be nested, you just indent the `-` so it lines up with the first letter of the previous line
  - I made this nested list by making the `-` line up with the `L`
  - foo
  - bar
- That's all I know about lists

## Code

We probably won't have code in our book, but it's useful in this document to explain syntax. You make code by wrapping it in back ticks like this `code`.

You can have code chunks by starting a line with three back ticks like this
```
Class Person:
    age: int
    name: str
    
    def greet(self, name):
        return f"Hello {name}, my name is {self.name}, I am {self.age} years old."
```

## Quotes

You can make a quote like you would see a forwarded email, you start the line with `>`

> Now is the winter of our discontent
> Made glorious summer by this sun of York;
> And all the clouds that lour'd upon our house
> In the deep bosom of the ocean buried.

## Comments

You can have text that renders normally. <? You can have text that is hidden and discusses the text, this is really useful and essential for editing and collaboration. ?>

# Markdown Demo

Markdown is plain text. It's meant to be easily readable -- and writable!

<!-- TOC -->
* [Markdown Demo](#markdown-demo)
  * [Advantages](#advantages)
  * [Disadvantage](#disadvantage)
  * [Text Formatting](#text-formatting)
  * [Lists](#lists)
  * [Links](#links)
  * [Code](#code)
  * [Images](#images)
  * [Tables](#tables)
    * [Alignments](#alignments)
  * [Checklists](#checklists)
<!-- TOC -->

## Advantages

* Easy for anyone to read.
* Widely adopted by various wikis and note-taking apps.
* Natively supported by GitHub.
* Made to be converted to HTML.

## Disadvantage

* Minimal features (by design).
* Does not support syntax highlighting by default
* Many competing interpreters (such as Github-Flavored Markdown)
* Missing many features (such as line breaks), and the official solution is to embed HTML tags.
* Many features implemented inconsistently (or not at all) in different products.
* _Only_ design for HTML.
* No ability to create a page break or line-break.[^1]
* No auto-generated table of contents or index.

[^1]: Although you can add horizontal lines. (And footnotes.)

---

## Text Formatting

* You can *emphasize* words.
* Let people known you're **really** serious.
* Put technical values, such as a `variable` or Keystroke (`Ctrl+c`) in backticks.

## Lists

We've already used lists, but can also create numbered lists:

1. This is the first thing. 
2. This is the second.
3. This is the third.
4. Auto-numbering for the win!

## Links

Any URL will automatically become a link: https://example.com

Or, give it name: [demo site](https://example.com)


## Code

Now let's add some code

    def main():
        # This is a comment
        print('hello')

There is an alternative way to write code, called "code-fencing":

```python
def main():
    # This is a comment
    print('hello')
```

There is _no_ syntax highlighting in Markdown by default, but some third-party converters support it. This text is being compiled with `pandoc`, which supports syntax highlighting. Let's demonstrate

## Images

![cat](https://aoeus.com/Lucifer.png)

## Tables

| header 1 | header1 |
|----------|---------|
| val 1    | val2    |
| val 3    | val4    |

### Alignments
| Name   | Age |
|:-------|----:|
| Fred   |  35 |
| Barney |  33 |


## Checklists

Simple list:

- [x] This thing is done
- [ ] New Task
- [ ] Wash car
- [x] Do laundry
- [ ] Grocery shopping


# You are invited to contribute

## The repository for this guide

This guide is hosted in a [GitLab repository](https://gitlab.com/StudentProjects/guide).

If you want to contribute, please fork, modify and create a merge request following PC3.

## Markdown

Please use [markdown ](https://docs.gitlab.com/ee/user/markdown.html#standard-markdown) for your text.

## Linter

Markdown Linter has been used to maintain the standard and consistency of all the Markdown files.This Linter helps to analyze and indicate the lines of code that violates the markdown's rules.

If you are using Visual Studio Code for markdown editing then you can use its [Markdownlint Extension. ](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

## Manual of style
We recommend to follow the [Wikipedia manual of style](https://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style).

**Headings, headers, and captions:** Use sentence case, not title case, capitalization in all section headings. Capitalize the first letter of the first word, but leave the rest lower case except for proper names and other items that would ordinarily be capitalized in running text. Source: [Wikipedia](https://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style/Capital_letters)

## Syntax highlighting for code blocks

Only the [fenced](https://docs.gitlab.com/ee/user/markdown.html#code-and-syntax-highlighting) code blocks support syntax highlighting. You need to provide a [language indicator](http://prismjs.com/#languages-list) as well.

Example for C++ language indicator `cpp`:

<pre>```cpp
int main()
{
    std::string s1 = "Hello";
    std::string s2 = "World";
    using std::swap;
    swap(s1, s2);
}
```</pre>

becomes:

```cpp
int main()
{
    std::string s1 = "Hello";
    std::string s2 = "World";
    using std::swap;
    swap(s1, s2);
}
```

Syntax highlighting will not work if you do not provide a language indicator (the `cpp` is missing).

<pre>```
int main()
{
    std::string s1 = "Hello";
    std::string s2 = "World";
    using std::swap;
    swap(s1, s2);
}
```</pre>

becomes:

```
int main()
{
    std::string s1 = "Hello";
    std::string s2 = "World";
    using std::swap;
    swap(s1, s2);
}
```

## Emojis

You can use standard [emojis](https://www.webpagefx.com/tools/emoji-cheat-sheet/).

Examples:

`:rocket:` becomes :rocket:

`:smiley_cat:` becomes :smiley_cat:

Use with caution and let's not exaggerate... :wink:

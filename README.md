# GitHub-Markdown-Notes

[GitHub Markdown Web Article](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)


[See my profile page](docs/Profile.md)

## Headings
To create a heading
# A first-level heading
## A second-level heading
### A third-level heading

## Styling Text
Example Text - Shortcuts in Windows

**Bold Text** - Ctrl + B

_Italic Text_ - Ctrl + I

~~Strikethrough Text~~

**This text is _extremely_ important** - Bold and nested italic

***All this text is important*** - All bold and italic

The KA10 <sub>This is a subscript text</sub> - Subscript

The KA10 <sup>This is a superscript text</sup> - Superscript

## Quoting text
Text that is not a quote

> Text that is a quote

## Quoting code
Use `git status` to list all new or modified files that haven't yet been committed.

A basic Java Class is:
```
class Demo {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

## Supported color models

The background color is `#ffffff` for light mode and `#000000` for dark mode.

HEX Color Code: 	`#0969DA`

Notes:
>A supported color model cannot have any leading or trailing spaces >within the backticks.
>
>The visualization of the color is only supported in issues, pull >requests, and discussions.

## Links
This site was built using [GitHub Pages](https://pages.github.com/).

## Relative links
[See my profile page](docs/Profile.md)

## Lists
You can make an unordered list by preceding one or more lines of text with -, *, or +.
- George Washington
* John Adams
+ Thomas Jefferson

To order your list, precede each line with a number.

1. James Madison
2. James Monroe
3. John Quincy Adams

## Nested Lists
1. First list item
   - First nested list item
     - Second nested list item
       - This is similar

## Specifying the theme an image is shown to
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">


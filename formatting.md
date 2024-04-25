# Markdown formatting

## Pictures

This displays a different image depending on light/dark theme

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="YOUR-DARKMODE-IMAGE">
 <source media="(prefers-color-scheme: light)" srcset="YOUR-LIGHTMODE-IMAGE">
 <img alt="YOUR-ALT-TEXT" src="YOUR-DEFAULT-IMAGE">
</picture>

Replace your-darkmode-image and your-lightmode- image with image URLs.
Replace your-alt-text with description of images for use with a screen reader.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

This is a responsive image.

## Adding a Table

## This is a header

| Rank  | Thing-to-rank |
|------:|---------------|
|      1|               |
|      2|               |
|      3|               |

# Collapsed section

To add a collapsed section, i.e. the above table, wrap the table in details section:

<details>
<summary>My table</summary>

## This is a header

| Rank  | Thing-to-rank |
|------:|---------------|
|      1|               |
|      2|               |
|      3|               |

</details>

To make it open by default add the open attribute to the details tag.

## Adding a quote

---
> If we pull together and commit ourselves, then we can push through anything.

— Mona the Octocat

## Adding a comment

## About me

<!-- TO DO: add more details about me later -->

# Headings
## Second level heading
### Third level heading

## Styling text

**This is bold text**  
__This is bold text as well__  
*Some italic text*  
_This works as well_  
~~The Tilde will strike through~~  
**Bold and _nested_ italics**  
***This is bold AND italics***  
We can also do <sub>subscript</sub> text  
And also <sup>superscript</sup>!!!  

## Quoting code

Use back ticks to quote code:

Use `git status` to list all new or modified files that haven't yet been committed

To put it into blocks use triple back ticks:

Some basic Git commands are:
```
git status
git add
git commit
```

## Colours!!

The background color is `#ffffff` for light mode and `#000000` for dark mode.

## Links

Wrap the text in a bracket to create a link:  

This site was built using [GitHub Pages](https://pages.github.com/)

## Lists

- Tom
* Dick
+ Harry

Any of those precursors will work.

1. Tom
2. Dick
3. Harry

Or you can number them!

If you really want to be clever, you can nest them!

1. First  
    1. First nested  
    2. Something else  
        1. Another nest!  
2. Second item  
    1. Second first nest  
        2. Another nest again!  
        3. Stuff.

Use four spaces or some tabs to create the nests, eight for a second nest. Two spaces are needed at the end for a new line.

## Task list

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

## Paragraphs

You can create a new paragraph by leaving a blank line between lines of text.

## Footnotes

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

## Alerts

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Hiding in comments

<!-- This content will not appear in the rendered Markdown -->

## Ignoring markdown formatting

Let's rename \*our-new-project\* to \*our-old-project\*.

put the stuff in slash asterisk to ignore formatting.

## Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

## Styling text

**Bold Text**

*Italic text*

~~Strich text~~

**Bold and _nested italic_**

***All Bold and italic text***

This is <sub>subscript</sub> text

This is <sup>subscript</sup> text

---

## Quoting text

> This is Quote text

---

## Quoting Code

use `git status` to list all new or modified file

some basic `Git` commands are
```
git status
git add
git commit
```

---

## Color models
The background color is `#ffffff` for light mode and `#000000` for dark mode.

For color red : `#ff0000`

---

## Links

Visit [Google](https://www.google.com)

You need to visit (Not working as expected) [Heading](https://github.com/karthi-mr/test-markdown/edit/main/README.md#headings)

Testing relative. **Always need to use this _relative links_** - [relative link](#headings)

---

## Images

**image**

![Alternative text used to display when image is not shown](https://myoctocat.com/assets/images/base-octocat.svg)

**Alt text**

![Now alternative text will be display due to wrong image](https://myoctocat.com/assets/images/base-octocat1.svg)

---

## specifying theme for image

**Showing moon (dark mode)**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

**Showing sun (light mode)**

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
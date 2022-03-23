# Rowan
![rowan_cover](https://user-images.githubusercontent.com/17025808/159715767-56f8c2f7-293c-41a9-8760-d7487155b668.png)

**Rowan** is a color palette (17 colors) designed for IDEs, editors & code highlighters.  

Simple but very efficienty palette with greyscale colors for the background and well defined colors for the texts 

## Light & Dark
**Rowan** exists in two variants *Light* and *Dark*.

![rowan_light](https://user-images.githubusercontent.com/17025808/159701641-7bdb60aa-a75f-4e4e-815f-e06ee46dbc40.png)

![rowan_dark](https://user-images.githubusercontent.com/17025808/159701683-b50197e0-10c1-450c-930a-028906ad5bf2.png)

As you can see the *Light* and *Dark* variants of use the same color values except for the **keywords**.

The greyscale colors aren't a true gradient from one color to another, the Lightness (HSL) values are as follows:

![rowan_greyscale](https://user-images.githubusercontent.com/17025808/159725136-6485ecd7-2fc0-4125-987e-2369f15518b7.png)

## Colors Info / Guidelines
| Short Name | Color Name | Light | Dark | Apply on | Description |
|:----------:|:----------:|:---------:|:--------:|:--------:|:-----------:|
| `bgr` | background | ![01](https://user-images.githubusercontent.com/17025808/159727711-a0c8beb1-8c7f-45db-a528-6c3229474e94.png) | ![07](https://user-images.githubusercontent.com/17025808/159728300-ea89d62b-6cff-4e15-abf2-bbab06af4d0f.png) | background | Code Block Background, Editor Background |
| `hgl` | highlighted | ![02](https://user-images.githubusercontent.com/17025808/159727812-34a91590-9e3e-48d9-b616-ba8d3f988f8a.png) | ![06](https://user-images.githubusercontent.com/17025808/159728206-d7a0a867-f07a-4416-9595-363f60f08e60.png) | background | Highlighted Line(s), Search Results Highlighed (not user selection) |
| `sel` | selection | ![03](https://user-images.githubusercontent.com/17025808/159727946-d2f3c32f-32a1-4c08-a25e-7c61fc243eb6.png) | ![05](https://user-images.githubusercontent.com/17025808/159728145-0463630f-69cf-43de-944d-0a4b3011944f.png) | background | User Selection of word(s) or line(s) |
| `com` | *comments* | ![04](https://user-images.githubusercontent.com/17025808/159728013-1a58af7d-3cce-476f-b374-93efc645b851.png) | ![04](https://user-images.githubusercontent.com/17025808/159728013-1a58af7d-3cce-476f-b374-93efc645b851.png) | text | Code Comments (comments are normally displayed in *italic*) |
| `lin` | line n° | ![05](https://user-images.githubusercontent.com/17025808/159728145-0463630f-69cf-43de-944d-0a4b3011944f.png) | ![03](https://user-images.githubusercontent.com/17025808/159727946-d2f3c32f-32a1-4c08-a25e-7c61fc243eb6.png) | text | Line Numbers |
| `def` | default | ![06](https://user-images.githubusercontent.com/17025808/159728206-d7a0a867-f07a-4416-9595-363f60f08e60.png) | ![02](https://user-images.githubusercontent.com/17025808/159727812-34a91590-9e3e-48d9-b616-ba8d3f988f8a.png) | text | Default color for text, delimiters & ponctuations (`{`,`}`,`;`,`,`,...) |
| `acc` | Accent | ![07](https://user-images.githubusercontent.com/17025808/159728300-ea89d62b-6cff-4e15-abf2-bbab06af4d0f.png) | ![01](https://user-images.githubusercontent.com/17025808/159727711-a0c8beb1-8c7f-45db-a528-6c3229474e94.png) | text | Use when default text are selected to keep text readibility |
| `kwd` | **keywords** | ![kwd_light](https://user-images.githubusercontent.com/17025808/157437330-38849a15-578b-4bc5-a1a9-b04fcb22ff50.png) | ![kwd_dark](https://user-images.githubusercontent.com/17025808/157437362-a3d7da14-b24b-4985-ba75-6fe0d1d7dffe.png) | text | Keywords, Keyword Declaration (e.g. `var` in JavaScript), Keyword Type (`int`, `float`, ...), Keyword Namespace (`namespace`) |
| `esc` | escaped | ![esc](https://user-images.githubusercontent.com/17025808/157437402-d691fd7d-c4c0-4fbd-be31-71c437331095.png) | ![esc](https://user-images.githubusercontent.com/17025808/157437402-d691fd7d-c4c0-4fbd-be31-71c437331095.png) | text | Escaped Characters, Regex, Interpoled Strings, Character Entities |
| `res` | reserved | ![res](https://user-images.githubusercontent.com/17025808/157437461-2abf575e-777e-4e7b-83fa-6baa66682e99.png) | ![res](https://user-images.githubusercontent.com/17025808/157437461-2abf575e-777e-4e7b-83fa-6baa66682e99.png) | text | Reserved Keywords, Constant Keywords, Pseudo Keywords |
| `opr` | operators | ![opr](https://user-images.githubusercontent.com/17025808/157437520-84542c82-ea2d-46ac-a7f9-50555b3ee885.png) | ![opr](https://user-images.githubusercontent.com/17025808/157437520-84542c82-ea2d-46ac-a7f9-50555b3ee885.png) | text | Operators, Word Operators |
| `str` | strings | ![str](https://user-images.githubusercontent.com/17025808/157437573-51c7a5f9-618e-4980-8746-525d03e4f92b.png) | ![str](https://user-images.githubusercontent.com/17025808/157437573-51c7a5f9-618e-4980-8746-525d03e4f92b.png) | text | Strings, DocStrings |
| `var` | variables | ![var](https://user-images.githubusercontent.com/17025808/157437611-51c9242e-9086-420e-a7f3-e07370021236.png) | ![var](https://user-images.githubusercontent.com/17025808/157437611-51c9242e-9086-420e-a7f3-e07370021236.png) | text | Variable Names, Attributes Names |
| `nam` | names | ![nam](https://user-images.githubusercontent.com/17025808/157437655-b29bcc05-a007-4b28-8003-6d7dcc5a8b5f.png) | ![nam](https://user-images.githubusercontent.com/17025808/157437655-b29bcc05-a007-4b28-8003-6d7dcc5a8b5f.png) | text | Namespace Names, Class Names, Decorator Names, Exception Names, Function Names |
| `nbr` | numbers | ![nbr](https://user-images.githubusercontent.com/17025808/157437726-7598721d-7ef6-4903-807a-4cfe8129e902.png) | ![nbr](https://user-images.githubusercontent.com/17025808/157437726-7598721d-7ef6-4903-807a-4cfe8129e902.png) | text | All kind of Numbers (integer, float, hex, binary, ...) |
| `err` | errors | ![err](https://user-images.githubusercontent.com/17025808/157437772-ef2e2fd6-8b8a-442d-9863-a1cf2fe9d8fa.png) | ![err](https://user-images.githubusercontent.com/17025808/157437772-ef2e2fd6-8b8a-442d-9863-a1cf2fe9d8fa.png) | text OR wavy underline | Errors (the color can be applied to text or only to a wavy underline), Diff Deleted (apply on text) |
| `ins` | inserted | ![ins](https://user-images.githubusercontent.com/17025808/157437809-fa25de21-e150-45a2-b809-27c011c6893a.png) | ![ins](https://user-images.githubusercontent.com/17025808/157437809-fa25de21-e150-45a2-b809-27c011c6893a.png) | text | Diff Inserted, Success Messages |

As you can see every colors are meant to be used for a specific purpose. Of course, if in your case you can't use all the colors do your best to stay as close as possible to the original palette. 

## Palette Colors Values
Find in [this page](https://github.com/BenSouchet/rowan/blob/main/VALUES.md) a table with the exact colors codes in multiple color models (HEX, RGB, HSV, HSL, Lab).  

There is also files in the [`palette/` folder](https://github.com/BenSouchet/rowan/tree/main/palette) defining the colors in HEX in multiple formats: [YAML](https://github.com/BenSouchet/rowan/tree/main/palette/yaml), [CSS](https://github.com/BenSouchet/rowan/tree/main/palette/css), [SCSS](https://github.com/BenSouchet/rowan/tree/main/palette/scss).

**Important**: if you implement the color palette in an editor, a website, a service, ... please do not modify the color codes (use the exact ones listed in [this page](https://github.com/BenSouchet/rowan/blob/main/VALUES.md)).

## Additionnal Info
If you implement this palette as a color theme somewhere, code comments should be displayed in *italics*, and keywords should be in **bold** (to easily identify them).

## Sixteen Color Palette
**Polarized** is a seventeen (17) color palette but if you need (or are restricted) to only sixteen colors, you can ignore the accent (`acc`) color or use the numbers (`nbr`) color for the Diff Inserted texts.

## Others Ressouces & Useful links
- [Sorbus Auto-Theme for Rouge Highlighter](https://github.com/BenSouchet/sorbus), in this project **Rowan** is the default color palette.
- [Color Blend](https://bensouchet.github.io/color-blend/), website to blend two colors and generate intermediates colors.
- [mycolor.space](https://mycolor.space/), top wevbsite to find matching colors, generate palettes.
- [Colorizer.org](http://colorizer.org/), super tool to convert and play with colors into multiples color models (HSV, HSL, Lab, ...).

## Author & maintainer
Polarized has been created and is currently maintained by [Ben Souchet](https://github.com/BenSouchet).

All the files present in this repository are under [MIT license](https://github.com/BenSouchet/rowan/blob/main/LICENSE).

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
| `bgr` | background | ![bgr_light](https://user-images.githubusercontent.com/17025808/157435460-bdf1df00-b898-412d-849c-cc60e90ab7b9.png) | ![bgr_dark](https://user-images.githubusercontent.com/17025808/157435643-abdbc5dd-bbe9-4318-9a18-36fbae6cc946.png) | background | Code Block Background, Editor Background |
| `hgl` | highlighted | ![hgl_light](https://user-images.githubusercontent.com/17025808/157435484-9eed3590-b746-49fa-aac3-917c4f59ba6f.png) | ![hgl_dark](https://user-images.githubusercontent.com/17025808/157435684-0e04d721-57f0-44cb-a8fc-ca921a7e3626.png) | background | Highlighted Line(s), Search Results Highlighed (not user selection) |
| `sel` | selection | ![sel_light](https://user-images.githubusercontent.com/17025808/157435507-16839184-c041-41fe-b10c-2cac7c0bc1b3.png) | ![sel_dark](https://user-images.githubusercontent.com/17025808/157435706-b1782db8-f4e5-4854-a9fc-4f4f486e7116.png) | background | User Selection of word(s) or line(s) |
| `com` | *comments* | ![com_light](https://user-images.githubusercontent.com/17025808/157435531-a88f9254-91ae-430a-8b39-8acb21d1a0cf.png) | ![com_dark](https://user-images.githubusercontent.com/17025808/157435734-46e58344-56b2-4ee1-9581-166a03038818.png) | text | Code Comments (comments are normally displayed in *italic*) |
| `lin` | line n° | ![lin_light](https://user-images.githubusercontent.com/17025808/157435562-0568c867-1c22-4400-963f-9ef78d7e7c00.png) | ![lin_dark](https://user-images.githubusercontent.com/17025808/157435773-079becd4-450b-40e9-af19-a71644487193.png) | text | Line Numbers |
| `def` | default | ![def_light](https://user-images.githubusercontent.com/17025808/157435586-66054cd5-5503-4974-a5c2-9f092d159469.png) | ![def_dark](https://user-images.githubusercontent.com/17025808/157435796-725b1438-f8a0-4185-b9d0-190807c7a87e.png) | text | Default color for text, delimiters & ponctuations (`{`,`}`,`;`,`,`,...) |
| `acc` | Accent | ![acc_light](https://user-images.githubusercontent.com/17025808/157435615-5f7098df-7333-4df1-9fe1-4a3cf3f3b4a0.png) | ![acc_dark](https://user-images.githubusercontent.com/17025808/157435849-b2f39dee-367d-4ee6-94bb-01b136e3ef81.png) | text | Use when default text are selected to keep text readibility |
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

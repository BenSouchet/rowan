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
| `kwd` | **keywords** | ![BB](https://user-images.githubusercontent.com/17025808/159949334-1f0ba41c-6907-44ba-9d95-c4bc4e4e90f1.png) | ![AA](https://user-images.githubusercontent.com/17025808/159948263-7d62b71e-cc8a-4aa7-98d0-3112714e35f7.png) | text | Keywords, Keyword Declaration (e.g. `var` in JavaScript), Keyword Type (`int`, `float`, ...), Keyword Namespace (`namespace`) |
| `esc` | escaped | ![08](https://user-images.githubusercontent.com/17025808/159948534-1404e5ef-f321-4a85-9d32-61ed9b503199.png) | ![08](https://user-images.githubusercontent.com/17025808/159948534-1404e5ef-f321-4a85-9d32-61ed9b503199.png) | text | Escaped Characters, Regex, Interpoled Strings, Character Entities |
| `res` | reserved | ![09](https://user-images.githubusercontent.com/17025808/159948577-8a022c8e-8b08-447f-88c6-b6c83bebcc55.png) | ![09](https://user-images.githubusercontent.com/17025808/159948577-8a022c8e-8b08-447f-88c6-b6c83bebcc55.png) | text | Reserved Keywords, Constant Keywords, Pseudo Keywords |
| `opr` | operators | ![10](https://user-images.githubusercontent.com/17025808/159948631-7ff427b6-88ce-4307-920c-c629c172c95b.png) | ![10](https://user-images.githubusercontent.com/17025808/159948631-7ff427b6-88ce-4307-920c-c629c172c95b.png) | text | Operators, Word Operators |
| `str` | strings | ![11](https://user-images.githubusercontent.com/17025808/159948687-18332171-65c3-4cf7-9c89-96b32c2322c1.png) | ![11](https://user-images.githubusercontent.com/17025808/159948687-18332171-65c3-4cf7-9c89-96b32c2322c1.png) | text | Strings, DocStrings |
| `var` | variables | ![12](https://user-images.githubusercontent.com/17025808/159948734-8505b63f-d9ba-466a-adbc-cc0cf67a864d.png) | ![12](https://user-images.githubusercontent.com/17025808/159948734-8505b63f-d9ba-466a-adbc-cc0cf67a864d.png) | text | Variable Names, Attributes Names |
| `nam` | names | ![13](https://user-images.githubusercontent.com/17025808/159948793-8a34dc7d-a579-4274-b220-12d521229c3c.png) | ![13](https://user-images.githubusercontent.com/17025808/159948793-8a34dc7d-a579-4274-b220-12d521229c3c.png) | text | Namespace Names, Class Names, Decorator Names, Exception Names, Function Names |
| `nbr` | numbers | ![14](https://user-images.githubusercontent.com/17025808/159948833-ac2ba43c-043a-4fbc-b767-d6db8ac1bd76.png) | ![14](https://user-images.githubusercontent.com/17025808/159948833-ac2ba43c-043a-4fbc-b767-d6db8ac1bd76.png) | text | All kind of Numbers (integer, float, hex, binary, ...) |
| `err` | errors | ![15](https://user-images.githubusercontent.com/17025808/159948881-946642d2-5879-4de4-bf69-ae7bc756f895.png) | ![15](https://user-images.githubusercontent.com/17025808/159948881-946642d2-5879-4de4-bf69-ae7bc756f895.png) | text OR wavy underline | Errors (the color can be applied to text or only to a wavy underline), Diff Deleted (apply on text) |
| `ins` | inserted | ![16](https://user-images.githubusercontent.com/17025808/159948932-dec8ead2-e38d-4ec7-b101-7bb861cd70d3.png) | ![16](https://user-images.githubusercontent.com/17025808/159948932-dec8ead2-e38d-4ec7-b101-7bb861cd70d3.png) | text | Diff Inserted, Success Messages |

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
- [Polarized Color Palette](https://github.com/BenSouchet/polarized), another cool color palette (based on Solarized).
- [Color Blend](https://bensouchet.github.io/color-blend/), website to blend two colors and generate intermediates colors.
- [mycolor.space](https://mycolor.space/), top wevbsite to find matching colors, generate palettes.
- [Colorizer.org](http://colorizer.org/), super tool to convert and play with colors into multiples color models (HSV, HSL, Lab, ...).

## Author & maintainer
Polarized has been created and is currently maintained by [Ben Souchet](https://github.com/BenSouchet).

All the files present in this repository are under [MIT license](https://github.com/BenSouchet/rowan/blob/main/LICENSE).

---
marp : true
title : Marpit repo template
theme: uncover
paginate: true
footer: 'Gianluca Aguzzi, 2021'
---

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5

---
# Fonts  
*Italic*
**Bold**

---
### Ordered lists
1. first
2. second 
3. third
### Fragmented
1) first
2) second 
3) third

- - -
### Unordered lists
- something fun
- wordy sentence
- wof wof
### Fragmented
* something fun
* wordy sentence
* wof wof
---
# Code (always fun :))
```
trait ScalaSentence {
    def ? : ScalaSentence = this
    def because : ScalaSentence = this
    def it : ScalaSentence = this
    def is : ScalaSentence = this
    def magic() : Unit = println("Yummy")
}
object WhyScala extends ScalaSentence
WhyScala.?.because.it.is.magic()
```
---
# Links
[A good book](https://springframework.guru/gang-of-four-design-patterns/)

---

# Table
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

[Markdown table examples](https://www.markdownguide.org/extended-syntax/)

---
# Citations
> Sometimes it is the people no one can imagine anything of who do the things no one can imagine.
- Alan Turing
---
# Basic images
![w:150 h:150](./images/one.jpg)
![h:150](./images/one.jpg)

---
# Basic filters
| | | | |
| - | - | - | - |
| ![w:50 h:50 blur](./images/one.jpg) | ![w:50 h:50 brightness](./images/one.jpg) | ![w:50 h:50 contrast](./images/one.jpg) | ![w:50 h:50 contrast](./images/one.jpg) |
| ![w:50 h:50 drop-shadow](./images/one.jpg) | ![w:50 h:50 grayscale](./images/one.jpg) | ![w:50 h:50 hue-rotate](./images/one.jpg) | ![w:50 h:50 invert](./images/one.jpg) |
| ![w:50 h:50 opacity](./images/one.jpg) | ![w:50 h:50 saturate](./images/one.jpg) | ![w:50 h:50 sepia](./images/one.jpg) | ![w:50 h:50](./images/one.jpg) |

---
# Marpit directive
## Fit entirly<!-- fit -->

---
<!-- class : invert -->
# Change class
---
<!-- 
footer: 'Change footer here'
class: normal
-->
# Why not theme? :)
---
marp: true
theme: gaia
---
# <!--fit--> MARP in action

![h:150 w:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)

---

## Starting

This is how things works

1. you have the page props

```fontmatter
---
marp: true
theme: gaia
---
```

& there are more options

---

## The typography - 1

| visually | Syntax |
|-|-|
|**bold**|`**bold**`|
|*italic*|`*italic*`|
|~~strikethrough~~|`~~strikethrough~~`|
|`code`|`` `code` ``|

> **Note**: Marp dose not support `html` allow html tags by default except `<br>` tag.

---

## The typography - 2

Headings: replace `#` with `##` to `######` for `h1` to `h6`

```md
## This is head 1 ( max size )
### This is head 2
```

*rendered as*

## This is head 1 ( max size )
### This is head 2

---

## The Images

```md
![image props](url)
```

> A rather unscalled image

![image](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)

---

## The image scale

```md
![w:150 h:150](url)
```

![w:1 h:1](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:6 h:6](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:11 h:11](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:16 h:16](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:21 h:21](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:26 h:26](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:31 h:31](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:36 h:36](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:41 h:41](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:46 h:46](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:51 h:51](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:56 h:56](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:61 h:61](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:66 h:66](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:71 h:71](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:76 h:76](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:81 h:81](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:86 h:86](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:91 h:91](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:96 h:96](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:101 h:101](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:106 h:106](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:111 h:111](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:116 h:116](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:121 h:121](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:126 h:126](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:131 h:131](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:136 h:136](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:141 h:141](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![w:146 h:146](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)

Size in action ( 1 to 146 )

---

## The Images - 2

Marp has some props to control images

### Image filters

| effect | syntax |
|- |-|
| blur | `![blur:5px](url)` |
| brightness | `![brightness:0.5](url)` |
| contrast | `![contrast:0.5](url)` |
| drop-shadow | `![drop-shadow:5px 5px 5px rgba(0,0,0,.5)](url)` |
| grayscale | `![grayscale:1](url)` |

---

|||
|-|-|
| hue-rotate | `![hue-rotate:90deg](url)` |
| invert | `![invert:1](url)` |
| opacity | `![opacity:0.5](url)` |
| saturate | `![saturate:0.5](url)` |
| sepia | `![sepia:1](url)` |

You can apply CSS filters to image through markdown image syntax. Include `<filter-name>(:<param>(,<param>...))` to the alternate text of image.

---

## Image filters

![blur:5px w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![brightness:0.2 w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![contrast:0.5 w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![drop-shadow:2 5px 5px 5px rgba(0,0,0,.5) w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![grayscale:1 w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![hue-rotate:90deg w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![invert:1 w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![opacity:0.5 w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![saturate:0.5 w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)![sepia:1 w:150 h:150](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)

All effects in action ( in order )

---

## Image background

```md
![bg](url)
```

![bg](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)

> `This how you can set an image as a background for one slide`

---

### Background props

|keyword| Description|
|-|-|
| cover | Resize the image to cover the entire container, even if it has to stretch the image or cut a little bit off one of the edges |
| contain | Resize the image to make sure the image is fully visible |
| fit | Resize the image to fit the container, keeping the aspect ratio and without cropping or stretching the image |
| auto | Set the background size to its default value |
| `x%` | scaling factor by percentage value |

---

## `Multiple backgrounds`

![bg](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)
![bg grayscale](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)
![bg](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)

`This is how you can set multiple backgrounds for one slide`
`just add more images with bg keyword`

```md
![bg](url)
![bg](url)
![bg](url)
```

---

## Split backgrounds

```md
![bg left](url)
```

![bg left](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)

**format**: `![bg <position>](url)` and the position can be `left` or `right`

---

## split backgrounds - 2

![bg right:20%](https://i.pinimg.com/1200x/ba/92/7f/ba927ff34cd961ce2c184d47e8ead9f6.jpg)

**format**: `![bg <position>:<size>](url)` and the size can be `x%`

**example**:

```md
![bg right:20%](url)
```

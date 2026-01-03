[:house: < README](./README.md)

---

# Text Formating

Escaping characters with: `\`:

`*Italic*` :arrow_right: *Italic*
`\*Italic\*` :arrow_right: \*Italic\*


---

## Emphasis

| Markdown | Rendered Text |
|-|-|
|`*Italic*`|*Italic*|
|`**Bold**`|**Bold**|
|`~~Strikethrough~~`|~~Strikethrough~~|

A combination is also possible e.g.: 

`~~**Bold** *Italic*~~`

~~**Bold** *Italic*~~

---

## Text Style

### Inline Code

```Use `git status` to check state.```

Use `git status` to check state.


### Code Block

````
```c++
#include <iostream>
inline void foo(){
    std::cout << "Hello, World!\n";
}
```
````

```c++
#include <iostream>
inline void foo(){
    std::cout << "Hello, World!\n";
}
```

the `c++` tag can be used to specify language specific syntax-highlighting. 

---

## Blockquotes

```md
> first level quote
> > second level quote
>
> one line is needed to go back to first level
```

> first level quote
> > second level quote
>
> one line is needed to go back to first level

---

## Footnotes

`Reference something with a footnote[^1]`

Reference something with a footnote[^1]

`[^1]: Content of the footnote`

[^1]: Content of the footnote

---

## Lists

### Unordered

```md
- Item
  - Sub-item
    - Sub-Subitem
      - ...
```

- Item
  - Sub-item
    - Sub-Subitem
      - ...

### Ordered

```md
1. First
2. Second
   1. first
   2. second
      1. first
      2. second
         1. ...
3. ...
```

1. First
2. Second
   1. first
   2. second
      1. first
      2. second
         1. ...
3. ...


### Task Lists

```md
- [x] Done
  - [ ] not done
- [ ] Not done
```

- [x] Done
  - [ ] not done
- [ ] Not done

---

## Tables

```md
|Name|Value|
|-|-|
|A|4|
|B|2|
```
|Name|Value|
|-|-|
|A|4|
|B|2|

Spacing does not matter:
```md
|    Name|    Value|
|    -|------   |
|   A   |4|
|B|2                |
```

Automatic text alignment:

```md
|left aligned|central|right aigned|
|:-|:-:|-:|
|A |1  |i |
|B |2  |ii|
```
|left aligned|central|right aigned|
|:-|:-:|-:|
|A|1|i|
|B|2|ii|


---

[:arrow_up: Back to Top](./text.md) 
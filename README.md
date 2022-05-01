# Markdown notes

## 1. Common Syntax

### 1.1 Title

```markdown
# First-level Title
## Second-level Title
### ...
```

### 1.2 Typeface
**Bold type**

*Italic*

***Bold and Italic***

~Strikethrough~

```markdown
**Bold type**
*Italic*
***Bold and Italic***
~Strikethrough~
```

### 1.3 Unordered List
- first layer
- another line
  - second layer
- ...

```markdown
- first layer
- another line
  - second layer
...
```
### 1.4 Ordered List
1. Ordered List 1
2. Ordered List 2
3. ...

```markdown
1. Ordered List 1
2. Ordered List 2
3. ...
```

### 1.5 Quote
> More is different —— Philip W.Anderson
> 
>  Dorothy followed her through many of the **beautiful** rooms in her castle.  
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```markdown
> More is different —— Philip W.Anderson
> 
>  Dorothy followed her through many of the **beautiful** rooms in her castle.  
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
```
### 1.6 Link
[Link to this page](https://github.com/Zeralt-c/hello-world/edit/readme-edits/README.md)
```markdown
[Link to this page](https://github.com/Zeralt-c/hello-world/edit/readme-edits/README.md)
```

### 1.7 Picture
![My profile picture](https://user-images.githubusercontent.com/76831870/166150134-29fc8a25-34e0-4fdf-b1f1-2b35f9c25616.jpg)
```markdown
![My profile picture](https://user-images.githubusercontent.com/76831870/166150134-29fc8a25-34e0-4fdf-b1f1-2b35f9c25616.jpg)
```

### 1.8 Divider
part A

---

part B
```markdown
part A

---

part B
```

### 1.9 Form
| Index | Project | Deadline |
| :- | :-: | -: |
| 1 | smartknob | X |
| 2 | Machine learning | 2022/5/10/ |
| 1415926 | Anolog electronics | 2022/5/22/ |

```markdown
| Index | Project | Deadline |
| :- | :-: | -: |
| 1 | smartknob | X |
| 2 | Machine learning | 2022/5/10/ |
| 1415926 | Anolog electronics | 2022/5/22/ |
```

## 2. Code Block
Use backticks `` to quote code `printf("hello world")`.

Highlight the code block:
Use three backticks before and after the code block to be highlighted, and **the first line of backticks indicates the language of the code block**

```java
// FileName: HelloWorld.java
public class HelloWorld {
  // Java 入口程序，程序从此入口
  public static void main(String[] args) {
    System.out.println("Hello,World!"); // 向控制台打印一条语句
  }
}
```

The following languages are supported:
```
bash
clojure, cpp, cs, css
dart, dockerfile, diff
erlang
go, gradle, groovy
haskell
java, javascript, json, julia
kotlin
lisp, lua
makefile, markdown, matlab
objectivec
perl, php, python
r, ruby, rust
scala, shell, sql, swift
tex, typescript
verilog, vhdl
xml
yaml
```

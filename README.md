# -> H1 Header <-

----
### -> CheckBoxes <- H3-Header

- [ ] A) This text will be normal
- [x] B) *This text will be italic*
- [ ] C) **This text will be bold**
- [x] D) **This text will be _italic_ inside bold**
- [x] E) ~~Mistaken text.~~

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

----
##### -> Unordered lists (1) <- H5-Header

* A
* B
* C

----
##### -> Unordered lists (2) <- H5-Header

- A
- B
- C

----
##### -> Ordered lists (1) <- H5-Header

1. A
2. B
3. C

----
##### -> Nested lists (1) <- H5-Header

1. Item 1
  1. A corollary to the above item.
  2. Yet another point to consider.
2. Item 2
  * A corollary that does not need to be ordered.
    * This is indented four spaces, because it's two spaces further than the item above.
    * You might want to consider making a new list.
3. Item 3

----
##### -> Inline formats <- H5-Header

Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.

----
----
----
##### -> Code Block <- H5-Header

```
function test() {
  console.log("notice the blank line before this function?");
}
```
----
##### -> Syntax highlighting <- H5-Header

* javascript

```javascript
function test() {
  console.log("notice the blank line before this function?");
}
```
----
* css

```css
.class{
    background-color: #f00;
}
#id{
    background-color: #0f0;
}

```
----
* python

```python
import sys

def Foo():

    """ Comment """
    a = 5;
    b = 5;
    c = a+b;

    print(c)


```
----
* C

```c
#include <stdio.h>

int main()
{
    int a, b, c;
    printf("Enter the first value:");
    scanf("%d", &a);
    printf("Enter the second value:");
    scanf("%d", &b);
    c = a + b;
    printf("%d + %d = %d\n", a, b, c);
    return 0;
}

```
----
##### -> Tables <- H5-Header

* create tables by assembling a list of words

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

----
* For aesthetic purposes, you can also add extra pipes on the ends:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

----
* Note that the dashes at the top don't need to match the length of the header text exactly:

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

----
* You can also include inline Markdown such as links, bold, italics, or strikethrough:

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

----
1. Finally, by including colons : within the header row, you can define text to be 
    1.  :left-aligned 
    2.  right-aligned:
    3.  :center-aligned:

----
----
----


##### -> Images <- H5-Header

![images](http://www.spongebob-spiele.net/images/spongebob.png)


![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

##### -> Links <- H5-Header

[Visit GitHub!](https://www.github.com).

http://github.com - automatic!
[GitHub](http://github.com)

----








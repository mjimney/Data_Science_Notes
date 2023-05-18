Markdown Sample

**######## Key Link ########**  
[Core Markdown Guide ](https://www.markdownguide.org/basic-syntax/)  
[GitHub Guide to Markdown](https://guides.github.com/features/mastering-markdown/)  
[VSCode Guide to Markdown](https://code.visualstudio.com/docs/languages/markdown)

**######## Headers ########**

# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


**######## Horizontal Lines ########**
___

---

***


**######## Font Format (Markdown) ########**

**This is bold text**

__This is bold text__  

*This is italic text*

_This is italic text_

~~Strikethrough~~



**######## Font Format (HTML Tags) ########**

<b>This is bold text</b> 

<u>This is underlined text</u>




**######## Blockquotes ########**

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.

**######## Lists ########**

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar

**######## Code ########**

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting


``` python
# python
def simple_function(x):
    print ('running function')
    return x**2 + 2

simple_function(3)
```

``` sql
-- SQL
select *
from clients
where age > 40
and state = 'NY'
```

``` js
//JavaScript
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

**######## Tables ########**

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


**######## Links ########**

[link text](https://github.com/mjimney/Data_Science_Notes)

[link with title](https://github.com/mjimney/Data_Science_Notes "title text!")



**######## Images ########**

GitHub Images = https://octodex.github.com/

![nyantocat](https://octodex.github.com/images/nyantocat.gif)

![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")


# GitHub Markdown

### Table of Contents
**[What is it?](#what-is-markdown)**  
**[What can you do with it?](#what-can-you-do-with-it)**  
**[Examples](#examples)**  

## What is Markdown?
A type of markup language
* Plain text formatting
* Easily converted to HTML
* Plain text --> Rich text

Two Types:
* Standard Markdown (SM)
* GitHub Flavored Markdown (GFM)

## What can you do with it?
* Styling
* Word formatting
* Add images
* Create Lists (ordered/unordered)
* Links
* Code blocks


# Examples
### Headers
Headers are made using the '#' symbol, and the H1 and H2 tags create an automatic underline on the page.
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

### Bold, Italics, and Strikethrough
These can be accomplished by wrapping a section of a paragraph in either asterisks, underscores or tildes.

```
Italics can be done like *this* or _this_.
Bold can be done like **this** or __this__.
You can also combine bold and italics like **_this_**.
Strikethrough is done with a double tilde like ~~this~~.
```

Italics can be done like *this* or _this_.  
Bold can be done like **this** or __this__.  
You can also combine bold and italics like **_this_**.  
Strikethrough is done with a double tilde like ~~this~~.  

### Lists
Lists are created in two ways: ordered, and unordered.
```
An unordered list uses asterisks like this  
* I want to make
* an unordered list
* using asterisks

An ordered list is created using numbers  

1. This is an ordered list
2. because it uses
3. numbers.  
  * There are also sub-lists 
```
An unordered list uses asterisks like this  
* I want to make
* an unordered list
* using asterisks

An ordered list is created using numbers  

1. This is an ordered list
2. because it uses
3. numbers.  
  * There are also sub-lists 


### Links
Links can be created by wrapping a paragraph in square brackets [] and parentheses ()
```
Doing this will create a link to the [google homepage](http://www.google.com)
You can even add a description for when you [hover over the link](http://www.google.com "Google Homepage")!
```
Doing this will create a link to the [google homepage](http://www.google.com).  
You can even add a description for when you [hover over the link](http://www.google.com "Google Homepage")!

### Codeblocks and Syntax Highlighting
You can create a code block that stands out from the other text. Then specify a language to highlight the code!
```
By using three back-ticks (```) before and after the code you can create a code block!
```  
If you specify a language directly after the first three back-ticks, it will autmoatically highlight the syntax for that code block.  

* ```java

```java
class HelloWorldApp {
    public static void main(String[] args) {
        System.out.println("Hello World!"); // Display the string.
    }
}
```


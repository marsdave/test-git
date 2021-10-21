# test-git
Repository for testing out GitHub.

## Branches
Instead of committing this change of the readme directly to the main branch, I have created a new branch (which has since been deleted). The changes can then later be pulled into the main branch via "pull request".

## Markdown
Here I am testing out *different* Markdown **syntax**.

### Lists
Here is an unordered list:
* First item
* Second item
  * First item in sub-list
    * First item in sub-sub-list - why is the markdown text for this red?
      * First item in sub-sub-sub-list - here the markdown is black again.
        *  The list icon does not change anymore.

Now here is an ordered list:
1. First item in ordered list
1. Second item
   1. Sub-lists... 
   2. ...require an additional space here.
      1. Sub-sub-list
         1. Sub-sub-sub-list

### Code segments
Inline code can be done this way: `print("Hello World")`, whereas dedicated code windows are done this way:

    if isCode
      return true
      
Another way to do the same is called *code fencing*, and works like this:
```
if isCode
  print("Success!")
```
However, this method uses accent graves, which I think is just awful. I do not know which option I prefer, I feel like there could have been a better way to implement coding...

### Images

![Test Logo](/images/logo.png)
Format: ![Alt Text](url)

Let's see if that works.

### Links and Quotes
http://github.com - automatic!
[GitHub](http://github.com)

Oppenheimer quote (which he himself had translated from a Sanskrit version of the Baghavad Gita):
> Now I am become Death, destroyer of worlds.

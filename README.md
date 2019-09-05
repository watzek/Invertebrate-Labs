Welcome to Invertebrates! Your local *Spineless* Wonders!  
=========================================================
This repository contains all the labs needed for BIO-212 (Invertebrate Zoology)  
The following, is instruction for setting up everything you will need!  
If you have any problems or questions, come to the DI office (Watzek 343, up the stairs to the left)

## Setup
1. **<font color="teal">Download the lab files</font>**
  - Scroll up on this page, and click the green 'Clone or download' button
  - Select Download ZIP
  - Unzip the file!  


2. **<font color="teal">Create a Watzek Datasci account</font>**
  - Navigate to [Watzek Datasci](https://datasci.watzek.cloud)
  - Click 'sign in', and sign in using your **lclark email address and password**  
  - When prompted, create a new password for datasci
      - *we recommend using your lclark password, so you don't forget it*
  - Click ['Jupyter Notebooks'](https://jupyter.datasci.watzek.cloud)  


3. **<font color="teal">Upload files to Jupyter</font>**
  - Click 'upload' on the upper-right side of the page
  - Select each lab (Lab 1-8)
  - For each lab, select Upload
  - Yay! You're done!  



Markdown
=====================================
Markdown lets you add formatting to text such as *italics*, **bold**, <font color="red">Colored Text</font>, [Links](https://www.youtube.com/watch?v=dQw4w9WgXcQ), and more!

By learning a little bit of syntax, you can use this tool to turn plaintext directly into HTML (what websites are made of). This document and all of the labs are made using markdown.

## Using Markdown in Jupyter notebooks  
To start using markdown in Jupyter:
1. click 'New' and select a language from the top 'Notebook'section (Python 2, Python 3, R, SageMath, it doesn't really matter for our purposes).
2. You will be taken to a new webpage containing the notebook you just created
3. Select the sole cell on the page, and select Cell > Cell Type > Markdown from the top menu
4. Select the input section of the cell and you can type freely

**To Create a new Cell**
Insert > (Above or Below) *or* press 'a' or 'b'
**To Run a Cell (Render the Markdown)**
Cell > Run Cells *or* press shift+enter

## Markdown Basics  
We will cover some of the basics here, and any additional information can be found in the 'Links' section below.

**To italicize text, simply surround it with '*'**
```
don't put any spaces after the fist * or before the last,
*This is italicized*
* This is not *
```

**To bold text, surround it with two '*'**
```
again, beware the spaces
**This is Bold**
** This is Not**
```

**To add a header, prepend the text with #**
```
You can add multiple #'s to make the header smaller/less important

# Header 1
## Header 2
## Header 3

remember the space after the #'s!
#This is not a header
```


**To add color to text**
```
prepend the text with <font color="MyColor">,
and append </font>

only some colors are supported, including:
purple
red
blue
green
etc.

if you want to make text bold/italic/header and colored, put the *,**,# on the outside of the <font></font> tags
```

**To make a link**
```
use this formatting:

[words to appear in place of the link](the actual link)

For an image, but an ! before it all
![Alternate text (if image is broken)](link to a picture)
```

**To make lists**
```
*, -, + all work for bullets, remember a space after the bullet

* list item 1
* another 1
- you get it

For ordered lists, just use numbers and a '.' instead
you don't even have to use the correct numbers

1. First item
2. Second
3. Third
9. Fourth
10. Fifth

the numbers will be displayed as 1,2,3,4,5
```


The 'Links' section below has some links to websites that go over all of the markdown syntax.


Links
=============
**Resources**
* [One](https://commonmark.org/help/)
* [Two](https://daringfireball.net/projects/markdown/)
**Other**
* ['Markdown Here' Chrome Extension](https://chrome.google.com/webstore/detail/markdown-here/elifhakcjgalahccnjkneoccemfahfoa)

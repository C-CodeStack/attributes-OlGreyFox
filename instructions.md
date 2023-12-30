# HTML ATTRIBUTES

Attributes are words in the opening tag that control the behavior or appearance of an element.

## Task 1

Find the opening ```<body>```tag.

Add the following code:

```<body style="background-color:gray">```

Run the code.  Notice your background is now gray.

The name of the attribute **(style)** is written first, followed by an equal sign. 

The **name** of the property you are changing  **(background-color)** is next.

Then add a colon.

Next is the value of property you are changing. **(gray)**.

(Change the background color to suit your preference)


## Task 2 ##

Find the ```<h1>``` element with the words 'The Boxer'
Add the following code to the opening ```<h1>``` tag:

```<h1 style="color:orange">```

Once again:

**Style** is the attribute you are changing. 
**color** (text color) is the name of the property you are changing.
**orange** how you are changing the property, or the **value of the property** .

(Change the color of the heading to suit your preference)

## Task 3 ##

You can change more than one style value at a time.

Add the following code to the your ```<h1>``` element you changed in the  previous task:

```<h1 style="color:gray; font-size:48px">```

Each additional value should be written in between the same quotation marks, and should be separated by a space and a ```;```  Semi-colon.

## Task 4 ##

Instead of using ```<i>``` tags to create italics, you can use a style attribute.  Add the following code to the opening ```<h2>``` tag:

 ```<h2 style="font-style:italic; font-size:24px">```

 ## Common Font Properties:

```font-family```	Specifies the font family for text.

[Click Here for Info on Websafe Fonts](https://www.w3schools.com/cssref/css_websafe_fonts.asp)

```font-size```	Specifies the font size of text. This is usually done in pixels like this: ```12px```

```font-style```	Specifies the font style for text	(normal, italic, oblique, inherit)

```font-weight```	Specifies the weight of a font	normal, bold, bolder, lighter, 100, 200, 300, 400, 500, 600, 700, 800, 900, (Careful, many of these are not supported!)


 ## Task 5: Challenge! ##

 Using the style attributes, change all of the font-size ```<p>``` elements to 12 pixels ```12px```.  Change the font-family to ```Helvetica```.

### Common Text Properties

Here are some common text values to use with the style attribute:

```color``` changes the color.   You can use simple color names (red, blue, green, etc.) or you can use color hex codes:

[Click Here for More Info on Color Hex Codes](https://www.color-hex.com/)

```text-align```	Aligns the text in an element	left, right, center, justify

```text-decoration```	Adds decoration to text	none, underline, overline, line-through

## Task 6

Add some text-decoration and color to the ```<h2>``` element.


## Hyperlinks ##

You can use ```<a>``` tags to create a hyperlink.  A hyperlink is something you can click to take you to another document, or another location in the same document. You can use a ```href``` attribute to define where the hyper link takes you.

## Task 7

**Find the Wikipedia link above the first paragraph. Add an ```<a>``` tag and a ```<href>''' element like this:**

```<a href="https://en.wikipedia.org/wiki/Boxer_(dog)">LEARN MORE</a>```

The words **LEARN MORE** are the only part of the element you will see on the page. This is what you click to go to the specific hyperlink location.

**Test the link.**

## Task 8

If you notice, the link you click opens in the same browser window.  You can add an additional attribute ```target="_blank"``` to make the link open in another browser window.

**Add the attribute ```target="_blank" to the wikipedia link like this:**

```<a href="https://en.wikipedia.org/wiki/Boxer_(dog)" target="_blank">LEARN MORE</a>```

## Task 9: Challenge ##

Add a hyperlink underneath the Wikipedia link that points to the URL below. The "clickable" words are up to you. Add a target attribute so that the link opens in another window:

https://www.akc.org/dog-breeds/boxer/


 ## Image Attributes ##

 You can add images to your HTML page using an ```<img>``` tag.  You add attributes to an ```<img>``` to define the source of the image, the size, and many other properties.

## Task 10

** Copy the code below and paste it in a new browser tab or window:**

https://upload.wikimedia.org/wikipedia/commons/6/6f/Male_fawn_Boxer_undocked.jpg

You should see a picture of a boxer.  Now paste the same code into your HTML file,  above the ```<h1>``` element.

Add an ```<img>``` tag and attribute like this:

```<img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Male_fawn_Boxer_undocked.jpg">```

```src``` is a SOURCE attribute.  The code is telling the browser to display the image from that location.

**You don't need a closing tag for ```<img>``` elements.** 

## Task 11 ##

Look at the file tree on the left.  You will see several image files in the same folder as your html file.

To display an image that is in the same folder (or file directory) use the file name as the source. Add the code below to your html page, after the hyperlinks.

```<img src="boxer01.jpeg">```

**Add an  ```<img>``` tag for ```boxer02.jpeg``` underneath the first picture.**

## Task 12: Resizing Images ##

You will notice that the images are too big.  You can add a ```width``` or ```height``` attribute to resize images. 

You can change the size by percentage:

```<img src="boxer01.jpeg" width="50%">```

Or you can use exact pixel measurements:

```<img src="boxer01.jpeg" width="250px">```

If you change *** just *** the width, the height will also change in proportion.  If you know the exact width and height of the image, you can add a ```height``` attribute to change both separately.

**Reduce the size of all images by 50%.**

## Block vs Inline

If you notice, when you add images and hyperlinks, they appear on the page adjacent to each other.  Headings and Paragraphs begin on a new line. 

Headings and Paragraphs are **Block-Level** elements. They always start on a new line. Browsers usually add space before and after a block-level element.  Block elements take up the full width of the page.

Images and Hyperlinks are  **Inline** elements.  Inline elements do not start on a new line and they  take only as much space as necessary.

## Task 13

For now you can add  a ```<br>``` tag after each Hyperlink and Image.






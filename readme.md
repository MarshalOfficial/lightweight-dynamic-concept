# Light Dynamic Concept!

In this concept we will use a **Dynamic** mechanism to create and rendering fully functional web or mobile apps. It will be hard at first to create database, API and front-end infrastructure, and then be easy to maintain and develop your product with less coding.


# Basic Objects

They are multiple basic object that we use to processing user interface elements and behavior of the forms.


## Reports

Every list-view that shows data by rows, we call it report here, and will have multiple columns with some properties that will say below.


## Actions

Every form that show some input on it and have button to submit a request, we call it an action here.

## Menu

A hierarchic tree base menu that will shown as admin panel, which item of menu will be used for a report or an action.

## Metadata
The core data information about objects, we name it metadata or meta. Each object has its own meta information, for example a menu item meta information will show title, type and etc, an action meta information will show what are input parameters of action and what and how many submit button does it need. don't worry we will explain more and detail about it later in below.



# Scenario

The Back-end will response to front-end some metadata that consist of menus, front-end will populate and hold menus metadata, then shown the menus to the user, each menu will be for an object of an action or report, when user click on an action menu, front-end will dynamically generate a form with inputs and button that metadata said for this action, or when user click on a report menu, front-end dynamically generate report page in row and column base list-view with some optional filter in header of the page.
With this platform we can do most of functional software needs dynamically and the front-end code will be with the least changes and with back-end we will generate multiple forms and report that users need.
There is no matter you use which language, framework and stack for you'r database, back-end rest API and front-end, for me these days i am using MS SQL server database engine, python FastAPI framework for the rest API and angular or react for the front.
	
## Menu

## Action

## Report

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg3NDkwODY4NiwtMTQxNjcwNjMzNiw3MD
M3NTA5NDYsMTU0NDkxNTIzMiw0MzMzNTM3MDUsMzMyMjg3MjAs
LTM4Mzk1OTUyNiwtMTc1NTkxNjIyMiwtMjAyNDM3NjQ0MiwxMT
g1NDc2MjY1LDMxNTQyMDExMiwtMzMyNDU1MzYzXX0=
-->
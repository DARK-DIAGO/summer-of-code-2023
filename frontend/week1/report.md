# How the page is divided into nested elements(Tree_Structure) 

When we look at a web page, we can see that it is made up of different parts, just like how a tree has branches. These parts are called elements. Imagine the main element as the trunk of the tree, and other elements are like branches that come out from it. Some elements have their own branches too! This nesting of elements forms a tree-like structure.

By looking at the elements and how they are nested, we can see if they resemble a tree. We can also use special tools to explore and understand the elements better.


# Editing Properties of Elements [Ctrl+Shift+I]
Did you know that we can change how a web page looks? Each element on a page, like buttons or text boxes, has different properties like colors, sizes, and positions. By editing these properties, we can make the page look different. For example, we can change the color of a button or make a text box bigger. It's like having a magic wand to transform the appearance of a web page!

Remember, though, these changes are only visible on our own computer and don't affect the actual website. It's a fun way to explore and play with the design of a page.



# CSS Selectors
document.querySelector("#username") selects an element with the ID "username".

Once we've selected an element, we can use the dot (.) operator to manipulate it. We can change its style or get information from it. For example, to get the value of an input field, we can use element.value.

## Some CSS Selectors
#id	#firstname	Selects the element with id="firstname"
| CSS Selector | Example    |
| :-----: | :---: |
| #element-id | document.querySelector("#username")   |
| .class-name | document.querySelector(".container")   |
| tag-name | document.querySelector("h1")   |
| parent-selector child-selector | document.querySelector(".container .title")   |
| selector1, selector2 | document.querySelector("input, textarea")   |
| [attribute-name="value"] | document.querySelector('[data-type="submit"]')   |


# <link> and <script>
In the Network tab of the browser's developer tools, we can see the requests made by the web page to load different resources like HTML, CSS, and JavaScript files. When we reload the page, we can observe these requests and how they are related to <link> or <script> tags in the page's code.

# Disable Cache
"Disable Cache" affect the loading. Disabling cache makes the browser fetch all resources again instead of using cached versions, which can help in testing and debugging.

# Throlling
we use the throttling feature in the developer tools to simulate different network conditions. This helps us understand how the web page performs under slow connections or limited bandwidth.


## BONUS
# CSS
CSS (Cascading Style Sheets) justifies its name as styles can be inherited from parent to child elements, allowing for efficient and consistent design across a web page.

# Event Listeners [Note]
Removing these event listeners on interactive elements like buttons would result in the loss of their intended functionality, rendering them unresponsive to user input and impacting the overall interactive experience of the website.


# Observe the HTTP requests, and see what (memory cache) and (disk cache)
Memory Cache : **The memory cache stores recently accessed web page resources for faster retrieval.**

Disk Cache : **The disk cache stores web page resources on the hard drive for quicker access in subsequent visits.**


**Why is the size of the page transferred less than the total resources?**
The size of the page transferred is often less than the total resources due to caching. Cached resources are stored locally, reducing the need to fetch them again from the server, resulting in faster loading times and less data transfer.
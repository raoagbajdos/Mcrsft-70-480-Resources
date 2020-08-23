IT Exams VQ Q&A
span element - The <span> tag is an inline container used to mark up a part of a text, or a part of a document.
The <span> tag is easily styled by CSS or manipulated with JavaScript using the class or id attribute.
The <span> tag is much like the <div> element, but <div> is a block-level element and <span> is an inline element.
e.g.
A <span> element which is used to color a part of a text:
<p>My mother has <span style="color:blue">blue</span> eyes.</p>
<ul> - unordered list
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>


document.getElementById(“Div1”.appendChild(document.getElementById(“Span1”))


function validate() {
    var value = $(“#txtValue”).val();
    If (!regex.test(value) || value == “”)
    alert(“please enter valid value”);
    return;
    }
return emailPattern.test(user input):



<form>
Email:
<input type=“email” name=“email”/>
</form>




str=$(“form”).serialize();
str=decodeURIComponent(str);



// at line 06, replace the code with the following code:
url: "http://contoso.com/Service.svc/GetCountry? Username=username&password=password",


xhr.upload.onprogress =






accepts: ‘application/bint, text/xml’
// use the following condition to check if the html response content is binary: If(request.getResponseHeader(“Content-Type”)==“application/bint”
var request = $.ajax({
    uri: ‘/‘,
    accepts: ‘application/bint.text/xml’,
dataFilter: function (data, type) {
if(request.getResponderHeader(“ContentType”)== “application/bint”)
    return parseBint(data);
else
    return parseXML(data); {
},
success: function (data) {
    start(data);
}
});




<input type=“range”
    min=“18” max=“90”
step=“5” value=“37”
Required/>




function Loader() {
    this.status = “ready”
    this.temp = 50;
    this.updateStatus = function (newStatus) {
        this.status = newStatus;
    };
}

window.status property - The status 






<figure>
<img src=“details.png” />
<figcaption>
Image description
</figcaption>
</title>




Answer - B
document.getElementById(divName).appendChild(newInputDiv);

Explanation:
We create a now div element with the textbox.
We then use appendChild() method appends this node as the last child the input node divname.
References:
https://www.w3schools.com/jsref/met_node_appendchild.asp



var para = document.createElement("a");
var attr = document.createAttribute("href");
attr.value = "help.html";
para.setAttributeNode(attr);
var node = document.createTextNode("Help");
para.appendChild(node);
var element = document.getElementById("navlist");
element.appendChild(para);





self.addEventListener(‘message’, function(event));
…
self.postMessage(‘Worker: ‘ + data);
…
self.close

Explanation:
Box 1:
addEventListener
The addEventListener() method attaches an event handler to the specified element.
In context of a worker, both self and this refer to the global scope. The worker can eitheradd an event listener for the message event, or it can define the onmessage handler to listen for any messages sent by the parent thread.
Box 2:
postmessage
Pass a message to the worker.
Box 3:
close()




Terminating Workers -
Workers are resource-intensive; they areOS-level threads. Therefore, you do no want to create a large number of worker threads, and you should terminate the web worker after it completes its work. Workers can terminate themselves, like this: self.close();
Reference:
https://www.w3schools.com/jsref/met_document_addeventlistener.asp https://www.html5rocks.com/en/tutorials/workers/basics/




Answer - B & C
From the main page, use the onmessage event handler of the web worker to capture events

From the web worker, use the onmessage event handler of the main page to capture events



$(document).ready(function () {
    $(’table td: nth-child(2) input’).focus(
        function () {
        $(this).parent().next().css
        (“background-color”, “#00F00”);
    });
    $(’table td: nth-child(2) input’).blur(
        function () {
            $(this).parent().next().css
            (“background-color”, “#FFFFFF#);
    });
});



@media screen and (min-width: 200px) and (max-width: 480px)
…
@media screen and (min-width: 480px)






The flexibility ratio for this child. If a child had 1 and its sibling had 2, any additional space in the parent box would be consumed twice as much by the sibling. It defaults to 0, which is inflexible



Answer - B
onreadystatechange: Sets or retrieves the event handler for asynchronous requests




var ctry = document.getElementById(“Country”).value;

if (!arr[ctry]) {

var txt = “Country is not valid.”;
txt += “Valid values are”;

for (var 1 in arr)
    if (are(i) txt +=I+””;
document.getElementById(“valid”).innerText = txt;
    }
}
</script>


A - JSON
D - String
E - JavaScript





<body>
    <input id=“btnSubmit” type=“button” value=“Submit” onclick=“disable(this)” />
    <script>
        function disable(ctrl) {
    )
    <script>
</body>

Answer - A





var canvas = document.getElementById(‘mycanvas’);
…
context.fillStyle = “rgb(255,0,0)”;
context.fillRect(50,50,100,100)”;




document.getElementById(“picture”).style.position = “relative”
document.getElementById(“picture”).style.top = “5px”;



<section>













<style type=“text/css>
    #grid {
        display: -ms-grid;
        -ms-grid-columns:100px 250px 100px 250px 100px;
        -ms-grid-rows: auto;
        }
</style>



Solution - B
Answer - B
Add the following style to the site.css file:
div#container > ul {
   border: 1px solid black;
}

Explanation
CSS File:
ul {
border: 1px solid black;
}
Inline CSS:
<ul class="container" style="border: 1px solid black">



Answer - B

if (typeof (e) == ValidationException) {
    handleValidationException(e.message);
} else if (e instanceof LogicException) {
    handleLogicException (e.message);
} else }
    throw e;
} 






var items = document.getElementByTagName(“li”)

for (var i=0, 1=items.lenngth; i<1;
i++)
languages.push(items(i).innerHTML);

languages.sort();

for (var i=0, 1=items.length; i<1;
i++)
items(i).innerHTML = languages(i);


The getElementsByTagName() method accesses all elements with the specified tagname.
Example:
// Get the listitems and setup an array for sorting
var lis = ul.getElementsByTagName("LI");
var vals = [];
// Populate the array
for(var i = 0, l = lis.length; i < l; i++)
vals.push(lis[i].innerHTML);
// Sort it
vals.sort();
// Sometimes you gotta DESC
if(sortDescending)
vals.reverse();
// Change the list on the page
for(var i = 0, l = lis.length; i < l; i++)
lis[i].innerHTML = vals[i];

Push before you sort



$.each(jsonFruit, function (key, val) {

$(“#fruitTable”).append($<tr><td>” + key”</td><td>” + val + “</td></tr>”));

});

Iterate (.each) —> append



this.img = document.createElement(‘img’);

img.alt = img.Description;
img.src = image.FileName;

return this.img;

Image Object -
The Image object represents an embedded image.
For each <img> tag in an HTML document, an Image object is created.
Notice that images are not technically inserted into an HTML page, images are linked to HTML pages. The <img> tag creates a holding space for the referenced image.
Image Object Properties include:
-> alt, Sets or returns the value of the alt attribute of an image
-> src, Sets or returns the value of the src attribute of an image









message: body,
filename: FileName

Properties: key value pairs 






400, 800, 1000, another

Explanation:
* The innermost assignment to the loanAmount variable should be the highest.
* Local variables have local scope: They can only be accessed within the function.

* A variable declared outside a function, becomes GLOBAL.
A global variable has global scope: All scripts and functions on a web page can access it.




e.dataTransfer.setData(’text’, target.id);
…
var id = e.dataTransfer.getData(’text’);

setData —> getData




req.onreadystatechange=function() {

req.open(“GET”, “TextFile.txt”, true);
req.send();

Explanation:
* onreadystatechange
When a request to a server is sent, we want to perform some actions based on the response.

The onreadystatechange event is triggered every time the readyState changes
.
The readyState property holds the status of the XMLHttpRequest.

Example:
xmlhttp.onreadystatechange=function()
{
if (xmlhttp.readyState==4 && xmlhttp.status==200)
{
document.getElementById("myDiv").innerHTML=xmlhttp.responseText;
}
}
* Send a Request To a Server
To send a request to a server, we use the open() and send() methods of the XMLHttpRequest object: xmlhttp.open("GET","xmlhttp_info.txt",true); xmlhttp.send();

References:
https://www.quanzhanketang.com/ajax/ajax_xmlhttprequest_onreadystatechange.html https://www.w3schools.com/js/js_ajax_http.asp







navigator.geolocation.watchPosition
(locSuccess, locFai);
…
var spd = position.coords.speed;







#content {display: -ms-flexbox;
        -ms-flex-direction: row;
…
#content #main {-ms-flex: 1;


// Explanation:
* -ms-flexbox
To enable flexbox layout, you must first create a flexbox container. Do this by setting the display property of an element to either "-ms-flexbox" (for a block-level flexbox container) or "-ms-inline-flexbox" (for an inline flexbox container).

* -ms-flex-direction: row;
When creating a flexbox container, you can also set its orientation that is, specify whether its children are displayed from right-to-left, left-to-right, top-to-bottom, or bottom-to-top.

* -ms-flex
Specifies whether the width or height of a child element is flexible based on the space available in the object. This value also indicates the proportion of space available that is allocated to the child element.
References:
https://technet.microsoft.com/en-us/learning/hh673531(v=vs.94).aspx




Explanation:
* contentType
contentType is the type of data you're sending.
We have to send the content-type of application/soap+xml as this is the only type that the web service allow.
* type
We post a SOAP request.
* dataType:
dataType is what you're expecting back from the server: json, html, text, xml, etc. jQuery will use this to figure out how to populate the success function's parameter.




if (window.XMLHttpRequest) {

xmlhttp = new XMLHttpRequest();)

else {

xmlhttp = new ActiveXObject(“Microsoft.XMLHTTP”);)

xmlhttp.open (“GET”, “message.xml”, false);

xmlhttp.send();

xmlDoc = xmlhttp.response.XML



Parse an XML Document -
Example. The following code fragment parses an XML document into an XML DOM object: if (window.XMLHttpRequest)
{// code for IE7+, Firefox, Chrome, Opera, Safari
xmlhttp=new XMLHttpRequest();
}
else
{// code for IE6, IE5
xmlhttp = new ActiveXObject(“Microsoft.XMLHTTP”);
}
xmlhttp.open(“GET”,”books.xml”,false);
xmlhttp.send();
xmlDoc = xmlhttp.responseXML;







$(this).serializeArray();



$(‘#btnEdit’).show();

// With jQuery, you can hide and show HTML elements with the hide() and show() methods:





* The <select> element is used to create a drop-down list.
The <option> tags inside the <select> element define the available options in the list.
* option.value
text
Specifies the value to be sent to a server
Reference:
https://www.w3schools.com/tags/tag_option.asp














Explanation:
When readyState is 4 and status is 200, the response is ready:

Example -
xmlhttp.onreadystatechange=function()
{
if (xmlhttp.readyState==4 && xmlhttp.status==200)
{
document.getElementById("myDiv").innerHTML=xmlhttp.responseText;
}
}
Note:
* readyState == 4
Holds the status of the XMLHttpRequest. Changes from 0 to 4:
0: request not initialized
1: server connection established
2: request received
3: processing request
4: request finished and response is ready
* status==200
200: "OK"
404: Page not found



Answer : D
$.ajax({
    url: “Services/WSAjax.asmx/GetPopulationCity”,
    dataType: “text”, type: “POST”, data: { city: “Boston” }
});


Explanation:


* type:
We post a SOAP request.

* data:
Data to be sent to the server.

The data option can contain either a query string of the form key1=value1&key2=value2, or an object of the form {key1: 'value1', key2: 'value2'}.


Reference:
http://api.jquery.com/jQuery.ajax/



// to group heading elements use:
<hgroup></hgroup>





type: “POST”,
dataType: “son”,
url: “/product/create"



Answer - B 
readAsArrayBuffer method

The readAsArrayBuffer method is used to read a File, Blob, MSStream into memory as an ArrayBuffer object.

The FileReader interface's readAsArrayBuffer() method is used to start reading the contents of a specified Blob or File. When the read operation is finished, the readyState becomes DONE, and the loadend is triggered. At that time, the result attribute contains an ArrayBuffer representing the file's data.



Explanation:
Example:
Sometimes situations arise when user should fill a single or more than one fields with alphabet characters (A-Z or a-z) in a HTML form. You can write a JavaScript form validation script to check whether the required field(s) in the HTML form contains only letters. â€"
Javascript function to check for all letters in a field
view plainprint?
function allLetter(inputtxt)
{
var letters = /^[A-Za-z]+$/;
if(inputtxt.value.match(letters))
{
return true;
}
else
{
alert("message");
return false;
}
}
To get a string contains only letters (both uppercase or lowercase) we use a regular expression (/^[A-Za-z]+$/) which allows only letters. Next the match() method of string object is used to match the said regular expression against the input value.




squareShape=document.mySquare;
...
myTimer=myTimer.interval(speed.value);
…
squareShape.setAttribute(“transform”, “angle("




$(“form”).submit(function () {

if ($(“input:first”).val() == “OK”) {

return true;
)
return false;
)
);

//Explanation:
first
Selects the first matched element.



The grid-row CSS shorthand property specifies a grid item’s size and location within the grid row by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start and inline-end edge of its grid area.

The grid-column CSS shorthand property specifies a grid item's size and location within a grid column by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the inline-start and inline-end edge of its grid area.





this.loanAmount = 100;
…
this.loanAmount += 1000;
…
this.loanAmount +=1000;
…
myApp.loanAmount);

2100





box-sizing: border-box;

border-radius: 10px;




callback.call(httpRequest.responseXML);
…
processResults(this);




<input type=“password” required autocomplete=“off”>

Explanation:

Input Type: password -
<input type="password"> defines a password field.
The characters in a password field are masked (shown as asterisks or circles).
The autocomplete attribute specifies whether or not an input field should have autocomplete enabled.
The autocomplete attribute works with the following <input> types: text, search, url, tel, email, password, datepickers, range, and color.



Solution - A

var stock = this;
$.get(‘data.xml’, function (data) {
    stock.parseStock(data);
});




ordersListing.dispatchEvent(new CustomEvent
(“ordersReceived”, {
    detail: {
        orderCount: 5
    },
    bubbles: false
    Cancellable: true
}));

ordersListing.addEventListener
(“ordersReceived”, showOrdersReceivedCount);

ordersReceived.dispatchEvent
(ordersReceivedEvent)


<select> element - used to create a drop-down list

Contoso - Contoso. Contoso Ltd. (also known as Contoso and Contoso University) is a fictional company used by Microsoft as an example company and domain. 

SOAP - Simple Object Protocol - web service to retrieve data

.val( ) method {jQuery} - Get the current value of the first element in the set of matched elements or set the value of every matched element.

Syntax
$(selector).val()

//
$(selector).val(value)
When used to return value: 
This method returns the value of the value attribute of the FIRST matched element.

When used to set value: 
This method sets the value of the value attribute for ALL matched elements.
Note: The val() method is mostly used with HTML form elements.
$("button").click(function(){
  $("input:text").val("Glenn Quagmire");
});

.eq( ) method - The eq() method is an inbuilt method in jQuery which is used to locate the selected elements directly and returns an element with specific index.

Parameters: Here the parameter “index” specifies the index of the element.
Can either be positive or a negative number.

NOTE:
* The index number always starts at 0, so the first number will have index 0 (not 1).
* Using a negative number as an index starts the index count from the end of the list.

jQuery code to show the working of the eq() method:
example - below code will select specified elements
<html>

<head>
    <title>GeeksForGeeks articles</title>
    <script src="https://ajax.googleapis.com/ajax/libs/
                 jquery/3.3.1/jquery.min.js"></script>
    <script type="text/javascript">
        $(document).ready(function() {
            $(".heading").eq(0).css("color", "red");
            $(".heading").eq(2).css("color", "yellow");
        });
    </script>
</head>

<body>
    <h1 class="heading">GeeksForGeeks</h1>
    <h2 class="heading">GeeksForGeeks</h2>
    <h3 class="heading">GeeksForGeeks</h3>
    <h4 class="heading">GeeksForGeeks</h4>
</body>
  
</html>

Output

Syntax
$(selector).eq(index)

.text( ) method {jQuery} - Get the combined text contents of each element in the set of matched elements, including their descendants, or set the text contents of the matched elements.
Example:

Find the text in the first paragraph (stripping out the html), then set the html of the last paragraph to show it is just text (the red bold is gone).
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>text demo</title>
  <style>
  p {
    color: blue;
    margin: 8px;
  }
  b {
    color: red;
  }
  </style>
  <script src="https://code.jquery.com/jquery-3.5.0.js"></script>
</head>
<body>
<p><b>Test</b> Paragraph.</p>
<p></p>
<script>
var str = $( "p" ).first().text();
$( "p" ).last().html( str );
</script>
</body>
</html>

Demo:
em {CSS Unit} - length unit where em is Relative to the font-size of the element (2em means 2 times the size of the current font) 

e.g. 5em

URI - Uniform Resource Indicator - A URI (Uniform Resource Identifier) is a string that refers to a resource. The most common are URLs, which identify the resource by giving its location on the Web. URNs, by contrast, refer to a resource by a name, in a given namespace, such as the ISBN of a book..A Data URI (Uniform Resource Identifier) is a scheme that allows data to be encoded into a string, and then embedded directly into HTML or CSS. The more commonly known URL (Uniform Resource Locator) is a subset of Data URI that specifically identifies a resource’s location, such as the IP address of a website.

WCF - is a framework for building service-oriented applications. Using WCF, you can send data as asynchronous ($.ajax) messages from one service endpoint to another.

bint - binary data type - custom binary data type

object.prototype.constructor - JS Object Constructors

Object Types (Blueprints) (Classes)

The examples from the previous chapters are limited. They only create single objects.
Sometimes we need a "blueprint" for creating many objects of the same "type".
The way to create an "object type", is to use an object constructor function.
In the example above, function Person() is an object constructor function.
Objects of the same type are created by calling the constructor function with the new keyword:
// Object Types (Blueprints) (Classes)
var myFather = new Person(“John”, “Doe”, 50, “blue”);
var myMother = new Person(“Sally”, “Rally”, 48, “green”);

// this keyword as a reference to the object

//Adding a Property to the object
myFather.nationality = “English"

function Person(first, last, age, eye) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eye;
}
built-in JavaScript Constructor
var x1 = new Object();    // A new Object object
var x2 = new String();    // A new String object
var x3 = new Number();    // A new Number object
var x4 = new Boolean();   // A new Boolean object
var x5 = new Array();     // A new Array object
var x6 = new RegExp();    // A new RegExp object
var x7 = new Function();  // A new Function object
var x8 = new Date();      // A new Date object

Did You Know?

As you can see above, JavaScript has object versions of the primitive data types String, Number, and Boolean. But there is no reason to create complex objects. Primitive values are much faster.
ALSO:
Use object literals {} instead of new Object().
Use string literals "" instead of new String().
Use number literals 12345 instead of new Number().
Use boolean literals true / false instead of new Boolean().
Use array literals [] instead of new Array().
Use pattern literals /()/ instead of new RegExp().
Use function expressions () {} instead of new Function()
e.g.
var x1 = {};            // new object
var x2 = "";            // new primitive string
var x3 = 0;             // new primitive number
var x4 = false;         // new primitive boolean
var x5 = [];            // new array object
var x6 = /()/           // new regexp object
var x7 = function(){};  // new function object

String Objects

Normally, strings are created as primitives: var firstName = "John"
But strings can also be created as objects using the new keyword: var firstName = new String("John")
Learn why strings should not be created as object in the chapter JS Strings. 
Number Objects

Normally, numbers are created as primitives: var x = 123
But numbers can also be created as objects using the new keyword: var x = new Number(123)
Learn why numbers should not be created as object in the chapter JS Numbers. 
Boolean Objects

Normally, booleans are created as primitives: var x = false
But booleans can also be created as objects using the new keyword: var x = new Boolean(false)
Learn why booleans should not be created as object in the chapter JS Booleans.
JavaScript Object Prototypes
All JavaScript objects inherit properties and methods from a prototype. “prototype inheritance”.

Using the prototype Property

The JavaScript prototype property allows you to add new properties to object constructors:
function Person(first, last, age, eyecolor) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eyecolor;
}

Person.prototype.nationality = "English”;

// The JavaScript prototype property also allows you to add new methods to objects constructors:
function Person(first, last, age, eyecolor) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eyecolor;
}

Person.prototype.name = function() {
  return this.firstName + " " + this.lastName;
};

ASP.net - ASP.NET is an open source web framework, created by Microsoft, for building modern web apps and services that run on macOS, Linux, Windows, and Docker.

> ul - unordered list element - The HTML <ul> element represents an unordered list of items, typically rendered as a bulleted list.
<ul>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
</ul>
Output:


ordersListing.dispatchEvent(new CustomEvent
(“ordersReceived”, {
    detail: {
        orderCount: 5
    },
    bubbles: false
    cancellable: true
}));


ordersListing.addEventListener
(“ordersReceived”, showOrdersReceivedCount);


ordersReceived.dispatchEvent
(ordersReceivedEvent)


Explanation:
* From Scenario: Do not allow other DOM elements to receive the event.




So: bubbles: false -
* From scenario: Allow the event to be cancelled.




So: cancellable: true -
* From scenario:
The webpage must contain an HTML element named ordersListing that will receive the custom event notification.
* Events which are designated as bubbling will initially proceed with the same event flow as non-bubbling events. The event is dispatched to its target EventTarget and any event listeners found there are triggered. Bubbling events will then trigger any additional event listeners found by following the EventTarget's parent chain upward, checking for any event listeners registered on each successive EventTarget. This upward propagation will continue up to and including the Document.
EventListeners registered as capturers will not be triggered during this phase. The chain of EventTargets from the event target to the top of the tree is determined before the initial dispatch of the event. If modifications occur to the tree during event processing, event flow will proceed based on the initial state of the tree.

Note:
* Ajax (an acronym for Asynchronous JavaScript and XML) is a group of interrelated web development techniques used on the client-side to create asynchronous web applications. With Ajax, web applications can send data to, and retrieve data from, a server asynchronously (in the background) without interfering with the display and behavior of the existing page. Data can be retrieved using the XMLHttpRequest object. Despite the name, the use of XML is not required (JSON is often used instead), and the requests do not need to be asynchronous.

this.v3+this.v4;
…
add.call (o. 15. 3) ;

Explanation:
* What is the difference between call and apply?
apply lets you invoke the function with arguments as an array; call requires the parameters be listed explicitly.

Pseudo syntax:
theFunction.apply(valueForThis, arrayOfArgs)
theFunction.call(valueForThis, arg1, arg2, ...)


Partial Solution 1:
.red text
{
color: red;
}

Partial Solution 2:
span#myTextSpan
{
color: red;
}

Answer : AC

Explanation:


You can refer to class, by .redText, or the span, by span#myTextSpan. (id)



Answer - D
Explanation:
Increase the radius (the r property) of the circle (not the graphic) by a factor 1.5.

myCircle.r = myCircle.r * 1.5;

Incorrect:
CurrentScale is used for zooming.
Reference:
https://www.w3schools.com/html/html5_svg.asp

${‘input[name=“*name”]’).css({background=color’: #E0ECF8’});

* - selecting all attributes



Explanation:
Cross-origin resource sharing (CORS) is a mechanism that allows Javascript on a web page to make XMLHttpRequests to another domain, not the domain the
Javascript originated from. Such "cross-domain" requests would otherwise be forbidden by web browsers, per the same origin security policy. CORS defines a way in which the browser and the server can interact to determine whether or not to allow the cross-origin request. It is more powerful than only allowing same- origin requests, but it is more secure than simply allowing all such cross-origin requests.

You must use Cross Origin Resource Sharing
It's not as complicated as it sounds...simply set your request headers appropriately...in Python it would look like: self.response.headers.add_header('Access-Control-Allow-Origin', '*'); self.response.headers.add_header('Access-Control-Allow-Methods', 'GET, POST, OPTIONS'); self.response.headers.add_header('Access-Control-Allow-Headers', 'X-Requested-With'); self.response.headers.add_header('Access-Control-Max-Age', '86400');

CORS - Cross-Origin Resource Sharing - is a mechanism that allows Javascript on a web page to make XMLHttpRequests to another domain, not the domain the
Javascript originated from. Such "cross-domain" requests would otherwise be forbidden by web browsers, per the same origin security policy. CORS defines a way in which the browser and the server can interact to determine whether or not to allow the cross-origin request. It is more powerful than only allowing same- origin requests, but it is more secure than simply allowing all such cross-origin requests.


$(“article:first-of-type”).css(“background-color”, “#f2f2f2”);

Explanation:
The :first-of-type selector matches every element that is the first child, of a particular type, of its parent.
Reference:
https://www.w3schools.com/cssref/sel_first-of-type.asp


input: disabled
…
    document.getElementById(‘eMail’). disabled = false;
} else {

    document.getElementById(‘eMail’). disabled = true; 

Explanation:
The disabled property sets or returns whether an email field should be disabled, or not.
A disabled element is unusable and un-clickable. Disabled elements are usually rendered in gray by default in browsers.

Example -
Disable an email field:
document.getElementById("myEmail").disabled = true; 

Rating (Between 1 and 10): <input=“range” name=“rating” min=“1” max=“10” default=“5”>

Explanation:
input type="range"
The <input type="range"> is used for input fields that should contain a value within a range.
Depending on browser support, the input field can be displayed as a slider control.

Example -
<form>
<input type="range" name="points" min="0" max="10"/>
</form>


xhr.responseType = ‘blob’;
xhr.onload = function(e) {
    if (this.status == 200) {
        img.src = window.URL.createObjectURL(this.response);
        document.body.appendChild(img);

Explanation:
As an image will be returned the response type must be blob, not document.
Similarly, this.response must be used not this.responseText.
Reference:
https://developer.mozilla.org/en-US/docs/Web/API/URL/createObjectURL
The URL.createObjectURL() static method creates a DOMString containing a URL representing the object given in the parameter. The URL lifetime is tied to the document in the window on which it was created. The new object URL represents the specified File object or Blob object.
To release an object URL, call revokeObjectURL().
Syntax
const objectURL = URL.createObjectURL(object)
Parameters
object
A File, Blob, or MediaSource object to create an object URL for.
Return Value
A DOMString containing an object URL that can be used to reference the contents of the specified source object.

Explanation:
parseInt
The parseInt() function parses a string and returns an integer.

Syntax: parseInt(string,radix)
string Required. The string to be parsed

radix Optional. A number (from 2 to 36) that represents the numeral system to be used.

The isNaN() function determines whether a value is an illegal number (Not-a-Number).
This function returns true if the value is NaN, and false if not.




Answer - D

<input name=“SecurityCode”
    type=“password”
    maxlength=“6”
    placeholder=“Enter PIN Code”
/>




image.addEventListener(‘mousemove’, function (e) {

content.innerHTML= “x: “ +e.x + “<br/>y: “ + e.y + “<br/>”;



Explanation:
* border: 1px solid #f00;
a red border 1 pixel thick.
* background-image: linear-gradient(to bottom, green,black);
Linear Gradients (goes down/up/left/right/diagonally).
Starts at the top with green and goes to bottom with black.
* margin: 10px 10px 10px 10px;
The CSS margin properties define the space around elements.
The top, right, bottom, and left margin can be changed independently using separate properties.
Incorrect Answers:
* border-color: red;
will not display any border
* Radial Gradients (defined by their center).









JSONP Request





<iframe sandbox=“value”>(frame1.htmlnX/iframe/>


Explanation:
JSON.stringify converts a JavaScript value to a JavaScript Object Notation (JSON) string.
References:
https://www.w3schools.com/js/js_json_stringify.asp
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify





Answer : D

Explanation:


innerHTML
The innerHTML property sets or returns the HTML content (inner HTML) of an element.
Example -

Change the HTML content of a <h1> element with id="header": document.getElementById("header").innerHTML = "A dynamic page";

References:
https://www.w3schools.com/jsref/prop_html_innerhtml.asp



.navigation li {
    font-family: MyFont1;
}

@font-face {
    font-family: MyFont1;
    src: url (‘font/WebFont1.eot’);
}




<span id=“myTextSpan” class=“myStyle” style=“font-family: Arial”>Hello, World!</span> 





var myBigRig = new myApplication.Vehicle(‘display’, “silver’, 2, ‘manual’, 16);
MyBigRig.Describe();

var myMotorhome = new myApplication.Vehicle(‘display’, ‘blue’, 2, ‘manual’, 2);
myMotorcycle.Describe();


$(document).on('click', '.get-widgets', function (e) {


Answer - A
if(!(counter % 25))








Answer - A
Modify all INPUT elements elements by using the following HTML attribute:

onlick=“stopPropagation(event)”

Declare the JavaScript function named stopPropagation() in the HEAD section

function stopPropagation(event) {
    event = event || window.event;
    if (event.stopPropagation) {
        event.stopPropagation();
    } else {
        event.cancelBubble = true;
    }
}

Answer - B
Place all INPUT elements within a SPAN element



Answer : B

Explanation:


* The <fieldset> tag is used to group related elements in a form.


The <fieldset> tag draws a box around the related elements.


The <legend> tag defines a caption for the <fieldset> element.


Example:


Group related elements in a form:


<form>


<fieldset>


<legend>Personalia:</legend>


Name: <input type="text"><br/>


Email: <input type="text"><br/>


Date of birth: <input type="text"/>


</fieldset>


</form>


Reference:


https://www.w3schools.com/tags/tag_fieldset.asp


https://www.w3schools.com/TAGS/tag_legend.asp




<fieldset>
    <legend>Enter your information:</legend>
Name: <input type=“text” /><br />
Email: <input type=“email” /><br />
</fieldset>
<button value=“submit”>Submit</button>

<form>
<fieldset>
<legend>Personalia:</legend>
Name: <input type="text"><br/>
Email: <input type="text"><br/>
Date of birth: <input type="text"/>
</fieldset>
</form>






Document.getElementByid(“numberBtn”).onclick = validateNumberInput;

var currentNumberValue =
document.getElementById(“numberValue”).value;

function validateNumberInput() {

if(typeof(currentNumberValue)! = ’number’)

alert(‘Please enter a number’);}




<article>
    <header>
    Welcome to the Semantic Web!
</header>
<div class=“posting”>
…
</div>
</article>


Answer : A

Explanation:

* The outermost assignment, counter = 10; will decide the output that is displayed.

* Local variables have local scope: They can only be accessed within the function.

Example -
// code here can not use carName
function myFunction() {
var carName = "Volvo";
// code here can use carName
}
* A variable declared outside a function, becomes GLOBAL.


A global variable has global scope: All scripts and functions on a web page can access it.
Example -
var carName = " Volvo";
// code here can use carName
function myFunction() {
// code here can usecarName
}



Explanation:
* Object.prototype.constructor
Returns a reference to the Object function that created the instance's prototype. Note that the value of this property is a reference to the function itself, not a string containing the function's name. The value is only read-only for primitive values such as 1, true and "test".
* The constructor property is created together with the function as a single property of func.prototype.
Reference:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/constructor





Answer : C

menuitem: hover
color: yellow
transition-property: color
transition:duration 5s
…
}

Explanation:

transition-property

The transition-property property specifies the name of the CSS property the transition effect is for (the transition effect will start when the specified CSS property changes).

Tip: A transition effect could typically occur when a user hover over an element.

Note: Always specify the transition-duration property, otherwise the duration is 0, and the transition will have no effect.

CSS3 transition-property Property
References:
https://www.w3schools.com/cssref/css3_pr_transition-property.asp






Explanation:

src: url(/Special.ttf) format(’truetype’);
}
body {
        font-family: ’special’, sans-serif;

Using The Font You Want -
In the CSS3 @font-face rule you must first define a name for the font (e.g. myFirstFont), and then point to the font file.
To use the font for an HTML element, refer to the name of the font (myFirstFont) through the font-family property:


Example -
@font-face {
font-family: myFirstFont;
src: url(sansation_light.woff);
}
div {
font-family: myFirstFont;
}
Note:
* CSS3 Web Fonts - The @font-face Rule
Web fonts allow Web designers to use fonts that are not installed on the user's computer.
When you have found/bought the font you wish to use, just include the font file on your web server, and it will be automatically downloaded to the user when needed.
Your "own" fonts are defined within the CSS3 @font-face rule.
* TrueType Fonts (TTF)
TrueType is a font standard developed in the late 1980s, by Apple and Microsoft. TrueType is the most common font format for both the Mac OS and Microsoft
Windows operating systems.






Answer : D

Explanation:
Use three arguments: element, min, max.
Compare element.value with min and max.


article {
    columns: 2
    min-width: 200px;
}




Answer - D

ajax.done = function (data) {
    displayData(data);
    };

The deferred.done() method accepts one or more arguments, all of which can be either a single function or an array of functions. When the Deferred is resolved, the doneCallbacks are called. Callbacks are executed in the order they were added. Since deferred.done() returns the deferred object, other methods of the deferred object can be chained to this one, including additional .done() methods.



Solution - C & D
C - From the web page, call the terminate() method
D - From the web worker process, call the close() method



Spawning a dedicated worker -
Creating a new worker is simple. All you need to do is call the Worker() constructor, specifying the URI of a script to execute in the worker thread (main.js): var myWorker = new Worker("worker.js”);

Reference:
https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers





websockets
Explanation:
Web Sockets is a next-generation bidirectional communication technology for web applications which operates over a single socket and is exposed via a
JavaScript interface in HTML 5 compliant browsers.
Once you get a Web Socket connection with the web server, you can send data from browser to server by calling a send() method, and receive data from server to browser by an on message event handler.





















Answer - B

<Fieldset> tag is used to group related elements in a form.

<legend> tag defines a caption for the <fieldset> element.

HTML <img> alt attribute - the required alt attribute specifies an alternate text for an image, if the image cannot be displayed.
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
Try it Yourself »

jQuery text( ) method - jQuery text() Method
The text() method sets or returns the text content of the selected elements. When this method is used to return content, it returns the text content of all matched elements (HTML markup will be removed). When this method is used to set content, it overwrites the content of ALL matched elements.
$("button").click(function(){
  $("p").text("Hello world!");
});

Difference between text ( ) method and val ( ) method

.val() works on input elements (or any element with a value attribute?) and .text() will not work on input elements. .val() gets the value of the input element -- regardless of type. .text() gets the innerText (not HTML) of all the matched elements.

text() return the combined text contents of all matched elements (such as p, div, and so on) val() is used to obtain the value of an input element (such as input, select, and so on)
according to the official documentation text() should not be used with input elements



.menuItems li
{
display: inline
}

to ensure that the <li> elements are aligned horizontally.


tr: nth-child(3n+1) {background-color: blue;}








navigator.geolocation. getCurrent(hasPosition, noPosition);

    function hasPosition(position) {
        restaurant = findRestaurants(positioncoords.latitude, position.coords.longitude);
…
    function noPosition() {
    …
}




<body>
    Product: <input name= ‘product’ list=‘product_list’>
    select id= ’product_list’>
        <option value = ‘Car’>
        <option value = ‘Boat’>
    </select>
</body>



displayAlertIfBigNumber = function(aNumber)
{
    switch isBig(aNumber) {
        case true:
            alert(“aNumber is big”)
            break;
        default;
            alert(“aNumber is not big”);
            break
    }
}



(function () {
…
})();


var jsObject = JSON.parse(objStr);
Convert obj string into array




<style>
    .flex {
        flex : 1;
    }
    .flex2 {
        flex : 2;
    }
</style>








document.getElementById(“yellowDiv”).className += border;

function addElements() {

var option = document.getElementById(“shippingType”);
    var newOption = document.createElement(“option”);
    newOption.text = “Air”;
    option.appendChild(newOption);

document(“footer”).innerHTML = “All rights reserved”;


Answer - D

document.getElementById("myDIV").style.transform = “rotate(90deg)";


try {

fnl ();

} catch (error) {

if (error.name == ‘RangeError’) {

catchRangeError();}

else if (error.name === ’SyntaxError’) {

catchSyntaxError(); }
}



function newOrder(orderId, orderShip, callback) {
    document.write(’New order being processed”);
    callback()
}
newOrder(“333”, “EXPRESS”, function() {
    …
;})


Answer - B socket.send()

socket.send($(“#message”).val());



function drawOnCanvas() {
var context = document.getElementById(‘canvas1’);
var context = canvas.getContext(‘2d’);
context.fillRect(10, 10, 100, 100);
}


overflow-Y





<style>
#main {
    width: 180px;
    height: 150px;
    border: 1px solid black;
    display: flex;
    flex-flow: wrap-reverse column;
}


Add the following code to the yellow div.margin:auto



Answer - A, C & E

JSON
javaScript
String




Validate2 will be called when the user clicks the userName text box.
<input type=“text” id=“userName” onlick=“Validate2()”/>

Validate1 will be called when the user clicks the userNameLabel label.
<div id=“div3” onlick=“Validate1()”>
<label id=“userNameLabel” for=“userName”>User Name:</label>





<input type=“button” value=“oneButton” onclick=“alert(this.value);” />


Answer - C
alert(window.eval(‘product’));


try {
document.write(“Welcome<br/>”);
document.write(getContent());
}
catch (e) {
document.write(“getContent throws an 
exception: “ + e.message + “<br/>”};
}

finally {
document.write(“<br/>Bye”);
}



var host = “ws://sample-host/echo”;
…
socket.onopen


Everything apart from Windows 8








Live DOM - you can see a hierarchically structured view of the DOM


Answer - QUnit-Metro









render: function () {
    this.getAsyncData(function () {
        this.displayProcessDone();
    }.bind.(displayProcessDone));
}

bind
displayProcessDone







flex-direction: row-reverse



$ (document).ready(function () {
var xhrequest;
if (window.XMLHttpRequest) {
    xhrequest = new ActiveXObject ();
}



var x = document.forms[“myForm”][“fname”].value;
if (x == null || x == “”)
{




var personFormData = $(“#personForm”.serialize(submitPersonForm)




LogData.prototype.newFunction = function () {
    Return ’Stacktrace: ‘ + this.stackTrace +
                ‘ExId: ‘ + this.exceptionId;

Stack trace - In simple terms, a stack trace is a list of the method calls that the application was in the middle of when an Exception was thrown.



var var1 = new XMLHttpRequest ();
…
var1.responseType = “json”;









function readXMLFile () {

if (window.XMLHttpRequest) {

xmlhttp = new XMLHttpRequest ();}

else {

xmlhttp = new ActiveXObject
(‘’Microsoft.XMLHTTP’’);}

xmlhttp.open(‘’GET’’, ‘’message.xml’’,
false);

xmlhttp.send();

xmlDoc = xmlhttp.responseXML;

document.getElementById(‘’to’’), innerHTML = 
    xmlDoc.getElementByTagName(‘’tp’’)
[0].childNodes[0].nodeValue;
document.getElementById(‘’form’’).innerHTML =
    xmlDoc.getElementByTagname(‘’from’’)
[0].childNodes[0].nodeValue;
document.getElementById(‘’message’’).innerHTML = document.getElementByTagName(‘’body’’)
[0].childNodes[0].nodeValue;}





Answer - D

var jsObject = $.parseJSON(objStr)




$.ajax ({
    type: “GET”,
    url: “WebService1.svc/customers”,
    dataType: XML
    success: function (wcf) {
    ...






return JSON.parse(objToParse, function (k, v) {
    if (k == “name” && !v)
    v = “_empty_”




<div style=“box-sizing: border-box”>
    <span>
        Customer Name
    <q style=“ display: inline”>Ben Smith</q>
    </span>
</div>



.tile {
border-radius: 100px/50px




<video width= “320” height= “240”>
<source src= “video.mp4” type=“video/mp4”>
<source src= “video1.ogg” type= “video/ogg”>
</video>




var request = $.ajax({
    url: ‘/‘,
    accepts: “application/bint, text/xml’,
        dataFilter: function (data, type) {
    if (request.getResponseHeader (“Content-Type”)== “application/bint”)
    return parseBint(data);
else
    return parseXML(data);
},
success: function (data) {
    start(data);
    }
});



Answer - A
function validate() {
    var name = $(“#txtValue”).val();
    if(name ==null || name == “”)
        alert(“please enter valid value”);
        return;
}


Answer - B

a CSS attribute selector
Use the CSS attribute selector -
a[href*=".org"] { color: red; }
References:
https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors



input[type=checkbox]: checked + label {
    color: red;
}



#main div: nth-child (even) {
    order: 1;

CSS Order Property - The order property is a sub-property of the Flexible Box Layout module. Flex items are displayed in the same order as they appear in the source document by default. The order property can be used to change this ordering.



function Student (someName) { var fullname=someName; }

function Student (fullName) { This.fullname=fullname; }

HTML <script> Tag - The HTML <script> element is used to embed executable code or data; this is typically used to embed or refer to JavaScript code. 

<script src="javascript.js"></script>

<script>
  alert("Hello World!");
</script>


div.#multi-column-4

column-count: 4;

column-gap: 20px;



$(document).ready(function () {
    $(‘li.list1 > li ul a’). > ({
    })
})

return arrayObj.every.(isBigenough);


localStorage.setItem(“score”, myScore);




<label> - 

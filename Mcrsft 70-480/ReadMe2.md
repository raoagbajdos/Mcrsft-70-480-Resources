


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

Web Workers (background tasks / multithreading)

A web worker is a JavaScript running in the background, without affecting the performance of the page.

The Web Worker API provides a way for web application authors to spawn background scripts that run in parallel with the main page. You can spawn several threads at a time to use for long-running tasks. A new worker object requires a .js file, which is included via an asynchronous request to the server. (Run in the background)
var myWorker = new Worker(‘worker.js’);

All communication to and from the worker thread is managed through messages. Both the host worker and the worker script can send messages by using postMessage and listen for a response by using the onmessage event. The content of the message is sent as the data property of the event.

 

Web Sockets (WS / WSS) – bidirectional communication through web sockets API

The WebSocket specification defines an API establishing "socket" connections between a web browser and a server. In plain words: There is a persistent connection between the client and the server and both parties can start sending data at any time.

wss or ws is a valid protocol to create a WebSocket

 

XMLHttpRequests  {server interaction} - XHR objects are used to interact with servers. You can retrieve data from a URL without having to do a full-page refresh. This enables a Web page to update just part of a page without disrupting what the user is doing. XMLHttpRequest is used heavily in AJAX (asynchronous) programming.

Despite its name, XHR can be used to retrieve any type of data, not just XML.

Constructor
XMLHttpRequest ( )
The constructor initialises an XHR. It must be called before any other method.

 

RegEx – A regular expression is a type of object. This is a string of text that allows you to create patterns that help match, locate, and manage text. It can be either constructed with the RegEx constructor or written as a literal value by enclosing a pattern in forwards slash (/) characters. Regular expressions are a mix of special characters and literal characters that make up the
pattern that someone would want to match.
A regular expression is basically a sequence of characters that forms a search pattern.
The search pattern can be used for text search and text replace operations.
 

AJAX – Asynchronous JavaScript And XML – AJAX is the art of exchanging data with a server and updating parts of a web page - without reloading the whole page.

($) AJAX just uses a combination of: A browser built-in XMLHttpRequest (XHR) Object (to request data from a web server) JavaScript and HTML DOM (to display or use the data).

AJAX allows web pages to be updated asynchronously (not existing or occurring at the same time) by exchanging data with a web server behind the scenes.

Asynchronous means “not exisiting or happening at the same time”. Async programming refers to the occurrence of events independent of the main program flow.
 Synchronous operations block instructions until the task is completed, while asynchronous operations can execute without blocking other operations. Asynchronous operations are generally completed by firing an event or by calling a provided callback function.


AJAX is a developer's dream, because you can: 
•	Update a web page without reloading the page
•	Request data from a server - after the page has loaded
•	Receive data from a server - after the page has loaded
•	Send data to a server - in the background
  
•	

jQuery {JavaScript Library}– jQuery provides several methods for AJAX functionality. jQuery methods are primarily used for event handling & HTML DOM tree manipulation / traversal.

With the jQuery AJAX methods, you can request text, HTML, XML, or JSON from a remote server using both HTTP Get and HTTP Post - And you can load the external data directly into the selected HTML elements of your web page! 

$(document).ready(function(){
  $("p").click(function(){
    $(this).hide();
  });
});

Wiring up events with jQuery allows you to assign the event listener to many elements at once by using the selector syntax
 

XPath - XPath stands for XML Path Language. It uses a non-XML syntax to provide a flexible way of addressing (pointing to) different parts of an XML document. 

 

Conditional Ternary Operator - The conditional ternary operator in JavaScript assigns a value variable based on some condition and is the only JavaScript operator that takes three operands:

The ternary operator is a substitute for an if statement ins which both the if and else clauses assign different value to the same field, like so:
if (condition)
result = ’something’;
else
result = ’somethingelse’;

The ternary operator shortens this if/else statement into a single statement:
result = (condition) ? ’something’ : ’somethingelse’;



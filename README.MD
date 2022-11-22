<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>San Joaquin Valley Town Hall</title>
<link rel="shortcut icon" href="images/favicon.ico">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="js/jquery.slicknav.min.js"></script>
<script type="text/javascript">
$(document).ready(function () {
$('#nav_menu').slicknav({prependTo: "#mobile_menu"});
});
</script>


<style>


/*
Mobile Menu Core Style
*/

.slicknav_btn {
position: relative;
display: block;
vertical-align: middle;
float: right;
padding: 0.438em 0.625em 0.438em 0.625em;
line-height: 1.125em;
cursor: pointer;
}
.slicknav_menu .slicknav_menutxt {
display: block;
line-height: 1.188em;
float: left;
}
.slicknav_menu .slicknav_icon {
float: left;
margin: 0.188em 0 0 0.438em;
}
.slicknav_menu .slicknav_no-text {
margin: 0
}
.slicknav_menu .slicknav_icon-bar {
display: block;
width: 1.125em;
height: 0.125em;
-webkit-border-radius: 1px;
-moz-border-radius: 1px;
border-radius: 1px;
-webkit-box-shadow: 0 1px 0 rgba(0, 0, 0, 0.25);
-moz-box-shadow: 0 1px 0 rgba(0, 0, 0, 0.25);
box-shadow: 0 1px 0 rgba(0, 0, 0, 0.25);
}
.slicknav_btn .slicknav_icon-bar + .slicknav_icon-bar {
margin-top: 0.188em
}
.slicknav_nav {
clear: both
}
.slicknav_nav ul, .slicknav_nav li {
display: block
}
.slicknav_nav .slicknav_arrow {
font-size: 0.8em;
margin: 0 0 0 0.4em;
}
.slicknav_nav .slicknav_item {
display: block;
cursor: pointer;
}
.slicknav_nav a {
display: block
}
.slicknav_nav .slicknav_item a {
display: inline
}
.slicknav_menu:before, .slicknav_menu:after {
content: " ";
display: table;
}
.slicknav_menu:after {
clear: both
}
/* IE6/7 support */
.slicknav_menu {
*zoom: 1
}
/*
User Default Style
Change the following styles to modify the appearance of the menu.
*/

.slicknav_menu {
font-size: 16px;
}
/* Button */
.slicknav_btn {
margin: 5px 5px 6px;
text-decoration: none;
text-shadow: 0 1px 1px rgba(255, 255, 255, 0.75);
-webkit-border-radius: 4px;
-moz-border-radius: 4px;
border-radius: 4px;
background-color: #222222;
}
/* Button Text */
.slicknav_menu .slicknav_menutxt {
color: #FFF;
font-weight: bold;
text-shadow: 0 1px 3px #000;
}
/* Button Lines */
.slicknav_menu .slicknav_icon-bar {
background-color: #f5f5f5;
}


.slicknav_nav ul {
list-style: none;
overflow: hidden;
}
.slicknav_nav ul {
padding: 0;
margin: 0 0 0 20px;
}
.slicknav_nav .slicknav_item {
padding: 5px 10px;
margin: 2px 5px;
}
.slicknav_nav a {
padding: 5px 10px;
margin: 2px 5px;
text-decoration: none;
color: #fff;
}
.slicknav_nav .slicknav_item a {
padding: 0;
margin: 0;
}

.slicknav_nav a:hover {
-webkit-border-radius: 6px;
-moz-border-radius: 6px;
border-radius: 6px;
background: #ccc;
color: #222;
}

/* the styles for the elements */
* {
margin: 0;
padding: 0;
}

html {
background-color: white;
}

body {
font-family: Arial, Helvetica, sans-serif;
font-size: 100%;
width: 99%; /* changed from 800 pixels */
max-width: 960px;
margin: 0 auto;
border: 3px solid #931420;
background-color: #fffded;
}

a:focus, a:hover {
font-style: italic;
}

/* the styles for the header */
header {
padding: 1.5em 0 2em 0;
border-bottom: 3px solid #931420;
background-image: -moz-linear-gradient(
30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
background-image: -webkit-linear-gradient(
30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
background-image: -o-linear-gradient(
30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
background-image: linear-gradient(
30deg, #f6bb73 0%, #f6bb73 30%, white 50%, #f6bb73 80%, #f6bb73 100%);
}

header h2 {
font-size: 175%;
color: #800000;
}

header h3 {
font-size: 130%;
font-style: italic;
}

header img {
float: left;
padding: 0 3.75%; /* 30 / 800 x 100 */
}

.shadow {
text-shadow: 2px 2px 2px #800000;
}

/* the styles for the navigation menu */
#nav_menu ul {
list-style-type: none;
margin: 0;
padding: 0;
position: relative;
}

#nav_menu ul li {
float: left;
width: 20%; /* 160 / 800 x 100 */
}

#nav_menu ul li a {
display: block;
text-align: center;
padding: 1em 0;
text-decoration: none;
background-color: #800000;
color: white;
font-weight: bold;
}

#nav_menu a.current {
color: yellow;
}

#nav_menu ul ul {
width: 100%;
display: none;
position: absolute;
top: 100%;
}

#nav_menu ul ul li {
float: none;
}

#nav_menu ul li:hover > ul {
display: block;
}

#nav_menu > ul::after {
content: "";
clear: both;
display: block;
}

/* the styles for the main content */
main {
clear: left;
}

/* the styles for the section */
section {
width: 65.625%; /* 525 / 800 X 100 */
float: right;
padding: 0 2.5% 20px 2.5%; /* 20 / 800 x 100 */
}

section h1 {
font-size: 150%;
padding: .5em 0 .25em 0;
margin: 0;
}

section h2 {
color: #800000;
font-size: 130%;
padding: .5em 0 .25em 0;
}

section p {
padding-bottom: .5em;
}

section blockquote {
padding: 0 2em;
font-style: italic;
}

section ul {
padding: 0 0 .25em 1.25em;
list-style-type: circle;
}

section li {
padding-bottom: .35em;
}

/* the styles for the article */
article {
padding: .5em 0;
border-top: 2px solid #800000;
border-bottom: 2px solid #800000;
}

article h2 {
padding-top: 0;
}

article h3 {
font-size: 105%;
padding-bottom: .25em;
}

article img {
float: right;
max-width: 40%;
min-width: 150px;
margin: .5em 0 1em 1em;
border: 1px solid black;
}

/* the styles for the aside */
aside {
width: 26.875%; /* 215 / 800 x 100 */
float: right;
padding: 0 0 20px 2.5%; /* 20 / 800 x 100 */
}

aside h2 {
color: #800000;
font-size: 130%;
padding: .5em 0 .25em 0;
}

aside h3 {
font-size: 105%;
padding-bottom: .25em;
}

aside img {
padding-bottom: 1em;
}

/* the styles for the footer */
footer {
background-color: #931420;
clear: both;

}

footer p {
text-align: center;
color: white;
padding: 1em 0;
}

#mobile_menu {
display: none;
}

/* tablet portrait to standard 960 */
@media only screen and (max-width: 959px) {
section h1 {
font-size: 135%;
}

section h2, aside h2 {
font-size: 120%;
}
}

/* mobile landscape to tablet portrait */
@media only screen and (max-width: 767px) {
header img {
float: none;
}

header {
text-align: center;
}

section {
float: none;
width: 95%; /* 100 - (2 x 2.5) for padding */
}

aside {
float: none;
padding-right: 2.5%; /* 20 / 800 x 100 */
width: 95%; /* 100 - (2 x 2.5) for padding */
}

article img {
max-width: 30%;
}

#speakers {
-moz-column-count: 2;
-webkit-column-count: 2;
column-count: 2;
}

#nav_menu {
display: none;
}

#mobile_menu {
display: block;
}

.slicknav_menu {
background-color: #800000 !important;
}
}

/* mobile portrait to mobile landscape */
@media only screen and (max-width: 479px) {
body {
font-size: 90%;
}
}

</style>
</head>

<body>
<!-- Google Tag Manager (noscript) -->
<noscript>
<iframe src="https://www.googletagmanager.com/ns.html?id=GTM-W4XGTGH"
height="0" width="0" style="display:none;visibility:hidden"></iframe>
</noscript>
<!-- End Google Tag Manager (noscript) -->
<header>
<img src="images/town_hall_logo.gif" alt="Town Hall logo" height="80">
<h2>San Joaquin Valley Town Hall</h2>
<h3>Celebrating our <span class="shadow">75<sup>th</sup></span> Year</h3>
</header>
<nav id="mobile_menu"></nav>
<nav id="nav_menu">
<ul>
<li><a href="index.html" class="current">Home</a></li>
<li><a href="speakers.html">Speakers</a></li>
<li><a href="luncheons.html">Luncheons</a></li>
<li><a href="tickets.html">Tickets</a></li>
<li><a href="aboutus.html"> About Us</a>
<ul>
<li><a href="#">Our History</a></li>
<li><a href="#">Board of Directors</a></li>
<li><a href="#">Past Speakers</a></li>
<li><a href="#">Contact Information</a></li>
</ul>
</li>
</ul>
</nav>
<main>
<section>
<h2>Our Mission</h2>
<p>San Joaquin Valley Town Hall is a non-profit organization that is run by an
all-volunteer board of directors. Our mission is to bring nationally and
internationally renowned, thought-provoking speakers who inform, educate,
and entertain our audience! As one or our members told us:</p>
<blockquote>&ldquo;Each year I give a ticket package to each of our family members.
I think of it as the gift of knowledge...and that is priceless.&rdquo;
</blockquote>

<h1>Speaker of the Month</h1>
<article>
<h2>Fossil Threads in the Web of Life</h2>
<img src="images/sampson_dinosaur.jpg" alt="Scott Sampson with dinosaur">
<h3>February<br>
Scott Sampson</h3>
<p>What's 75 million years old and brand spanking new? A teenage Utahceratops!
Come to the Saroyan, armed with your best dinosaur roar, when Scott Sampson, Research
Curator at the Utah Museum of Natural History, steps to the podium. Sampson's research
has focused on the ecology and evolution of late Cretaceous dinosaurs and he has conducted
fieldwork in a number of countries in Africa.</p>
<p>
<a href="speakers/c7_sampson.html">Read more.</a>&nbsp;
<a href="media/sampson.swf" target="_blank">Or play video.</a>
</p>
</article>

<h2>Our Ticket Packages</h2>
<ul>
<li>Season Package: $95</li>
<li>Patron Package: $200</li>
<li>Single Speaker: $25</li>
</ul>
</section>
<aside>
<h2>Guest speakers</h2>
<div id="speakers">
<h3>October<br><a href="speakers/toobin.html">Jeffrey Toobin</a></h3>
<img src="images/toobin75.jpg" alt="Jeffrey Toobin photo">
<h3>November<br><a href="speakers/sorkin.html">Andrew Ross Sorkin</a></h3>
<img src="images/sorkin75.jpg" alt="Andrew Ross Sorkin photo">
<h3>January<br><a href="speakers/chua.html">Amy Chua</a></h3>
<img src="images/chua75.jpg" alt="Amy Chua photo">
<h3>February<br><a href="speakers/c7_sampson.html">Scott Sampson</a></h3>
<img src="images/sampson75.jpg" alt="Scott Sampson photo">
</div>
</aside>
</main>
<footer>
<p>&copy; 2018, San Joaquin Valley Town Hall, Fresno, CA 93755</p>
</footer>
<script>

(function (e, t, n) {
var r = {
label: "MENU",
duplicate: true,
duration: 200,
easingOpen: "swing",
easingClose: "swing",
closedSymbol: "&#9658;",
openedSymbol: "&#9660;",
prependTo: "body",
parentTag: "a",
closeOnClick: false,
allowParentLinks: false
}, i = "slicknav", s = "slicknav";
e.fn[i] = function (n) {
return this.each(function () {
function h(e) {
var t = e.data("menu");
if (!t) {
t = {};
t.arrow = e.children("." + s + "_arrow");
t.ul = e.next("ul");
t.parent = e.parent();
e.data("menu", t)
}
if (e.parent().hasClass(s + "_collapsed")) {
t.arrow.html(o.openedSymbol);
t.parent.removeClass(s + "_collapsed");
p(t.ul, true)
} else {
t.arrow.html(o.closedSymbol);
t.parent.addClass(s + "_collapsed");
p(t.ul, true)
}
}

function p(e, t) {
var n = v(e);
var r = 0;
if (t) r = o.duration;
if (e.hasClass(s + "_hidden")) {
e.removeClass(s + "_hidden");
e.slideDown(r, o.easingOpen);
e.attr("aria-hidden", "false");
n.attr("tabindex", "0");
d(e, false)
} else {
e.addClass(s + "_hidden");
e.slideUp(r, o.easingClose, function () {
e.attr("aria-hidden", "true");
n.attr("tabindex", "-1");
d(e, true);
e.hide()
})
}
}

function d(t, n) {
var r = t.children("li").children("ul").not("." + s + "_hidden");
if (!n) {
r.each(function () {
var t = e(this);
t.attr("aria-hidden", "false");
var r = v(t);
r.attr("tabindex", "0");
d(t, n)
})
} else {
r.each(function () {
var t = e(this);
t.attr("aria-hidden", "true");
var r = v(t);
r.attr("tabindex", "-1");
d(t, n)
})
}
}

function v(e) {
var t = e.data("menu");
if (!t) {
t = {};
var n = e.children("li");
var r = n.children("a");
t.links = r.add(n.children("." + s + "_item"));
e.data("menu", t)
}
return t.links
}

function m(t) {
if (!t) {
e("." + s + "_item, ." + s + "_btn").css("outline", "none")
} else {
e("." + s + "_item, ." + s + "_btn").css("outline", "")
}
}

var i = e(this);
var o = e.extend({}, r, n);
if (o.duplicate) {
var u = i.clone();
u.removeAttr("id");
u.find("*").each(function (t, n) {
e(n).removeAttr("id")
})
} else var u = i;
var a = s + "_icon";
if (o.label == "") {
a += " " + s + "_no-text"
}
if (o.parentTag == "a") {
o.parentTag = 'a href="#"'
}
u.attr("class", s + "_nav");
var f = e('<div class="' + s + '_menu"></div>');
var l = e("<" + o.parentTag + ' aria-haspopup="true" tabindex="0" class="' + s + '_btn"><span class="' + s + '_menutxt">' + o.label + '</span><span class="' + a + '"><span class="' + s + '_icon-bar"></span><span class="' + s + '_icon-bar"></span><span class="' + s + '_icon-bar"></span></span></a>');
e(f).append(l);
e(o.prependTo).prepend(f);
f.append(u);
var c = u.find("li");
e(c).each(function () {
var t = e(this);
data = {};
data.children = t.children("ul").attr("role", "menu");
t.data("menu", data);
if (data.children.length > 0) {
var n = t.contents();
var r = [];
e(n).each(function () {
if (!e(this).is("ul")) {
r.push(this)
} else {
return false
}
});
var i = e(r).wrapAll("<" + o.parentTag + ' role="menuitem" aria-haspopup="true" tabindex="-1" class="' + s + '_item"/>').parent();
t.addClass(s + "_collapsed");
t.addClass(s + "_parent");
e(r).last().after('<span class="' + s + '_arrow">' + o.closedSymbol + "</span>")
} else if (t.children().length == 0) {
t.addClass(s + "_txtnode")
}
t.children("a").attr("role", "menuitem").click(function () {
if (o.closeOnClick) e(l).click()
})
});
e(c).each(function () {
var t = e(this).data("menu");
p(t.children, false)
});
p(u, false);
u.attr("role", "menu");
e(t).mousedown(function () {
m(false)
});
e(t).keyup(function () {
m(true)
});
e(l).click(function (e) {
e.preventDefault();
p(u, true)
});
u.on("click", "." + s + "_item", function (t) {
t.preventDefault();
h(e(this))
});
e(l).keydown(function (e) {
var t = e || event;
if (t.keyCode == 13) {
e.preventDefault();
p(u, true)
}
});
u.on("keydown", "." + s + "_item", function (t) {
var n = t || event;
if (n.keyCode == 13) {
t.preventDefault();
h(e(t.target))
}
});
if (o.allowParentLinks) {
e("." + s + "_item a").click(function (e) {
e.stopImmediatePropagation()
})
}
})
}
})(jQuery, document, window)
</script>
</body>
</html>

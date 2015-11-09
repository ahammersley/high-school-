# high-school-
this shows all we went over in intro to web design over the course of one semester
<html>
<head>
<title>Form</title>
<style type="text/css">
/* To remove hyperlink line on text */
a {text-decoration:none}
</style>
</head>

<body background="greyback.jpg" bgproperties=fixed bgcolor=white text=blue link=red vlink=green leftmargin=200 rightmargin=200 topmargin=50><!-- Used bgproperties=fixed to freeze the background picture.-->

<div align=center>
<h1><a name="">Organizing Tags</a></h1>
</div>


<ol>
<li><h2>Learning to create HTML tags can help you in many ways:</h2></li>
	
<li><h3>You will develop a deeper understanding of how HTML really works.</h3></li>
<li><h4>You will be able to trouble shoot web pages when errors occur.</h4></li>		
<li><h5>You will be able to view other pages and learn how certain effects are created.</h5></li>
<li><h6>You will be able to understand how HTML and JavaScript work together.</h6></li>
</ol>


<a href="http://www.sun.com" target=_blank><img src="mug.gif" align=left hspace=20 vspace="" alt="hot coffee" border=0></a>There are many ways to organize a web page.  The web project will organize text, hypertext links, colors, and fonts.  It will also demonstate single spacing, double spacing, and the use of line breaks.

<pre>
    Roses are red. 
Violets are blue. 

    Your site stinks. 
But, my site is cool.
</pre>

<blockquote>The blockquote causes extra margin space to the left of the content. This makes the content appear as more indented than the surrounding text as by this example.</blockquote>

<p>This web page will display how to organize web pages in a number of different ways using:</p>

<a href="#powerful" name="top">Powerful Lines</a>
<br><a href="#sources">Hyperlinks to HTML and Javascript Sources</a>
<br><a href="#others">Hyperlinks to Previously Created Web Pages</a>
<br><a href="#fonts">Fancy Fonts</a>
<br><a href="#pictures">Perfect Pictures</a>
<br><a href="#tables">Orderly Tables</a>
<br><a href="#extras">Extraordinary Extras</a>

<hr size=10>
<h2><a name="powerful">Powerful Lines</a></h2>

A horizontal rule tag 10% wide and 10 increments high.
<hr width=10% size=10 color=red>

A horizontal rule tag 50% wide and 30 increments high.
<hr width=50% size=30 color=green>

A horizontal rule tag 100% wide and 20 increments high.
<hr width=100% size=20 color=purple>

A horizontal rule tag 100% wide, 10 increments high & no shade.
<hr width=100% size=10 noshade>

<a href="#top">Back to Top</a>

<p><h2><a name="sources">Hyperlinks to HTML Sources</a></h2></p>

<a href="http://www.microsoft.com" target=_blank>Microsoft</a>
<br><a href="http://www.bcchs.org" target=_blank>BCCHS</a>
<br><a href="http://www.sun.com" target=_blank>Sun Microsystems</a>
<br><a href="http://www.oracle.com" target=_blank>Oracle</a>


<p><a href="#top">Back to Top</a></p>

<p><h2><a name="others">Hyperlinks to Other Pages</a></h2></p>

<br><a href="project1.htm">Project 1</a>
<br><a href="project1a.htm">Project 1a</a>
<br><a href="project1b.htm">Project 1b</a>

<p><a href="#top">Back to Top</a></p>

<p><h2><a name="fonts">Fancy Fonts</a></h2></p>

<font face=helvitica size=4 color=red>This is <b>Helvitica</b> font at size 4.</font>

<br><font face=times size=6 color=green>This is <i>Times</i> font at size 6.</font>

<br><font face=arial size=8 color=orange>This is <sup>Arial</sup> font at size 8.</font>
<br><font face=courier size=2 color=purple>This is&nbsp;&reg;&copy;&lt;&gt;   <sub>courier</sub> font at size 2.</font>&#153;


<p style="font-family:verdana; font-size:580%; color:#0000ff">A paragraph w/css</p>

<p><a href="#top">Back to Top</a></p>

<p><h2><a name="pictures">Perfect Pictures</a></h2></p>

<img src="monkey.gif" align=right height=50 width=50>
<br clear=all><!--Used the br clear=all code to move the hr monkey picture below the other monkey picture.-->
<div align=center>
<img src="monkey.gif" height=5 width=50%><!--Created a hr with the monkey picture using height and width-->
</div>
<!--Added 3 more monkey pictures and adjusted height and width. Added borders of 5, 15 and 25 pixels. Finally, used style script to add color and border sytles to pictures.-->
<p><img src="monkey.gif" height=100 width=100 style="border: 5px purple dotted;">
<img src="monkey.gif" height=150 width=150 style="border: 15px green dashed;">
<img src="monkey.gif" height=200 width=150 style="border: 25px red solid;"></p>


<p><a href="#top">Back to Top</a></p>

For more information please contact <a href="mailto:rohlederal@bcchs.org">Al Rohleder @ bcchs.org</a>.

<p><a name="#tables"><h2>Orderly Tables</h2></a></p>

<table border=5 cellpadding=10 align=center>
<tr>
	<th>Monkeys</th>
	<th>Colors</th>
	<th>Fonts</th>
</tr>
<tr>
	<td><img src="monkey.gif" heigth=50 width=50></td>
	<td bgcolor=green align=center>GREEN</td>
	<td align=center><font face=Courier size=8>Courier</td>
</tr>
<tr>
	<td><img src="monkey.gif" height=75 width=50></td>
	<td bgcolor=red align=center>RED</td>
	<td align=center><font face=times size=7 color=green>Times</td>
</tr>
</table>

<br>
<table width=80% border=5 bordercolor=red cellpadding=10 cellspacing=10 align=center bgcolor=yellow>
<tr>
	<th width=20% height=150 colspan=3 border=5>Monkeys<br>Colors<br>Fonts</th>
	
</tr>
<tr>
	<td rowspan=2><img src="monkey.gif" heigth=50 width=50></td>
	<td bgcolor=green align=center>GREEN</td>
	<td style="font-family:courier; font-size:14pt; color:green" align=center valign=top><font face=Courier size=8>Courier</td>
</tr>
<tr>
	<td><img src="monkey.gif" height=75 width=50></td>
	<td bgcolor=red align=center>RED</td>
	
</tr>

</table>

<p><a href="#top">Back to Top</a></p>
<hr>

<p><a name="#extras"><h2>Extraordinary Extras</h2></a></p>

<form name="sample form">

Enter your first name:<input type="text" value="First Name" size=25>
<br>Enter your last name:<input type="text" value="Last Name" size=25>
<p>
Pick your favorite college football team from this list:
<select>
<option selected>Kansas
<option>Kansas State
<option>Nebraska
<option>Miami
<option>USC
<option>Arizona
<option>Notre Dame
<option>Florida
</select>
<p>

The best place to eat is:
<br> 
<input type="radio" name="best">Wendy's<br>
<input type="radio" name="best">McDonalds<br>
<input type="radio" name="best">Arby's<br>
<input type="radio" name="best">Subway<br>
<input type="radio" name="best">Taco Bell<br>
<input type="radio" name="best">Jimmy Johns<br>
<input type="radio" name="best">Pizza Hut<br>
<p>

I like to eat:
<br>
<input type="checkbox">Hamburgers<br>
<input type="checkbox">Ice Cream<br>
<input type="checkbox">Pizza<br>
<input type="checkbox">French Fries<br>
<input type="checkbox">Cereal<br>
<p>

Tell us a little bit about yourself.
<br>
<textarea name="textarea1" rows=4 cols=50></textarea>
<p>

<input type="submit" value="Submit the Form">
<input type="reset" value="Reset the Form">


</body>
</html> 

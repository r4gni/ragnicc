---
layout: post
title: "Hello World"
date: 2013-02-07 15:04
comments: true
sharing: true
categories: 
---

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. 

{% pullquote %}
Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. {'At vero eos et accusam et justo duo dolores'} et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.   
{% endpullquote %}

Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.   

{% codeblock Wordpress-Plug-in Hermits United lang:php https://github.com/r4gni/Hermits-United/blob/master/hermitsunited.php Hermits United@github %}
function hello_doctor() {
$chosen = hello_doctor_get_lyric();
echo "<p id='quote'>$chosen</p>";
echo "<p id='doctor'>Dr Who<p>";
}
{% endcodeblock %}

Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat. Duis autem vel eum iriure dolor in hendrerit in vulputate velit esse molestie consequat, vel illum dolore eu feugiat nulla facilisis at vero eros et accumsan et iusto odio dignissim qui blandit praesent luptatum zzril delenit augue duis dolore te feugait nulla facilisi.   

{% blockquote Lorem Ipsum, https://lorem.de Lorem Generator %}
Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming id quod mazim placerat facer
{% endblockquote %}






{% codeblock Wordpress-Plug-in Hermits United lang:php https://github.com/r4gni/Hermits-United/blob/master/hermitsunited.php Hermits United@github %}
function hello_doctor() {
$chosen = hello_doctor_get_lyric();
echo "<p id='quote'>$chosen</p>";
echo "<p id='doctor'>Dr Who<p>";
}
{% endcodeblock %}

When writing longform posts, I find it helpful to include pull quotes to help readers easily identify the topics covered in each section. Some prefer to break things up with lots of headings, and while this seems to be a trend it doesn’t work so well for long form prose. It is important to note that pull quotes are merely visual in presentation and should not appear twice in the text. That is why it a CSS only technique for styling pull quotes is preferable. Octopress includes a handy pull quote plugin to make this easy for you.

Inspect the source and you’ll see the pulled content appears in the data-pullquote attribute of the paragraph. The pull quote effect is created entirely with CSS, and is supported by all modern browsers as well as IE8 and up.


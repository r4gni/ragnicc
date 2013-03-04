---
layout: post
title: "Hello World"
date: 2013-02-07 15:04
comments: true
sharing: true
categories: 
---
Octopress offers a CSS only technique for pull quotes, based on the technique by Maykel Loomans.

Syntax

{% pullquote %}
Surround your paragraph with the pull quote tags. Then when you come to
the text you want to pull, {" surround it like this "} and that's all there is to it.
{% endpullquote %}
Here’s a more realistic example of how you might use a pull quote. 

{% codeblock Wordpress-Plug-in Hermits United lang:php https://github.com/r4gni/Hermits-United/blob/master/hermitsunited.php Hermits United@github %}
function hello_doctor() {
$chosen = hello_doctor_get_lyric();
echo "<p id='quote'>$chosen</p>";
echo "<p id='doctor'>Dr Who<p>";
}
{% endcodeblock %}

When writing longform posts, I find it helpful to include pull quotes to help readers easily identify the topics covered in each section. Some prefer to break things up with lots of headings, and while this seems to be a trend it doesn’t work so well for long form prose. It is important to note that pull quotes are merely visual in presentation and should not appear twice in the text. That is why it a CSS only technique for styling pull quotes is preferable. Octopress includes a handy pull quote plugin to make this easy for you.

Inspect the source and you’ll see the pulled content appears in the data-pullquote attribute of the paragraph. The pull quote effect is created entirely with CSS, and is supported by all modern browsers as well as IE8 and up.

{% blockquote @r4gni, https://twitter.com/r4gni/status/304935411866800128 r4gni@twitter.com %}
All out of poker face.
{% endblockquote %}
<?php
function write($text)
{
	print($text);
}
function writebold ($text)
{
print("<b>$text</b>");
}
$myfunction = "write";
$myfunction("你好!<br>");
print("<br>\n");
$myfunction="writebold";
$myfunction("再见!");
print("<br>\n");
?>
